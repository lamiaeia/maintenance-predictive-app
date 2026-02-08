#  Maintenance Prédictive – Application Flask

Cette application Flask permet de **prédire le risque de panne d’une machine industrielle**
et d’estimer le **temps de vie restant (RUL – Remaining Useful Life)** à l’aide de modèles
de **Machine Learning**.

---

##  Fonctionnalités

-  Authentification des utilisateurs (Login / Inscription)
- Saisie manuelle des caractéristiques de la machine  
  (Température, Vitesse, Couple, Usure, Type)
-  Prédiction du risque de panne (Random Forest)
-  Estimation du temps restant avant panne (Modèle de Cox)
-  Tableau de bord d’analyse (KPI, Graphiques, Radar)
-  Historique des prédictions par utilisateur
-  Interface moderne (HTML / CSS)

---

## 🛠 Technologies utilisées

- **Backend :** Python / Flask
- **Machine Learning :**
  - Random Forest (Prédiction de panne)
  - Cox Proportional Hazards (Estimation RUL)
- **Data :** Pandas / NumPy
- **Visualisation :** Matplotlib
- **Base de données :** SQLite (SQLAlchemy)
- **Frontend :** HTML5 / CSS3

---

##  Installation & Lancement

1. **Cloner le projet**
   ```bash
   git clone https://github.com/VOTRE_NOM/maintenance-predictive-app.git
