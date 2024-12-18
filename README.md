# 📊 **Scopus Data Pipeline and Analytics Dashboard**

## 🚀 **Aperçu du Projet**

Ce projet met en place un pipeline de traitement de données complet en utilisant des outils modernes pour extraire, transformer et visualiser des données provenant de **Scopus** via une API. L'architecture ETL (Extract, Transform, Load) est construite pour assurer une transformation efficace des données et leur visualisation interactive.

---

## 📐 **Architecture du Projet**

![Architecture](path_to_image.png) <!-- Remplacez path_to_image par l'URL de l'image sur GitHub -->

Le pipeline se compose des étapes suivantes :

1. **Source de Données**  
   - **Scopus API** : Extraction des données brutes via des appels API.

2. **Stockage des Données Brutes**  
   - Utilisation de **Snowflake** pour stocker les données brutes extraites.

3. **Transformation des Données**  
   - **PySpark** est utilisé pour :
     - **Nettoyage des données** : Suppression des doublons et valeurs nulles.  
     - **Prétraitement des données** : Tokenization, normalisation, filtrage.  
     - **Modélisation des données** : Création de structures de tables optimisées.  

4. **Stockage des Tables**  
   - Stockage des tables factuelles et dimensionnelles dans **Microsoft SQL Server**.

5. **Visualisation des Données**  
   - Création de tableaux de bord interactifs avec **Power BI** pour l'analyse des données.

---

## 🛠️ **Outils et Technologies Utilisés**

| **Étape**                | **Technologie**                  |
|--------------------------|---------------------------------|
| Source de données        | Scopus                    |
| Stockage des données     | Snowflake                       |
| Transformation des données | PySpark                       |
| Stockage des tables      | Microsoft SQL Server            |
| Visualisation            | Power BI                        |


