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
This guide is designed for first-time network administrators new to the A10 Control platform.  
Our goal is to help you quickly understand what A10 Control is, how to get started, and where to find key information to begin managing your A10 devices effectively.

---

## 2. Scope

This guide will help you:

- Get an overview of the A10 Control platform.
- Complete initial setup tasks.
- Access and log in to the A10 Control platform.
- Understand key features and the intended use of the platform.
- Become familiar with the dashboard and navigation.
- Find help and additional resources.

---

## 3. Overview

**What is A10 Control?**  
A10 Control is a centralized management platform designed to simplify monitoring, configuration, and management of your A10 Thunder® Series and AX Series Application Delivery Controllers (ADCs), as well as other network devices.  
Instead of managing each device individually, A10 Control provides a single interface to oversee your entire A10 infrastructure.

**Who is it for?**  
For network administrators, engineers, and IT professionals responsible for deploying, operating, and troubleshooting A10 network devices. This guide is tailored for first-time network admins.

**Why is it used?**

- **Simplify Management:** Manage multiple A10 devices from one central location.
- **Improve Efficiency:** Streamline routine tasks—configuration deployment, software upgrades, and performance monitoring.
- **Enhance Visibility:** Get a comprehensive view of your network’s health and performance via dashboards and reports.
- **Automate Operations:** Ensure consistency and faster deployment by automating repetitive tasks.

---

## 4. Initial Setup Tasks

Before you can start using A10 Control, complete the following tasks.

### Pre-requisites

- **Appropriate Hardware or VM:** A server or VM meeting minimum system requirements for A10 Control.
- **Network Connectivity:** The server or VM must communicate with your A10 devices.
- **Licensing Information:** Necessary license keys for A10 Control.

### High-Level Installation Steps

> Steps may vary depending on deployment type (virtual appliance or ISO installation):

1. **Download the A10 Control Software**  
   Obtain the installer image or virtual appliance from the official A10 Networks site.

2. **Deploy/Install A10 Control**  
   - **For VMs:** Import the provided virtual appliance file.  
   - **For physical servers:** Boot from the installer ISO and follow prompts.

3. **Basic Network Configuration**  
   - Assign a static **IP Address** to the A10 Control instance.
   - Set **Subnet Mask** and **Gateway**.
   - Configure **DNS Servers** for hostname resolution.

4. **Initial Account Setup**  
   Create the initial administrator account and password during installation.

---

## 5. Access & Login

Once installed and running, access A10 Control via its web interface.

### Steps to Access:

1. Open a web browser (Chrome, Firefox, Edge, etc.).
2. In the address bar, enter the IP address or hostname configured for your A10 Control instance:  
   Example:  
   - `https://192.168.1.100`  
   - `https://a10control.yourdomain.com`
3. Press **Enter** → You should see the login page.

### Login Credentials

- **Default Credentials:**  
  Fresh installs may default to:  
  `Username: admin`  
  `Password: a10`  
  > **Important:** Change these immediately after your first login.
- **Custom Credentials:**  
  Use the details you set during installation or provided by your IT team.

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

After logging in, you’ll land on the **main dashboard**, your central hub for network performance and health.

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

From the dashboard, navigate to:

- **Device List:** All registered A10 devices with their current status.
- **Alerts/Events:** Logged alerts and events.
- **Basic Reports:** Simple usage and performance summaries.

---

## 8. Additional Help

- Inside the platform, click **Help** or the **?** icon for context-based assistance.
- Visit the **A10 Networks Support Portal**.
- Contact your internal IT support team for further guidance.

---

**✅ You are now ready to begin managing your A10 network infrastructure with A10 Control!**
