# Escalibur Exploitation Framework

Welcome to Escalibur Exploitation Framework! This is a simple post-exploitation framework written in Python. It provides a set of commands for executing shell commands, listing files, gathering system information, and attempting privilege escalation. Additionally, it includes information about popular exploits.

## Features

- Execute shell commands on compromised systems.
- List files in the current directory or a specified directory.
- Show system information including hostname, IP address, and system details.
- Attempt privilege escalation by listing available sudo privileges.
- Show information about popular exploits.

## Usage

To use the Escalibur Exploitation Framework, simply run the Python script `post_exploitation_framework.py`. Follow the on-screen instructions to enter commands and interact with compromised systems.

### Available Commands

- `execute <command>`: Execute a shell command.
- `list_files [<directory>]`: List files in the current directory or specified directory.
- `system_info`: Show system information.
- `escalate_privileges`: Attempt to escalate privileges.
- `show_exploits`: Show information about available exploits.
- `exit`: Exit the framework.

## Exploits

The framework includes information about the following popular exploits:

1. **EternalBlue**
   - **CVE**: CVE-2017-0144
   - **Description**: A vulnerability in Microsoft's implementation of the Server Message Block (SMB) protocol. Exploited by WannaCry ransomware.

2. **Heartbleed**
   - **CVE**: CVE-2014-0160
   - **Description**: A vulnerability in the OpenSSL library's implementation of the TLS heartbeat extension, allowing an attacker to read sensitive information from the memory of the affected system.
   ##Info about the rest of the exploits
   Other Exploits are included in the exploits.txt file

## Disclaimer

This framework is intended for educational and ethical testing purposes only. Unauthorized use of this tool may violate applicable laws. Use at your own risk.

## Contribution

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

