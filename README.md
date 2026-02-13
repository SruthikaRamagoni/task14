Security Configuration Summary 
The Linux server was hardened by reviewing default configurations and reducing attack surface exposure. Unused user accounts were removed and sudo access was restricted based on the least privilege principle.
SSH was secured by disabling root login and implementing key-based authentication to prevent brute-force attacks. System packages were updated, and automatic security updates were enabled to mitigate known vulnerabilities.
A firewall was configured using UFW to allow only essential services, with all other incoming traffic denied by default. Unnecessary services were identified and disabled to reduce potential attack vectors.
Sensitive files such as /etc/shadow were verified for correct permissions. Authentication logs and system logs were reviewed to detect suspicious activities.
As a result, the system is protected against common threats such as unauthorized access, brute-force attacks, privilege escalation, and service exploitation.
