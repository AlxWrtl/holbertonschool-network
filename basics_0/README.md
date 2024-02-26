# Networking Essentials Toolkit

## Introduction

This toolkit offers a comprehensive suite of utilities and informational resources designed to facilitate understanding and diagnostics of network-related concepts and issues. It spans foundational networking topics such as the OSI model, types of networks, MAC and IP addressing, as well as the differences and uses of UDP and TCP protocols. Additionally, it includes practical Bash scripts for checking active internet connections and verifying host availability on the network.

## Table of Contents

- [Networking Essentials Toolkit](#networking-essentials-toolkit)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Educational Resources](#educational-resources)
    - [Scripts](#scripts)
  - [Features](#features)
  - [Dependencies](#dependencies)
  - [Configuration](#configuration)
  - [Documentation](#documentation)
  - [Examples](#examples)
  - [Troubleshooting](#troubleshooting)
  - [Contributors](#contributors)
  - [License](#license)

## Installation

No installation is required for accessing the informational resources. For the scripts, ensure you have a Bash shell environment and necessary permissions to execute scripts.

## Usage

### Educational Resources

1. **OSI Model**: A comprehensive guide to understanding the OSI (Open Systems Interconnection) model and its 7 layers.
2. **Types of Network**: Overview of different types of networks including LAN, WAN, and others.
3. **MAC and IP Address**: Explains the differences between MAC (Media Access Control) and IP (Internet Protocol) addresses.
4. **UDP and TCP**: Details the use cases and differences between UDP (User Datagram Protocol) and TCP (Transmission Control Protocol).

### Scripts

1. **TCP and UDP Ports**:
   - Lists active internet connections (only servers).
   - Command: `./TCP_and_UDP_ports.sh`

2. **Is the Host on the Network**:
   - Checks if a specific host is available on the network using its IP address.
   - Usage: `./is_the_host_on_the_network.sh {IP_ADDRESS}`

## Features

- Educational guides on key networking concepts.
- Bash scripts for network diagnostics and checks.

## Dependencies

- Bash shell
- Standard Unix/Linux utilities (`ping`, `ss`)

## Configuration

No additional configuration is required for the educational content. Ensure execution permissions for the scripts using `chmod +x <script_name>.sh`.

## Documentation

For more detailed information on networking concepts, refer to [RFC documents](https://www.rfc-editor.org/) and [IEEE standards](https://standards.ieee.org/).

## Examples

Checking if a host with the IP address 192.168.1.1 is on the network:

```bash
./is_the_host_on_the_network.sh 192.168.1.1
