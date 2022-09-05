# first-common-directory
Notre premier répertoire GIT en commun
## Etape 1
Créez un fork de ce répertoire en cliquant sur `Fork` en haut à droite, il se trouvera sur github.com/*VotreUsername*/
## Etape 2
Clonez ce répertoire en copiant l'adresse ssh de votre clone -> `code` -> git@github.com:*VotreUsername*/first-common-directory.git

Sur votre disque D:, clonez votre fork en passant par le Git Bash :

    git clone git@github.com:*VotreUsername*/first-common-directory.git

## Etape 3
Entrez dans le dossier

    cd first-common-directory

## Etape 4
- Vérifiez que `main` est apparu dans le Git Bash
- Vérifiez que vous êtes bien lié à votre fork :
    
    git remote -v
    
Vous devriez y voir le lien vers `origin`, c'est là que vous pourrez modifier les fichiers

## Etape 5
Ajoutez l'`upstream`, le lien vers le projet original : 

    git remote add upstream git@github.com:WebDevCF2m2022/first-common-directory.git
    
    # pour vérifier les serveurs
    git remote -v
    
C'est de là que vous récupérerez le projet après les validations, et c'est vers ce serveur que vous pourrez demander une intégration de votre travail via un `pull request`

A suivre ...
