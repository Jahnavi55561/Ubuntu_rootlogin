# Ubuntu_rootlogin
# AWS EC2 Direct Root Login using SSH

## 📌 Project Overview

This project demonstrates how to configure an Ubuntu AWS EC2 instance for direct root-user login through SSH using password authentication.

The initial connection is established using the default `ubuntu` user and an AWS `.pem` private key. The SSH configuration is then modified to allow root login with a password.

---

## 🛠️ Technologies and Tools Used

- Amazon Web Services (AWS)
- Amazon EC2
- Ubuntu 26.04 LTS
- MobaXterm
- OpenSSH
- SSH Protocol
- Linux Terminal

---

## 🎯 Objective

The objective of this task is to:

1. Launch an Ubuntu EC2 instance.
2. Connect to the EC2 instance using SSH.
3. Configure a root-user password.
4. Enable root login through SSH.
5. Enable password authentication.
6. Restart the SSH service.
7. Connect directly as the `root` user using MobaXterm.
8. Verify successful root access.

---

## 🔐 Initial SSH Connection

The EC2 instance was initially accessed using:

```text
Username: ubuntu
Port: 22
Authentication: AWS .pem private key
