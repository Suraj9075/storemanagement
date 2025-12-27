# Store Management System

A full-stack **Store Management System** built with **Java Spring Boot** (backend) and **Angular** (frontend) using **HTML, CSS, and TypeScript**.

This application allows managing products, categories, and store operations through a clean UI powered by Angular and a robust REST API powered by Spring Boot.

---

## 🧰 Technology Stack

- 🔹 **Backend:** Java Spring Boot (REST API)
- 🔹 **Frontend:** Angular (TypeScript, HTML, CSS)
- 🔹 **Database:** (Your choice — e.g., MySQL / H2 / PostgreSQL)
- 🔹 **UI:** Responsive Web Pages
- 🔹 **Build Tools:** Maven (Backend), Angular CLI (Frontend)

---

## 📁 Project Structure

storemanagement/

├── store-frontend/ # Angular frontend

│ ├── src/

│ ├── angular.json

│ └── ...

├── store.manegement/ # Spring Boot backend

│ ├── src/

│ ├── pom.xml

│ └── ...

├── .gitignore

├── README.md


---

## 🛠️ Features

✔ Create, Read, Update, Delete (CRUD) Products  
✔ Category Management  
✔ REST APIs using Spring Boot  
✔ Single Page Application using Angular  
✔ Dynamic UI with TypeScript + HTML + CSS

---

## 🚀 Setup Instructions

### Backend

1. Go to the backend folder:
   
    bash

    cd store.manegement


2. Build & run the Spring Boot app
   
    mvn clean install

    mvn spring-boot:run

### FRONTEND


1. Go to the frontend folder:
cd store-frontend


2. Install Angular dependencies:
npm install


3. Start the Angular app:
ng serve --open
