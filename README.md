# Jenkins Declarative Pipeline – CI/CD Automation

This project demonstrates the implementation of a Jenkins Declarative Pipeline to automate the core stages of the software build lifecycle. The pipeline is defined using a Jenkinsfile, enabling a clean, version-controlled, and maintainable CI configuration.

The objective of this project is to understand pipeline-as-code concepts, automate build processes, and establish a foundation for more advanced CI/CD workflows. 

---

## 🔹 Project Design
The pipeline is written using Jenkins Declarative syntax, providing a structured and readable approach to defining build stages, making the pipeline easy to maintain and extend.

---

## 🔹 Pipeline Stages
1. **Compile**
   - Pulls the latest source code from the GitHub repository
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