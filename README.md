# 📱 Smart Collect - Application Mobile

<p align="center">
  <a href="https://github.com/AlhsGdev/smartcollect_apk/raw/main/app-release.apk">
    <img src="https://img.shields.io/badge/T%C3%A9l%C3%A9charger%20l'APK-Smart%20Collect-2563EB?style=for-the-badge&logo=android&logoColor=white" alt="Télécharger APK Smart Collect" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/AlhsGdev/smartcollect_apk/raw/main/app-release.apk">
    <b>⬇️ Téléchargement direct : app-release.apk</b>
  </a>
</p>

---

**Smart Collect** est une application mobile conçue pour simplifier la création de formulaires tabulaires sur mesure, la collecte d'informations sur le terrain en mode 100% hors-ligne, ainsi que la gestion et la synchronisation sécurisée des données sur Google Drive.

---

## ✨ Fonctionnalités Clés

* 📊 **Gestion de Tableaux Personnalisés :** Créez des tables avec colonnes dynamiques (texte, chiffres, numéros de téléphone avec indicatif pays, menus déroulants).
* 🏷️ **Champs Obligatoires et Optionnels :** Prise en charge du préfixe `@` lors de la configuration des colonnes pour définir des champs facultatifs (les autres champs restent strictement obligatoires).
* 📅 **Gestion et Historique des Rendez-vous :** Planification, rappels de suivi et archivage complet des rendez-vous par entrée.
* 📞 **Actions Rapides Intégrées :** Appels téléphoniques et redirection WhatsApp en un clic à partir des coordonnées saisies.
* 🖨️ **Impression et Export PDF :** Génération de rapports personnalisés avec filtrage avancé des données, personnalisation des polices et orientation (Portrait / Paysage).
* 📑 **Interopérabilité Excel :** Téléchargement de modèles vierges et import automatique de données depuis des fichiers `.xlsx`.
* ☁️ **Sauvegarde Google Drive Sécurisée :** Synchronisation directe (portée restreinte `drive.file`) sans aucun serveur intermédiaire tiers.
* 🔒 **Sécurité et Confidentialité :** Code Dart entièrement offusqué en compilation Release (`--obfuscate`).

---

## 📥 Installation

1. Cliquez sur le badge ci-dessus pour télécharger le fichier `app-release.apk`.
2. Ouvrez le fichier téléchargé sur votre terminal Android.
3. Autorisez l'installation d'applications inconnues si le système le demande.

---

## 🛠️ Installation via ADB (Développeurs / Chromebook)

```bash
adb install -r app-release.apk
