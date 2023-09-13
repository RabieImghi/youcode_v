# youcode
# rabiaYCode
git init // Cette commande est utilisée pour créer un nouveau dépôt Git vide dans un répertoire local. 

git add . // est utilisée pour ajouter des fichiers à la zone de préparation (également appelée l'index) dans un dépôt Git.

git commit -m "first commit" // Ce message devrait décrire brièvement les modifications que vous avez apportées dans ce commit.
----- -m : permet à l'utilisateur de fournir un message de commentaire ou de description pour accompagner le commit. 

git branch -M main //  Cette commande est souvent utilisée pour changer le nom de la branche principale d'un référentiel Git en "main" (au lieu de "master" par exemple) pour suivre les conventions plus inclusives et appropriées.

git remote add origin https://github.com/ra2003bie/Ycode.git //Cette commande est utilisée pour ajouter un référentiel distant (remote) nommé "origin" à un dépôt Git, avec l'URL spécifiée qui pointe vers le référentiel distant sur GitHub. Cela permettra au dépôt local de se connecter au référentiel distant pour pousser et tirer des modifications.

git status //  Elle permet d'afficher l'état actuel du référentiel Git, montrant les fichiers qui ont été modifiés, ajoutés, supprimés ou qui sont en attente d'être validés (commit). Cette commande est souvent utilisée pour avoir un aperçu rapide des changements effectués dans un projet Git.

git push -u origin main // Cette commande permet de pousser (envoyer) les modifications locales de la branche principale (habituellement appelée "main") vers le dépôt distant "origin" et d'établir un suivi (tracking) entre la branche locale et la branche distante.


git pull //  signifie essentiellement "tirer les dernières modifications" ou "récupérer les dernières mises à jour" depuis le référentiel distant (comme GitHub) vers votre copie locale du projet.