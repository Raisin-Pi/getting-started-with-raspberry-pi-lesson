# Leçon 1 - Bien débuter avec le Raspberry Pi

Le Raspberry Pi est un petit ordinateur plus petit qu'un paquet de cartes, qui peut modifier la façon dont nous percevons et abordons l'informatique. Dans cette leçon, nous allons présenter les composants de base du Raspberry Pi et à quoi il se rapportent dans un ordinateur traditionnel.

Nous allons discuter de la nature générale de l'informatique et comment le même ordinateur peut être programmé pour faire simultanément beaucoup de choses différentes, du traitement de texte à la musique électronique. Enfin, nous allons introduire le principe le plus fondamental de la programmation: un programme comme une séquence d'instructions.

## Objectifs d'apprentissage

- Connaître l'architecture de base d'un dispositif informatique.
- Comprendre la différence entre le matériel et le logiciel.
- Être en mesure d'installer un Raspberry Pi, le démarrer, charger l'interface utilisateur graphique, et naviguer dans le bureau pour la première fois.

## Connaissances acquises

**Tous les étudiants sont en mesure de :**

- Branchez les composants d'un Raspberry Pi.
- Comprendre que les ordinateurs sont des appareils à usage général, et que chaque ordinateur est différent.
- Identifier l'architecture de base d'un ordinateur: processeur, stockage et les entrées/sorties.

**La plupart des étudiants sont en mesure de:**

- Installer un Raspberry Pi pour la première fois, se connecter, et charger l'interface utilisateur graphique.
- Identifier les différents types d'ordinateurs et d'expliquer ce qui en fait des ordinateurs.
- Identifier l'architecture de base d'un ordinateur: processeur, stockage et les entrées/sorties.

**Certains étudiants sont en mesure de:**

- Installer un Raspberry Pi, se connecter, et charger l'interface utilisateur graphique sans assistance.
- Expliquer, avec des exemples, les similitudes et les différences d'un Raspberry Pi par rapport à un ordinateur personnel.

## Résumé de la leçon

- Une introduction aux parties physiques de base d'un Raspberry Pi
- Une introduction aux deux types d'interface d'ordinateur:
	- ligne de commande
	- graphique

## Débuter

Distribuez les [Les cartes de dispositif informatique](files/Computing-Device-Card-Sort.zip) à des paires d'étudiants. Demandez-leur de faire correspondre le dispositif à la description. Ensuite, demandez aux élèves de créer deux piles: une pour les dispositifs qu'ils jugent comme un type d'ordinateur, et un pour les appareils qu'ils ne pensent pas être des types d'ordinateurs.

Après quelques minutes, discuter des résultats de cette exercice avec la classe. Notez que toutes les cartes sont des types de dispositifs informatiques! Inspirez vous des réponses des élèves pour discuter de ce qui fait un ordinateur.

## Main development

1. Watch the official ['What is a Raspberry Pi?'](http://www.youtube.com/watch?v=e0wkVVVLvR8) animation.

1. Start with all the parts of the Raspberry Pi on a table:

	- keyboard
	- mouse
	- SD memory card
	- power supply
	- monitor
	- monitor cable
	- Raspberry Pi

	Ask the class to name and describe each component as you connect it to the Raspberry Pi in front of them.

	Explain that these components are **hardware**. Hardware refers to the physical elements of the computer that you can see and touch. This includes what is sometimes hidden inside the case.

	Finally, plug in the power and watch it boot up. An alternative demonstration would be to leave out the memory card and attempt to boot the Pi, which will fail. You can then describe the memory card as something that contains instructions to tell the Raspberry Pi how to start.

1. Demonstrate that the Raspberry Pi is a **standard** computer by opening up some applications and closing them again. If you are able to connect the Raspberry Pi via a network connection, then open up a web browser and surf to several different sites.

	Explain that this is software. Software is the term given to programs that run on the computer system and make the hardware work. Software has many uses, such as making a calculation or organising files. There are two main types of software: system software which runs and manages your computer, and application software which performs a specific task or function.

1. Distribute equipment to students and ask them to set up their own Raspberry Pis. Distribute the power supplies last, checking that students have connected their cables and SD cards correctly before they are powered up.

1. Ask students to log in to their Pis for the first time using the following login information:

	```
	Login: pi
	password: raspberry
	```

	Note that students will not see any text when typing the password but assure them it is working. Why do they think this might be the case? *Hint: what might happen if someone was looking over their shoulder?*

	Once logged in, explain to the students that they can give instructions to the Raspberry Pi using the **command line interface**.

1. Load the graphical user interface by typing `startx`.

	Explain to the students that they have now loaded the **Graphical User Interface** or GUI of the operating system. Ask them to identify any parts that they recognise such as the desktop, task bar, menu system, mouse pointer, icons, etc.

1. As an extension task, ask students to compare a Raspberry Pi to a desktop computer. What are the similarities? What are the differences? In what situations could you use a Raspberry Pi instead of a desktop computer? (e.g. in a weather station)

## Plenary

Students are to label a Raspberry Pi to include:

- all inputs (and where they connect to the Pi)
- all outputs (and where they connect to the Pi)
- processor
- storage (i.e. where the SD card goes)
- power.

This could be completed with sticky notes, a hand drawn diagram on paper, or on a computer using shapes and call out boxes.
