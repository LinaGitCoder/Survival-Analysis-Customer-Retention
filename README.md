# ⏳ Analyse de Survie : Modélisation de la Rétention Client

## 📌 Présentation du Projet
Ce projet dépasse la simple classification binaire pour s'intéresser à la **dimension temporelle** du départ client. L'objectif est de prédire *quand* un événement (churn, fin de contrat) est susceptible de se produire.

## 🛠️ Expertise Statistique
* **Librairie spécialisée :** `lifelines`
* **Courbes de Kaplan-Meier :** Estimation de la fonction de survie globale.
* **Test du Log-Rank :** Comparaison statistique des durées de survie entre différents segments (ex: selon le type de contrat).
* **Interprétation :** Analyse des données censurées (clients toujours actifs au moment de l'étude).

## 📊 Insights Clés
* Visualisation de la probabilité de rétention au fil des mois.
* Identification des points de rupture temporels où le risque de départ est le plus élevé.

## 🔍 Comment consulter le projet ?
1. **Lecture rapide :** Fichier `Customer_Survival_Analysis.ipynb` sur GitHub.
2. **Exécution interactive :** Bouton **"Open in Colab"** dans le notebook.
