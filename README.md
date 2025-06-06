# 📦 Analyse des Ventes Amazon

## 🎯 Objectif
Ce projet a pour objectif d'analyser les ventes réalisées sur Amazon afin d'en tirer des enseignements stratégiques. Il s'agit d'identifier les produits les plus performants, d’observer les tendances de consommation au fil du temps, et de formuler des recommandations pour optimiser les ventes et la rentabilité.

---

## 🗂️ Données
- **Source :** Fichier CSV fourni (vente Amazon)
- **Nombre de lignes :** 1465 lignes
- **Nombre de colonnes :** 16 colonnes
- **Colonnes clés :**
      - 'product_id', 'product_name', 'category', 'discounted_price',
       'actual_price', 'discount_percentage', 'rating', 'rating_count',
       'about_product', 'user_id', 'user_name', 'review_id', 'review_title',
       'review_content', 'img_link', 'product_link'

---

## 🧰 Outils et librairies
- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- textblob

---

## 📊 Analyses réalisées

1. **Nettoyage des données**
   - Vérification et gestion des valeurs manquantes
   - Convertion de certaines colonnes en float
   - Vérification et gestion des doublons

2. **Analyse de corrélation**

3. **Regroupement et agrégation**
   - Calcul des statistiques sommaires
   - Création de tableaux croisés dynamiques

---

## 📈 Visualisations
   - Nuage de points (relation entre le prix réel et la note)
   - Histogramme (Distribution du prix réel)
   - Heatmap (Matrice de corrélation)

---

## 🗃️ Fichiers inclus
- `amazon.ipynb` : Notebook complet contenant le code, les analyses et les visualisations
- `data_amazon.csv` : jeu de données source

---

## 🚀 Pour exécuter ce projet
1. Cloner le repo :
   ```bash
   git clone https://github.com/LouisD92/amazon-sales-analysis.git


