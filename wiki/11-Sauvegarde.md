# Sauvegarde

* 🔖 **Export**
* 🔖 **Import**
* 🔖 **Migration**

___

## 📑 Export

Pour sauvegarder votre site il faut faire une copie des dossiers et de la base de donnée.

### 🏷️ **Fichiers**

Pour copier vos fichiers, utiliser un client ftp si le site est hébergé et sinon naviguez jusqu'au dossier htdocs ou www de votre server.

Copiez l'ensemble dans un dossier portant le nom du site et une date.

### 🏷️ **Base de données**

Il est possible de créer une sauvegarde de votre base en utilisant PhpMyAdmin ou directement Wordpress.

#### **PhpMyAdmin**

Cliquez sur votre base de données puis sur l'onglet `Export`. COnservez les options par défaut puis lciquez sur `Exporter`. Un fichier avec l'extension SQL regroupe les informations des tables de votre base de données. Déplacez le fichier SQL dans votre dossier de sauvegarde.

#### **Wordpress**

Il y a un utilitaire de sauvegarde. Vous pouvez choisir ce que vous sauvegardez. Le fichier généré est en XML et peut être réimporté dans Wordpress.Déplacez le fichier XML dans votre dossier de sauvegarde.

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/export.png)

___

## 📑 Import

Que e soit sur PhpMyAdmin ou sur Wordpress il est possible d'importer des données exportées. L'option d'import est à côté de l'option d'export.
___

👨🏻‍💻 Manipulation

Créez une sauvegarde de votre site.

___
