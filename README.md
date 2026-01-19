# Networking-Fundamentals-Capstone

**📌 Project Overview**

This repository contains the Networking Fundamentals Capstone Project completed as part of the Akamai Network Engineering Professional Certificate.
The project is based on a fictitious business scenario to serve a Small Office / Home Office (SOHO) market.
In this scenario, RICHKIM EMPIRE is established as a cybersecurity-focused startup, and a complete internal network is designed, implemented, and validated.
The project demonstrates practical networking skills using Cisco Packet Tracer, including LAN design, IP addressing, DHCP, DNS, NAT, and public web service deployment.

**🏢 Company Scenario**

      **Company Name:** RICHKIM EMPIRE
      **Industry:** Cybersecurity Services
      **Business Size:** Small Office (8 Employees)


**Staff Structure:**

      Chief Executive Officer (CEO)
      Business / Operations Manager
      Technical Staff (Security & Networking)
       General Administrative Staff

The company maintains a public-facing website and requires a secure internal network to support daily operations and cybersecurity services.


**🛠️ Technologies & Tools Used**

      1. Cisco Packet Tracer
      2. IPv4 Networking
      3. DHCP (Dynamic Host Configuration Protocol)
      4. DNS (Domain Name System)
      5. NAT / PAT (Network Address Translation)
      6. LAN Switching & Routing
      7. SOHO Network Design Principles

**🌐 Network Design Summary**

**🔹 Internal Network**

      1. Private IPv4 addressing: 192.168.20.0/24
      2. Router-based DHCP for automatic IP assignment
      3. Centralized switch connecting
      4. Client PCs
      5. printers
      6. Network scanner
      7. Default gateway configured on the router

**🔹 Shared Office Devices**

      1. 4 Network Printers
      2. 1 Network Scanner

**🔹 Public Services**

      1. Public web server hosting the company website
      2. Domain name access via:
           http://www.company.com

🔹 Internet Connectivity & Security

      1. Edge router connected to ISP
      2. NAT Overload (PAT) implemented
      3. Internal IP addresses hidden from the Internet
      4. External users can only access the public web server

**✅ Testing & Validation**
The following tests were successfully performed:

        ✔ Internal client-to-client connectivity (ping test)
        ✔ DHCP address assignment verification
        ✔ Internal LAN access to public web server
        ✔ External client access to company website
        ✔ NAT translation verification via router CLI

These tests confirm correct network configuration, secure connectivity, and real-world SOHO functionality.
