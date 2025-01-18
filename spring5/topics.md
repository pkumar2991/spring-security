# Spring Security - 6
Here’s a structured plan for learning **Spring Security 6**, covering key concepts with hands-on examples.

---
### **1️⃣ Introduction to Spring Security** 
- What is Spring Security?  
- Why is security important?  
- Key features of Spring Security  
- Overview of Spring Security 6 changes  

### **2️⃣ Setting Up Spring Security 6**  
- Adding Spring Security dependency  
- Default security configuration  
- The new `SecurityFilterChain` approach (replacing `WebSecurityConfigurerAdapter`)  
- Live Demo: Basic security setup with Spring Boot  

### **3️⃣ Authentication & Authorization**
- **Authentication**  
  - UserDetailsService & PasswordEncoder  
  - JDBC Authentication  
  - In-memory authentication  
  - OAuth2 Authentication overview  
- **Authorization**  
  - Role-based access control (RBAC)  
  - Method-level security (`@PreAuthorize`, `@PostAuthorize`, `@Secured`)  
- Live Demo: Custom UserDetailsService & Role-based authorization  

### **4️⃣ JWT & OAuth2 Authentication** 
- Why JWT?  
- Spring Security with JWT  
- Configuring OAuth2 login  
- Live Demo: Securing REST APIs with JWT  

### **5️⃣ Spring Security Customizations** 
- Custom filters & exception handling  
- CORS & CSRF protection  
- Securing REST endpoints  
- Live Demo: Custom login page and security filters  
