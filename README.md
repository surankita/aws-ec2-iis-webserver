# 🚀 AWS EC2 + IIS Web Server Project

## Overview
This project demonstrates hosting a static website on an **AWS EC2 Windows Server** using **IIS Web Server**.

## Steps
1. Launched EC2 instance (Windows Server 2019, t2.micro).
2. Configured Security Group (RDP 3389, HTTP 80).
3. Connected via RDP.
4. Installed IIS Web Server role.
5. Created site pointing to `C:\inetpub\wwwroot`.
6. Deployed `index.html` file.
7. Accessed site via EC2 Public IP.

## Screenshots
- EC2 instance setup  
- IIS Manager configuration  
- wwwroot folder with index.html  
- Browser showing hosted page  

## Outcome
Website live at EC2 Public IP → “Hello Friend” displayed.  
Demonstrates skills in **Windows Server setup, IIS configuration, and AWS EC2 hosting**.

## Cleanup
After testing, IIS role and EC2 instance were removed to optimize costs.  
This shows **resource lifecycle management** and **CloudOps discipline**.

