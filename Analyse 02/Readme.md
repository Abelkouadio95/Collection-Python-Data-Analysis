# 📊 Analyse des Rendez-vous Médicaux – EDA et Insights

## 📌 Contexte
Ce projet se base sur un dataset de rendez-vous médicaux afin d’analyser les facteurs qui influencent la présence ou l'absence des patients à leurs consultations.  
L’objectif est de répondre à plusieurs questions clés grâce à une **analyse exploratoire des données (EDA)** et à la visualisation, en mettant en lumière les tendances et comportements liés aux absences.

Les données incluent des informations telles que :
- **Genre** des patients  
- **Âge**  
- **Présence ou absence** au rendez-vous (`No-show`)  
- **Rappels SMS**  
- **Bourses de santé (Scholarship)**  
- **Problèmes médicaux** (Hypertension, diabète, etc.)  
- **Délai entre la prise et la date du rendez-vous**  

---

## 🎯 Questions explorées
1. 👫 **Genre** – À quelle fréquence les hommes vont-ils à l’hôpital par rapport aux femmes ? Qui est le plus susceptible de se présenter ?
2. 📱 **Rappel SMS** – Recevoir un SMS de rappel augmente-t-il les chances de présence ? Influence du délai entre la prise et la date du rendez-vous ?
3. 🎓 **Bourse (Scholarship)** – Impact sur la présence ? Quels groupes d’âge sont les plus concernés ?
4. 🩺 **Conditions médicales** – Influence de maladies comme l’hypertension, le diabète, l’alcoolisme ou le handicap ? Variations selon le genre ?
5. 📅 **Jour de la semaine** – Y a-t-il des pics ou baisses d’absentéisme selon le jour ?
6. ⏳ **Délai d’attente** – Le temps entre la réservation et le rendez-vous impacte-t-il la présence ?
7. 👶👴 **Âge** – Les jeunes ou les seniors sont-ils plus assidus ?

---

## 📈 Visualisations utilisées
- **Histogrammes** : distribution de l’âge, répartition homme/femme  
- **Bar charts** : taux de présence selon le genre, les rappels SMS, et la bourse  
- **Boxplots** : relation entre délai d’attente et présence  
- **Heatmaps** : corrélations entre variables  
- **Countplots** : absentéisme par jour de la semaine et par condition médicale  

---

## 🛠️ Technologies utilisées
- **Python**  
- **Pandas** – manipulation et nettoyage des données  
- **Matplotlib** & **Seaborn** – visualisations  
- **NumPy** – calculs et statistiques  

---

## 🚀 Résultats clés
- 📱 Les rappels SMS **ne garantissent pas** la présence mais peuvent influencer légèrement selon le délai.  
- 🎓 Les bénéficiaires de bourses présentent un taux d’absence plus marqué, surtout chez certains groupes d’âge.  
- 👫 Les femmes représentent une plus grande proportion des rendez-vous, mais l’écart de présence avec les hommes est faible.  
- 📅 Certains jours affichent un absentéisme plus élevé, notamment en début de semaine.  

---

## 📂 Structure du projet
├── HospitalAppointment.ipynb # Notebook d'analyse et visualisations

├── README.md # Présentation du projet

└── data/ # Dataset
