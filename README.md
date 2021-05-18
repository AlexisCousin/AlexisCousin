- 👋 Hi, I’m @AlexisCousin
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
Partie 1 : Loi des nœuds et loi des mailles
➔ Voir Rappel 2
➔ Voir Vidéo 1 : Loi des nœuds - loi des mailles
Objectifs
• Représenter une tension.
• Connaître et savoir exploiter la loi des mailles et la loi des nœuds.
1. La loi des mailles
Une maille est une boucle fermée composée de plusieurs dipôles qui ne comporte pas forcément
de générateur.
a. Loi des mailles
Dans une maille orientée dont on a fixé arbitrairement le sens de parcours, la somme des
tensions est nulle.
b. Exemple :
Ici, dans la maille NCBAP, on peut écrire UCN+UBC+UAB+UPA−UPN=0
Schéma électrique d’un circuit
On remarque que la tension électrique aux bornes d’un générateur (ici une pile) se représente
en sens inverse de celles des autres dipôles.
En bleu sont représentées les tensions électriques et en rouge la maille NCBAP.
2. La loi des nœuds
Un nœud est une connexion qui relie au moins trois dipôles entre eux.
a. Loi des nœuds
Dans un circuit en dérivation, la somme des intensités des courants électriques qui arrivent à un
nœud est égale à la somme des intensités des courants électriques qui en repartent.
b. Exemple
On peut ici écrire I1+I2=I3+I4.
Représentation d’un nœud et des intensités qui y arrivent et en repartent
<!---
AlexisCousin/AlexisCousin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->Objectif
 Utiliser la loi d’Ohm.
 Exploiter la caractéristique d’un dipôle électrique : point de fonctionnement,
modélisation par une relation U=f(I) ou I=f(U).
1. La loi d’Ohm : Voir rappel 3 :
La tension électrique U aux bornes d’un conducteur ohmique est proportionnelle à
l’intensité I du courant électrique qui le traverse. La constante de proportionnalité est la valeur
de la résistance R de ce conducteur ohmique : U=R×I avec U en volt (V), R en Ohm (Ω) et I en
ampère (A).
2. Caractéristiques d'un dipôle
a. La caractéristique courant-tension
La caractéristique courant-tension d’un dipôle est la courbe qui traduit l’évolution de la tension
U aux bornes du dipôle en fonction de l’intensité I du courant qui le traverse. On la note U=f(I).
Cette courbe caractérise le dipôle considéré et permet de trouver l’intensité qui traverse un
dipôle connaissant la tension à ses bornes, ou inversement.
Exemple : cas d’une résistance (vu au collège)
Caractéristique courant-tension d’une résistance
b. La caractéristique tension-courant
Pour certains dipôles, on représente la caractéristique tension-courant, notée I=f(U).
Exemple : cas d’une diode
Caractéristique tension-courant d’une diode
2
c. Le point de fonctionnement
En traçant sur le même graphique toutes les caractéristiques des dipôles du circuit,
on détermine le point de fonctionnement du circuit. Le point de fonctionnement a les
coordonnées du point d’intersection des caractéristiques des dipôles du circuit.
Pour un circuit en série, l’intensité du point de fonctionnement sera celle qui circule dans le
circuit et la tension du point de fonctionnement sera celle aux bornes du dipôle concerné.
Exemple1 :
Le graphique ci-dessous montre le point de fonctionnement d’un circuit qui contient une
résistance et une pile (schémas ci-dessus).
Ce point de fonctionnement a les coordonnées (IF ; UF).
Tracé du point de fonctionnement
Exemple 2 : Voir le livre page 281
3. Les capteurs
a. Définition :
Un capteur électrique est un dipôle qui permet de convertir une grandeur physique comme
la luminosité, la température, la pression ou autre en un signal électrique.
Il permet donc de transformer une grandeur physique mesurable en une grandeur physique
exploitable par un dispositif de commande : ordinateur, microcontrôleur, etc.
Un capteur est caractérisé par sa courbe d’étalonnage qui permet de faire correspondre les
grandeurs mesurées aux grandeurs exploitables en sortie.
b. Quelques exemples de capteurs
