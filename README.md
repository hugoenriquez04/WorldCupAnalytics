# ORACLE RETO ENSEÑA 4.0: Hack The World Cup 2026
# Team: Recreativo de WHERE V=A
# Members: Alberto Gallego (GitHub: alberto95GT), Javier Campos (javicc22), Hugo Enríquez (hugoenriquez04)

### Project Description
This repository contains the final project developed for the Oracle Reto Enseña 4.0 Hackathon. Our team designed and implemented a solution hosted on Oracle Cloud Infrastructure (OCI) that combines Machine Learning and a Generative AI Agent to predict and analyze the results of the 2026 FIFA World Cup.

### Architecture and Technologies
* OCI Data Science and Jupyter Notebooks: Environment used for exploratory data analysis, feature engineering (including ELO ratings and historical match performance), and predictive model training.
* Oracle APEX: Used to develop the user interface and frontend of the web application ("World Cup 2026 Analytics"), where historical data and predictions are displayed.
* Generative AI: Integration of a conversational agent within the application to interact with the model's predictions and answer user queries.
* PL/SQL and SQL: Used to manage the Oracle Autonomous Database and the application's internal logic.

### Repository Structure
* `/notebooks`: Contains the main Jupyter Notebook (`wc2026_predictions_notebook.ipynb`) with the complete data science workflow.
* `/apex_app`: Contains the Oracle APEX application export file (`Export_WC2026_Analytics.sql`) and the `READABLE` data folder.
* `/images`: Contains screenshots of the application interface, prediction module, and AI assistant.

### Demonstration
A detailed explanation of the architecture and a demonstration of the application are available in the video at this Google Drive link:
https://drive.google.com/file/d/1rfjOO8-2IORal1b9Rv5iwYjrIj6MOkZk/view?usp=drive_link
