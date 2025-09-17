# Admin-Panel

This project involves designing and developing a simple, intuitive, and high-performance administration interface. It implements the key management modules, including banners, newsletters, users, articles, promotions, orders, and deliveries. Access security is ensured through a role- and privilege-based system, while the content displayed on the client side is managed dynamically.

## Modules : 

1. 📌 Banner :
   This module allows multimedia admin to create, edit, activate/deactivate, and prioritize banners.
    The banners can be displayed on the homepage or other sections of the website.

   ![banner](banner1.png)

    ![banner](banner2.png)

3. 📌 Newsletter Management :
   The administrator can send newsletters by email to all registered users, including HTML content, SEO elements, visuals, and more.

  ![newsletter](newsletter1.png)

  ![newsletter](newsletter2.png)

4.  📌 Admin Management
This module allows the management of administrator accounts.  
It includes the ability to **assign roles** (Super Administrator, Multimedia Administrator, Commercial Administrator) and to manage their **active/inactive status**.

5. 🔐 Security

The system is designed with strong security practices:

- **Authentication with JWT tokens** → Ensures only authenticated users can access protected endpoints.  
- **Role-based Authorization** → Access permissions are granted depending on the administrator’s role (e.g., only Super Admins can manage other admins).  
- **Login system** → Credentials are verified and a secure token is generated for subsequent requests.
  ![login](login.png)
  ![utilisateur](utilisateur.png)
  
5. 📌 Article Management
  
  This module allows administrators to add, edit, and delete products sold on the website.
  Each article includes details such as name, price, image, stock, and more.

  ![article](articles1.png)
  
  
6.📌 Promotion Management

  This module allows administrators to create promotional rules by selecting specific articles.
  Each promotion includes validity period, description, discount, and active/inactive status.

  ![promotion](promotion1.png)

  ![promotion](promotion2.png)
