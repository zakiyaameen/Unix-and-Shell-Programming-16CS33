# Unix-and-Shell-Programming-16CS33
Name of command: systemd-tty-ask-password-agent — List or process pending systemd password requests

Synopsis: systemd-tty-ask-password-agent [OPTIONS...] [VARIABLE=VALUE...]

Description: systemd-tty-ask-password-agent is a password agent that handles password requests of the system, for example for hard disk encryption passwords or SSL certificate passwords that need to be queried at boot-time or during runtime.

systemd-tty-ask-password-agent implements the Password Agents Specification, and is one of many possible response agents which answer to queries formulated with systemd-ask-password(1).

Options: The following options are understood:

--list Lists all currently pending system password requests.

--query Process all currently pending system password requests by querying the user on the calling TTY.
