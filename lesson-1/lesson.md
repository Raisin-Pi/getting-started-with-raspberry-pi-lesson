# Leçon 1 - Bien débuter avec le Raspberry Pi

Le Raspberry Pi est un petit ordinateur plus petit qu'un paquet de cartes, qui peut modifier la façon dont nous percevons et abordons l'informatique. Dans cette leçon, nous allons présenter les composants de base du Raspberry Pi et à quoi il se rapportent dans un ordinateur traditionnel.

Nous allons discuter de la nature générale de l'informatique et comment le même ordinateur peut être programmé pour faire simultanément beaucoup de choses différentes, du traitement de texte à la musique électronique. Enfin, nous allons introduire le principe le plus fondamental de la programmation: un programme comme une séquence d'instructions.

## Objectifs d'apprentissage

- Connaître l'architecture de base d'un dispositif informatique.
- Comprendre la différence entre le matériel et le logiciel.
- Être en mesure d'installer un Raspberry Pi, le démarrer, charger l'interface utilisateur graphique, et naviguer dans le bureau pour la première fois.

## Connaissances acquises

**Tous les enfants sont en mesure de :**

- Brancher les composants d'un Raspberry Pi.
- Comprendre que les ordinateurs sont des appareils à usage général, et que chaque ordinateur est différent.
- Identifier l'architecture de base d'un ordinateur: processeur, stockage et les entrées/sorties.

**La plupart des enfants sont en mesure de:**

- Installer un Raspberry Pi pour la première fois, se connecter, et charger l'interface utilisateur graphique.
- Identifier les différents types d'ordinateurs et d'expliquer ce qui en fait des ordinateurs.
- Identifier l'architecture de base d'un ordinateur: processeur, stockage et les entrées/sorties.

**Certains enfants sont en mesure de:**

- Installer un Raspberry Pi, se connecter, et charger l'interface utilisateur graphique sans assistance.
- Expliquer, avec des exemples, les similitudes et les différences d'un Raspberry Pi par rapport à un ordinateur personnel.

## Résumé de la leçon

- Une introduction aux parties physiques de base d'un Raspberry Pi
- Une introduction aux deux types d'interface d'ordinateur:
	- ligne de commande
	- graphique

## Débuter

Distribuez les [cartes de dispositif informatique](files/Computing-Device-Card-Sort.zip) à des paires d'enfants. Demandez-leur de faire correspondre le dispositif à la description. Ensuite, demandez aux enfants de créer deux piles: une pour les dispositifs qu'ils jugent comme un type d'ordinateur, et un pour les appareils qu'ils ne pensent pas être des types d'ordinateurs.

Après quelques minutes, discuter des résultats de cette exercice avec la classe. Notez que toutes les cartes sont des types de dispositifs informatiques! Inspirez vous des réponses des enfants pour discuter de ce qui fait un ordinateur.

## Développement principal

1. Regardez l'animation officielle en anglais si les enfants sont capables de comprendre ['Qu'est ce qu'un Raspberry Pi?'](http://www.youtube.com/watch?v=e0wkVVVLvR8).

1. Commencez avec toutes les parties du Raspberry Pi sur une table:

	- clavier
	- souris
	- carte mémoire SD
	- alimentation
	- moniteur
	- câble vidéo
	- Raspberry Pi

	Demandez aux enfants de nommer et décrire chaque composant que vous connectez au Raspberry Pi face à eux.

	Expliquez que ces composants sont du **hardware**. Hardware se réfère aux éléments physiques de l'ordinateur que vous pouvez voir et toucher. Cela comprend ce qui est parfois caché dans le boitier.

	Enfin, branchez l'alimentation et regardez-le démarrer. Une démonstration alternative serait de laisser la carte mémoire et tenter de démarrer le Pi, ce qui échouera. Vous pouvez ensuite présenter la carte mémoire comme quelque chose qui contient des instructions pour dire au Raspberry Pi comment démarrer.

1. Démontrez que le Raspberry Pi est un ordinateur **standard** en ouvrant et fermant certaines applications. Si vous êtes en mesure de connecter le Raspberry Pi via une connexion réseau, ouvrez un navigateur Web et surfez sur plusieurs sites.

	Expliquez que ceci est un logiciel. Le logiciel est le terme donné à des programmes qui fonctionnent sur le système informatique et font fonctionner le matériel. Le logiciel a de nombreuses utilisations, telles que la réalisation d'un calcul ou l'organisation des fichiers. Il existe deux principaux types de logiciels: le logiciel système qui fonctionne et gère votre ordinateur, et le logiciel d'application qui effectue une tâche ou une fonction spécifique.

1. Distribuez le matériel aux enfants et leur demander de mettre en place leur propre Raspberry Pi. Distribuez les alimentations à la fin, vérifier que les enfants aient relié leurs câbles et cartes SD correctement avant qu'ils ne soient mis sous tension.

1. Demandez aux enfants de se connecter à leur Pis pour la première fois en utilisant les informations d'identification suivantes:

	```
	Login: pi
	password: raspberry
	```

	Notez que les enfants ne verront pas de texte lors de la saisie du mot de passe, mais assurez-les qu'il fonctionne. Pourquoi pensent-ils que cela soit ainsi ? *Astuce: ce qui pourrait arriver si quelqu'un regardait par-dessus leur épaule?*

	Si vous utilisez la dernière version du logiciel, vous pouvez allez directement dans l'environnement du bureau ou l'**Interface Utilisateur Graphique**. Si vous utilisez une version plus ancienne, il faudra charger l'interface utilisateur graphique (GUI) en tapant `startx`. Expliquez aux enfants qu'ils ont maintenant chargé l'**Interface utilisateur graphique** (GUI) du système d'exploitation. Une fois connecté, expliquez aux enfants qu'ils peuvent donner des instructions au Raspberry Pi en utilisant l'**interface de ligne de commande** au lieu de GUI.

1. Demandez-leur d'identifier toutes les parties qu'ils reconnaissent comme le bureau, la barre des tâches, le système de menu, le pointeur de la souris, les icônes, etc.. Demandez aux enfants d'ouvrir la fênetre `Terminal` en cliquant sur **Menu**, **Accessoires** et **Terminal**. C'est à quoi ressemble l'**interface de ligne de commande**. Demandez aux enfants d'essayer différentes commandes comme `ls` pour lister des fichiers et des répértoires* et `cd`pour changer entre les différents répertoires. 

1. Pour aller plus loin, demandez aux enfants de comparer un Raspberry Pi à un ordinateur de bureau. Quelles sont les similitudes? Quelles sont les différences? Dans quelles situations pourriez-vous utiliser un Raspberry Pi au lieu d'un ordinateur de bureau? (Par exemple dans une station météorologique)

## Plénière

Les enfants étiquetent un Raspberry Pi pour décrire:

- toutes les entrées (et où elles se connectent au Pi)
- toutes les sorties (et où ils se connectent au Pi)
- processeur
- stockage (à savoir où la carte SD va)
- Alimentation.

Cela pourrait être complété par des notes autocollantes, un schéma dessiné à la main sur papier, ou sur un ordinateur.

*En informatique, un répertoire ou un dossier est une liste de descriptions de fichiers.
