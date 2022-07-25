# Slippi mirroring

## Matériel
- Une Wii hackée avec Homebrew Channel et Nintendont Slippi
- Une Wiimote (pour le premier paramétrage, inutile ensuite)
- Un PC avec port Ethernet et Slippi d'installé
- un adaptateur Ethernet - USB 2.0

## Préparation
- Connecter la Wii au PC en Ethernet

## 1. Paramétrage du PC
1. Ouvrir le menu démarrer et chercher "network status", ouvrir l'application
2. Cliquer sur "Change adapter settings"
3. Clic droit sur la connexion principale (le Wifi ou autre connexion) > Properties
4. Onglet Sharing :
   - Cocher la case
   - Choisir l'Ethernet correspondant à la Wii dans la liste déroulante

## 2. Paramétrage du réseau Wii
Depuis le menu système de la Wii :
1. Accéder au menu de paramétrage des connections :
   - Options Wii > Paramètres Wii > Internet (page 2) > Paramètres de connexion
2. Choisir une connexion :
   - Changer le mode de connection "Connexion par câble"
   - Lancer le test de connexion
   - Refuser la mise à jour
   - "Utiilser cette connexion" pour la définir comme par défaut
3. All good

## 3. Récupérer l'IP de la Wii
1. Lancer la Homebrew Channel
2. Attendre que le logo Wifi s'arrête de clignoter
3. Appuyer sur Start et récupérer l'addresse IP notée dans le coin de l'écran

## 4. Lancer Melee avec Slippi Network activé
1. Lancer Nintendont Slippi depuis la Homebrew Channel
2. Presser B sur l'ISO correspondant à Melee NTSC 1.02
3. Activer "Slippi Networking"
4. Presser Start pour sauvegarder la configuration pour cette session seulement
5. Lancer Melee NTSC 1.02

## 5. Connecter Slippi Launcher à la Wii
1. Lancer Slippi Launcher
2. Aller sur le 4ème onglet "Console Mirror"
3. Si la Wii n'apparaît pas, cliquer sur "+ New connection"
4. Entrer l'adresse IP dans le champ texte et activer le Enable Real-Time Mode
5. Sauvegarder les paramètres et cliquer sur "Connect"
6. Une fois connecté, cliquer sur Mirror
7. Profit.
