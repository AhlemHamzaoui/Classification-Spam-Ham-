# 📧 Spam Classifier using NLP & Naive Bayes
Encadré par : Mme Tasmine Hamdeni 

Ce projet consiste à construire un modèle de classification permettant de distinguer les **messages spam** des **messages légitimes (ham)**.  
Il repose sur des techniques de **Traitement Automatique du Langage (NLP)** et sur un modèle **Naive Bayes Multinomial**, particulièrement adapté aux données textuelles.

---

## 🚀 Objectif du projet
- Prétraiter un dataset de messages texte (SMS ou emails)
- Transformer le texte en représentations numériques exploitables (TF-IDF)
- Entraîner un modèle de classification
- Évaluer sa performance sur des données de test

---

## 🧰 Technologies utilisées
| Outil / Librairie | Rôle |
|------------------|------|
| Python | Langage principal |
| Scikit-learn | Modèle de ML + évaluation |
| NLTK / Regex | Nettoyage textuel |
| TF-IDF Vectorizer | Transformation des textes |
| NumPy / Pandas | Manipulation des données |

---

## 🧹 Prétraitement du texte
Les étapes de nettoyage appliquées :
- Mise en minuscules
- Suppression des ponctuations & caractères spéciaux
- Suppression des stopwords
- Lemmatisation ou racinisation
- Vectorisation avec **TF-IDF**

---

## 🤖 Modèle utilisé
**Multinomial Naive Bayes**  
→ Choisi car :
- Simple et rapide
- Performant pour la classification textuelle
- Basé sur la fréquence des mots

---

## 📊 Résultats

| Classe | Précision | Rappel | F1-score | Support |
|--------|----------|--------|----------|---------|
| ham    | 0.99     | 0.97   | 0.98     | 965     |
| spam   | 0.84     | 0.93   | 0.88     | 149     |
| **Accuracy globale** | **→ 0.97 (96.68%)** |

### ✅ Matrice de confusion

|       | Prédit ham | Prédit spam |
|-------|------------|-------------|
| **Réel ham**  | 939        | 26          |
| **Réel spam** | 11         | 138         |

➡️ **Très bon score de détection du spam** tout en limitant les faux positifs.

---




---

## 📝 Conclusion
Ce modèle offre une **précision élevée (~97%)** et identifie efficacement les messages indésirables.  
Il peut être facilement intégré dans :
- des applications web
- des systèmes de filtrage d'emails
- des robots de communication





---

## 👩‍💻 Auteure
**Ahlem Hamzaoui**  
Étudiantes en Data Science & IA  
2024 - 2025


