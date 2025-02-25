---
title: "Radhwen Saidi - Portfolio"
description: "Portfolio professionnel de Radhwen Saidi, Data Scientist et Machine Learning Engineer."
theme: jekyll-theme-slate
author: Radhwen Saidi
show_downloads: false
permalink: /index.html
---

![Radhwen Saidi](radhwen.png)

# Radhwen Saidi - Data Scientist | Machine Learning Engineer 💡

Bienvenue sur mon portfolio professionnel ! Je suis **Radhwen Saidi**, un **Data Scientist** et **Machine Learning Engineer** expérimenté, spécialisé dans le développement de solutions innovantes en **IA, Machine Learning, et MLOps**. Mon expertise me permet de transformer vos données en valeur stratégique et opérationnelle.

---

## 🧑‍💼 À propos de moi
- 🎓 **Diplômes** :
  - Mastère Spécialisé en Sciences des Données - INSA Rouen Normandie, France *(2022-2023)*
  - Diplôme d’Ingénieur en Informatique - ENSIM, Le Mans, France *(2020-2022)*
  - Diplôme d’Ingénieur en Informatique - ESPRIT, Tunisie *(2018-2020)*
- ✨ **Langues** :
  - Français : Courant
  - Anglais : Professionnel *(TOEIC : 865)*
  - Allemand : A2.2
- 📧 **Contact** : [radhwen.saidi@outlook.com](mailto:radhwen.saidi@outlook.com)

---

## 🗂️ Sections

<div>
  <button class="tablink" onclick="openTab(event, 'Expériences')">Expériences Professionnelles</button>
  <button class="tablink" onclick="openTab(event, 'Compétences')">Compétences Techniques</button>
  <button class="tablink" onclick="openTab(event, 'Certifications')">Certifications</button>
  <button class="tablink" onclick="openTab(event, 'Contact')">Contact</button>
</div>

<!-- Expériences Professionnelles -->
<div id="Expériences" class="tabcontent">
  
### **Data Scientist - ONEY Banque (France)** *(Octobre 2023 - Aujourd'hui)*
- **Modélisation IA stratégique** : Solutions ML pour détection de fraude, scoring crédit, segmentation client.
- **Applications analytiques** : Automatisation des analyses, monitoring des modèles, alertes et plans d’action.
- **Amélioration continue** : Optimisation des modèles pour une robustesse et une performance accrues.
- **Tech Stack** : `Python`, `R`, `SQL`, `Databricks`, `MLflow`, `PySpark`, `Snowflake`.

---

### **Data Scientist - Crédit Agricole Consumer Finance (France)** *(Octobre 2022 - Septembre 2023)*
- **Projet NLP** :
  - Classification de transactions bancaires avec fine-tuning de modèles **BERT**.
  - Prétraitements avancés des données avec **Regex**.
- **Projet Open Banking** :
  - Modèle de scoring crédit avec **XGBoost**, traçabilité via **MLflow**, interprétabilité avec **SHAP**.
- **Tech Stack** : `Python`, `Transformers`, `TensorFlow`, `MLflow`, `SQL`.

---

### **Stage Data Scientist - E-nno Switzerland SA (Genève, Suisse)** *(Mars 2022 - Septembre 2022)*
- Détection d’anomalies énergétiques avec ingestion cloud sur **AWS**.
- Déploiement scalable avec **Docker**, **GitLab CI/CD**, et orchestration **Kubernetes**.
- Monitoring via **Grafana** et gestion des workflows avec **Airflow**.
- **Tech Stack** : `Docker`, `AWS`, `PostgreSQL`, `Grafana`, `CI/CD`.

---

### **Stage Data Scientist - Teamwill Consulting (Paris, France)** *(Juillet 2021 - Septembre 2021)*
- Plateforme IA pour prédire le succès de projets de crowdfunding avec analyse sentimentale.
- Développement d’un chatbot conversationnel basé sur **Keras**.
- Déploiement cloud sur **AWS** avec **Flask**.
- **Tech Stack** : `Python`, `Flask`, `AWS`, `NLP`.

</div>

<!-- Compétences Techniques -->
<div id="Compétences" class="tabcontent">

## ⚙️ Compétences Techniques

### 🛠 Langages et Frameworks
- **Python**, **R**, **Flask**, **Java**, **C#**

### 🤖 Machine Learning et IA
- **Scikit-learn**, **PyTorch**, **TensorFlow**, **NLP**, **LLMs** (LangChain, LangGraph, RAG, Fine-tuning)

### ☁️ Big Data et Cloud
- **Spark/PySpark**, **SQL/NOSQL**, **AWS** (EC2, S3, ECR, SageMaker), **Heroku**, **Snowflake**, **Databricks**

### 🔄 MLOps et Déploiement
- **Docker**, **Airflow**, **MLflow**, **CI/CD**, **GitHub/GitLab**, **Streamlit**, **FastAPI**, **Poetry**, **Grafana**

### 📊 Visualisation de Données
- **Power BI**, **Plotly**, **Seaborn**, **Matplotlib**

</div>

<!-- Certifications -->
<div id="Certifications" class="tabcontent">

## 📚 Certifications
- **Machine Learning Scientist** - DataCamp
- **Deep Learning Specialization** - Coursera
- **TOEIC 865** - Anglais Professionnel

</div>

<!-- Contact -->
<div id="Contact" class="tabcontent">

## 🌐 Me Contacter

- **Email** : [radhwen.saidi@outlook.com](mailto:radhwen.saidi@outlook.com)
- **Téléphone** : +33 7 83 90 61 17
- **LinkedIn** : [Mon Profil LinkedIn](https://www.linkedin.com/in/radhwen-saidi/)
- **GitHub** : [Mon GitHub](https://github.com/radhwen-saidi)

</div>

---

### 📈 Améliorations Techniques

Pour implémenter des onglets dans votre GitHub Pages, vous pouvez ajouter du JavaScript et du CSS directement dans votre `README.md`. Voici un exemple de code à ajouter au début ou à la fin de votre fichier pour gérer les onglets :

```html
<style>
/* Style les boutons des onglets */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style le contenu des onglets */
.tabcontent {
  display: none;
  padding: 20px;
  border-top: none;
}

/* Style actif de l'onglet */
.tablink.active {
  background-color: #111;
}
</style>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Ouvre le premier onglet par défaut
document.addEventListener("DOMContentLoaded", function(){
  document.querySelector(".tablink").click();
});
</script>
