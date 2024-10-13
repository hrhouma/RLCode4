# RLCode3




## 1. Ouvrez l'invite de commande (Command Prompt) en tant qu'administrateur.

## 2. Naviguez vers le dossier où vous voulez créer votre projet. Par exemple :
   ```
   cd C:\Users\haythem\Documents
   ```


## 3. Créez la structure de dossiers avec ces commandes :
   ```
   mkdir q_learning_demo
   cd q_learning_demo
   mkdir QLearning
   mkdir helpers
   mkdir resources
   ```

Ces commandes vont créer le dossier principal `q_learning_demo` et ses sous-dossiers.

Ensuite, pour installer les dépendances :

## 4. Assurez-vous que pip est installé et à jour. Puis exécutez :
   ```
   pip install PyQt5 matplotlib gym
   ```

## 5. Pour créer les fichiers Python, vous pouvez utiliser la commande `type nul >` suivie du nom du fichier :
   ```
   type nul > main.py
   type nul > QLearning\QLearning.py
   type nul > helpers\helpers.py
   ```

## 6. Pour exécuter le projet, naviguez vers le dossier `q_learning_demo` et lancez le script principal :
   ```
   cd q_learning_demo
   python main.py
   ```

Ces commandes devraient fonctionner sur un système Windows. N'oubliez pas d'adapter les chemins si nécessaire selon votre configuration.
