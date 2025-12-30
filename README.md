## 🚀 Projets phares

### 1️⃣ People Analytics – Analyse de l’attrition des employés
**Problème métier**  
Taux d’attrition élevé et manque de visibilité sur les facteurs réels de départ des employés, rendant les décisions RH peu ciblées.

**Approche analytique**  
- Analyse exploratoire des données RH (âge, ancienneté, performance, satisfaction)
- Segmentation des profils à risque
- Identification des variables les plus corrélées à l’attrition

**Stack technique**  
Python (Pandas, NumPy, Matplotlib), Jupyter Notebook

**Impact & valeur métier**  
- Mise en évidence de leviers RH actionnables (ancienneté, surcharge de travail, satisfaction)
- Aide à la priorisation des actions de rétention
- Support analytique à la prise de décision stratégique RH
  
![Attrition des employés en fonction de l’ancienneté](images/attrition_par_anciennete.png)

---

### 📡 Telecom – Qualité de Service (QoS)

**Problématique**  
Comment synthétiser la qualité de la voix réseau afin de comparer objectivement les performances selon les environnements (urbain, rural, indoor, outdoor) et identifier les zones à risque ?

**Approche analytique**  
Construction d’un **score voix composite (0–100)** à partir de plusieurs KPI réseau (délai d’établissement, taux de réussite des appels, qualité radio, MOS), avec pondération et normalisation des indicateurs.

**Impact métier**  
- Comparaison claire de la performance voix par environnement  
- Identification automatique des environnements à risque  
- Aide à la priorisation des actions d’optimisation réseau

![Score voix par environnement](images/score_voix_par_environnement.png)

---

### 3️⃣ Visualisation interactive – Carte MOS

![Carte statique MOS voix – ARCEP 2022](images/Leaflet_statique.png)

*Lecture métier : cette carte met en évidence la distribution géographique des points de mesure MOS voix et permet d’identifier rapidement les zones de performance hétérogène, en particulier sur les axes de transport et en zones peu denses.*

**Problème métier**  
Données techniques difficiles à interpréter rapidement par des profils non techniques.

**Approche analytique**  
- Transformation des données brutes en visualisation interactive
- Carte statique intégrée au README pour un accès immédiat et lisible
- Stack technique : HTML, JavaScript, Leaflet

**Stack technique**  
HTML, JavaScript, Leaflet

**Impact & valeur métier**  
- Réduction du temps de compréhension des données pour les décideurs
- Support visuel pour la prise de décision tout en maintenant la clarté.
- Version interactive complète disponible via le lien, avec possibilité d’explorer les points MOS voix, zoom et popups

[Carte interactive P1 – Visualisation complète](https://nancy-jennifer.github.io/carte-leaflet/carte_leaflet_mos.html)

