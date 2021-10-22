GITHUB
========

## Présentation
### GitHub

*Plateforme collaborative pr ls dev, plus grand stockage de trvaux collaborative au mnde. 
En lui mm il n'est rien d autre qu1 reseaux social comme FB. 
Vs y construisez 1 profil, y déposez ds projets à share et vs vs connetez avc d autres utilisateurs, vs pouvez mm ls suivre. Mm si les utilisateurs y déposent ds projets de programmation ou de code, rien ne vous empéche d'y placer ds txts ou type de fichiers dns vos repertoires de projet.

## GIT
GIT *logiciel de contrôle de version*, ce qui signifie qu'il gère ls modifications d'un projet sns écraser n'importe quelle partie du projet.

## Lexique de Git et GitHub
### vocabulaire
**invite de commande**: En gros le programmme de l'ordi que ns utilisons pr entrer ds commandes Git.
On dit qu'on travaille en ligne de commande pr désigner le fait d'intéragir avc un système informatique, et non à l'aide d'une interface graphique.
les commandes tapées dns le trminal sont interprétées par un Shell.
[Doc: Journal du net](https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/) 

**Dépot**: C'est un répertoire ou de l'espace de stockage, ou vos prjets peuvent vivre.
ls utilisateurs raccourcissent ça en _"repo"_ pr _"repository"_. Il peut-être un espace de stockage sur Github ou un autre hebergeur en ligne. A l'intérieur d'un dépot, vous pouvez conservez ds fichiers de codes, ds fichiers txt et des img.

**Ctrl ds versions**: Fondamentalement l'objctf pr lequel Git a été conçu. Quand vs avez un fichier Word, vs l'écrasez à chaque fois que vs save. avc Git, vs n etes pas obligé de faire ça. Git conserve ds "instantannées" de chaque point de l'historique d'un projet, de sorte à ne jamais rien perdre ou écraser.

**Commit**: C'est la commd qui donne à Git toute sa puissance. Quand vs committez, vous prennez un instantannnée, une photo de votre dépot à ce stade vs donnant un point de ctrl que vs pouvez ensuite <u>réévaluer</u> ou simplement restaurer votre projet à cette version.
il est nécessaire de rappeler que le nom de vos commmits doivent-être parlant afin de vs remémorer ou en était le projet à ce stade.

**Branche**: Permet à plrs pers de travailler en mm temps sur le mm projet. habituellement, elle se débranchent du projet principale avc leurs propre version complètes et font ds modification dessus.
Après avoir terminer, ils refusionnenent cette branche avc la branche master, le répertoire principal du projet. 

### commandes spécifiques Git 
**git init**: Initialise un nouveau dépot git. 

**git config**: Raccourcis de configuration, ceci est tt particulièrement utile qund vs paramétrz Git pr la 1er fois (identifiant mot de passe)

**git help**: Oublié une commd ? pr afficher les 21 commds de git.

**git status**: Vérifie le statut de votre repository. Il permet de voire ls fichiers et quelles snt ls modifications à commiter et sur quelle branche ou repo vs êtes en train de travailler.

**git add**: Cette commd n ajoute pas ds fichiers dns votre votre repository. au lieu de cela, cela porte de new fichiers à l attestation de git. Après avoir ajouté le fichiers il peuvent être commités.

**git commit**: Après avoir effectuer toutes sorte de modification vs commitez pr save votre travail.
La save s'effectue en local avc 1 msg de votre choix.
