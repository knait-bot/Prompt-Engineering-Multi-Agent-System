
# TP1 – Prompt Engineering & Multi-Agent Systems

## Auteur

**Khalid Naitali**

---

## Introduction

Ce travail pratique a pour objectif d’explorer les techniques de **Prompt Engineering** et l’utilisation des **LLMs (Large Language Models)** à travers Python.

Le TP permet de comprendre comment interagir efficacement avec des modèles comme OpenAI, et d’évaluer différentes stratégies de prompting.

---

## Objectifs du TP

* Comprendre le fonctionnement des LLMs
* Implémenter différentes techniques de prompting :

  * Simple Prompt
  * Zero-shot Prompt
  * Few-shot Prompt
  * Chain-of-Thought (CoT)
* Manipuler un dataset réel
* Réaliser une tâche de **Sentiment Analysis**
* Évaluer les performances des prompts
* Développer une application finale basée sur un nouveau cas d’usage

---

## Environnement technique

* Python
* Jupyter Notebook
* LangChain
* OpenAI API
* Pandas
* Scikit-learn
* HuggingFace Datasets

---

## Méthodologie

### 1. Prompt Engineering

Plusieurs types de prompts ont été testés :

* **Simple Prompt** : interaction directe avec le modèle
* **Zero-shot** : sans exemple
* **Few-shot** : avec exemples
* **Chain-of-Thought** : raisonnement détaillé

Ces approches permettent d’améliorer progressivement la qualité des réponses.

---

### 2. Interaction avec les LLMs

Le modèle OpenAI a été utilisé via LangChain pour générer des réponses à partir des prompts définis.

---

### 3. Analyse du Dataset

Un dataset a été chargé et analysé afin de :

* comprendre sa structure
* visualiser les données
* préparer les données pour la tâche de classification

---

### 4. Sentiment Analysis

Une analyse de sentiment a été réalisée avec différentes approches :

* Zero-shot classification
* Few-shot classification

Les résultats obtenus ont été comparés afin d’identifier la meilleure méthode.

---

### 5. Évaluation

Les performances ont été évaluées en comparant les prédictions du modèle avec les résultats attendus.

---

### 6. Application finale

Une application supplémentaire a été développée utilisant un autre dataset.

Exemple :

* classification de texte
* résumé automatique
* détection de sentiment

---

## Résultats

Les résultats montrent que :

* le Few-shot Prompt améliore la précision
* le Chain-of-Thought améliore la compréhension
* le choix du prompt influence fortement la qualité du modèle

---

## Conclusion

Ce TP a permis de comprendre l’importance du Prompt Engineering dans l’utilisation des LLMs.

Il montre que de simples modifications dans les instructions peuvent améliorer significativement les résultats.

---

## Recommandations

* utiliser Few-shot pour des tâches complexes
* utiliser CoT pour le raisonnement
* tester plusieurs prompts pour optimiser les résultats

---

## Sécurité

⚠️ Les clés API ne doivent jamais être publiées dans GitHub.

---

## Auteur

**Khalid Naitali**


