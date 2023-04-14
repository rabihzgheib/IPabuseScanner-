# AbuseIPDB Scanner
Il s'agit d'un script python qui analysera les adresses IP des fichiers ou interagira manuellement avec l'API AbuseIPDB. Il reerrnva les informations sur l'adresse IP dans la sortie standard dans diverses formats 

## Installation
cloner le git de gitea 

## comment utiliser ce script


si vous cliquez sur le fichier requirements.txt dans VSCode il propose de créer un nouvel environnement ".venv"(easy ), sois vous installer les requirment avec PIP pour les plus avancées , une fois cette étape terminée

vous ouvrez un nouveau terminal(dans VSCode dan le repertoire de l'executable) et tapez la commande "python.exe .\AbuseIPDB.py -j file.json -f .\list.txt"
où le paramètre -j indique que vous souhaitez le rapport en JSON (recommandé), et le -f indique le chemin de votre fichier contenant la liste des IPs

pour plus d'informations sur le script, consultez le dépôt git https://github.com/mikebanks/AbuseIPdbSCAN.git