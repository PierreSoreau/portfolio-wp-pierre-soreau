# Mon Portfolio Wordpress
Un thème WordPress pour Portfolio sur mesure modifiable même sans savoir coder, en utilisant uniquement le site de wordpress.

## Comment voir le visuel de mon portfolio?

### Installation & Activation

### Option 1 : Vous utilisez Local
Si vous n'avez pas d'environnement WordPress déjà configuré, je vous recommande d'utiliser le logiciel gratuit **[Local](https://localwp.com/)** pour faire tourner ce thème sur votre machine.

1. Créez un nouveau site sur l'application Local.
2. Cliquez sur le bouton **"Site folder"** pour ouvrir les fichiers du site.
3. Naviguez jusqu'au dossier des thèmes : `app/public/wp-content/themes/`.
4. Ouvrez votre terminal dans ce dossier et clonez le dépôt :
   ```bash
   git clone [https://github.com/PierreSoreau/portfolio-wp-pierre-soreau.git](https://github.com/PierreSoreau/portfolio-wp-pierre-soreau.git)
5. Dans l'administration wordpress de votre site local, allez dans Apparence > Thèmes et activez le thème.

### Option 2 : Vous avez déjà un site WordPress en ligne

1. Téléchargez le code de ce dépôt en fichier `.zip` (bouton vert **Code** > **Download ZIP**).
2. Dans votre administration WordPress, allez dans **Apparence > Thèmes > Ajouter un nouveau**.
3. Cliquez sur **Téléverser un thème**, choisissez le fichier `.zip` et cliquez sur **Installer**.
4. **Activez** le thème une fois l'installation terminée.

## 🛠️ Technologies Utilisées

Ce thème a été conçu de A à Z (from scratch) en utilisant :

* **PHP** : Cœur de la logique du thème (utilisation de la "Loop" WordPress, création de fonctions sur-mesure dans `functions.php`).
* **HTML5** : Structure sémantique et accessible des pages.
* **CSS3** : Mise en page, design responsive (adapté aux mobiles et tablettes) et animations.
* **JavaScript (Vanilla)** : Gestion des interactions dynamiques côté client (menu burger).

## 🧠 Difficultées rencontrées et apprentissage

Lors de ce projet, j'ai rencontré deux défis majeurs. 
Le premier fut technique : étant habitué à coder l'intégralité de mes visuels de zéro, j'ai dû revoir mes méthodes pour m'adapter à l'organisation spécifique des fichiers WordPress et apprendre son langage (ses fonctions natives).
Le second défi fut ergonomique. WordPress étant un CMS, le but était que le thème soit 100% modifiable depuis l'interface d'administration. Il a donc fallu que je change de perspective, en délaissant mon regard de développeur pour me mettre à la place d'un utilisateur novice, afin d'anticiper ses besoins et lui faciliter la gestion du site sans aucune ligne de code.

