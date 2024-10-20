README: Couverture de Code avec Coverage.py
À propos de la Couverture de Code
La couverture de code est une mesure utilisée pour décrire le degré auquel le code source d'un programme est exécuté lors d'un test. Elle vous permet de découvrir les parties de votre code qui ne sont pas testées et donc potentiellement sujettes à des erreurs.

Utilisation de Coverage.py
Coverage.py est un outil populaire pour mesurer la couverture de code en Python. Voici comment l'utiliser :

Installation :
Installez coverage.py en utilisant pip :

bash
Copy code
pip install coverage
Exécution des Tests avec Coverage :
Pour exécuter vos tests tout en collectant des données de couverture, utilisez :

bash
Copy code
coverage run -m pytest
Remplacez pytest par votre framework de test si nécessaire.

Générer un Rapport :
Après avoir exécuté les tests, générez un rapport de couverture :

bash
Copy code
coverage report
Ce rapport montre le pourcentage de code couvert par vos tests.

Rapport Détaillé :
Pour obtenir un rapport détaillé en HTML :

bash
Copy code
coverage html
Cela génère un dossier htmlcov contenant un rapport détaillé visualisable dans un navigateur web.

Conseils d'Utilisation
Intégrez la couverture de code dans votre processus de CI/CD pour suivre automatiquement la qualité de vos tests.
Visez un pourcentage élevé de couverture, mais n'oubliez pas que 100% de couverture ne garantit pas l'absence de bugs.
Utilisez les rapports de couverture pour identifier les parties critiques de votre application qui nécessitent plus de tests.


IMPORTANT 

https://pypi.org/project/psycopg2-binary/#files pour installer psycopg2 avec la bonne version python compatbile (attention au x32 ou x64bits)

la commande pour installer python directement avec la version qu'on a téléchargé por le projet : 

C:\Users\TonNomUtilisateur\AppData\Local\Programs\Python\Python311\python.exe -m venv env
