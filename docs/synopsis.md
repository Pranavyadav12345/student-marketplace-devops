# 🎓 Student Marketplace Platform (DevOps Enabled)

---

## 👨‍💻 Team Members
- Pranav Yadav  
- Kamran Javeed  
- Bingi Likhil Chandra  

---

## 📌 Introduction
The **Student Marketplace Platform** is a web-based application designed to facilitate the buying, selling, and exchange of academic and personal items among students within a campus or university environment. Inspired by platforms like NoteKart, this system focuses specifically on student needs such as sharing notes, books, and other study materials.

In addition to core marketplace functionality, this project integrates **modern DevOps practices** to ensure continuous integration, automated deployment, scalability, and system reliability. The platform not only serves as a marketplace but also demonstrates real-world software development and deployment workflows used in industry.

---

## 🎯 Objectives
The primary objectives of this project are:

- To design and develop a **student-centric marketplace platform**  
- To enable seamless peer-to-peer transactions within a trusted environment  
- To reduce the cost of academic resources by promoting reuse  
- To implement a **CI/CD pipeline for automated build, testing, and deployment**  
- To ensure system scalability, availability, and performance using cloud technologies  
- To provide hands-on exposure to **DevOps tools and practices**

---

## ❗ Problem Statement
Students often encounter several challenges in their academic journey:

- High cost of textbooks, notes, and study materials  
- Difficulty in finding affordable second-hand resources  
- Lack of a dedicated and trusted platform for student transactions  
- Inefficient communication between buyers and sellers  

Traditional platforms such as generic e-commerce websites:
- Are not tailored for student needs  
- Lack verification mechanisms  
- Do not support academic-specific categories  

Additionally, most systems lack:
- Automated deployment pipelines  
- Scalability for increasing users  
- Real-time monitoring and maintenance  

---

## 💡 Proposed Solution
The proposed solution is a **web-based Student Marketplace Platform** that provides:

- A centralized system where students can register and create profiles  
- A product listing feature to upload notes, books, and other items  
- Advanced search and filtering options for easy navigation  
- Communication features to connect buyers and sellers  
- A secure and scalable backend infrastructure  

To enhance system efficiency and reliability, the platform integrates a **DevOps pipeline** that automates:
- Code integration  
- Testing  
- Deployment  
- Monitoring  

This ensures faster development cycles and high system availability.

---

## 🧩 System Modules

### 👤 User Module
- User registration and authentication (login/logout)  
- Profile creation and management  
- Secure session handling  

### 📦 Product Module
- Add new products (notes, books, electronics)  
- Edit or delete existing listings  
- View product details  

### 🔍 Search & Filter Module
- Search by keywords, subject, or category  
- Filter based on price, location, or type  
- Sort results for better usability  

### 💬 Communication Module
- Enables interaction between buyers and sellers  
- Messaging or contact system  
- Notification alerts  

### 🛠️ Admin Module
- Manage users and listings  
- Monitor system activity  
- Remove inappropriate content  

---

## 🏗️ System Architecture

<p align="center">
  <img src="docs/architecture.png" width="800"/>
</p>

### 🔹 Architecture Overview
The system follows a **3-tier architecture integrated with DevOps tools**:

1. **Presentation Layer (Frontend)**
   - Built using React.js  
   - Provides interactive and responsive user interface  

2. **Application Layer (Backend)**
   - Developed using Node.js and Express.js  
   - Handles business logic, APIs, and authentication  

3. **Data Layer (Database)**
   - MongoDB for storing user data, products, and messages  

### 🔹 DevOps Integration
- **Git & GitHub** → Version control  
- **CI/CD (GitHub Actions/Jenkins)** → Automated pipeline  
- **Docker** → Containerization  
- **AWS (EC2/S3)** → Deployment and hosting  
- **Nginx** → Reverse proxy and load balancing  
- **Prometheus & Grafana** → Monitoring and logging  

---

## 🔄 Workflow (DevOps Pipeline)

<p align="center">
  <img src="docs/workflow.png" width="800"/>
</p>

### 🔹 Workflow Explanation
1. Developer writes and updates code  
2. Code is pushed to GitHub repository  
3. CI/CD pipeline is triggered automatically  
4. Application is built and tested  
5. Docker container is created  
6. Application is deployed to AWS cloud server  
7. Nginx serves the application to users  
8. Monitoring tools track system performance and logs  

---

## 🛠️ Technology Stack

### 💻 Frontend
- React.js  
- HTML, CSS, JavaScript  

### ⚙️ Backend
- Node.js  
- Express.js  

### 🗄️ Database
- MongoDB  

### 🔧 DevOps Tools
- Git & GitHub  
- GitHub Actions / Jenkins  
- Docker  
- AWS (EC2, S3)  
- Nginx  
- Prometheus & Grafana  

---

## 🔐 Key Features
- Secure user authentication and authorization  
- Easy product listing and management  
- Efficient search and filtering system  
- Real-time communication capabilities  
- Automated deployment pipeline  
- Scalable and high-performance architecture  

---

## 📊 Unique Features
- Dedicated platform specifically for students  
- Integration of DevOps tools for automation  
- Real-time system monitoring  
- Cost-effective and user-friendly solution  

---

## 🚀 Future Scope
- Integration of secure online payment systems  
- AI-based product recommendations  
- Mobile application development  
- Kubernetes for container orchestration  
- Advanced analytics and reporting dashboard  

---

## 📌 Conclusion
The Student Marketplace Platform is a comprehensive solution that combines modern web technologies with DevOps practices to create a scalable and efficient system. It addresses real-world problems faced by students while also demonstrating industry-standard development and deployment methodologies.

This project not only enhances technical knowledge but also provides practical exposure to building and managing production-ready applications.

---