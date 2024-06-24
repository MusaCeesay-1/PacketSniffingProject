# Packet Sniffing Project

## Description

This project involves writing a Python script to sniff network packets using the `scapy` library. The script captures network packets on a specified network interface and prints the source IP, destination IP, protocol, and payload of each packet.

## Usage

To use the packet sniffing script, follow these steps:

1. **Clone the repository to your local machine**:
    ```sh
    git clone https://github.com/yourusername/PacketSniffingProject.git
    cd PacketSniffingProject
    ```

2. **Install the `scapy` library**:
    ```sh
    pip install scapy
    ```

3. **Run the script with administrative privileges**:
    ```sh
    sudo python packet_sniffing.py
    ```

4. **Ensure that the interface name in the script** (`en0`) matches an interface on your system. Use `ifconfig` to list your network interfaces and update the script if necessary.

### Example

Here is an example interaction with the script:

Source IP: 192.168.1.2, Destination IP: 192.168.1.3, Protocol: 6, Payload: ...# PacketSniffingProject
