# choco-latin.github.io
Test for github pages

## Besoins

- formulaire d'abonnement à une newsletter
- formulaire de contact
- formulaire d'inscription pour un évenement
- embed de publications instagram

On ne gardera pas le chat à la con

## solutions

il faut un service qui fasse tourner un serveur.

- https://formspree.io/plans
  - la version gratuite ne permet que 50 soumissions par mois, sinon 10€/mois pour 200 : trop cher !!
- https://docs.netlify.com/forms/setup/
  - rien compris
- https://formkeep.com/features/pricing? 50 par mois idem, sinon 5€ pour 1000
- https://liveformhq.com/pricing 3€/mois, soumissions illimitées, 5 forms/months
- https://formcarry.com idem que formspree
- Framaforms???

## framaforms

- c'est gratuit et libre
- pas trop de limites techniques si ce n'est 6 mois en temps (pas un souci)
- on peut laisser tout un tas de comptes avoir acces aux résultats (lecture seule)
- thèmes un peu limités (juste quelques couleurs) mais rouge ok
- possibilité de récupérer emails, nombre de participants etc
  - possibilité de limiter le nombre de participants au formulaire, mais pas le nombre d'invités... donc il faudra manuellement fermer les inscriptions si nécessaire...

Est-ce que la techno sera pérenne? pas clair...
- https://framacolibri.org/t/migration-de-yakforms-vers-drupal-11/22662/8
- https://framacolibri.org/t/yakforms-plus-a-jour/25166
- https://forum.frama.space/t/bug-formulaire-impossible-de-copier-acceder-au-reponses/1258/3

## test intégration embedded

formulaire dessous : 

<iframe src="https://framaforms.org/titre-test-integration-1750409054" width="100%" height="800" border="0"></iframe>

formulaire dessus :
