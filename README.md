# Implémentation d'une Solution Blockchain pour le Vote Électronique

Ce projet est une application simple de vote électronique basée sur la blockchain, développée en Python. Il permet d'assurer la transparence, l'intégrité, et l'unicité des votes exprimés.

> 🧑‍🏫 Ce projet a été réalisé dans un cadre académique sous la supervision de **Mr. OUAGUID**, et s’appuie sur le tutoriel pas-à-pas de [Satwik Kansal](https://gist.github.com/satwikkansal/4a857cad2797b9d199547a752933a715).

---

## 📌 Fonctionnalités

- ✅ Vote unique par utilisateur.
- ✅ Transparence via la blockchain.
- ✅ Interface utilisateur améliorée (HTML/CSS responsive).
- ✅ Résultats affichés en temps réel avec **Chart.js**.
- ✅ Page d’audit public des votes anonymisés.
- ✅ Synchronisation entre les nœuds.

---

## 📚 Tutoriel d’implémentation

Pour comprendre le fonctionnement interne de cette application blockchain, veuillez consulter le [tutoriel détaillé de Satwik Kansal](https://web.archive.org/web/20201222142511/https:/developer.ibm.com/technologies/blockchain/tutorials/develop-a-blockchain-application-from-scratch-in-python/#4-implement-a-proof-of-work-algorithm).

---

## ▶️ Instructions d’exécution

Clonez le projet :

```sh
$ git clone https://github.com/satwikkansal/python_blockchain_app.git
```

Installez les dépendances :

```sh
$ cd python_blockchain_app
$ pip install -r requirements.txt
```

Lancez un serveur de nœud blockchain :

```sh
$ export FLASK_APP=node_server.py
$ flask run --port 8000
```

Dans un autre terminal, exécutez l’interface utilisateur :

```sh
$ python run_app.py
```

Accédez à l’application à l’adresse : [http://localhost:5000](http://localhost:5000).

## 📸 Captures d’écran

1. Interface de vote

![image.png](https://github.com/chaymaAitB/Impl-mentation-d-une-Solution-Blockchain-pour-vote-lectronique/blob/main/screenshots/4.jpeg)

2. Soumission d’un vote

![image.png](https://github.com/chaymaAitB/Impl-mentation-d-une-Solution-Blockchain-pour-vote-lectronique/blob/main/screenshots/5.jpeg)

3. Vérification du vote unique par utilisateur 

![image.png](https://github.com/chaymaAitB/Impl-mentation-d-une-Solution-Blockchain-pour-vote-lectronique/blob/main/screenshots/6.jpeg)
