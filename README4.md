# Creating a Base Spring Boot Project

You can create a base Spring Boot project using the following tools: **Spring Initializr**, **IntelliJ IDEA**, and **VS Code**.

### 1. **Using Spring Initializr**
   - **Spring Initializr** is an online tool that allows you to quickly generate a Spring Boot project with your desired dependencies.
   
   #### Steps:
   1. Go to [Spring Initializr](https://start.spring.io/).
   2. Select the project type (Maven or Gradle), language (Java, Kotlin, or Groovy), and version of Spring Boot.
   3. Fill in the project metadata, such as **Group**, **Artifact**, **Name**, **Description**, and **Package name**.
   4. Select dependencies like **Spring Web**, **Spring Boot Actuator**, **Spring Data JPA**, etc.
   5. Click **Generate**, which will download a ZIP file containing the base Spring Boot project.

   After downloading, unzip the file and open the project in your IDE to start developing.

---

### 2. **Using IntelliJ IDEA**
   - **IntelliJ IDEA** provides an integrated environment to easily create and manage Spring Boot projects.
   
   #### Steps:
   1. Open IntelliJ IDEA and select **New Project**.
   2. In the project wizard, choose **Spring Initializr** from the left panel.
   3. Fill in the project details (Group, Artifact, Name, etc.) and select dependencies like **Spring Web**, **Spring Boot Actuator**, etc.
   4. Click **Finish**, and IntelliJ will generate and open the base Spring Boot project for you.

---

### 3. **Using VS Code**
   - **VS Code** provides an extension for Spring Boot development called **Spring Initializr**.

   #### Steps:
   1. Open **VS Code** and install the **Spring Boot Extension Pack** from the marketplace.
   2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the command palette.
   3. Type and select **Spring Initializr: Generate a Maven Project**.
   4. Choose the project settings, such as **Group**, **Artifact**, and **Dependencies**.
   5. Once the project is created, VS Code will automatically open the base Spring Boot project.

---

### Conclusion:
You can easily create a base Spring Boot project using:
- **Spring Initializr** (web-based)
- **IntelliJ IDEA** (IDE with built-in support)
- **VS Code** (with Spring Boot Extension)

Choose the tool that suits your workflow and start building your Spring Boot application!
