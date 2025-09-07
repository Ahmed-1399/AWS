
# 👤🔒 AWS IAM: Users, Groups & Permissions

Welcome! This guide demonstrates how to manage AWS IAM Users, Groups, and Permissions, with visual examples.

## 🧑‍💻 Users, 👥 Groups & 🛡️ Permissions
![IAM](./assets/Users-Groups-Permissions.png)

---

## 👤 Users
Create individual users for specific access needs.
![Users](./assets/Users.png)

---

## 👥 Groups
Organize users into groups for easier permission management.
![Groups](./assets/Groups.png)

---

## 🛡️ Permissions
- ➕ Add permissions to groups
- ➕ Add users to groups

![Permissions](./assets/Permissions.png)

---

## 👤 User1
![User1](./assets/User1.png)

- 🗂️ **Read-Only S3**
  - Can view S3 buckets.
  ![S3](./assets/User1-s3.png)

- ❌ **Failed to Create S3**
  - Access denied for creating S3 buckets.
  ![s3](./assets/User1-s3-failed.png)

---

## 👤 User2
![User2](./assets/User2.png)

- 🗂️ **Read-Only EC2**
  - Can view EC2 instances.
  ![EC2](./assets/User2-EC2.png)

- ❌ **Failed to Create EC2**
  - Access denied for creating EC2 instances.
  ![EC2](./assets/User2-EC2-Failes.png)

---

## 👤 User3
![User3](./assets/User3.png)

- ▶️⏹️ **View, Start & Stop EC2**
  - Can view, start, and stop EC2 instances.
  ![EC2](./assets/User3-stop-EC2.png)
