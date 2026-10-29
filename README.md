
<div align="center">

# 🏥 MedStock AI

### Smart Hospital Medicine & Blood Inventory Management System

**An intelligent healthcare inventory platform powered by the MERN Stack.**

Manage Medicines • Track Expiry • Monitor Blood Inventory • Reduce Waste • Connect Hospitals

<br/>

![MERN Stack](https://img.shields.io/badge/Stack-MERN-00A86B?style=for-the-badge)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

<br/>

![Status](https://img.shields.io/badge/Status-Under_Development-orange?style=flat-square)
![Project](https://img.shields.io/badge/Project-MCA_Major-blue?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-REST_API-purple?style=flat-square)

</div>

---

## 📌 About The Project

**MedStock AI** is a smart hospital inventory management platform designed to simplify medicine and blood stock management through a centralized digital system.

The application helps hospitals monitor medicine batches, track expiry dates, maintain blood inventory, manage stock transactions, and coordinate resource sharing between participating hospitals.

It also aims to integrate AI-assisted demand forecasting and expiry risk analysis to reduce medical wastage and improve inventory planning.

### Our Mission

> To build a smarter and more connected healthcare inventory ecosystem that reduces wastage, improves resource availability, and simplifies hospital inventory operations.

---

## 🎯 Problem Statement

Traditional hospital inventory management can face several challenges:

- Medicine wastage due to expired stock.
- Difficulty monitoring multiple medicine batches.
- Unexpected shortages of essential medicines.
- Limited visibility into blood availability.
- Manual stock calculation errors.
- Poor coordination between hospitals.
- Lack of predictive inventory planning.

MedStock AI aims to address these problems using centralized inventory management, automated monitoring, and intelligent analytics.

---

## ✨ Key Features

| Feature | Description |
|:---|:---|
| 🏥 Hospital Management | Manage multiple hospitals through a centralized platform |
| 💊 Medicine Inventory | Maintain medicine and batch-wise stock records |
| 🩸 Blood Bank | Manage blood groups, components, units, and availability |
| ⏳ Expiry Monitoring | Track upcoming and expired medicine batches |
| 📦 Smart Stock Management | Implement FEFO-based inventory allocation |
| 🧾 Billing Integration | Automatically update stock after billing |
| 🚨 Smart Alerts | Identify shortages, expiry risks, and critical stock |
| 🔄 Resource Sharing | Request medicines and blood from participating hospitals |
| 📊 Analytics | Monitor inventory movement, consumption, and wastage |
| 🤖 AI Integration | Planned demand forecasting and expiry risk analysis |
| 🔐 Role-Based Access | Secure access based on user responsibilities |

---

## 👥 User Roles

MedStock AI follows a hierarchical Role-Based Access Control (RBAC) system.

| Role | Responsibilities |
|:---|:---|
| Super Admin | Hospital approvals, platform management, centralized monitoring |
| Hospital Admin | Hospital operations, departments, staff, inventory, and reports |
| Pharmacist / Staff | Medicine stock, billing, batch management, and expiry monitoring |
| Blood Bank Staff | Blood inventory, unit tracking, quarantine, disposal, and requests |

### Role Hierarchy

```text
                    SUPER ADMIN
                         |
                   HOSPITAL ADMIN
                         |
             +-----------+-----------+
             |                       |
      PHARMACY DEPT.            BLOOD BANK
             |                       |
       PHARMACIST /              BLOOD BANK
          STAFF                    STAFF
```

---

## 🧩 Core Modules

<details>
<summary><b>01. Authentication & Authorization</b></summary>

<br/>

- Secure login and authentication
- JWT-based authorization
- Password hashing
- Protected API routes
- Role-based access control
- Hospital-level data isolation

</details>

<details>
<summary><b>02. Hospital Management</b></summary>

<br/>

- Hospital registration
- Hospital approval workflow
- Hospital profile management
- Staff management
- Department management
- Hospital-level reporting

</details>

<details>
<summary><b>03. Medicine Inventory Management</b></summary>

<br/>

- Medicine master records
- Batch-wise inventory
- Supplier management
- Stock-in and stock-out
- Expiry date tracking
- FEFO-based stock allocation
- Medicine billing
- Stock transaction history
- Barcode / QR scanning

</details>

<details>
<summary><b>04. Blood Bank Management</b></summary>

<br/>

- Blood inventory registration
- Blood group-wise availability
- Blood component management
- Unique blood unit tracking
- Blood expiry monitoring
- Blood unit scanning
- Physical stock verification
- Quarantine and disposal
- Blood inventory reports

</details>

<details>
<summary><b>05. Inter-Hospital Resource Sharing</b></summary>

<br/>

- Medicine availability locator
- Blood availability locator
- Emergency resource requests
- Resource request approval
- Inter-hospital transfer records
- Request status tracking

</details>

<details>
<summary><b>06. Alerts & Analytics</b></summary>

<br/>

- Low-stock notifications
- Critical shortage alerts
- Near-expiry alerts
- Blood unit expiry monitoring
- Inventory movement reports
- Wastage analysis
- Consumption statistics

</details>

<details>
<summary><b>07. AI-Assisted Features (Planned)</b></summary>

<br/>

- Medicine demand forecasting
- Expiry risk prediction
- Shortage prediction
- Stock replenishment recommendations
- Waste reduction analysis

</details>

---

## 🛠️ Technology Stack

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Database

![MongoDB](https://img.shields.io/badge/MongoDB_Atlas-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white)

### Development Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 🏗️ System Architecture

```text
                   MEDSTOCK AI
                        |
                +---------------+
                | React Frontend|
                |     Vite      |
                +-------+-------+
                        |
                    REST API
                        |
                +-------v-------+
                | Node.js       |
                | Express.js    |
                +-------+-------+
                        |
                +-------v-------+
                | Authentication|
                | JWT + RBAC    |
                +-------+-------+
                        |
                +-------v-------+
                | Business Logic|
                | & Services    |
                +-------+-------+
                        |
                +-------v-------+
                |   Mongoose    |
                +-------+-------+
                        |
                +-------v-------+
                | MongoDB Atlas |
                +---------------+
```

---

## 💡 How MedStock AI Works

### Example: Automatic Medicine Stock Deduction

Suppose a hospital pharmacy has the following inventory:

| Medicine | Available Stock | Sold Quantity | Remaining |
|:---|---:|---:|---:|
| Paracetamol | 100 | 10 | 90 |
| Amoxicillin | 50 | 5 | 45 |
| Cetirizine | 80 | 20 | 60 |

After successful billing, the system automatically updates the available stock.

**FEFO (First Expiry, First Out)** ensures that the earliest-expiring valid batch is prioritized during medicine allocation.

### Example: Inter-Hospital Resource Sharing

```text
Hospital A
    |
    | Requires Blood (B+)
    |
    v
MedStock AI Blood Locator
    |
    | Searches participating hospitals
    |
    v
Hospital B - Blood Available
    |
    v
Resource Request Submitted
    |
    v
Approval & Transfer Workflow
```

---

## 📋 System Requirements

| Component | Minimum Requirement |
|:---|:---|
| Processor | Dual-Core Processor |
| RAM | 4 GB (8 GB Recommended) |
| Storage | 2 GB Free Space |
| Operating System | Windows / Linux / macOS |
| Runtime | Node.js (LTS Recommended) |
| Database | MongoDB Atlas |
| Package Manager | npm |
| Browser | Chrome / Edge / Firefox |
| Code Editor | Visual Studio Code |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd MedStock-AI
```

### 2. Backend Setup

Navigate to the server directory:

```bash
cd server
npm install
```

Create a `.env` file inside the `server` directory.

Example configuration:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_secret
NODE_ENV=development
```

Use the environment variable names configured in your actual backend.

Start the backend:

```bash
npm run dev
```

### 3. Frontend Setup

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

### 4. Open Application

| Service | Development URL |
|:---|:---|
| Frontend | http://localhost:5173 |
| Backend | http://localhost:5000 |

> **Note:** Installation assumes the corresponding npm scripts and directories are configured. Never upload real environment secrets to GitHub.

---

## 🗄️ Proposed Database Collections

| Collection | Purpose |
|:---|:---|
| Users | Authentication and user roles |
| Hospitals | Hospital information |
| Departments | Hospital departments |
| Medicines | Medicine master data |
| Medicine Batches | Batch-wise inventory |
| Suppliers | Supplier information |
| Stock Transactions | Stock movement history |
| Bills | Medicine billing records |
| Blood Units | Blood inventory |
| Blood Transactions | Blood movement records |
| Resource Requests | Inter-hospital requests |
| Transfers | Resource transfer records |
| Alerts | System notifications |
| Audit Logs | Important activity records |

Collection names and schemas may evolve during development.

---

## 📈 Expected Outcomes

MedStock AI aims to achieve:

- Reduced medicine expiry and wastage.
- Improved hospital inventory accuracy.
- Better blood stock monitoring.
- Faster identification of resource availability.
- Improved inter-hospital coordination.
- Automated medicine stock calculations.
- Better inventory planning and reporting.
- A scalable foundation for intelligent healthcare inventory management.

---

## 🔮 Future Scope

- Advanced AI-based medicine demand forecasting.
- Intelligent inventory redistribution.
- Automated purchase recommendations.
- Real-time notification integrations.
- Mobile application support.
- Advanced predictive analytics.
- Integration with compatible hospital management systems.

---

## 👨‍💻 Project Team

<div align="center">

### MCA Major Project

**Marwadi University, Rajkot**

Faculty of Computer Applications (FOCA)

| Developer | Project |
|:---:|:---:|
| Kashyap Bharad | MedStock AI |
| Dhaval Parmar | MedStock AI |

**Academic Year: 2026–2027**

</div>

---

## ⚠️ Disclaimer

MedStock AI is an academic healthcare inventory management project. It is not a medical diagnosis or clinical decision-making system.

Real-world hospital deployment would require appropriate security, regulatory, operational, and healthcare compliance validation.

---

<div align="center">

### 🏥 MedStock AI

**Smarter Inventory. Reduced Waste. Better Resource Availability.**

Made with ❤️ using the MERN Stack.

</div>
