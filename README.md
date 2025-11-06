# vix-stock-index-analysis

### Configuration de l'environnement Python

Avant de commencer à travailler avec ce notebook, il est nécessaire de configurer correctement votre environnement Python. Cette étape permet d'assurer que toutes les dépendances sont installées et que le notebook fonctionne de manière isolée et reproductible.

**Étape 1 : Ouvrir le terminal**  

**Étape 2 : Créer un environnement virtuel**  
Un environnement virtuel permet d'isoler les dépendances du projet.  

- **Mac / Linux** :
```bash
python3 -m venv venv
```

* **Windows** :

```bash
python -m venv venv
```

**Étape 3 : Activer l'environnement virtuel**

* **Mac / Linux** :

```bash
source venv/bin/activate
```

* **Windows** :

```bash
.\venv\Scripts\activate
```

> **Remarque :** Une fois activé, vous devriez voir `(venv)` au début de votre ligne de commande.

**Étape 4 : Installer les dépendances**
Installez toutes les bibliothèques nécessaires en utilisant le fichier `requirements.txt` :

```bash
pip install -r requirements.txt
```

> Cela garantit que toutes les versions des packages sont conformes à ce projet.

**Étape 5 : Sélectionner le kernel Python dans VS Code**
Pour que le notebook utilise l'environnement virtuel :

1. Ouvrez la palette de commandes :

   * **Windows / Linux** : `Ctrl + Shift + P`
   * **Mac** : `Cmd + Shift + P`
2. Tapez `Python: Select Interpreter`
3. Sélectionnez l'environnement virtuel `venv` créé précédemment

**Étape 6 : Prêt à utiliser le notebook**
Patientez que tous les packages s'installent, puis vous pouvez maintenant exécuter les cellules du notebook en toute sécurité.
Toutes les bibliothèques nécessaires sont installées et isolées dans l'environnement virtuel.
