# Tinker Fashion (worktinker.com)

**Tinker Fashion** is a multivendor fashion e-commerce website designed as part of a Master’s project for the *Web Technologies in Business* course. It demonstrates how modern web technologies, cloud hosting, and e-commerce logic can be combined to create a real-world online marketplace.

---

## 1. Project Overview
- **Live Website**: [https://worktinker.com](https://worktinker.com)  
- **Objective**: Build and deploy a fully functional, cloud-hosted e-commerce site that supports multiple vendors, customers, and secure payments.  
- **Business Model**:  
  - Independent vendors can create stores, manage inventory, and sell products.  
  - Customers can browse, add products to cart, and complete secure checkout.  
  - Vendors can purchase *advertising slots* to feature products more prominently.  

This project mimics real-world e-commerce platforms such as *The Iconic* or *ASOS Marketplace* while including unique advertising and promotion features for vendors.

---

## 2. Core Features

### Customer Features
- **Product Catalog**: Browse categorized listings with detailed descriptions, pricing, and images.  
- **Shopping Cart**: Add or remove items and view a summary before checkout.  
- **Checkout & Payment**: Real integration with **Stripe** and **PayPal** (live gateways).  
- **User Accounts**: Customers can sign up, log in, and track orders. Google login is available.  
- **Order Confirmation**:  
  - Customers receive confirmation via email and SMS.  
  - Order history is available in the “My Account” dashboard.  

### Vendor Features
- **Vendor Dashboard**: Powered by **Dokan Pro**, enabling vendors to:  
  - Create and manage products (CRUD).  
  - Track orders and sales.  
  - View analytics and reports.  
- **Advertising Slots**:  
  - Vendors can pay a one-time fee or recurring subscription to feature products.  
  - Slots: 12 available per category (4 rows × 3 slots).  
  - Featured products are displayed at the top of shop pages and category pages for 1, 2, or 4 weeks.  

### Admin Features
- **Admin Panel**: Full WordPress/WooCommerce backend for managing:  
  - Vendors  
  - Customers  
  - Products  
  - Orders  
  - Advertising slots  

---

## 3. Tech Stack

- **Platform**: WordPress CMS  
- **E-commerce Engine**: WooCommerce  
- **Multivendor System**: Dokan Pro  
- **Theme**: Flatsome (customized with unique elements and icons designed by author)  
- **Payment Gateways**: Stripe and PayPal (real, live payment processing)  
- **Database**: MySQL (managed via Hostinger’s WordPress hosting)  
- **Languages**: PHP, HTML, CSS, JavaScript  
- **Hosting**: Hostinger Cloud Hosting with SSL enabled  

---

## 4. Deployment

The website is deployed on **Hostinger cloud hosting** with a custom domain and SSL certificate. The deployment process was smooth, and no major issues were encountered. Below are the detailed steps followed:

1. **Hosting & Domain Setup**
   - Purchased hosting and domain from Hostinger.
   - Installed WordPress using Hostinger’s one-click installer.
   - Connected the domain via Hostinger DNS and verified propagation.

2. **SSL & HTTPS**
   - Activated free SSL through Hostinger’s hPanel.
   - Configured the site to force HTTPS, ensuring secure connections.

3. **WordPress Configuration**
   - Set correct site URL and permalinks.
   - Installed Flatsome theme and created a child theme for custom icons and UI elements.
   - Installed required plugins: WooCommerce for e-commerce, Dokan Pro for multivendor, Stripe and PayPal for payments.

4. **Database & Content**
   - MySQL database automatically provisioned by Hostinger.
   - Products, vendor data, and customer accounts stored securely through WooCommerce/Dokan.

5. **Email & Notifications**
   - Configured SMTP for reliable order confirmation emails.
   - Integrated SMS plugin to send order updates to customers and vendors.

6. **Payment Gateways**
   - Stripe and PayPal live keys configured.
   - Test transactions performed successfully before going live.

7. **Performance & Uptime**
   - Hostinger caching enabled for faster load times.
   - Verified responsive performance across desktop, tablet, and mobile.
   - Monitoring shows stable uptime.

8. **Backup & Security**
   - Daily automatic backups enabled via Hostinger.
   - SSL + WordPress role management ensure secure logins and transactions.
   - All plugins kept updated to reduce vulnerabilities.

---

## 5. Data Handling

- **Products**: Vendors can create, update, and delete product listings directly from the vendor dashboard.  
- **Users**: Managed via WooCommerce. Both vendors and customers have separate account types with distinct permissions.  
- **Orders**: Created automatically at checkout; stored in WooCommerce. Vendors and customers can access order details in their respective dashboards.  
- **CRUD Operations**:  
  - **Vendors**: Create, Read, Update, Delete products.  
  - **Customers**: Create accounts, view/update profile, read order history.  
  - **Admin**: Full CRUD over all entities.  

---

## 6. Security Considerations

- **HTTPS**: Entire website secured with SSL from Hostinger.  
- **Authentication**:  
  - WooCommerce’s built-in secure login/registration.  
  - Passwords hashed using WordPress security standards.  
  - Google login (OAuth) adds an extra security layer.  
- **Role-Based Access**:  
  - Customers: Purchase products and view orders.  
  - Vendors: Manage products, advertising, and orders.  
  - Admins: Manage all site functions.  
- **Input Validation**: WooCommerce validates checkout and form inputs to prevent injection attacks.  
- **Vulnerabilities**: None identified. All standard WordPress security practices (regular plugin updates, secure hosting) are applied.  

---

## 7. Documentation & Presentation

- This README serves as clear documentation of the website’s **features**, **tech stack**, and **deployment**.  
- Both **vendors and customers** can directly refer to the live site [https://worktinker.com](https://worktinker.com) as proof of functionality.  
- Instructions are provided here for both user types:  
  - **Customers**: Sign up, browse catalog, add items to cart, checkout, receive confirmation.  
  - **Vendors**: Register as a vendor, add products, purchase advertising slots, and monitor sales.  

---

## 8. Reflection

### What Worked Well
- Smooth integration of Stripe and PayPal for real transactions.  
- Vendor features (via Dokan Pro) provide a realistic multivendor marketplace experience.  
- Flatsome theme gave flexibility, while custom icons and elements made the design unique.  
- Hosting on Hostinger ensured fast load speeds and stable uptime.  
- “Tinker AI” chatbot adds customer support functionality.  

### Future Improvements
- **Technical**: Add a Point-of-Sale (POS) integration so vendors can sync physical and online store sales.  
- **UX/Business**: Standardize size charts across vendors (e.g., AU sizes: 6, 8, 10) to avoid confusion and reduce product returns.  

---

**Author**: *Randimal Herath*  
