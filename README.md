Ce projet est composé de plusieurs microservices, chaque microservice est dans une repository indépendant, vous allez trouver chaque repository ci dessous.

"Microservice-produits" :
Ce Microservice gère le produit. Il propose 2 opérations simples : lister tous les produits et récupérer un produit par son id.

👉 link : https://github.com/pipo9/m-produits

"Microservice-commandes" :
Microservice de gestion des commandes. Il permet de passer une commande et de récupérer une commande par son id.

👉 link : https://github.com/pipo9/m-commandes

"Microservice-paiements" :
Microservice permet de simuler le paiement d'une commande. Une fois le paiement enregistré, il fait appel au Microservice-commandes pour mettre à jour le statut de la commande.

👉 link : https://github.com/pipo9/m-paiement

"Microservice-client-ui" :
Simple client pour consommer nos Microservices.

👉 link : https://github.com/pipo9/m-clientui
