# [Articles](https://wordpress.com/fr/support/articles/)

* 🔖 **Saisie**
* 🔖 **Catégories**
* 🔖 **Format**
* 🔖 **Extrait**
* 🔖 **Publication**
* 🔖 **Permaliens**

___

## 📑 Saisie

Comme observé précédemment il est possible d'utiliser les blocs pour rédiger son article. Il est possible de copier l'ensemble du contenu en cliquant sur le menu ....

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/copy-article.png)

Pour le coller, dans un article il suffit de faire `ctrl + v`.

___

👨🏻‍💻 Manipulation

Copier/coller un article

___

## 📑 Catégories

Comme observé il est possible d'assigner des catégories à un article.

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/article-category.png)

___

## 📑 Format

Il est possible de définir le format d'un article.


![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/format.png)

Le thème ne prend pas forcement en compte le format concernant les articles. Pour ajouter cette fonctionnalité, le code suivant active cette option.

Vous devez ajouter au fichier `function.php` de votre thème le contenu suivant en fin de fichier.
```php
function wpc_theme_support() {
    add_theme_support('post-formats', array(
			'aside',
			'chat',
			'gallery',
			'image',
			'link',
			'quote',
			'status',
			'video',
			'audio'
		)
	);
}

add_action('after_setup_theme','wpc_theme_support');
```

___

## 📑 Extrait

Il est possible de spécifier un extrait qui sera visible lors de l'aperçu de l'article. Chaque thème l'utilise différemment.

La première étape est de créer un extrait.

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/extrait.png)

Ensuite il faut activer la visualisation des extraits dans les réglages.

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/extrait-activer.png)

___

👨🏻‍💻 Manipulation

Créer une série d'article au bon format avec des extraits.

___

## 📑 Publication

Un article peut être sauvegardé comme Brouillon, peut être en relecture ou publié, immédiatement ou à une date ultérieure.

![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/publicatio.png)

___

## 📑 Permaliens

Il est possible de modifier le permalien d'un article.


![image](https://raw.githubusercontent.com/seeren-training/Wordpress/master/wiki/resources/permalien.png)

___

👨🏻‍💻 Manipulation

Créer des permalien qui correspondent à un référencement ciblé.

___