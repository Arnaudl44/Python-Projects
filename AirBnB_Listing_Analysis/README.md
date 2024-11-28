# 🏠 AirBnB Listing Analysis

Analyse des annonces AirBnB à Paris pour évaluer l'impact des régulations récentes sur le marché.

## 📋 Contexte du projet
Avec la croissance de la popularité d'AirBnB, Paris est devenu une cible majeure des régulations visant à limiter le nombre de propriétés disponibles. Ce projet explore ces impacts.

## 🛠️ Outils utilisés
- **Python** : pandas, matplotlib, seaborn
- **Données** : Listings AirBnB à Paris (source : fichier `Listings.csv`)

## 📊 Objectifs
1. Profiler et nettoyer les données.
2. Préparer les données pour la visualisation.
3. Visualiser et analyser les tendances.

## 🚀 Insights clés
### Impact des régulations de 2015 :
- 📉 **Baisse significative** des nouveaux hôtes après 2015.
- 📈 **Légère augmentation des prix moyens**, suggérant une adaptation à la réduction de l'offre.

### Prix moyens par quartier :
- 🏙️ **Les plus chers** : Elysée, Louvre, Champs-Élysées (>150€/nuit).
- 🏘️ **Les moins chers** : Quartiers périphériques (<70€/nuit).

### Prix et capacité d'accueil :
- 💰 Dans le quartier **Elysée**, le prix augmente avec la capacité, mais se stabilise au-delà de **6 personnes**.
- 🏡 Les **grandes capacités (5+ personnes)** offrent un meilleur prix par personne.

### Tendance des nouveaux hôtes :
- 📈 **Croissance régulière** avant 2015.
- 📉 **Forte chute** après 2015, liée aux régulations.

### Saisonnalité :
- 📆 **Forte variation saisonnière** en périphérie (été/fêtes).
- 🔒 **Stabilité des prix élevés** dans les quartiers centraux, témoignant d'une demande constante.


## 📂 Structure des fichiers
- **AirBnB_Listing_Analysis.ipynb** : Script Python contenant toute l'analyse.
- **data/** : Dossier contenant les fichiers de données.
- **README.md** : Explications du projet.

---

### 4️⃣ **Ajouter et pousser les fichiers sur GitHub**
1. Clonez votre repository GitHub en local :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-repository.git
