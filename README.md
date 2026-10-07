Game4Learning (G4L) Enterprise IT Infrastructure & Intranet
[View the Live Intranet Portal Here](Insert your GitHub Pages link here)

Overview
This repository contains the comprehensive Work Integrated Learning (WIL) project for Game4Learning (G4L), detailing the end-to-end design, budgeting, and deployment strategy for a multi-site enterprise IT infrastructure. The project includes a fully functional static intranet portal built to host the organization's Standard Operating Procedures (SOPs), Network Topologies, and Disaster Recovery Plans.

Technical Architecture & Network Design
Topology: Star network topology connecting Site A and Site B via a secure VPN tunnel.

Segmentation: Strict VLAN implementation isolating Admin (VLAN 10), Development (VLAN 20), Guest (VLAN 30), and CCTV (VLAN 40) traffic.

Hardware Allocation: Comprehensive provisioning of redundant core switches, PoE access switches, internal file/database servers, and Wi-Fi access points.

Security: Multi-layered defense including firewall traffic filtering, Active Directory (AD DS) role-based access control (RBAC), and physical security protocols.

IT Governance & Service Management
Disaster Recovery (DRP): Defined Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO) of 24 hours, utilizing daily local NAS backups and weekly offsite cloud synchronization.

Service Desk SLAs: Structured incident management ticketing systems categorizing faults from P3 (Minor) to P1 (Critical) with a 15-minute response target.

Standard Operating Procedures (SOP): Documented daily lab start-up sequences, automated system health checks, and secure account provisioning guidelines.

Project Management
Managed a comprehensive infrastructure budget of R1,564,050 spanning end-user devices, servers, networking hardware, and ISP connectivity.

Developed detailed Work Breakdown Structures (WBS), Gantt charts, and risk matrices encompassing economic, technical, and hardware variables.
