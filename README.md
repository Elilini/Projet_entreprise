Projet Algorithmique L2 - Entreprise:Instructions d'installation et d'exécution
Membres du groupe :
IDHAYAKUMAR Elilini -44011065
YAYHA LABCHIRI Rania 44008335


**1. Prérequis Système**
Pour l'environnement : installer Python 3.11.9.
Pour l'IA Locale:
Installer Ollama et télécharger le modèle Mistral 
Ensuite taper dans windows powershell:ollama pull mistral

**2.Structure du projet**

**3. Configuration du Backend**
Se placer dans le dossier backend/.

Créer l'environnement virtuel :
Dans powershell taper:python -m venv venv

Activer l'environnement :
Taper dans Windows powershell: .\venv\Scripts\activate

Installer les dépendances :
Taper dans Windows powershell:pip install fastapi uvicorn requests duckduckgo_search

Lancer le serveur :
Taper dans Windows powershell:python main.py
Le serveur est prêt sur http://127.0.0.1:8000.

**4:**
Pour lancer le serveur il suffit de taper ces commandes dans powershell:
cd C:\projet-entreprise(lien du fichier dans lequel est le projet)
.\venv\Scripts\activate
cd backend
python main.py



**5. Lancement du Frontend**
Naviguer dans le dossier frontend/.
Ouvrir le fichier index.html avec un navigateur web.
Saisir un SIREN (ex: 542051180) pour lancer l'analyse
