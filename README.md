# ☀️ PV-AI Forecast

### Prévision de la production photovoltaïque par Intelligence Artificielle

**Projet de recherche scientifique**

---

## 🔬 À propos

**PV-AI Forecast** est un projet de recherche consacré à la prévision de la production photovoltaïque à partir de données réelles.

Le système étudie trois horizons de prévision :

**+15 min · +1 h · +6 h**

---

## 🌍 Données

L'étude utilise plusieurs sources réelles provenant de :

🇮🇹 Italie · 🇦🇺 Australie · 🇮🇳 Inde · 🇧🇷 Brésil

avec notamment **51 centrales photovoltaïques BR-PVGen**.

---

## 🤖 Approches

**Machine Learning**

Ridge · Random Forest · XGBoost

**Deep Learning**

LSTM · GRU

Les modèles sont comparés à des méthodes de référence comme la persistance.

---

## 📊 Quelques résultats

### +1 heure

**Random Forest : 2,82 % nMAE**
**Skill : +34,18 %**

### +6 heures

**Random Forest : 5,43 % nMAE**
**Skill : +70,38 %**

Ces résultats sont obtenus sur le dataset SolarTech Lab.

---

## 🧪 Méthodologie

```text
Données
   ↓
Prétraitement
   ↓
Feature Engineering
   ↓
ML / Deep Learning
   ↓
Validation temporelle
   ↓
Analyse des résultats
```

## Le projet intègre également une étude d'ablation et une analyse SHAP pour étudier l'influence des variables.

## 📂 Contenu

```text
PV-AI-Forecast/
│
├── notebooks/
│   └── PV_AI_Forecast.ipynb
│
├── results/
├── figures/
├── requirements.txt
└── README.md
```

---

## 🚀 Perspectives

Amélioration de la généralisation inter-sites, intégration de prévisions météorologiques réelles et développement vers des systèmes énergétiques intelligents.

---

## 👨🏽‍🔬 Auteur

**Serigne Fallou Faye**
Étudiant en Génie Électrique, **ESP Dakar, Sénégal**

**Intérêt :** Intelligence Artificielle · Énergies renouvelables · Systèmes énergétiques intelligents

---

⭐ *Projet de recherche, Septembre 2026*
