#  TASK 8: Run a Simple Java Maven Build Job in Jenkins

# 🚀 Jenkins + Maven Project Build

## 📌 Task Overview

This project demonstrates the integration of **Jenkins** with a simple **Java Maven** project to automate the build process. The goal was to set up Jenkins on an AWS EC2 instance, install necessary tools (Java, Maven), and run a successful Maven build through a freestyle Jenkins job.

---

## 🛠️ Technologies Used

- 🐧 Ubuntu 22.04 LTS (EC2)
- ☕ Java 17 (OpenJDK)
- 🐳 Jenkins (Latest LTS)
- 🐘 Apache Maven 3.9.9
- 🌐 GitHub (for code hosting)

---

## ⚙️ Steps Followed

### 1. ✅ EC2 Instance Setup
- Launched Ubuntu 22.04 EC2 on AWS.
- Updated packages and installed dependencies.

### 2. ☕ Java Installation
```bash
sudo apt update
sudo apt install openjdk-17-jdk -y

**Maven Project Setup** 

hello-java-maven/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── com/
                └── example/
                    └── HelloWorld.java

**✅ Output**
Maven build completed successfully.

Jenkins job shows "BUILD SUCCESS" in the console.

.jar file is generated in the target/ directory.

