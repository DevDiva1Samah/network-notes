1. TLS (Transport Layer Security)
But : Sécuriser les échanges entre ordinateurs.
Ancien nom : SSL (Secure Sockets Layer).
Emplacement : Couche Présentation dans le modèle OSI.
Fonctionnement : HTTP + TLS = HTTPS (sécurisation du protocole HTTP).
Rôle : Chiffrement pour protéger les données contre l’interception.


2. TLS fournit 3 garanties principales :
Authentification : Vérifie que tu communiques avec le bon serveur.
Intégrité : Assure que les données n'ont pas été altérées.
Confidentialité : Les données échangées sont invisibles pour les tiers.


3. Chiffrement avec clé partagée
Fonction de chiffrement : Transforme un message simple en un message codé (chiffré) avec une clé.
Processus :
Utilisateur A envoie un message chiffré à B.
B utilise la même clé partagée pour déchiffrer et lire le message.
Importance : Tant que la clé est secrète, l'échange est sécurisé.


4. Problème de partage de clé
Facilité : Le chiffrement est simple une fois la clé partagée.
Problème : La transmission de la clé sur le réseau risque d’être interceptée.


5. Échange de clé de Diffie-Hellman
Objectif : Créer une clé partagée sans la transmettre directement.
Étapes :
A et B choisissent des nombres communs (a et b).
A choisit un nombre secret (p) et B un autre (q).
A et B calculent des clés publiques et les échangent.
A et B utilisent les informations échangées pour créer une clé partagée.
Résultat : A et B ont une clé secrète commune sans qu’elle ait transité directement sur le réseau.
