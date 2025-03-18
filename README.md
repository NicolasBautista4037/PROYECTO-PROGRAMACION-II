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

## **Posibles Tecnologías a Utilizar**  

1. **Telegram Bot API**  
   - Permite la comunicación entre los usuarios y el bot, procesando mensajes y comandos de manera fluida.  

2. **Python con Telebot / Node.js con Telegraf.js**  
   - Facilitan la implementación del chatbot, ofreciendo bibliotecas optimizadas para interactuar con Telegram y procesar datos.  

3. **Firebase Firestore**  
   - Almacena de manera segura las transacciones, presupuestos y configuraciones de usuario sin necesidad de gestionar servidores complejos.  

4. **Google Sheets API**  
   - Permite exportar los datos financieros a una hoja de cálculo, facilitando el análisis y almacenamiento de los registros del usuario.  

5. **Matplotlib / Pandas (Python)**  
   - Se utilizarán para generar reportes gráficos simples y análisis de patrones de gasto de los usuarios.  

6. **News API (Opcional)**  
   - Si se implementa el módulo de noticias, esta API permitirá obtener información actualizada sobre inversiones y tendencias del mercado.  
  
## **Flujo del Sistema**  

1. **Inicio y Autenticación**  
   - El usuario inicia una conversación con el bot en Telegram.  
   - Se valida su identidad a través de la API de Telegram.  
   - Se registra en Firebase Firestore si es un nuevo usuario.  

2. **Registro de Transacciones**  
   - El usuario ingresa un comando para añadir ingresos o egresos.  
   - El bot solicita detalles como monto, categoría y fecha.  
   - Los datos se almacenan en Firebase Firestore.  

3. **Generación de Reportes y Análisis**  
   - El usuario consulta su balance o categorías de gasto.  
   - El bot recupera y procesa los datos almacenados.  
   - Se generan reportes y gráficos utilizando Pandas y Matplotlib.  

4. **Gestión de Presupuestos y Recordatorios**  
   - El usuario define límites de gasto en diferentes categorías.  
   - Se configuran alertas cuando se alcanza un umbral de gasto.  
   - El bot envía recordatorios automáticos sobre pagos y presupuesto.  

5. **Interacción con Noticias y Tendencias Financieras (Opcional)**  
   - El bot obtiene información de inversión mediante News API.  
   - Se envían resúmenes periódicos de tendencias del mercado.  
   - El usuario puede consultar datos actualizados sobre sectores financieros.  

6. **Cierre de Sesión y Exportación de Datos**  
   - El usuario puede exportar su historial financiero a Google Sheets.  
   - Se permite cerrar sesión o eliminar su cuenta si lo desea.

## Cronograma de actividades

  - [Notion](https://www.notion.so/1ba0617628a88039bb99f026a0142996?v=1ba0617628a880e5a9fa000ca4f8fe97)

