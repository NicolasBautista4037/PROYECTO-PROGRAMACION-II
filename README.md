# PROYECTO-PROGRAMACION-II
Este repositorio contiene todo lo relacionado con el desarrollo del proyecto para la asignatura de programacion II

# Bot Gestor de Finanzas Personales

## Breve Descripción del Problema que Resuelve

Muchos usuarios tienen dificultades para gestionar sus finanzas de manera eficiente, lo que puede llevar a gastos innecesarios, falta de planificación y desequilibrios en su presupuesto. (opcional) Además, el acceso limitado a información sobre tendencias financieras e inversión dificulta la toma de decisiones estratégicas. Este proyecto soluciona este problema al ofrecer un chatbot en Telegram que permite:
- Registrar y clasificar ingresos y egresos.
- Generar reportes interactivos de gastos.
- Recibir recordatorios inteligentes sobre pagos y presupuestos.
- Brindar asesoría financiera básica de forma automatizada mediante análisis de patrones de gasto, alertas de exceso, sugerencias de ahorro y consejos de 
  compras inteligentes.
- Recibir noticias de inversión y tendencias del mercado. (Opcional) 

## Integrantes del Equipo

- [Johán Nicolás Bautista Raba](https://github.com/NicolasBautista4037)

## Lista Inicial de Módulos del Sistema

1. **Autenticación y Gestión de Usuarios:**  
   - Registro e inicio de sesión a través de la API de Telegram.  
   - Gestión segura de la información personal.

2. **Procesamiento de Datos:**  
   - Registro y clasificación de transacciones (ingresos y egresos).  
   - Generación de reportes y gráficos interactivos para el análisis financiero.

3. **Interfaz e Interacción (Chatbot de Telegram):**  
   - Comunicación en tiempo real para la introducción de datos y consulta de reportes.  
   - Comandos para gestionar transacciones, presupuestos y recordatorios.

4. **Módulo de Noticias y Tendencias Financieras (Opcional):**  
   - Integración con APIs de noticias económicas y de inversión.
   - Resúmenes periódicos sobre tendencias del mercado.

## **Posibles Tecnologías Usadas**   
### **1️⃣ Telegram Bot API**  
   **¿Por qué?** Permite la comunicación entre los usuarios y el bot, procesando mensajes y comandos de manera fluida.  

### **2️⃣ Python con Telebot / Node.js con Telegraf.js**  
   **¿Por qué?** Facilitan la implementación del chatbot, ofreciendo bibliotecas optimizadas para interactuar con Telegram y procesar datos.  

### **3️⃣ Firebase Firestore**  
   **¿Por qué?** Almacena de manera segura las transacciones, presupuestos y configuraciones de usuario sin necesidad de gestionar servidores complejos.  

### **4️⃣ Google Sheets API**  
   **¿Por qué?** Permite exportar los datos financieros a una hoja de cálculo, facilitando el análisis y almacenamiento de los registros del usuario.  

### **5️⃣ Matplotlib / Pandas (Python)**  
   **¿Por qué?** Se utilizarán para generar reportes gráficos simples y análisis de patrones de gasto de los usuarios.  

### **6️⃣ News API (Opcional)**  
   **¿Por qué?** Si se implementa el módulo de noticias, esta API permitirá obtener información actualizada sobre inversiones y tendencias del mercado.  



