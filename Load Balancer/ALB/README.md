# 🚀 ALB (Application Load Balancer)

Welcome to the documentation for the **Application Load Balancer (ALB)** architecture! This guide covers the overall structure, security, and deployment details of a robust ALB setup in the cloud. 

---

## 🏗️ Architecture Overview

![🖼️ Architecture Diagram](./assets/ALB-Architecture.png)

---

## 🖥️ Instances

### Instance 1
![🖼️ Instance 1](./assets/instance-1.png)

### Instance 2
![🖼️ Instance 2](./assets/instance-2.png)

---

## 🔐 Security Groups

### SG-ALB Inbound
![🖼️ SG-ALB Inbound](./assets/SG-ALB-Inbound.png)

### SG-ALB Outbound
```bash
# 🚦 Route "HTTP" traffic only to the security group of the instances for enhanced security
```
![🖼️ SG-ALB Outbound](./assets/SG-ALB-Outbound.png)

---

### SG-Instances Inbound
```bash
# 🔒 Allow SSH & receive traffic only from the security group of ALB for improved protection
```
![🖼️ SG-EC2-Inbound](./assets/SG-EC2-Inbound.png)

### SG-Instances Outbound
![🖼️ SG-EC2-Outbound](./assets/SG-EC2-Outbound.png)

---

## 🎯 Target Group

![🖼️ Target Group](./assets/Target-Group.png)

---

## 🌐 Application Load Balancer (ALB)

![🖼️ ALB](./assets/ALB.png)

---

## 🚚 Deployment Process
```bash
# 🌀 The ALB uses round-robin routing: initially you'll see "instance-1", and upon refreshing, it will display "instance-2".
```
![🖼️ Deployment Step 1](./assets/Deploy-1.png)
![🖼️ Deployment Step 2](./assets/Deploy-2.png)

---

## 📚 Summary

This architecture ensures secure and highly available application delivery using AWS ALB, EC2 instances, and tightly managed security groups. For any questions or further details, feel free to reach out! 😊