# KouKidz — prototype v1
Prototype responsive de l'application KouKidz, avec une identité Bordeaux, blanc et doré.

Le prototype inclut l'accueil, les catégories, le catalogue, la recherche, les détails produit, le panier et le profil. Le panier et les informations de profil sont conservés dans le navigateur. La commande est préparée via WhatsApp.

Le catalogue contient uniquement des produits placeholders pour tester les parcours. Aucun produit réel n'est encore ajouté.

## Installation PWA
L'application doit être servie depuis `localhost` ou une adresse HTTPS. L'ouverture directe du fichier HTML (`file://`) ne permet pas l'installation ni le service worker.

- Android : ouvrir l'adresse dans Chrome, puis utiliser « Installer l'application » ou « Ajouter à l'écran d'accueil ».
- iPhone/iPad : ouvrir l'adresse dans Safari, toucher Partager, puis « Sur l'écran d'accueil ».

Le service worker met en cache la coque de l'application pour permettre son ouverture hors ligne après le premier chargement réussi.
