# Escalibur Exploitation Framework

Welcome to Escalibur Exploitation Framework! This is a simple post-exploitation framework written in Python. It provides a set of commands for executing shell commands, listing files, gathering system information, and attempting privilege escalation. Additionally, it allows you to view information about popular exploits.

## Features

- Execute shell commands on compromised systems.
- List files in the current directory or a specified directory.
- Show system information including hostname, IP address, and system details.
- Attempt privilege escalation by listing available sudo privileges.
- View information about popular exploits.

## Usage

To use the Escalibur Exploitation Framework, simply run the Python script `post_exploitation_framework.py`. Follow the on-screen instructions to enter commands and interact with compromised systems.

### Available Commands

- `execute <command>`: Execute a shell command.
- `list_files [<directory>]`: List files in the current directory or specified directory.
- `system_info`: Show system information.
- `escalate_privileges`: Attempt to escalate privileges.
- `show_exploit <exploit_number>`: Show information about a specific exploit.
- `exit`: Exit the framework.

## Exploits

The framework includes information about the following popular exploits:

1. EternalBlue (CVE-2017-0144): A vulnerability in Microsoft's implementation of the Server Message Block (SMB) protocol. Exploited by WannaCry ransomware.
2. Heartbleed (CVE-2014-0160): A vulnerability in the OpenSSL library's implementation of the TLS heartbeat extension, allowing an attacker to read sensitive information from the memory of the affected system.
3. Shellshock (CVE-2014-6271, CVE-2014-7169): A vulnerability in the Bash shell's handling of environment variables, allowing remote code execution.
4. Spectre (CVE-2017-5753, CVE-2017-5715): A class of speculative execution side-channel vulnerabilities affecting modern microprocessors, allowing unauthorized disclosure of information.
5. Meltdown (CVE-2017-5754): A vulnerability in modern microprocessors that allows unauthorized reading of kernel memory, potentially leading to information disclosure.
6. SQL Injection: A code injection technique used to attack data-driven applications by inserting malicious SQL statements into input fields.
7. Cross-Site Scripting (XSS): A type of security vulnerability typically found in web applications, allowing attackers to inject malicious scripts into web pages viewed by other users.
8. Remote Code Execution (RCE): A class of vulnerabilities that allow an attacker to execute arbitrary code on a target system remotely.
9. Directory Traversal: A vulnerability that allows an attacker to access files and directories that are stored outside the web root folder.
10. CSRF (Cross-Site Request Forgery): A type of attack that tricks the victim into executing unwanted actions on a web application in which they're authenticated.

## Disclaimer

This framework is intended for educational and ethical testing purposes only. Unauthorized use of this tool may violate applicable laws. Use at your own risk.

## Contribution

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
