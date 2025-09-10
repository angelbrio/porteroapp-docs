# 🧤 PorteroApp  

![React](https://img.shields.io/badge/Frontend-React-61dafb?logo=react&logoColor=61dafb&labelColor=20232a)  
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?logo=firebase&logoColor=FFCA28&labelColor=20232a)  
![Status](https://img.shields.io/badge/Status-Online-success?style=flat&logo=google-chrome)  

**PorteroApp** es una aplicación web para registrar acciones de un portero durante el partido, gestionar porteros y registrar eventos en tiempo real ⚽🔥.  

👉 **Demo online:** [porteroapp-aeddd.web.app](https://porteroapp-aeddd.web.app)  

---

## 📸 Registro en la app

<img width="1701" height="1297" alt="image" src="https://github.com/user-attachments/assets/e54b0109-72f4-41cd-9fdc-09d554024cd2" />

## 📸 Creacion de portero
<img width="1702" height="1300" alt="image" src="https://github.com/user-attachments/assets/84cd8864-fd4d-4caf-9cc6-0df41e235c2f" />

## 📸 Creacion de partido

<img width="1703" height="1306" alt="image" src="https://github.com/user-attachments/assets/6e18c1ae-3602-4e9f-8b09-d61bce69c594" />

## 📸 Registro de acciones durnate el partido
<img width="1684" height="2128" alt="image" src="https://github.com/user-attachments/assets/c0bc6c52-4b7b-4fbd-9cf0-bf258901f868" />

<p align="center">
  <img src="docs/demo1.png" width="400" alt="Demo 1">
  <img src="docs/demo2.png" width="400" alt="Demo 2">
</p>

---

## 🚀 Características principales
- Registro e inicio de sesión con **Firebase Auth** 🔐.  
- Gestión de **partidos, eventos y porteros** en tiempo real con **Firestore** 📊.  
- Despliegue en la nube con **Firebase Hosting** ☁️.  
- Interfaz responsive hecha con **React + Hooks** ⚛️.  
- **Seguridad**: reglas en Firestore para proteger datos de los usuarios.  

---

## 🏗️ Arquitectura del proyecto
```ascii
         +-----------------+
         |    React App    |
         |  (PorteroApp)   |
         +--------+--------+
                  |
                  v
          [ Firebase SDK ]
                  |
    +-------------+-------------+
    |  Auth   |  Firestore  |  Hosting  |
    |  Users  |   Data RT   |   WebApp  |
    +---------+-------------+-----------+

🛠️ Tecnologías usadas

Frontend: React, JavaScript (ES6+), HTML5, CSS3.

Backend (BaaS): Firebase (Auth, Firestore, Hosting, Storage).

Control de versiones: Git + GitHub.

Despliegue: Firebase Hosting.

🔒 Seguridad

Reglas de Firestore para restringir acceso según usuario.

Verificación de email obligatoria.

Control de cuentas aprobadas automatica antes de habilitar acceso.

📌 Roadmap

Creacion de cuenta

Creacion de portero

Creacion de partidos de la temporada

✨ Autor

👤 Ángel Briones
📎 LinkedIn https://www.linkedin.com/in/angel-briones-munoz/
 · 📧 briones.angel.munoz@gmail.com

<p align="center"> Hecho con ❤️, ⚛️ y ☁️ <br> <sub>Proyecto personal desplegado con Firebase Hosting.</sub> </p> `
