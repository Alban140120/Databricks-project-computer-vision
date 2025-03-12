# 📌 Databricks Project - Computer Vision in Medical Imaging

## 🏥 Contexte

Ce projet vise à explorer l'utilisation de l'Intelligence Artificielle et du Deep Learning pour l'analyse d'images médicales au format DICOM. L'objectif est de créer un modèle capable d'identifier la présence d'un cancer à partir d'images médicales, en s'appuyant sur Databricks comme environnement de développement.

## 🗂️ Structure du projet

📁 My folder/

├── 📁 dicom_images/ → Contient les images médicales au format DICOM

├── 📄 config.py → Configuration du projet

├── 📄 test_dicom.zip → Archive contenant des images DICOM

├── 📓 Projet ml computer vision medical → Notebook Databricks pour l'entraînement du modèle

## 🛠️ Technologies utilisées

Python (TensorFlow, Keras, OpenCV, NumPy, Pydicom)

Databricks (gestion des clusters, stockage DBFS, notebooks)

GitHub (versioning du projet)

MLflow (suivi des expériences ML - à venir)

## 🚀 Pipeline du projet

Stockage des images dans DBFS

Prétraitement des images (lecture, redimensionnement, normalisation)

Entraînement d’un modèle de Deep Learning (CNN avec TensorFlow/Keras)

Évaluation du modèle sur un jeu de test

Déploiement futur d’une application de prédiction

## 🔜 Prochaines étapes

📌 Créer le modèle de Deep Learning

📌 Affiner le modèle en testant différentes architectures

📌 Optimiser l’entraînement pour améliorer les performances

📌 Développer une interface permettant d’uploader une image et obtenir une prédiction

## 📝 Notes

Ce projet est en cours de développement et fera l’objet d'améliorations régulières.