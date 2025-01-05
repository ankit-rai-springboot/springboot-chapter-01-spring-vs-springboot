# Key Terms When Creating a Spring Boot Project

When creating a Spring Boot project, you need to provide the following information:

### 1. **Group ID**  
   - Think of this as your organization's unique identifier.  
   - It usually follows the format of a domain name in reverse.  
     Example: `com.example` or `org.companyname`.

   **Why is it needed?**  
   - It ensures your project is uniquely identified, especially when publishing it as a library or dependency.

---

### 2. **Artifact ID**  
   - This is the name of your specific project or application.  
     Example: `myapp` or `user-service`.

   **Why is it needed?**  
   - It distinguishes your project from others within the same group.  
   - Combined with the Group ID, it forms the unique identifier for your project (`groupId:artifactId`).

---

### 3. **Name**  
   - A human-readable name for your project.  
     Example: `User Service Application`.

   **Why is it needed?**  
   - It's mainly used for display purposes, such as in your project metadata or build tools.

---

### 4. **Package**  
   - This is the base package where all your project’s Java classes will reside.  
     Example: `com.example.myapp`.

   **Why is it needed?**  
   - It organizes your project files logically and avoids naming conflicts.

---

### Example: Setting Up a Spring Boot Project  
Here’s an example of what you might input:  
- **Group ID**: `com.example`  
- **Artifact ID**: `user-service`  
- **Name**: `User Service Application`  
- **Package**: `com.example.userservice`

With this setup, your project is unique and well-structured for future development.
