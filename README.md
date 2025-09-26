# stat_project_weather
Collaborative repository for a statistics project on weather data.

## Pour collaborer sur ce repository
Voici la marche à suivre pour que l'on puisse collaborer.

### 1. Récupérer le repository avec le notebook et les données
*git clone https://github.com/ali-hou-supaero/stat_project_weather.git*

### 2. Travail personnel sur le notebook

### 3. Sauvegarder vos modifications en local

### 3.1 git add
*git add .* OU *git add mon_notebook.ipynb*

Cette commande permet de préparer les fichiers dans l'attente de leur sauvegarde définitive. 

git add . permet de préparer tous les fichiers que vous avez modifiés alors que git add mon_notebook.ipynb prépare uniquement le fichier spécifié dans la commande.

Métaphore : vous rangez vos feuilles dans votre classeur.

### 3.2 git commit
*git commit -m "Ajout de la question 3"*

Cela permet de sauvegarder en local les fichiers qui avaient été ajoutés précédemment avec un message. Les fichiers sont maintenant sauvegardés en local par l'outil git. 

Cela permet de suivre en local les différentes versions du fichier par exemple.

Cette étape est nécessaire car il est préférable de sauvegarder vos fichiers pour facilement gérer les conflits par la suite.

Métaphore : vous rangez le classeur dans lequel vous y aviez ranger vos feuilles.

### 4. Récupérer les nouveautés du repository
*git pull origin main*

Cette commande permet de récupérer les nouveautés du repository qui ont été envoyées sur GitHub en ligne.

### 5. Résoudre les conflits (s'il y en a)
Git devrait vous guider pour résoudre les conflits s'il y en a.

Voilà pourquoi il était important de sauvegarder vos fichiers. Git peut facilement comprendre les modifications que vous avez faites puisque vous les avez sauvegardées en local. Lorsque vous récupérez les modifications du repository, il peut alors identifier les différences et vous guider pour résoudre les conflits potentiels.

A priori, vu que l'on travaille sur des parties séparées, il ne devrait pas y en avoir.

### 6. Envoyer les modifications que vous avez faites en local sur le GitHub en ligne
*git push origin main*

Les éventuels conflits entre les modifications locales et la version en ligne ont été résolus en local. Vous pouvez maintenant envoyer le fichier résultant sur le GitHub en ligne.
