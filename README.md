# 🎬 Tier List Video Maker

Un outil web simple et sans dépendance pour créer de belles tier lists animées à partir d'images.

Conçu pour la chaîne YouTube **Marco & Jay**, ce projet a pour objectif de faciliter la création de tier lists soignées pour les vidéos : classez vos images, personnalisez l'animation et exportez le résultat, sans logiciel spécialisé.

## 🌐 Accès gratuit

Le projet est utilisable gratuitement en ligne : [tierlist-video-maker.jeremyracine2017.workers.dev](https://tierlist-video-maker.jeremyracine2017.workers.dev/).

## 🧩 Utilisation

1. Ouvrez `index.html` dans un navigateur récent.
2. Cliquez sur **Importer des images** ou faites glisser vos images dans l'application.
3. Classez chaque image dans une catégorie de **S** à **E**. Vous pouvez aussi saisir son nom avant de la classer.
4. Choisissez un mode et lancez **Aperçu**, ou exportez le résultat.

Les images importées sont triées par nom de fichier. Aucun serveur ni aucune installation de dépendances ne sont nécessaires.

## ✨ Fonctionnalités

- Classement dans six catégories personnalisables (S, A, B, C, D et E).
- Sous-niveaux permettant d'insérer les éléments au début, au milieu ou à la fin d'une catégorie.
- Aperçu animé avec réglages de vitesse, rythme, durée, son et apparence.
- Choix de la résolution, de la fréquence d'images, du fond et du mode d'ajustement des images.
- Trois modes : animation complète, animation d'un seul élément et image finale.
- Sauvegarde et ouverture d'un projet `.tierlist.json` avec les images et le classement inclus.
- Export d'une image PNG ou d'une séquence PNG, avec option de transparence.
- Export vidéo en MP4 lorsque le navigateur le prend en charge, sinon en WebM.
- Préférences de l'interface conservées dans le stockage local du navigateur.

## ⌨️ Raccourcis clavier

- **S, A, B, C, D, E** ou **1 à 6** : classer l'image en attente dans la catégorie correspondante.
- **+**, puis une catégorie : insérer l'image au début de la catégorie.
- **−**, puis une catégorie : insérer l'image à la fin de la catégorie.
- **Retour arrière** : annuler le dernier classement.
- **Espace** : passer l'image en attente à la fin de la liste.
- **Échap** : interrompre l'aperçu en cours.

Les raccourcis **+** et **−** s'utilisent lorsque l'option **Sous-niveaux (+ / −)** est activée.

## 📦 Exports et compatibilité

- L'export vidéo est enregistré en temps réel : gardez l'onglet de l'application actif pendant l'opération.
- L'export PNG en séquence utilise le sélecteur de dossier du navigateur. Il nécessite un navigateur compatible, tel que Chrome ou Edge.
- La transparence concerne l'export PNG ; la vidéo est exportée avec un fond opaque.
- Les fichiers du projet sauvegardé incluent les images importées. Conservez-les dans un endroit sûr pour pouvoir rouvrir le projet.

## 🛠️ Technologies

Application autonome construite avec HTML, CSS et JavaScript natifs. Le rendu de l'animation est dessiné dans un élément `canvas`.
