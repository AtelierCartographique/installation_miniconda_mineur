# installation_miniconda_mineur
Installation de Miniconda et des dépendences pour le mineur de données géoréférencées

1. installez Miniconda pour la dernière version de Python : https://docs.conda.io/en/latest/miniconda.html Assurez-vous d'installer pour tous les utilisateurs.
2. Ouvrez l'aplication Powershell de Windows et tappez : conda info. Si vous avez un message d'erreur, suivez l'instruction 3, sinon, passez au 4
3. Appuyez sur la touche windows et tappez Variables "Dans l'application .modifiez les variables", cliquez "Variables d'environnement", puis double-cliquez sur "Path". Ajoutez-y deux variables : "C:\ProgramData\Miniconda3", et "C:\ProgramData\Miniconda3\Scripts"
4. Téléchargez la fiche d'aide pour les commandes Conda : https://conda.io/projects/conda/en/latest/user-guide/cheatsheet.html
5. Créez un nouvel environnement Conda pour le scripte Python de minage de données. Dans Powershell : conda create --name mineurCraigslist python=3.8
