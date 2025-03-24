# MongoDB avec Python

MongoDB est une base de données NoSQL orientée document, idéale pour stocker des données flexibles sous forme de JSON. Python peut interagir avec MongoDB grâce à la bibliothèque pymongo.


## Installation

- Installer la bibliothèque :

```bash
  pip install pymongo
```

- Importer et tester la connexion :

```bash
  from pymongo import MongoClient
  client = MongoClient("mongodb://localhost:27017/")
  print("Connexion établie avec MongoDB")
```

