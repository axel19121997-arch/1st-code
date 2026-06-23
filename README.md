Voici une version mise à jour de ton README.md. J'ai enrichi les fonctionnalités pour refléter tout ce qui est réellement présent dans ton script (les combats, l'inventaire, le hasard, les sorts débloquables) et j'ai ajouté une section dédiée aux illustrations graphiques (victoire.png et gameover.png) avec les prérequis nécessaires pour que les utilisateurs n'aient pas de bugs d'affichage !

🏰 Projet Mini-RPG - Le Donjon de Naheulbeuk
Bienvenue dans le dépôt de mon tout premier projet de jeu vidéo ! C'est un mini-RPG textuel avec interface graphique, développé en Python et inspiré de l'univers déjanté et humoristique de la célèbre saga audio Le Donjon de Naheulbeuk.

Ce projet s'inscrit dans le cadre de mon apprentissage autodidacte de la programmation, de Python et de la gestion d'interfaces graphiques (GUI).

🚀 Fonctionnalités actuelles
Création de personnage complète : Personnalisation ou génération aléatoire du sexe, de la race (Humain, Elfe, Ogre, Nain, etc.) et de la classe (Guerrier, Mage, Ménestrel, Chaman...).

Système de statistiques dynamique : Gestion des caractéristiques (Courage, Force, Intelligence, Adresse) influencées par la classe et l'équipement.

Exploration procédurale : Progression à travers 20 salles générées aléatoirement (pièges à esquiver, marchands, fontaines magiques).

Taverne du Donjon : Événement de repos pour dépenser son or, restaurer ses PV (Points de Vie) ou sa Mana.

Combats au tour par tour : Affrontements contre un bestiaire varié (du Rat malodorant au Troll des cavernes) jusqu'au mythique combat final contre Zangdar.

Compétences & Sorts uniques : Deux capacités spéciales par classe, dont une destructrice se débloquant automatiquement lors du passage au niveau 2.

Gestion du Butin (Loot) : Ouverture de coffres au trésor contenant des armes de rareté différente (Commun, Rare, Légendaire) modifiant directement vos statistiques.

Événements textuels & RP : Intégration de traits humoristiques ("Chante faux", "BASTOOOOON") et choix situationnels face aux patrouilles d'Orcs.

🎨 Visuels et Médias
Le jeu intègre un affichage dynamique d'illustrations pour marquer les fins de parties, cependant j'ai conscience du bug d'affichage et je vais travaillais dessus pour le corriger :

🏆 victoire.png : S'affiche fièrement lorsque vous terrassez Zangdar et récupérez la douzième statuette de Gladeulfeurha.

💀 gameover.png : S'affiche pour saluer la triste fin de votre compagnie si vos PV tombent à zéro.

⚠️ Note importante : Pour que les images s'affichent correctement dans l'interface, les fichiers victoire.png et gameover.png doivent impérativement être placés dans le même dossier que le script Python principal.

🛠️ Technologies utilisées
Langage : Python 3

Bibliothèques standards : tkinter (Interface graphique), random, os

Bibliothèque tierce : Pillow (PIL) pour la gestion et le redimensionnement fluide des images PNG.

Outils : Git & GitHub pour le versioning.

📦 Comment lancer le projet ?
Pour tester le jeu sur votre machine, suivez ces étapes :

1. Cloner le projet
Bash
git clone https://github.com/axel19121997-arch/1st-code.git
cd 1st-code
2. Installer les dépendances (requis pour les images)
L'affichage des illustrations de fin nécessite la bibliothèque Pillow. Installez-la via votre terminal :

Bash
pip install Pillow
3. Exécuter le jeu
Lancez le script principal avec Python :

Bash
python "Jeu final.py"
