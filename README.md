# SOHO Network Security with Apache and XRDP

## Overview
This project presents the configuration and security of a SOHO LAN connected to the Internet through a virtual router. The implementation was performed on Ubuntu 22.04 in VirtualBox.

## Objectives
- configure a virtual SOHO network
- verify IP addressing and routing
- install and configure Apache
- run the web server on port 8008
- secure web resources
- configure Remote Desktop access with XRDP
- test and validate the implemented services

## Technologies Used
- Ubuntu 22.04 LTS
- Oracle VirtualBox
- Apache2
- XRDP
- Windows client

## Network Architecture
- NAT adapter for Internet access
- virtual LAN environment for testing
- Apache running on port 8008
- XRDP running on port 3389

## Security Features
- Basic authentication for protected web content
- IP-based access restriction
- separation between public and restricted directories

## Repository Structure
- `docs/` – project report
- `screenshots/` – service validation screenshots
- `configs/` – Apache and access control configuration
- `scripts/` – installation script

## Screenshots

### Apache Setup & Security
![Apache Running](screenshots/apache/01_apache_service_running.png)
![Port 8008](screenshots/apache/02_apache_ports_8008.png)
![Default Page](screenshots/apache/03_apache_default_page.png)
![403 Forbidden](screenshots/apache/04_apache_403_forbidden.png)
![User Authentication](screenshots/apache/05_htpasswd_user_created.png)

### Network Configuration
![IP Configuration](screenshots/network/07_network_ip_config.png)
![Routing Table](screenshots/network/08_ip_route_terminal.png)

### Remote Desktop (XRDP)
![XRDP Service](screenshots/xrdp/09_xrdp_service_running.png)
![Remote Connection](screenshots/xrdp/10_xrdp_remote_connection.png)
## Author
Student: Marius Zaharia Andronic
Facultatea: Fiesc Calculatoare – dual
