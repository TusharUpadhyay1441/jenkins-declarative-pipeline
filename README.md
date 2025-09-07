# Jenkins Declarative Pipeline – CI/CD Automation

This repository demonstrates a **Jenkins Declarative Pipeline** setup to automate the software build lifecycle.  
The pipeline is defined in the `Jenkinsfile` and currently includes **Compile** and **Package** stages.  

---

## 🔹 Project Overview
The pipeline is created using **Jenkins Declarative syntax**, which makes it more structured and easier to maintain.  
This setup ensures a **clear sequence of steps** for code compilation and packaging into deployable artifacts.

---

## 🔹 Pipeline Stages
1. **Compile**
   - Pulls the latest source code.
   - Compiles the code.
   - Ensures there are no compilation errors.
   - Example: `mvn clean compile`

2. **Package**
   - Packages the compiled code into a deployable artifact.
   - Example: `mvn package`

---