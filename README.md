# 📱 Smart Collect - Application Mobile

**Smart Collect** est une application mobile moderne conçue pour simplifier la création de formulaires tabulaires sur mesure, la collecte d'informations sur le terrain en mode 100% hors-ligne, ainsi que la gestion et la synchronisation sécurisée des sauvegardes sur Google Drive.

---

## ✨ Fonctionnalités Clés

* 📊 **Gestion de Tableaux Personnalisés :** Créez des tables avec colonnes dynamiques (texte, chiffres, numéros de téléphone avec indicatif pays, menus déroulants).
* 🏷️ **Champs Obligatoires et Optionnels :** Prise en charge du préfixe `@` lors de la configuration des colonnes pour définir des champs facultatifs (tous les autres champs restant strictement requis).
* 📅 **Gestion et Historique des Rendez-vous :** Planification, rappels de suivi et archivage complet des rendez-vous par entrée.
* 📞 **Actions Rapides Intégrées :** Appels téléphoniques et redirection WhatsApp en un clic à partir des coordonnées saisies.
* 🖨️ **Impression et Export PDF :** Génération de rapports personnalisés avec filtrage avancé des données, personnalisation des polices et orientation (Portrait / Paysage).
* 📑 **Interopérabilité Excel :** Téléchargement de modèles vierges et import automatique de données depuis des fichiers `.xlsx`.
* ☁️ **Sauvegarde Google Drive Sécurisée :** Synchronisation directe (portée restreinte `drive.file`) sans aucun serveur intermédiaire tiers.
* 🔒 **Sécurité et Confidentialité :** Code Dart entièrement offusqué en compilation Release (`--obfuscate`).

---

## 📥 Téléchargement et Installation

### 1. Télécharger l'APK
Téléchargez la dernière version compilée depuis la section **[Releases](../../releases)** ou directement depuis le fichier `SmartCollect-release.apk` présent sur ce dépôt.

### 2. Installation sur terminal Android
1. Transférez le fichier `.apk` sur votre appareil.
2. Autorisez l'installation depuis des applications inconnues si demandé par le système Android.
3. Ouvrez le fichier pour installer l'application.

---

## 🛠️ Installation via ADB (Développeurs / Chromebook)

Pour installer directement l'application via le terminal :

```bash
adb install -r SmartCollect-release.apk
