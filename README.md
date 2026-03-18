## mettre tes fichiers sur GitHub avec Git

Ouvre un terminal dans ton dossier de projet

    Exemple :

    Clique droit dans le dossier → Ouvrir dans le terminal;

    cd chemin/vers/ton/projet

Initialiser Git;

    git init

Ajouter tous les fichiers;

    git add .

Faire un premier commit;

    git commit -m "Premier commit"

Créer un dépôt sur GitHub;

    Va sur github.com

    New repository

    Donne un nom

    ❌ coche pas README 

    Crée le repo

    GitHub donne une URL du style :
    https://github.com/ton-pseudo/nom-du-repo.git


Lier ton projet local à GitHub;
    
    git branch -M main
    
    git remote add origin https://github.com/ton-pseudo/nom-du-repo.git

Envoyer les fichiers sur GitHub;
    
    git push -u origin main

Pour les prochaines mises à jour;
    
    git add .
    
    git commit -m "Description des changements"
    
    git push



