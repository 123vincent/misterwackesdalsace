# Mister Wackes d'Alsace

**Site actif : [https://misterwackesdalsace.fr/](https://misterwackesdalsace.fr/)**

---

Blog personnel de **Frédéric Aemmer**, alias *Mister Wackes d'Alsace* — personnage de carnaval alsacien inspiré de la tradition des [wackes et waggis](https://fr.wikipedia.org/wiki/Wackes).

Le site retrace les aventures de Mister Wackes d'Alsace lors des carnavals, fêtes de village, marchés de Noël et autres événements alsaciens (Mulhouse, Colmar, Séléstat, Strasbourg et alentours) : photos, galeries, récits de sorties.

## Stack technique

| Élément            | Détail                                                                          |
| ------------------ | ------------------------------------------------------------------------------- |
| Générateur de site | [Hugo](https://gohugo.io/) (site statique)                                      |
| Hébergement        | [Cloudflare Pages](https://pages.cloudflare.com/)                               |
| Source             | [GitHub](https://github.com) — déploiement automatique depuis la branche `main` |
| Langue             | Français                                                                        |

## Structure du projet

```
content/
  posts/          # Articles classés par année (2013, 2014, 2015, 2018…)
  a-propos/       # Page de présentation du personnage
assets/           # Ressources front-end (CSS, JS…)
static/           # Images et fichiers statiques
layouts/          # Templates Hugo personnalisés
hugo.toml         # Configuration du site
```

## Développement local

```bash
# Prérequis : Hugo installé (https://gohugo.io/installation/)
hugo server
```

Le site est accessible sur `http://localhost:1313`.

## Déploiement

Tout push sur la branche `main` déclenche un build automatique sur Cloudflare Pages.
