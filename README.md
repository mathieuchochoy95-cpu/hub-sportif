# Hub sportif

Programme d'entraînement, suivi des séances, tableau de bord et nutrition pour le street workout, le volley et la course à pied.

## Mise en ligne (GitHub Pages)

1. Crée un dépôt public sur GitHub, par exemple `hub-sportif`.
2. Dépose tous les fichiers de ce dossier à la racine du dépôt (bouton « Add file », puis « Upload files »).
3. Dans le dépôt : Settings, puis Pages. Dans « Build and deployment », choisis la source « Deploy from a branch », la branche `main` et le dossier `/ (root)`, puis Save.
4. Après une à deux minutes, le hub est en ligne sur `https://<ton-identifiant>.github.io/hub-sportif/`.

## Installation sur téléphone

- iPhone (Safari) : bouton Partager, puis « Sur l'écran d'accueil ».
- Android (Chrome) : menu ⋮, puis « Installer l'application » ou « Ajouter à l'écran d'accueil ».

## Données

Les données sont enregistrées sur l'appareil, dans le navigateur. Elles ne se synchronisent pas entre téléphone et ordinateur.
Fais une sauvegarde complète chaque semaine : onglet « Suivi des séances », bouton « Exporter mes données », « Sauvegarde complète (JSON) ».
Le même menu permet de restaurer une sauvegarde sur un autre appareil.

Le dépôt peut être public : il ne contient aucune donnée personnelle, seulement l'application.

## Mettre à jour

Remplace `index.html` dans le dépôt. Si tu modifies aussi d'autres fichiers, change le nom du cache dans `sw.js` (`hub-sportif-v1` en `hub-sportif-v2`) pour forcer la mise à jour sur les téléphones.
