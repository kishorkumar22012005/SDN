# SDN
# Step Up Your Own Virtual SDN Lab

Welcome to the **Virtual SDN Lab** setup guide! This project helps you build your own Software Defined Networking (SDN) lab environment using open-source tools, all on a virtualized setup.

## 🧠 What is SDN?

**Software Defined Networking (SDN)** is an approach to networking that uses open protocols and software-based controllers to manage network behavior dynamically, rather than using traditional hardware-centric methods.

This lab allows you to:
- Understand SDN fundamentals
- Experiment with OpenFlow
- Deploy controllers like Ryu, POX, or ONOS
- Simulate networks using Mininet

## 🖥️ Lab Components

- Mininet – Network emulator  
- SDN Controller – Ryu / POX / ONOS (choose your preference)  
- Wireshark – Packet analysis (optional)  
- Ubuntu (recommended) – As the host OS (virtual or native)  
- VirtualBox / VMware – For virtualization (if needed)  

## ⚙️ Prerequisites

- Ubuntu 20.04+ or compatible Linux distro  
- At least 4 GB RAM and 20 GB disk space  
- Internet access for installing packages  
- VirtualBox or VMware if running on Windows/Mac  

## 🛠️ Installation & Setup

### 1. Clone this repository

```bash
git clone https://github.com/yourusername/virtual-sdn-lab.git
cd virtual-sdn-lab
