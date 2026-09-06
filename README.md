# gerod_deck

Deck de présentation de **GEROD** — Gestion Routière de Djibouti.

Un seul fichier, autonome : [`GEROD_Presentation.html`](GEROD_Presentation.html).
Il s'ouvre dans n'importe quel navigateur, sans serveur ni installation.

## Contenu

Douze diapositives, du processus de détection à la mise en place :

1. Ouverture
2. Filmer n'est pas connaître
3. Le processus de détection — de l'image à la plaque
4. La philosophie de GEROD
5. Une donnée produite : le passage
6. Les fonctions de base
7. Les fonctions avancées
8. La gestion des infractions
9. La connaissance routière
10. Le suivi et l'évaluation
11. Une installation progressive
12. Clôture

## Commandes

| Touche | Effet |
|---|---|
| `←` `→` `espace` | Naviguer (un clic avance aussi) |
| `S` | Sommaire, pour sauter à une diapositive |
| `T` | Basculer thème clair / thème sombre |
| `F` | Plein écran |
| `Début` `Fin` | Première / dernière diapositive |

L'adresse porte le rang : `GEROD_Presentation.html#7` ouvre directement la septième.

## Notes techniques

- Scène fixe de 1280 × 720 mise à l'échelle du viewport — la typographie est
  identique sur tout projecteur.
- Deux thèmes complets. Sans choix explicite, le deck suit le réglage du
  système ; le choix fait à l'écran est mémorisé.
- Animation d'ouverture reprise du splashscreen de l'application, adaptée aux
  deux thèmes.
- Les polices viennent de Google Fonts : une connexion améliore le rendu, son
  absence ne casse rien (repli système).
- Lighthouse (desktop) : performance 99, accessibilité 100, bonnes pratiques
  100, SEO 100. Les contrastes ont été vérifiés dans les deux thèmes, toutes
  diapositives dépliées.
