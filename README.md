# NAT-configuration-Static-Dynamic-PAT

 - IP Addressing

- Public Network: 150.1.0.0/24

- Public IP Address Range: 150.1.0.1 – 150.1.0.9

- Private Network: 192.168.1.0/24

## Project Objectives

## 1. Dynamic NAT – Private-to-Public Communication

Configure Dynamic NAT to allow internal users (192.168.1.0/24) to access internal resources and external public servers using their private IP addresses. Private source addresses are dynamically translated into available public IP addresses when communicating with external networks.

## 2. Static NAT – Public Access to Internal Servers

Configure Static NAT to allow external users to access designated internal servers using their assigned public IP addresses. Each internal server is mapped to a dedicated public IP address, enabling external connectivity without exposing its private IP address.

- Key Concepts Demonstrated

- Dynamic Network Address Translation

- Static Network Address Translation

- Inside Local and Inside Global addresses

- NAT translation tables and verification

- Private-to-public and public-to-private communication

- Access control and traffic filtering

<div>
  <img width="900" height="680" alt="image" src="https://github.com/user-attachments/assets/0ef52103-6d37-463b-a449-b9c7aa000fd8" />
</div>
