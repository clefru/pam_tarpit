# pam_tarpit
'tarpit' module for pam to piss off and slow down crackers


# Usage
1. Compile the module
2. Add the module to your system (OS X /usr/lib/pam/, Linux /lib/security)
3. Add the module to your pam.d for something (say SSHD)
4. Reap the benefits!

# PAM.D example:
* The arguments are users to tarpit on
` auth       sufficient     pam_tarpit.so root daemon nobody`
