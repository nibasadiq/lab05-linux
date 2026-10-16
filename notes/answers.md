/bin is a shortcut link to /usr/bin, kept so that old programs still work. /usr/bin is where most common commands like ls, git, and python3 live as installed by Ubuntu. Meanwhile, /usr/local/bin is meant for programs that you add by hand, keeping them separate from Ubuntu's own files.
1. Log file for failed SSH attempts:
/var/log/auth.log or systemd journal stream 'journalctl -u ssh'.

2. Why SSH keys are safer:
SSH public keys use asymmetric cryptography, preventing brute-force attacks and credential interception compared to raw password logins.
