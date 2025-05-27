# Landing page du projet MVP
Visitez cette landing page [ICI](https://samuelroland.github.io/mvp/)

**Warning: ce projet est au stade de prototype, il n'est pas viable sur le long terme en terme technique.**

## Comment rédiger
1. Cloner ce repos
1. Installer `jekyll` (voir [ici](https://jekyllrb.com/docs/installation/))
1. Lancer `jekyll serve -l` (`-l` sert au live reload)
1. Editez `index.md` pour changer le contenu de le page principal, utiliser des classes TailwindCSS quand nécessaire
1. Modifier des schémas avec Excalidraw dans le dossier `schemas`, exporter des versions PNG en 3x et optimiser les avec `optipng`
1. Stocker les images sous `imgs` et optimiser les avec `optipng` avant de les commiter pour alléger le poids total de la page web. Le site fait 1.28MB (le 2025-05-27) actuellement.
1. Modifier `_layouts/default.html` pour changer le layout global si nécessaire
1. Faites attention à tester aussi la version mobile (Ctrl+Shift+M sur Firefox) pour s'assurer que cela s'affiche correctement sur petit écrans
1. `git push` pour déployer, c'est tout.

## Comment ça marche
1. La version CDN de TailwindCSS est inclue pour le style, ce n'est pas adaptée pour la production au départ
1. [Tailwind Typography](https://github.com/tailwindlabs/tailwindcss-typography) est intégré pour avoir une bonne base de style et ne pas tout refaire à la main. Une petite dose de customisation a été faite dans `default.html` pour être moins espacé que le setup de départ et d'avoir qqch de centré et plus large que la version par défaut.
1. Ce site est déployé via Github pages, il suffit de push et la CI se charge de compiler le projet et de le pousser sur https://samuelroland.github.io/mvp/.
