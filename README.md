# 📌 Databricks Project - Computer Vision in Medical Imaging

### 🏥 Contexte

Ce projet explore l'utilisation de l'Intelligence Artificielle pour l'analyse d'images médicales au format DICOM.
L'objectif est d'appliquer des techniques de réduction de dimension (ACP) et de clustering (K-Means) pour identifier des structures et tendances dans les données d'imagerie médicale.
Le tout est développé dans Databricks, permettant une gestion efficace du stockage et du calcul distribué.

### 🗂️ Structure du projet

📁 My folder/

├── 📁 dicom_images/ → Contient les images médicales au format DICOM

├── 📄 config.py → Configuration du projet

├── 📄 test_dicom.zip → Archive contenant des images DICOM

├── 📓 Projet ACP Clustering DICOM → Notebook Databricks pour le traitement et l'analyse des images

### 🛠️ Technologies utilisées

🔹 Python (NumPy, Pydicom, OpenCV, Matplotlib, Scikit-learn)

🔹 Databricks (gestion des clusters, stockage DBFS, notebooks)

🔹 GitHub (versioning du projet)

🔹 MLflow (suivi des expérimentations - à venir)

### 🚀 Pipeline du projet

✅ Stockage des images DICOM dans DBFS

✅ Prétraitement des images (lecture, redimensionnement, normalisation)

✅ Détection d'anomalies (images trop petites, très sombres, métadonnées manquantes...)

✅ Réduction de dimension avec ACP (Analyse en Composantes Principales)

✅ Clustering des images avec K-Means

✅ Visualisation des résultats