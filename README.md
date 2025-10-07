# 🏦 BankApp — Application Bancaire en Python (Tkinter)

Une application bancaire graphique développée en **Python / Tkinter**, permettant la **gestion de comptes clients**, des **budgets** et des **transactions**, avec un **système d’authentification** et un **stockage sécurisé** (cryptage en codage César 🔐).

---

## 🚀 Fonctionnalités principales

### 🔐 Authentification
- Création de comptes clients (nom d’utilisateur + mot de passe).
- Connexion sécurisée (identifiants stockés dans un fichier crypté).
- Vérification automatique de l’identité à chaque lancement.

### 💰 Gestion des comptes
- Consultation du solde actuel.
- Historique complet des transactions.
- Ajout / retrait d’argent en temps réel.

### 📊 Gestion du budget
- Suivi des revenus et des dépenses.
- Catégorisation des transactions (nourriture, transport, loisirs, etc.).
- Visualisation des statistiques budgétaires.

### 📁 Stockage des données
- Toutes les informations (utilisateurs, soldes, transactions) sont stockées localement dans des fichiers texte **cryptés par un codage César**.
- Le décryptage s’effectue automatiquement lors du chargement de l’application.

---

## 🧠 Technologies utilisées

| Composant              | Description                              |
|------------------------|------------------------------------------|
| 🐍 Python 3.x          | Langage principal                        |
| 🖼️ Tkinter             | Interface graphique native de Python      |
| 🔏 Codage César        | Cryptage basique pour la protection des fichiers |
| 📂 Fichiers `.txt`     | Base de données locale (sans SQL)        |

---




🔒 À propos du codage César
Le codage César est un chiffrement par décalage de lettres :

chaque caractère est remplacé par un autre situé à une distance fixe dans l’alphabet.

Dans ce projet :

Les données sont cryptées avant d’être sauvegardées.

Elles sont déchiffrées automatiquement à la lecture.

Cela permet une première approche simple de la sécurité des données.

(Ce n’est pas un vrai chiffrement moderne, mais c’est parfait pour un projet d’apprentissage L1 !)

🎯 Objectifs pédagogiques
Découvrir la programmation orientée objet avec Python.

Manipuler des interfaces graphiques (Tkinter).

Gérer des fichiers et des données persistantes.

Introduire les notions de cryptographie et de sécurité.

Concevoir une architecture modulaire (plusieurs fichiers Python).

✨ Idées d’améliorations futures
🔑 Passer à un vrai chiffrement (ex: cryptography ou hashlib).

💾 Sauvegarder les données dans une base SQLite.

📈 Ajouter des graphiques pour le suivi du budget.

🌐 Créer une version web (Flask / Django).

📱 Adapter l’interface pour mobile (Kivy).

👨‍💻 Auteur
Benoufella Mohamed Yacine
💡 Projet universitaire : Application bancaire en Python (Tkinter)
