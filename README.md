# Domain Availability Checker

A simple bash script to check if a domain is available for registration using the `whois` command.

## Features

- Quickly check the availability of a domain name.
- Supports various TLDs by matching common `whois` responses.
- Outputs the domain name in green if available and in red if already registered.

## Prerequisites

- **Bash**: The script is written in bash and should work on any Unix-like operating system.
- **whois**: Ensure that the `whois` command is installed on your system. You can install it using the package manager for your OS:

  - **Ubuntu/Debian**:
    ```bash
    sudo apt-get install whois
    ```
  - **CentOS/RHEL**:
    ```bash
    sudo yum install whois
    ```
  - **macOS**:
    ```bash
    brew install whois
    ```

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/mcsaban/chdomain.git
    cd domain-availability-checker
    ```

2. **Make the script executable**:
    ```bash
    chmod +x chdomain
    ```

## Usage

Run the script with the domain name you want to check:

```bash
./chdomain domainname.com
