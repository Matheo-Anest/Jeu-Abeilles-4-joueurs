# 🐝 La Guerre du Nectar : Bzzz !

Bienvenue dans le jeu **Bzzz**, un jeu de stratégie au tour par tour développé en Python. Quatre colonies d'abeilles s'affrontent sur un plateau pour récolter le précieux nectar, gérer leurs ressources et défendre leur territoire.

---

## 🛠️ Installation et Prérequis

### Prérequis
* Vous devez avoir **Python** installé sur votre machine.
* Le projet utilise la bibliothèque **Pillow** pour les images.
* Installation : `pip install pillow`.

### Arborescence du dossier
* `main.py`
* `modele.py`
* `tkiteasy.py`
* `images/` (dossier contenant les fichiers .png)

---

## 🚀 Comment lancer le jeu

1. Ouvrez votre terminal ou invite de commande.
2. Placez-vous dans le dossier du jeu.
3. Lancez la commande : `python main.py`.

---

## 🎮 Tutoriel : Comment jouer ?

Le jeu se joue entièrement à la **souris**.

### 1. Début de partie 
Au lancement, choisissez votre abeille de départ : **Ouvrière**, **Bourdon** ou **Éclaireuse**.

### 2. Actions principales
* **Interface** : Le panneau en bas indique votre couleur, votre nombre d'abeilles et votre nectar.
* **Faire spawn une abeille** : Cliquez sur votre ruche (si elle est vide et que vous avez assez de nectar). Attention, déplacer une abeille termine la phase de ponte pour ce tour.
* **Déplacement et Butinage** : Cliquez sur une abeille pour voir ses mouvements possibles. Cliquez sur une fleur pour choisir entre vous déplacer ou butiner. Le nectar est récupéré à la fin du tour.
* **Sécuriser le nectar** : Déplacez vos abeilles dans votre base (zone de 4x4 cases autour de la ruche) pour décharger automatiquement le nectar récolté.
* **Fin du tour** : Cliquez sur "Fin de Tour" ou attendez que toutes les actions soient épuisées.

### 3. Escarmouches (Combats)
Le combat est automatique à la fin du tour si une de vos abeilles est à côté d'une ennemie. L'abeille perdante tombe KO, perd son nectar et est immobilisée temporairement.

---

## 🏆 Conditions de Victoire

* **Victoire Éclair** : Un joueur possède plus de 50% du nectar total.
* **Victoire aux points** : Plus de nectar sur le plateau ; le joueur le plus riche gagne.
* **Temps écoulé** : La limite de 300 tours est atteinte.
