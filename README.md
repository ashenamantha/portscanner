# portscanner
Python -nmap based port scanning tool


# Ashen's Port Scanner

A simple and effective port scanning tool built in Python using the nmap library. This tool allows users to scan specified port ranges on target IP addresses to identify open ports and services.

## Description

This port scanning utility leverages Python's nmap module to provide detailed information about network ports. It's designed to be straightforward to use while providing valuable network reconnaissance information. Users can specify an IP address and a port range to scan, and the tool will display the status of each port within the specified range.

## Features

- IP address validation
- Custom port range scanning
- Clear display of port statuses
- Error handling for unresponsive ports
- User-friendly command line interface

## Installation

### Prerequisites

- Python 3.x
- pip package manager
- nmap installed on your system

### Setup

1. Install nmap on your system:

```bash
# For Debian/Ubuntu-based distributions
sudo apt install nmap

# For Red Hat/Fedora-based distributions
sudo dnf install nmap

# For macOS (using Homebrew)
brew install nmap
```

2. Clone the repository:

```bash
git clone https://github.com/ashenamantha/port-scanner.git
cd port-scanner
```

3. Install the required Python packages:

```bash
# Install pip if not already installed
sudo apt install python3-pip

# Install the required Python package
pip install python-nmap
```

## Usage

Run the script using Python:

```bash
python3 port_scanner.py
```

Follow the interactive prompts:
1. Enter the target IP address
2. Enter the port range you want to scan (e.g., `1-100`)

The script will then scan each port in the specified range and report its status.

## Example Output

```
Please enter the ip address that you want to scan: 192.168.1.1
You entered a valid ip address.
Please enter the range of ports you want to scan in format: <int>-<int> (ex would be 60-120)
Enter port range: 20-25
Port 20 is closed
Port 21 is open
Port 22 is open
Port 23 is closed
Port 24 is closed
Port 25 is filtered
```

## Ethical Considerations

This tool is intended for network administrators, security professionals, and ethical hackers to assess network security with proper authorization. Unauthorized port scanning may be illegal in many jurisdictions and violate computer misuse laws.

**Always ensure you have explicit permission to scan the target network or system.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by [Ashen Amantha](https://github.com/ashenamantha)

---

**Disclaimer:** This tool is for educational purposes only. The author assumes no liability for any misuse of this software or for any damages resulting from its use.
