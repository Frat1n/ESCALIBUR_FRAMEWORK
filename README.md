# Escalibur Exploitation Framework

Welcome to Escalibur Exploitation Framework! This is a simple post-exploitation framework written in Python. It provides a set of commands for executing shell commands, listing files, gathering system information, and attempting privilege escalation. Additionally, it includes information about popular exploits.

## Installation

To use the Escalibur Exploitation Framework, clone this repository to your local machine and run the Python script `post_exploitation_framework.py`.

## Usage

Available commands:
- `execute <command>`
- `list_files [<directory>]`
- `system_info`
- `escalate_privileges`
- `show_exploits`
- `exploit <exploit_name>`
- `connect <ip_address>`
- `set_ip <ip_address> (OLD)`
- `run_exploit`
- `RHOST <ip_address> (NEW)`
- `LHOST <ip_address> (NEW)`
- `exit`

## Exploits

The framework includes information about the following popular exploits:
1. **EternalBlue**
   - **CVE**: CVE-2017-0144
   - **Description**: A vulnerability in Microsoft's implementation of the Server Message Block (SMB) protocol. Exploited by WannaCry ransomware.
2. **Heartbleed**
   - **CVE**: CVE-2014-0160
   - **Description**: A vulnerability in the OpenSSL library's implementation of the TLS heartbeat extension, allowing an attacker to read sensitive information from the memory of the affected system.

   <!-- Add information about other exploits here -->

## Connecting to a Computer

To connect to a computer using its IP address, use the `connect <ip_address>` command. For example:
connect 192.168.1.100

bash
Copy code

## Setting the IP Address of the Target Computer

To set the IP address of the target computer, use the `set_ip <ip_address>` command. For example:
set_ip 192.168.1.100

perl
Copy code

## Exploiting Vulnerabilities for Reverse Shell

To exploit vulnerabilities and create a reverse shell connection with the target computer, use the `exploit <exploit_name>` command. For example:
exploit eternalblue


## Running Exploit

To run the exploit configured with the specified RHOST and LHOST, use the `run_exploit` command.

## Setting Remote Host (RHOST) and Local Host (LHOST)

To set the IP address of the target computer (RHOST) and the local IP address (LHOST) for exploit purposes, use the `RHOST <ip_address>` and `LHOST <ip_address>` commands, respectively.

## Disclaimer

This framework is intended for educational and ethical testing purposes only. Unauthorized use of this tool may violate applicable laws. Use at your own risk.

## Contribution

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
