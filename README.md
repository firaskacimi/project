# project
**Full-Stack MERN Final Project Specification Document**

## **1. Project Overview**

- **Project Name:** **Algerian PC E-Commerce Platform**
- **Short Description:**  
  A full-stack MERN e-commerce web application for browsing, customizing, and purchasing PCs. The platform supports role-based dashboards (super admin, stock managers, order trackers, and regular users), employee gamification system (leveling up based on performance), and real-time order tracking with email notifications. It also features an admin dashboard for monitoring employees, stock, and orders.

## **2. Group Members**

| Name | Email | GitHub Profile |
| kacimi el hassani firas | itsmemario0230@gmai.com | firaskacimi |

## **3. Selected Theme**

_(Choose one by marking an "X")_

- [ ] **Task Management Application**
- [x] **E-Commerce Website**
- [ ] **Real-time Chat Application**
- [ ] **Book Recommendation App**
- [ ] **MERN Application**

## **4. Features & Functionalities**

### **Frontend Features**

- User authentication (Signup/Login)
- Role-based dashboard (**Buyer**)
- Browse and search for available   
- PC customization feature (choose CPU, GPU, RAM, Storage, etc.)
- Order system (standard PCs or customized builds)
- Order tracking page (status: Processing → Assembling → Shipped → Delivered) with estimated delivery time
- User profile with purchase history & order status
- Responsive UI with a clean design

### **Backend Features**

- User authentication with JWT
- Role-based access control (Super Admin, Stock Manager, Order Tracker, Customer)
- CRUD operations for stock and orders
- Order tracking system with status updates & delivery ETA
- Admin dashboard to monitor employees’ performance, orders, and stock
- Email notifications (order confirmation, order tracking updates, promotions, coupons)
- Database management using MongoDB

### **Additional Features (if any)**

- **Email notifications** 

Customer order confirmations & status updates (“Your PC is being assembled”).
Promotions & coupon codes.

- **Event categories & filters** for better browsing
- **Role-based dashboards**
  Super Admin → oversee employees, manage stock, track orders, and monitor platform activity

         Stock Manager → manage product availability and stock levels

         Order Tracker → update customer order progress and delivery status

- **Employee gamification system**
Employees earn XP for completing tasks efficiently (e.g., updating stock, processing orders quickly, resolving issues).

Leveling up unlocks bonuses, badges, or recognition in the dashboard.

- **Employee leaderboards** Super Admin can track the best-performing employees.

## **5. Technologies Used**

- **Frontend:** React, Tailwind CSS
- **Backend:** Express.js, Mongoose
- **Database:** MongoDB (Atlas)
- **Additional Libraries/Tools:** JWT for authentication,Nodemailer (for email notifications), bcrypt.js (for password hashing), Cloudinary or Multer (for product images), Socket.IO (optional, for real-time order status updates)

## **6. Project Milestones & Timeline**

| Milestone             | Expected Completion Date  |
| --------------------- | ------------------------- |
| Project Setup         | 2 days (01/03) ~ (03/03)  |
| Backend Development   | 1 week (04/03) ~ (12/03)  |
| Frontend Development  | 2 weeks (12/03) ~ (25/03) |
| Integration & Testing | 4 days (26/03) ~ (30/03)  |
| Final Deployment      | 1 day (31/03)             |

## **7. Additional Notes**

The platform focuses on PC e-commerce in Algeria, with custom PC build options.

Employees are motivated with gamification to improve efficiency and maintain engagement.

Order tracking provides customers with real-time transparency and improves trust.

Future improvements may include:

Payment gateway integration (when Algeria supports online payments)

Mobile-friendly enhancements

AI-based PC build recommendations
