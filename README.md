# RETO ENSEÑA ORACLE 4.0: Hack The World Cup 2026 
# Equipo: Recreativo de WHERE V=A
# Integrantes: Alberto Gallego (GitHub: alberto95GT), Javier Campos (javicc22), Hugo Enríquez (hugoenriquez04)


*Nota: La versión en inglés se encuentra más abajo (English version below).*

### Descripción del Proyecto
Este repositorio contiene el proyecto final desarrollado para el Hackathon Reto Enseña 4.0 de Oracle. Nuestro equipo diseñó e implementó una solución alojada en Oracle Cloud Infrastructure (OCI) que combina Machine Learning y un Agente de IA Generativa para predecir y analizar resultados del Mundial de Fútbol 2026.

### Arquitectura y Tecnologías
* OCI Data Science y Jupyter Notebooks: Entorno utilizado para el análisis exploratorio de datos, ingeniería de características (como calificaciones ELO y rendimiento histórico de partidos) y el entrenamiento del modelo predictivo.
* Oracle APEX: Desarrollo de la interfaz de usuario y el frontend de la aplicación web ("World Cup 2026 Analytics") donde se visualizan los datos históricos y las predicciones.
* IA Generativa: Integración de un agente conversacional dentro de la aplicación para interactuar con las predicciones del modelo y responder consultas de los usuarios.
* PL/SQL y SQL: Gestión de la base de datos autónoma de Oracle y lógica interna de la aplicación.

### Estructura del Repositorio
* `/notebooks`: Contiene el Jupyter Notebook principal ("wc2026_predictions_notebook.ipynb") con todo el flujo de trabajo de ciencia de datos.
* `/apex_app`: Contiene el archivo de exportación de la aplicación de Oracle APEX ("Export_WC2026_Analytics.sql") y la carpeta de datos "READABLE".
* `/images`: Capturas de pantalla de la interfaz de la aplicación, el módulo de predicciones y el asistente de IA.

### Demostración
La explicación detallada de la arquitectura y la demostración de la aplicación se encuentra disponible en el video adjunto en este enlace de Google drive: https://drive.google.com/file/d/1rfjOO8-2IORal1b9Rv5iwYjrIj6MOkZk/view?usp=drive_link

---

## English Version

### Project Description
This repository contains the final project developed for the Oracle Reto Enseña 4.0 Hackathon. Our team designed and implemented an end-to-end solution hosted on Oracle Cloud Infrastructure (OCI) that combines Machine Learning and a Generative AI Agent to predict and analyze the 2026 FIFA World Cup results.

### Architecture and Technologies
* OCI Data Science & Jupyter Notebooks: Environment used for exploratory data analysis, feature engineering (including ELO ratings and historical match momentum), and predictive model training.
* Oracle APEX: Used to build the user interface and frontend of the web application ("World Cup 2026 Analytics") to display historical data and tournament predictions.
* Generative AI: Integration of a conversational agent within the application to interact with the model's predictions and answer user queries.
* PL/SQL & SQL: Used for managing the Oracle Autonomous Database and the internal application logic.

### Repository Structure
* `/notebooks`: Contains the main Jupyter Notebook ("wc2026_predictions_notebook.ipynb") covering the data science workflow.
* `/apex_app`: Contains the Oracle APEX application export file ("Export_WC2026_Analytics.sql") along with the "READABLE" data folder.
* `/images`: Screenshots of the application interface, prediction module, and the AI assistant.

### Demonstration
A detailed explanation of the architecture and a live demonstration of the application are available in the video attached to this Google Drive link: https://drive.google.com/file/d/1rfjOO8-2IORal1b9Rv5iwYjrIj6MOkZk/view?usp=drive_link