# Programmation Python pour les Humanités

Pour ce cours, nous utilisons les notebooks IPython. Suivez les instructions en dessous pour installer l'ensemble des programmes requis pour ce cours. (Merci beaucoup à Folgert Karsdorp pour son aide à fournir des instructions d'installations et des scripts de lancement!)

## Instructions d'installation

D'abord, on va installer python, le langage de programmation que nous allons utiliser pendant de cours. Pour cela, nous utiliserons la distribution gratuite Anaconda, qui aura tous les packages nécessaires. Important: nous utiliserons Python3.4 dans ce cours, mais d'abord nous installer la version 2.7 de Python, suivez donc **exactement** ces instructions:

- Allez sur http://continuum.io/downloads
- Téléchargez l'installateur graphique pour Python 2.7 (Pas Python 3.4 !) qui correspond à votre système d'exploitation (Mac OSX, Windows ou Linux)
- Lancer l'installateur graphique (Si vous avez des problèmes, regardez http://docs.continuum.io/anaconda/install.html)

Maintenant, nous aurons besoin de mettre à jour Anaconda pour Python3.4 en ligne de commande. D'abord, ouvez le terminal (cet écran noir appeurant dans lequel vous pouvez tapez des commandes pour votre ordinateur):

- Sous Mac OS X, naviguez vers /Applications/Utilities et double-click "Terminal"
- Sous Windows, cliquez "Démarrer" > "Tous les Programmes" > "Accessoires" > "Invité de Commandes"
- Sous Linux: combinaison de touche Ctrl+Alt+T

Réalisez ensuite les lignes de commandes dans ce termina: entrez chaque commande (puis entrée après chaque commande):

Sur windows:
- conda create -n py34 python=3.4 anaconda
- source py34

Autre plate-forme:
- conda create -n py34 python=3.4 anaconda
- source activate py34

Téléchargez le dossier pour ce cours, en navigant vers https://github.com/ponteineptique/python-course et cliquez sur "Download ZIP/Téléchargez le Zip". Sauvegarder et extraire le dossier ZIP où cela sera pratique pour vous, comme le bureau. Vous devriez être capable désormais de lancer les notebooks interactifs dans votre navigateur. Ouvez le dossier dézippé puis:

- Sous Windows: double-click "start-windows.bat"
- Sous Mac OSX: double-click "start-osx.command"
- Sous Linux: double-click "start-unix.sh"

Après avoir double-cliqué le fichier une fois, votre navigateur devrait s'ouvrir (préférablement sous Chrome ou Firefox) sur la page http://127.0.0.1:8888/ (ou quelque chose de ressemblant) qui dit `IP[y]: Notebook'. (Note that this might take a while on slower machines, so don't panic if this page doesn't show up immediately.) If for some reason, the notebook is opened by Internet Explorer, copy the URL and paste that in either Google Chrome or Firefox. If none of this worked, send me an email (firstname.lastname@uantwerp.be), but in the meanwhile you can still use the static versions of each chapter, listed below.

## Static Notebooks

[Chapter 1 - Variables](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%201%20-%20Variables.ipynb)

[Chapter 2 - Collections](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%202%20-%20Collections.ipynb)

[Chapter 3 - Conditions](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%203%20-%20Conditions.ipynb)

[Chapter 4 - Loops](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%204%20-%20Loops.ipynb)

[Chapter 5 - Functions and Files](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%205%20-%20Functions%20and%20Files.ipynb)

[Chapter 6 - Regular Expressions](http://nbviewer.ipython.org/github/mikekestemont/python-course/blob/master/Chapter%206%20-%20Regular%20Expressions.ipynb)

[Chapter 7 - More on Loops](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%207%20-%20More%20on%20Loops.ipynb)

[Chapter 8 - The Pattern Package (advanced)](http://nbviewer.ipython.org/urls/raw.github.com/mikekestemont/python-course/master/Chapter%208%20-%20The%20Pattern%20Package.ipynb)
