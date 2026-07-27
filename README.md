# Home_Assistant_MicroWakeWord_FR
Un Notebook Google Colab pour créer facilement ses propres mots d'éveil pour Home Assistant et ESPHome.

# 🎙️ Générateur de Mot d'Éveil Personnalisé (MicroWakeWord) pour Home Assistant

Bienvenue ! Ce projet permet à la communauté francophone de Home Assistant de créer très facilement un modèle de mot d'éveil personnalisé (Wake Word) pour ESPHome, sans avoir besoin d'un ordinateur puissant ou de connaissances en code.

## 🚀 Comment ça marche ?
Tout se passe sur Google Colab. Vous enregistrez votre voix, et les serveurs de Google s'occupent de l'entraînement !

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GhostWolf09/Home_Assistant_MicroWakeWord_FR/blob/main/MicroWakeWord_mot_d'%C3%A9veil_perso.ipynb)

*(Cliquez sur le badge ci-dessus pour démarrer)*

## 🛠️ Prérequis
- Un compte Google gratuit (pour utiliser Colab. Même si, acheter 100 crédits est plutôt conseillé)
- Un micro ou l'enregistreur sur votre smartphone pour enregistrer vos échantillons de voix (.wav)
- Un appareil ESP32 sous ESPHome (version 2024.7.0 minimum)

## 📖 Instructions
1. Ouvrez le Notebook via le bouton ci-dessus.
2. Lisez bien les instructions de chaque cellule.
3. Exécutez les cellules une par une (le bouton "Play" à gauche de chaque bloc).
4. Téléchargez vos fichiers `.tflite` et `.json` à la fin.

## Remerciements
Basé sur l'excellent travail du dépôt original [micro-wake-word](https://github.com/OHF-Voice/micro-wake-word)
