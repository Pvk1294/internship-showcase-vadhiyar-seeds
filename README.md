# Internship Showcase: Full-Stack Mobile App Developer

**Company:** Vadhiyar Seeds Pvt. Ltd.
**Role:** App Developer Intern
**Duration:** [Start Date] – [End Date]

> **Note:** As the sole developer on this project, I was responsible for the entire lifecycle, from concept and architecture to development, deployment, and submission. The source code is proprietary.

---

### ✅ Project Status

The application is feature-complete and the backend is live on its cloud infrastructure. The React Native mobile app has been submitted to the Google Play Store and is currently under review.

➡️ **[Link to Google Play Store Listing](Your-Play-Store-Link-Here)** *(Once it's live, update this link!)*

---

### 📝 Project Overview & Business Problem

The project was to build a comprehensive, full-stack **mobile loyalty platform** from the ground up to digitize and strengthen the company's relationship with its network of distributors.

The core of the solution is a **"scan-to-earn" system** that replaces manual, paper-based loyalty programs with a secure, scalable, and user-friendly mobile application.

---

### 🚀 My Role & Key Contributions

As the primary developer, I engineered the entire system, including:

* **Full-Stack Development:** Designed and built the backend REST API using **Node.js/Express** and the cross-platform mobile application using **React Native**.
* **Database Architecture:** Modeled the database schema and implemented type-safe interactions using **Prisma ORM** with a **PostgreSQL** database.
* **Feature Implementation:** Developed all key features, including the secure QR code scanning and validation logic, the points ledger, and the multi-tiered reward redemption system.
* **Admin Panel & Tooling:** Created the integrated admin panel for distributor management and developed the powerful back-office tool for generating and managing large batches of unique QR codes.
* **End-to-End Deployment:** Single-handedly managed the entire deployment process on **Google Cloud Platform**, configuring the VM, database, load balancer, and SSL.

---

### ✨ Key Features

The application features a dual-interface design for both Distributors and Administrators.

#### Distributor-Facing Features (React Native App):

* **Secure Onboarding:** Streamlined sign-up with an admin approval workflow.
* **QR Code Scanning:** Instantly scan unique product QR codes to earn loyalty points.
* **Points Ledger & History:** A detailed transaction history to track points earned and redeemed.
* **Tier-Based Reward System:** A multi-level reward system (Bronze, Silver, Gold) that unlocks progressively better benefits.
* **Reward Redemption:** An in-app catalogue to browse and redeem points for rewards.

#### Admin Panel Features (Integrated):

* **Distributor Management:** A dashboard to view, approve, reject, or suspend distributor accounts.
* **Bulk QR Code Generation:** A powerful tool for generating and managing large batches of unique, secure QR codes.
* **Advanced Analytics:** A dashboard providing insights into user activity and redemption rates.
* **Reward Catalogue Management:** Full CRUD functionality for managing available rewards.

---

### 🏛️ Technical Architecture

The system is designed with a modern, decoupled architecture for scalability and maintainability.

```text
+---------------------------+       +---------------------------------+       +--------------------------+
|                           |       |                                 |       |                          |
|   React Native Mobile App |------>|   Google Cloud Load Balancer    |------>|   Node.js/Express Backend|
|      (iOS & Android)      |       |       (SSL Termination)         |       |   (GCP Compute Engine)   |
|                           |       |                                 |       |                          |
+---------------------------+       +---------------------------------+       +-------------+------------+
                                                                                              |
                                                                                              | (Prisma ORM)
                                                                                              v
                                                                                    +---------+----------+
                                                                                    |                    |
                                                                                    |   PostgreSQL DB    |
                                                                                    |     (Cloud SQL)    |
                                                                                    |                    |
                                                                                    +--------------------+

```
---

### 💻 Technology Stack

| Category | Technologies Used |
| :--- | :--- |
| **Frontend (Mobile)** | React Native, Expo, Expo Router, React Context API |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL with Prisma ORM |
| **Authentication** | JSON Web Tokens (JWT), SHA-256 Hashing |
| **Deployment** | Google Cloud Platform (GCP Compute Engine, Cloud SQL, Load Balancer) |
| **Process Management**| PM2 |

---

### 📜 Verification & Accolades

*(If you have a Letter of Recommendation or Certificate for this internship, add it here just like you did for the other one. This adds immense credibility.)*

* 📄 **[View Letter of Recommendation & Completion Certificate]https://drive.google.com/drive/folders/1wTOjpYTKEtlUQJSTXKM4UR9hRaGGKp25?usp=sharing**
