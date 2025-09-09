# Tinker Fashion (worktinker.com)

**Tinker Fashion** is a multivendor e-commerce platform for fashion—dresses, jewelry, heels, watches, and accessories—built with WordPress and WooCommerce, featuring vendor dashboards and real payment processing.

---

##  Project Overview

- **Live Website**: [https://worktinker.com](https://worktinker.com)  
- **Launch Year**: 2025  
- **Location**: Nobel Park, Victoria, Australia

**Mission**: Empower confident, stylish self-expression through accessible, elegant fashion—combining quality, comfort, and inclusivity. :contentReference[oaicite:0]{index=0}

---

##  Features & Functionality

- **Product Catalog**: Fully functional, showcasing collections like New Arrivals, Best Sellers, and detailed product pages. :contentReference[oaicite:1]{index=1}  
- **Shopping Cart**: Standard add/remove workflow in place.  
- **Checkout & Payments**: Live Stripe and PayPal integration enabling real transactions.  
- **User Authentication**: WooCommerce standard login/register + Google OAuth. Vendor and customer roles supported.  
- **Order Confirmation**: Customers receive both email and SMS notifications; sellers also receive alerts; order history is accessible via user account.  
- **Multivendor Support**: Hosted with Dokan Pro, enabling vendor dashboards, listings, and ads.  
- **Vendor Advertising**: Vendors can purchase featured promotional slots (12 available per category) which showcase their products prominently for configurable durations (1, 2, or 4 weeks).

---

##  Tech Stack & Customization

- **Foundation**:  
  - WordPress CMS  
  - WooCommerce for e-commerce  
  - Flatsome theme—for layout and design  
  - Dokan Pro—for vendor capabilities  

- **Customization**:  
  - Custom icons and UI elements crafted to match brand identity  
  - Advert slot logic integrated into category/shop templates  

- **Integrations Learned**:  
  - Stripe & PayPal payment gateways  
  - Vendor dashboard setup via Dokan Pro  
  - WordPress theme customization (Flatsome child theme)

---

##  Deployment Details

- **Hosting Provider**: Hostinger  
- **URL**: [https://worktinker.com](https://worktinker.com)  
- **Performance**: Fast page load, SSL secured, stable uptime  
- **Notes**: Domain, DNS, SSL setup were executed smoothly—no deployment challenges encountered.

---

##  Data & Security Handling

- **Data Storage**: MySQL database (via WordPress) stores all data—products, users, orders.  
- **Authentication Security**:  
  - Secure password hashing (WordPress standard)  
  - Google OAuth via WooCommerce integration  

- **Order Management**:  
  - Orders created via checkout, stored in WooCommerce; accessible to customers (order history) and vendors/admins.  
  - CRUD operations: Vendors can create/update products; admins can manage all entities.

- **Security Best Practices**:  
  - HTTPS enforced via SSL  
  - Role-based access (customer, vendor, admin) enforced by WooCommerce & Dokan Pro  
  - Input validation handled by WordPress/WooCommerce backend  
  - **No known security vulnerabilities** at this time.

---

##  Documentation & How to Use

**Recommended GitHub structure** (if using):
