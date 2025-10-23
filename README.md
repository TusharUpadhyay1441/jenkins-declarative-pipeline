# Jenkins Declarative Pipeline – CI/CD Automation

This repository demonstrates a Jenkins Declarative Pipeline setup designed to automate the software build lifecycle. The pipeline is defined within a Jenkinsfile and currently implements two core stages: Compile and Package. 

---

## 🔹 Project Overview
The pipeline leverages Jenkins Declarative syntax, which provides a structured, readable, and maintainable configuration format. This approach facilitates a clear, step-by-step sequence for building and packaging software artifacts efficiently and reliably.

---

## 🔹 Pipeline Stages
1. **Compile**
   - Pulls the latest source code from the repository.
   - Compiles the code.
   - Ensures there are no compilation errors.
   - Example: `mvn clean compile`

2. **Package**
   - Packages the compiled code into a deployable artifact.
   - Example: `mvn package`

---

## 📸 Screenshots

## Pipeline Code
<img src="images/pipeline code.png">

-------------------------------------

## Pipeline Result
<img src="images/pipeline result.png">

-------------------------------------