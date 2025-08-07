# 🚗 WhatNext Vision Motors - Salesforce Capstone Project

WhatNext Vision Motors is a Salesforce-based capstone project designed to automate and optimize the operations of a fictional automobile dealership. It demonstrates the power of Salesforce CRM to manage vehicle orders, inventory updates, customer notifications, and more using automation tools like Apex, Flows, and Scheduled Jobs.

---

## 📌 Project Overview

In the dynamic world of vehicle sales, dealerships often face challenges such as inventory mismanagement, missed customer engagements, and inefficient manual processes. WhatNext Vision Motors addresses these issues with a cloud-first, automated solution built entirely on the Salesforce Lightning Platform.

---

## 🎯 Objectives

- Automate vehicle order processing
- Track and update inventory in real-time
- Remind customers about test drives via scheduled email flows
- Improve dealership efficiency and customer satisfaction

---

## 🛠️ Features

### ✅ 1. **Vehicle Order Management**
- Custom `Vehicle_Order__c` object
- Validations to ensure order accuracy
- Apex Trigger to update related inventory after order placement

### ✅ 2. **Inventory Management**
- Custom `Vehicle_Inventory__c` object
- Stock levels auto-updated using Apex and Batch class
- Dashboard & Reports to monitor vehicle stock and trends

### ✅ 3. **Scheduled Batch Process**
- `VehicleOrderBatch` – Processes vehicle orders in bulk
- `VehicleOrderBatchScheduler` – Runs at defined intervals to keep data up-to-date

### ✅ 4. **Automated Test Drive Reminders**
- Salesforce Flow: `Test Drive Reminder`
- Sends reminder emails to customers scheduled for a test drive

---

## 🧠 Tools & Technologies

- **Salesforce Lightning Experience**
- **Apex Triggers & Classes**
- **Flows & Process Builder**
- **Batch Apex & Schedulers**
- **Custom Objects, Fields & Relationships**
- **Reports & Dashboards**

---

## 🧪 Test Data

We used custom records in:
- `Vehicle_Order__c`
- `Vehicle_Inventory__c`
- `Customer__c`

Test cases validate:
- Inventory auto-adjustment
- Correct scheduling of batch jobs
- Email delivery via flow

---


## 📽️ Demo Video

> Check out our full walkthrough video here: *[https://drive.google.com/file/d/12RvBpF3wWNqFS7_sO5c4ghc_nsoxSRAk/view?usp=sharing]*

---
