# 🛠️ Installation & ⚙️ Configuration du Projet 🐍 Django & ⚛️ React

📘 Ce guide explique comment configurer un projet utilisant 🐍 Django pour le backend et ⚛️ React pour le frontend, ainsi que les outils nécessaires pour un 🖥️ environnement de développement moderne.

## 🐍 Installation de Python & Django

🚀 Pour commencer, installez 🐍 Django et Django REST Framework :

```bash
🐚 pip install django djangorestframework
```

🔧 Ensuite, créez les migrations et appliquez-les pour configurer la 🗄️ base de données :

```bash
🐚 python manage.py makemigrations  # 👀 Pour voir les changements
🐚 python manage.py migrate         # ✔️ Pour affecter les changements
```

▶️ Enfin, lancez le serveur de développement 🐍 Django :

```bash
🐚 python manage.py runserver
```

## ⚙️ Configuration de NPM & du Frontend

Pour configurer l’environnement JavaScript 📦, exécutez les commandes suivantes :

### 🛠️ Initialisation de NPM

Initialisez un projet NPM 📦 :

```bash
🐚 npm init -y
```

### 📦 Installation des dépendances de développement

Installez Webpack ⚙️ et ses outils :

```bash
🐚 npm i webpack webpack-cli --save-dev
```

Installez Babel 🛠️ pour la compilation de JavaScript moderne et ⚛️ React :

```bash
🐚 npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
```

### ⚛️ Installation des dépendances de production

Installez ⚛️ React et React DOM 🖥️ :

```bash
🐚 npm i react react-dom --save-dev
```

### 📚 Installation des bibliothèques supplémentaires

Pour une interface utilisateur enrichie ✨, installez Material-UI 🎨 et ses icônes 🖼️ :

```bash
🐚 npm install @material-ui/core
🐚 npm install @material-ui/icons
```

➕ Ajoutez le plugin Babel 🛠️ pour la prise en charge des propriétés de classes :

```bash
🐚 npm install @babel/plugin-proposal-class-properties
```

➡️ Installez React Router pour la gestion des routes 🛣️ :

```bash
🐚 npm install react-router-dom
```

## ✅ C**onclusio**n

Vous avez maintenant configuré un projet 🐍 Django pour le backend et ⚛️ React avec Webpack ⚙️ pour le frontend. Vous pouvez 🚀 démarrer le développement de votre application en utilisant les outils et les configurations ci-dessus.

