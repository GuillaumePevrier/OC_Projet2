<a name="readme-top"></a>
# Projet 02 - Créez la page d'accueil d'une agence de voyage avec HTML & CSS
_( L’objectif de ce premier projet est de vous mettre dans les meilleures conditions pour réussir votre parcours, puis votre évolution professionnelle.)_

![Image text](https://user.oc-static.com/upload/2022/06/20/16557256333819_FR_1155_P3_Banner-Booki.png)
## Description

Vous débutez votre alternance en tant que développeur web au sein de la start-up Booki. L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.
Vous êtes chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, vous travaillez en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer. 
Sarah vous envoie un e-mail pour vous présenter l’avancée du projet. 

Objet : Maquettes site Booki
De : Sarah
À : Vous
Bonjour,

Ça y est, Loïc a finalisé les maquettes desktop, tablette et mobile du site ! Tu vas pouvoir les intégrer. Elles sont disponibles en pièces jointes sur Figma. Pense à te connecter à Figma pour pouvoir voir toutes les informations sur les éléments de la maquette.
Tu trouveras également en pièce jointe le dossier contenant toutes les images à utiliser sur le site.
Pour que le projet soit très clair, Loïc et moi t’avons préparé une note de synthèse qui regroupe les spécifications et contraintes techniques à respecter (voir pièce jointe).

Pour que nous puissions consulter le site une fois fini, il faudra que tu versionnes l'ensemble de ton projet avec Git et que tu nous livres le lien vers le projet accessible sur GitHub avec :
un fichier “index.html” contenant l’ensemble du code HTML du projet ;
un dossier “CSS” comprenant un fichier “style.css” contenant l’ensemble du code CSS du projet ;
un dossier “images” contenant l’ensemble des images utilisées.

Bon courage pour ce projet, et bonne journée !

Sarah, CTO @Booki

## Compétences évaluées

- Étape n° 1 : Installer un environnement de développement front-end
- Étape n° 2 : Implémenter une interface responsive avec HTML et CSS
- Étape n° 3 : Intégrer du contenu conformément à une maquette avec HTML et CSS
- Étape n° 4 : Versionner son projet avec Git et Github


## La soutenance:

_( Durant la présentation orale, l’évaluateur interprétera le rôle de Sarah, votre CTO. La soutenance est structurée de la manière suivante .)_

<details>
	<summary>Présentation des livrables (15 minutes) </summary>

![Image text](https://user.oc-static.com/upload/2022/06/20/16557257586438_Banner_Soutenance_Dev.png)

* Vous présenterez votre travail en expliquant vos choix techniques :
   - Vous rappelez le contexte du projet (qu’est-ce qui a été réalisé, pourquoi et pour qui).
   - Vous présentez le rendu visuel du projet en montrant les versions mobile, tablette et desktop.
   - Vous présentez le code du projet sur Visual Studio Code. N’hésitez pas à montrer les points les plus complexes que vous avez dû réaliser.
   - Vous faites le bilan du projet. 
</details>

<details>
   <summary>Discussion (10 minutes) </summary>

![Image text](https://user.oc-static.com/upload/2022/06/20/16557257586438_Banner_Soutenance_Dev.png)

* Votre évaluateur, jouant toujours le rôle de Sarah, va vous questionner sur vos codes HTML et CSS. Il pourra vous challenger sur les points suivants : 
   - la validité de votre code auprès du W3C ;
   - le Web sémantique ;
   - l’importance de passer son code aux validateurs ;
   - le fonctionnement de Visual Studio Code ;
   - la spécificité en CSS ; 
   - l’étude et la découpe de la maquette  ;
   - l’importance de séparer le HTML du CSS.
</details>

<details>
   <summary>Débriefing (5 minutes)</summary>

![Image text](https://user.oc-static.com/upload/2022/06/20/16557257586438_Banner_Soutenance_Dev.png)

* À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de Sarah pour vous permettre de débriefer ensemble. 
</details>


## Lien utiles:

[Openclassrooms](https://openclassrooms.com/)

[jeux en ligne Flexbox Froggy](https://flexboxfroggy.com/#fr)

[Validateur HTML du W3C](https://validator.w3.org)

[Validateur CSS du W3C](https://jigsaw.w3.org/css-validator/validator.html.fr)

[Maquette du site](https://www.figma.com/file/aen32jonHhD7JnIEL2b3sE/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?node-id=3%3A0&t=H8M7Udb3Hgk6DsO1-0)

[Note de synthèse.pdf](https://course.oc-static.com/projects/Développeur+Web/IW_P3+HTML+CSS+Booki/Note+de+synthèse+pour+intégration+du+site+Booki+(IW).pdf)

[La documentation officielle pour utiliser Font Awesome](https://fontawesome.com/docs/web/setup/get-started)

[Tutoriel pour apprendre à créer une carte (card) avec CSS](https://www.w3schools.com/howto/howto_css_cards.asp)

[Article sur lapropriété Css objet-fit](https://developer.mozilla.org/fr/docs/Web/CSS/object-fit)

[Utilisation de la balise meta viewport pour controler la mise en page sur mobile](https://developer.mozilla.org/fr/docs/Web/HTML/Viewport_meta_tag)

## AIDE-MÉMOIRE GITHUB GIT

_Git est le sytème de gestion de version décentralisé open source qui facilite les activités GitHub sur votre ordinateur. Cet aide-mémoire permet un accès rapide aux instructions des commandes Git les plus utilisées._
<details>
	<summary>Commandes utiles GIT</summary>
	
<details>
	<summary>1. CRÉER DES DÉPÔTS</summary>
	

* Démarrer un nouveau dépôt ou en obtenir un depuis une URL existante

   ```sh
	git init [nom-du-projet]
   ```
	Crée un dépôt local à partir du nom spécifié
   ```sh
   git clone [url]
   ```
   Télécharge un projet et tout son historique de versions
</details>
<details>
	<summary>2. EFFECTUER DES CHANGEMENTS</summary>

* Consulter les modifications et effectuer une opération de commit

   ```sh
   git status
   ```
   Liste tous les nouveaux fichiers et les fichiers modifiés à commiter
   ```sh 
   git diff
   ```
	Montre les modifications de fichier qui ne sont pas encore indexées
   ```sh
	git add [fichier]
   ```
	Ajoute un instantané du fichier, en préparation pour le suivi de version
   ```sh
	git diff --staged
   ```
	Montre les différences de fichier entre la version indexée et la dernière version
   ``` sh
	git reset [fichier]
   ```
	Enlève le fichier de l'index, mais conserve son contenu
   ``` sh
	git commit -m "[message descriptif]"
   ```
	Enregistre des instantanés de fichiers de façon permanente dans l'historique des versions
</details>
<details>
	<summary>3. GROUPER DES CHANGEMENTS</summary>	  

* Nommer une série de commits et combiner les résultats de travaux terminés

   ```sh 
   git branch
   ```
   Liste toutes les branches locales dans le dépôt courant
	   
   ```sh
   git branch [nom-de-branche]
   ```
   Crée une nouvelle branche
	  
   ```sh 
   git checkout [nom-de-branche]
   ```
   Bascule sur la branche spécifiée et met à jour le répertoire de travail
		
   ```sh
   git merge [nom-de-branche]
   ```
   Combine dans la branche courante l'historique de la branche spécifiée
	
   ```sh
   git branch -d [nom-de-branche]
   ```
   Supprime la branche spécifiée
</details>
</details>
	
<p align="right">(<a href="#readme-top">Retour haut de page</a>)</p>

