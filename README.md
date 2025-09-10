# 🧤 PorteroApp  

![React](https://img.shields.io/badge/Frontend-React-61dafb?logo=react&logoColor=61dafb&labelColor=20232a)  
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?logo=firebase&logoColor=FFCA28&labelColor=20232a)  
![Status](https://img.shields.io/badge/Status-Online-success?style=flat&logo=google-chrome)  

**PorteroApp** es una aplicación web para organizar partidos de fútbol, gestionar porteros y registrar eventos en tiempo real ⚽🔥.  

👉 **Demo online:** [porteroapp-aeddd.web.app](https://porteroapp-aeddd.web.app)  

---

## 📸 Capturas
*(añade aquí imágenes o gifs mostrando tu app)*  

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

Control de cuentas aprobadas manualmente antes de habilitar acceso.

📌 Roadmap

 Añadir estadísticas por portero.

 Mejorar interfaz de usuario.

 Implementar notificaciones push.

 Crear panel de administración para aprobar cuentas.

✨ Autor

👤 Ángel Brio
📎 LinkedIn
 · 📧 contacto@example.com

<p align="center"> Hecho con ❤️, ⚛️ y ☁️ <br> <sub>Proyecto personal desplegado con Firebase Hosting.</sub> </p> `
