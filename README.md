**Analyse de la Qualité des Pommes avec Machine Learning**  
**Auteur :** BAH Saikou  

---

### **1. Introduction & Objectif**  
L'objectif de ce projet est d'analyser la qualité des pommes en utilisant plusieurs modèles de machine learning. En explorant un jeu de données spécifique, nous cherchons à :  
- Identifier les facteurs influençant la qualité des pommes.  
- Détecter d’éventuelles anomalies ou valeurs aberrantes.  
- Construire des visualisations pour mieux comprendre les données.  
- Comparer différentes approches de classification afin de trouver le modèle le plus performant.  

Ce projet met en pratique plusieurs techniques de data science : nettoyage des données, visualisation, ingénierie des caractéristiques et modélisation avec des algorithmes avancés.

---

### **2. Contenu du Projet**  

- **Exploration des données** : nettoyage, analyse univariée et bivariée.  
- **Prétraitement des données** : gestion des valeurs aberrantes et mise à l’échelle.  
- **Modélisation** : comparaison de plusieurs modèles (XGBoost, Random Forest, SVM, KNN, LGBM).  
- **Optimisation** : ajustement des hyperparamètres pour améliorer les performances.  
- **Interprétation des résultats** : évaluation des modèles avec des métriques clés et courbes ROC.  

---

### **3. Installation & Prérequis**  
#### **Environnement**  
Ce projet est conçu pour fonctionner dans un environnement Python (Jupyter Notebook ou script Python). Il est recommandé d’utiliser un environnement virtuel Conda.  

#### **Dépendances**  
Les bibliothèques nécessaires sont listées ci-dessous :  

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm
```

---

### **4. Jeux de Données**  
Le dataset utilisé contient plusieurs variables relatives aux caractéristiques des pommes (taille, poids, acidité, etc.), avec une variable cible **"Quality"** indiquant si une pomme est "bonne" ou "mauvaise".  

---

### **5. Modélisation & Résultats**  
Nous avons testé plusieurs modèles pour prédire la qualité des pommes :  

| Modèle                | Accuracy | ROC-AUC |
|-----------------------|----------|---------|
| **XGBoost Optimisé**  | 96.3%    | 97.0%   |
| **SVC Optimisé**      | 95.9%    | 96.5%   |
| Random Forest        | 89.9%    | 95.7%   |
| LGBM                 | 90.6%    | 96.1%   |
| KNN                  | 88.7%    | 95.1%   |

Les meilleurs modèles sont **XGBoost Optimisé** et **SVC Optimisé**, offrant les meilleures performances en termes de classification et de séparation des classes.

---

### **6. Difficultés & Défis**  
- **Présence de valeurs aberrantes** : Certaines caractéristiques présentaient de fortes variations, nécessitant des transformations et une mise à l’échelle.  
- **Données déséquilibrées** : Bien que les classes soient relativement équilibrées, il a fallu veiller à ne pas biaiser les modèles.  
- **Choix du meilleur modèle** : Plusieurs modèles ont été comparés, et un ajustement des hyperparamètres a permis d’obtenir de meilleures performances.  

---

### **7. Comment Contribuer ?**  
Toute amélioration ou suggestion est la bienvenue ! Vous pouvez contribuer en :  
- Proposant des améliorations sur la sélection des caractéristiques.  
- Expérimentant d'autres techniques de normalisation ou d'autres modèles.  
- Testant le projet sur d'autres types de fruits pour généraliser l’approche.  

---

### **8. Conclusion**  
Ce projet a permis d’explorer une problématique réelle en data science : la classification d'objets (ici des pommes) à partir de données numériques.  
Les résultats obtenus sont encourageants, avec des modèles capables de bien discriminer les pommes de bonne et de mauvaise qualité.  

---

### **9. Contact**  
Pour toute question ou suggestion, n'hésitez pas à me contacter : **https://saikou-bah.github.io/mon_site_public/**  

---
