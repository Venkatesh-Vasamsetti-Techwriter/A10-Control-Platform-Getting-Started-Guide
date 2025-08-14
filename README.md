# A10 Control Platform Getting Started Guide

## Table of Contents

- [1. Objective](#1-objective)
- [2. Scope](#2-scope)
- [3. Overview](#3-overview)
- [4. Initial Setup Tasks](#4-initial-setup-tasks)
  - [Pre-requisites](#pre-requisites)
  - [High-Level Installation Steps](#high-level-installation-steps)
- [5. Access & Login](#5-access--login)
  - [Steps to Access](#steps-to-access)
  - [Login Credentials](#login-credentials)
  - [Logging In](#logging-in)
  - [Troubleshooting Login Issues](#troubleshooting-login-issues)
- [6. Platform Overview: Key Features](#6-platform-overview-key-features)
- [7. Getting Started: Navigation & Dashboards](#7-getting-started-navigation--dashboards)
  - [Navigating the Dashboard](#navigating-the-dashboard)
  - [Key Metrics Displayed](#key-metrics-displayed)
  - [Basic Monitoring Views](#basic-monitoring-views)
- [8. Additional Help](#8-additional-help)

---

## 1. Objective

Welcome to the **A10 Control Getting Started Guide!**  
This guide is designed for first-time network administrators new to the A10 Control platform. Our goal is to help you quickly understand what A10 Control is, how to get started, and where to find key information to begin managing your A10 devices effectively.

---

## 2. Scope

This guide will help you:

- Overview of the A10 Control platform.
- Complete initial setup tasks.
- Access and log in to the A10 Control platform.
- Understand the key features and intended use of the platform.
- Become familiar with the dashboard and navigation.
- Find help and additional resources.

---

## 3. Overview

This section provides a quick introduction to what A10 Control is, who it’s designed for, and why it’s a valuable tool for network management.

**What is A10 Control?**  
A10 Control is a centralized management platform designed to simplify monitoring, configuration, and management of your A10 Thunder® Series and AX Series Application Delivery Controllers (ADCs), as well as other network devices. Instead of managing each device individually, A10 Control provides a single interface to oversee your entire A10 infrastructure.

**Who is it for?**  
For network administrators, engineers, and IT professionals responsible for deploying, operating, and troubleshooting A10 network devices. This guide is tailored for first-time network admins.

**Why is it used?**

- **Simplify Management:** Manage multiple A10 devices from one central location.
- **Improve Efficiency:** Streamline routine tasks—configuration deployment, software upgrades, and performance monitoring.
- **Enhance Visibility:** Get a comprehensive view of your network’s health and performance via dashboards and reports.
- **Automate Operations:** Ensure consistency and faster deployment by automating repetitive tasks.

---

## 4. Initial Setup Tasks

Before you can start using A10 Control, there are a few initial setup tasks. This section provides a high-level overview of what you’ll need to do to get the platform up and running.

### Pre-requisites

- **Appropriate Hardware or Virtual Machine:** A server or virtual machine meeting minimum system requirements for A10 Control.
- **Network Connectivity:** The server or VM must communicate with your A10 devices.
- **Licensing Information:** Necessary license keys for A10 Control.

### High-Level Installation Steps

The exact steps may vary slightly depending on your deployment method (e.g., virtual appliance, ISO installation). Generally, the process involves:

1. **Download the A10 Control Software**  
   Obtain the A10 Control installer image or virtual appliance from the official A10 Networks website.

2. **Deploy/Install A10 Control**  
   - **For Virtual Machines:** Import the provided virtual appliance file.  
   - **For Physical Servers:** Boot from the installer ISO and follow prompts.

3. **Basic Network Configuration**
   During the initial setup, you will typically configure:
   - **IP Address:** Assign a static  to the A10 Control instance.
   - **Subnet Mask and Gateway:** Essential network settings for communication.
   - **DNS Servers:** Configure  for hostname resolution.

4. **Initial Account Setup**  
   Create the initial administrator account and password during installation.

---

## 5. Access & Login

Once A10 Control is installed and running, you’ll need to access its web interface to begin managing your devices. This section guides you through accessing the platform and logging in.

### Steps to Access:

1. Open a web browser (Chrome, Firefox, Edge, etc.).
2. In the address bar, enter the **IP address** or **hostname** configured for your A10 Control instance:  
   Example:  
   - `https://192.168.1.100 or`  
   - `https://a10control.yourdomain.com`
3. Press **Enter** → You should see the login page.

### Login Credentials

- **Default Credentials:**  
  Fresh installs may default to:  
  `Username: admin`  
  `Password: a10`  
  > **Important:** Change these immediately after your first login.
- **Custom Credentials:**  
  Use the username and password you set up during the initial installation or the updated credentials provided by your system administrator.

### Logging In

- Enter your **Username** and **Password**.
- Click "**Login**".

### Troubleshooting Login Issues

- Check username/password (passwords are case-sensitive).
- Confirm network connectivity (ping the IP or hostname).
- Clear browser cache or try another browser.
- Contact your IT administrator if issues persist.

---

## 6. Platform Overview: Key Features

| Feature                               | What It Does |
|-------------------------------------|--------------|
| **Dashboard**                       | Central hub for system status, alerts, and actionable insights. |
| **Device Management**               | Add, configure, upgrade, and monitor A10 appliances in a single interface. |
| **Analytics & Reporting**           | Visualize traffic, performance, and security metrics across devices. |
| **Alerts & Notifications**          | Receive notifications via email, webhook, or dashboard alerts. |
| **Multi-tenancy & Role-Based Access** | Assign specific permissions to users or teams. |
| **Automation & Integration**        | APIs and automation for integrating with DevOps tools and workflows. |

---

## 7. Getting Started: Navigation & Dashboards

Once you’ve successfully logged into A10 Control, you’ll land on the main dashboard. This is your central hub for gaining quick insights into your network’s status and performance.

### Navigating the Dashboard

- **Summary Widgets:** Display KPIs like device health, alerts, and traffic stats.
- **Navigation Menu:** Access device management, analytics, settings, and more.
- **Search Bar:** Quickly find specific devices or configurations.

### Key Metrics Displayed

- **Device Status:** Which devices are online/offline and operational state.
- **Overall Health:** Summarized network health.
- **Traffic Overview:** Data usage and performance metrics.
- **Active Alerts:** Critical warnings or issues.

### Basic Monitoring Views

While the dashboard provides summaries, you can often click on specific widgets or use the navigation menu to drill down into more detailed monitoring views. Look for sections related to:

- **Device List:** All registered A10 devices with their current status.
- **Alerts/Events:** Logged alerts and events.
- **Basic Reports:** Simple usage and performance summaries.

---

## 8. Additional Help

- Inside the platform, click **Help** or the **?** icon for context-based assistance.
- Visit the **A10 Networks Support Portal** or ask your organizational IT support for detailed manuals or troubleshooting.
