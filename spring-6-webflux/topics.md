### **Spring Security in Spring WebFlux**  

We will focus on securing reactive applications using **Spring Security 6 with Spring WebFlux**.  
---
### **1️⃣ Introduction to Spring Security in WebFlux** 
- What is **Spring WebFlux**, and why use it?  
- Key differences between **Spring MVC Security** & **WebFlux Security**  
- How Spring Security integrates with **Reactor (Mono/Flux)**  
- Overview of **SecurityContext & ReactiveAuthenticationManager**  

### **2️⃣ Setting Up Spring Security in a WebFlux Project** 
- Adding dependencies (`spring-boot-starter-webflux`, `spring-boot-starter-security`)  
- Configuring **SecurityFilterChain** (Replacing `WebSecurityConfigurerAdapter`)  
- Understanding **AuthenticationWebFilter & SecurityContextRepository**  
- Live Demo: **Basic authentication with WebFlux**  

### **3️⃣ Authentication & Authorization in Reactive Applications** 
- **Reactive Authentication**  
  - UserDetailsService with **ReactiveUserDetailsService**  
  - BCryptPasswordEncoder for password encryption  
  - Using **AuthenticationManager** for custom auth logic  
- **Reactive Authorization**  
  - Role-based & method-level security in WebFlux (`@PreAuthorize`, `@PostAuthorize`)  
  - Securing endpoints using **ServerHttpSecurity**  
- Live Demo: **Custom authentication & role-based authorization**  

### **4️⃣ Implementing JWT Authentication in Spring WebFlux**
- Why JWT in a reactive system?  
- Creating a **JWT Authentication Filter**  
- Managing token storage in **ReactiveSecurityContextHolder**  
- Live Demo: **Securing WebFlux APIs with JWT**  

### **5️⃣ OAuth2 Authentication in WebFlux**
- Integrating **OAuth2 Login** with WebFlux  
- Using **ReactiveOAuth2UserService** for user details  
- Live Demo: **Securing WebFlux with OAuth2 & Google Login**  

### **6️⃣ Security Best Practices & Q&A**
- **Handling CSRF, CORS & XSS** in WebFlux  
- Protecting against **session hijacking** in reactive systems  
- Common mistakes & how to avoid them  
- Q&A and discussions  

---
