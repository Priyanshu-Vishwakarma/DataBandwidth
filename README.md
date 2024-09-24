# DataBandwidth
# Data Compression for Efficient Bandwidth at the Backbone Network

This project focuses on implementing header and packet compression at the backbone network to optimize bandwidth usage. By applying various compression techniques, the project achieved significant compression ratios, making network communication more efficient.

## Project Overview

In this project, we:
- **Implemented header and packet compression** using a combination of methods.
- **Applied compression techniques** such as:
  - Arithmetic Encoding
  - ZStandard
  - Custom dictionary-based compression
- Achieved **up to 85% compression** for numerical data.
- **Optimized IPv6 packet headers** from 40 bytes to just 6 bytes.

## Network Simulation

We used **GNS3** for simulating the network environment, following Cisco’s three-layer hierarchical model. The project was tested across multiple metrics, including:
- **Throughput**
- **Latency**

Network analysis and packet capture were performed using **Wireshark** to ensure accuracy and performance.

## Technologies Used
- **Compression Algorithms**: Arithmetic Encoding, ZStandard, Custom dictionary methods
- **Network Simulation**: GNS3
- **Network Analysis**: Wireshark

## Results
- Up to **85% compression** achieved for numerical data.
- **IPv6 headers optimized** from 40 bytes to 6 bytes, significantly improving bandwidth efficiency.
- Thorough testing showed **improvements in throughput** and **reduced latency** across the network.

## Future Work
- Further optimization of compression techniques for real-time data transmission.
- Exploration of additional compression algorithms for different data types.
- Scaling the solution for larger, more complex network architectures.

## How to Run
1. Clone this repository.
   ```bash
   git clone https://github.com/your-repo-name.git
2.Follow the instructions in the setup.md to configure GNS3 and run the simulation.
