
# HelloToastConstraintLayout

**HelloToastConstraintLayout** est une application Android simple qui démontre l'utilisation de `ConstraintLayout` pour concevoir une interface utilisateur. L'application comprend un compteur qui s'incrémente à chaque clic sur un bouton et affiche un message toast. Cette application aide les débutants à comprendre les concepts de base du développement Android, les dispositions de l'interface et la gestion des événements.

## Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Captures d'écran](#captures-décran)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Fonctionnalités

- **Message Toast** : Affiche un message toast lorsque l'utilisateur clique sur le bouton "Toast".
- **Compteur** : Incrémente un compteur chaque fois que l'utilisateur clique sur le bouton "Compter".
- **ConstraintLayout** : Montre l'utilisation de `ConstraintLayout` pour organiser les composants de l'interface utilisateur.
- **Styles Personnalisés** : Couleurs personnalisées et formatage de texte appliqués aux boutons et TextViews.

## Installation

Pour exécuter ce projet localement, suivez ces étapes :

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/ZinebELHALLA/HelloToastConstraintLayout.git
   ```
2. Ouvrez le projet dans **Android Studio**.
3. Laissez Android Studio configurer le projet et télécharger les dépendances nécessaires.
4. Connectez un appareil Android ou configurez un émulateur Android.
5. Cliquez sur le bouton **Run** dans Android Studio ou utilisez `Shift + F10` pour compiler et exécuter l'application.

## Utilisation

1. Ouvrez l'application sur votre appareil Android ou émulateur.
2. Vous verrez deux boutons : **Toast** et **Compter**, ainsi qu'un compteur affiché au centre de l'écran.
3. En cliquant sur le bouton **Toast**, un message toast indiquant "Hello, this is a Toast!" apparaîtra.
4. En cliquant sur le bouton **Compter**, le nombre affiché au centre de l'écran s'incrémentera.

### Structure du projet :

- **MainActivity.java** : Contient la logique pour les événements de clic sur les boutons et la gestion du compteur.
- **activity_main.xml** : Définit l'interface utilisateur, y compris les boutons et le TextView pour le compteur.
- **res/values/colors.xml** : Contient les définitions de couleurs personnalisées.
- **res/layout/activity_main.xml** : Définit la mise en page à l'aide de `ConstraintLayout`.
- **gradle** : Gère les dépendances du projet et les paramètres de construction.

## Captures d'écran

| Appui sur le bouton Toast | Appui sur le bouton Compter | 
|--------------------------|----------------------------|
| ![Toast Button](images/toast.png) | ![Count Button](images/count.png) |

## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, n'hésitez pas à forker le dépôt et à soumettre une pull request.

1. Forkez le dépôt.
2. Créez une nouvelle branche.
3. Effectuez vos modifications.
4. Soumettez une pull request pour examen.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
