# Préparer l'environnement de développement

### Prérequis

Pour commencer à développer Papillon vous avez besoin des outils suivants:

* Git ([https://git-scm.com](https://git-scm.com/))
* NodeJS ([https://nodejs.org/en](https://nodejs.org/en))
* xCode, si vous comptez compiler pour iOS
* Une fork de Papillon
* Un IDE comme VSCode ([https://code.visualstudio.com](https://code.visualstudio.com))

### Installation du repo

Ce script effectue un clonage du dépôt git de Papillon auquel vous ne pouvez pas effectuer de changements, c'est pour cela qu'il vous faut remplacer l'url après `clone` par celle de votre fork que vous avez créé précédemment.

{% tabs %}
{% tab title="npm" %}
```sh
git clone git@github.com:PapillonApp/Papillon.git
cd Papillon
npm install
```
{% endtab %}

{% tab title="pnpm" %}
```sh
git clone git@github.com:PapillonApp/Papillon.git
cd Papillon
pnpm install
```
{% endtab %}
{% endtabs %}

Et voilà vous avez maintenant votre propre version de Papillon

### Vers l'infini et l'au delà...!

Voilà! Vous avez une copie locale de Papillon prête à être améliorée par vos soins, pourquoi ne pas jeter un coup d'œuil à comment lancer le serveur de développement ou en apprendre un peu plus sur la structure du code?

La seule limite est votre imagination!
