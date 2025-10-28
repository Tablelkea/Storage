# 🌌 ElesiaStorage

**ElesiaStorage** est un plugin **Paper 1.21.8** permettant à chaque joueur de disposer d’un **système de stockage personnel** inspiré d’**Applied Energistics**.  
Chaque joueur possède **un coffre unique** connecté à une **base de données**, dans lequel il peut déposer ses items, puis les récupérer facilement via une commande.

---

## ⚙️ Fonctionnalités

- 🔒 Stockage **privé** par joueur (un seul coffre par joueur).
- 🧱 Bloc **spécifique** servant d’interface de dépôt.
- 💾 Données stockées dans une **base de données** (MySQL ou SQLite).
- ⌨️ Commande intuitive pour récupérer des items :
-
```bash
/storage <item> <quantité>

## ⚡ Système fluide, sans perte d’objets ni duplication.


## 🧩 Compatible avec Paper 1.21.8 et Java 17+.


## 📦 Installation
Téléchargez la dernière version de ElesiaStorage.jar.

Placez le fichier dans le dossier plugins/ de votre serveur Paper.

Redémarrez le serveur.

Configurez la base de données dans le fichier config.yml.

## 💬 Commandes
Commande / Description
```bash
/storage <item> <quantité>	Récupère un item depuis votre stockage personnel.
/storage open (optionnel)	Ouvre l’interface du coffre de stockage.
```

🗄️ Base de données
ElesiaStorage enregistre tous les contenus dans une base de données (MySQL ou SQLite selon la configuration).
Chaque joueur dispose d’un espace de stockage unique, lié à son UUID.

## 🧑‍💻 Informations techniques
Nom du plugin : ElesiaStorage

Version Minecraft : Paper 1.21.8

Langage : Java 17+

Auteur : TonPseudo