
# ✈️ Flight Ticket Generator

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![POO](https://img.shields.io/badge/Object%20Oriented-Programming-blue?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Sistema de escritorio desarrollado en **Java** bajo el enfoque de **Programación Orientada a Objetos (POO)** que permite gestionar la emisión de tickets de vuelo y exportarlos en **PDF** y/o **TXT**.

---

## 🌟 Características Principales
✅ Registro simple de datos del pasajeros  
✅ Generación de tickets en formato **PDF** y/o **.TXT**  
✅ Interfaz gráfica con **Swing**  
✅ Uso de **clases, herencia y polimorfismo**  
✅ Código para practicar conceptos de POO

---

## 🧠 Estructura del Proyecto
| Carpeta           | Descripción                                                         |
|-------------------|---------------------------------------------------------------------|
| **/Datos**        | Contiene los objetos (cliente/fecha/pago/reserva/detalle_reserva)   |
| **/Frames**       | Frames internos (contacto/detalles/facturacion/confirmacion/etc.)   |
| **/Imagenes**     | Fondos de frames/login                                              |
| **/Interface**    | Modulos                                                             |  
| **/Ventas**       | UI/Main                                                             |

---

## 📸 Capturas

### 🔐 Login
![Login](./captures/login.jpg)

### 🏠 Inicio
![Home Screen](./captures/main.jpg)

### 📑 Detalles de Reserva
![Booking Details](./captures/p1.jpg)

### 📞 Información de Contacto
![Contact Info](./captures/p2.jpg)

### 💳 Facturación
![Billing](./captures/p3.jpg)

### ✅ Confirmación de Detalles
![Confirmation](./captures/p4.jpg)

### 🖨️ Terminar e Imprimir Ticket
![Print Ticket](./captures/p5.jpg)

### 📄 Ticket en PDF
![PDF Ticket](./screenshots/ticket_pdf.jpg)

---

## ⚙️ Cómo Ejecutar el Proyecto
```bash
# Clonar el repositorio
git clone https://github.com/JoseIlizarbe/flight-ticket-generator.git
cd flight-ticket-generator

# Compilar los archivos Java
javac -d bin src/pong/*.java

# Ejecutar la aplicación
java -cp bin pong.Ventana
```

---

## 🖥️ Requisitos
✅ **JDK 8** o superior  
✅ IDE recomendado: **IntelliJ IDEA / Eclipse / VS Code**  
✅ Sistema operativo: **Windows / Linux / macOS**

---

## 💾 Tecnologías Utilizadas
- **Java SE**
- **Swing** (Interfaz Gráfica)
- **POO (Programación Orientada a Objetos)**
- Generación de archivos PDF **ITextPDF**
- Look and Feel **JTattoo**

---

## 👨‍💻 Autor
Jose Ilizarbe  
[![GitHub](https://img.shields.io/badge/GitHub-JoseIlizarbe-black?style=for-the-badge&logo=github)](https://github.com/JoseIlizarbe)

---

## 📄 Licencia
Este proyecto está bajo la licencia [MIT](https://opensource.org/licenses/MIT). ¡Libre de usar y modificar!

---
