# choco-latin.github.io
Test for github pages
[live here](choco-latin.github.io) 

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
- pour le formulaire de contact on peut simplement passer par des services comme https://web3forms.com/ qui renvoient le texte par mail. cf. https://www.reddit.com/r/webdev/comments/1325q3s/anyone_used_formsubmitco_before/ bon au fond c'est pareil que tout ce qui précède
- https://www.staticforms.xyz/pricing 500 emails par mois gratuit, sympa?

## framaforms

- c'est gratuit et libre
- pas trop de limites techniques si ce n'est 6 mois en temps (pas un souci)
- on peut laisser tout un tas de comptes avoir acces aux résultats (lecture seule)
- thèmes un peu limités (juste quelques couleurs) mais rouge ok
- possibilité de récupérer emails, nombre de participants etc
  - possibilité de limiter le nombre de participants au formulaire, mais pas le nombre d'invités... donc il faudra manuellement fermer les inscriptions si nécessaire...
- l'intégration marche très bien, notamment en mobile
- est-ce que une fois le formulaire rempli on peut envoyer un mail de confirmation? générer un pdf?
  - a priori oui on peut envoyer un mail après réservation. Il semble également possible de demander une confirmation par email
  - bon c'est pas hyper bien foutu... en gros toute personne qui remplit le formulaire est enregistrée. Dans un deuxième temps ils recoivent un mail demandant de confirmer, ce qui les range dans la catégorie "confirmé" que l'on peut filtrer mais pas sur les données d'analyse...
  - ah mais il faut définir un temps pour que les gens confirment (par default infini) et APRES c'est supprimé..! 
  - non ce n'est pas supprimé. n'a pas l'air très au point ... https://framacolibri.org/t/systeme-de-validation-non-fonctionnel/19966
  - j'ai ouvert une issue : https://framacolibri.org/t/soucis-avec-le-systeme-de-validation/26374
  - en tout cas on peut bien recevoir un mail de confirmation après avoir cliqué sur le lien

Est-ce que la techno sera pérenne? pas clair...
- https://framacolibri.org/t/migration-de-yakforms-vers-drupal-11/22662/8
- https://framacolibri.org/t/yakforms-plus-a-jour/25166
- https://forum.frama.space/t/bug-formulaire-impossible-de-copier-acceder-au-reponses/1258/3

## test intégration embedded

formulaire dessous : 

<iframe src="https://framaforms.org/titre-test-integration-1750409054" width="100%" height="800" border="0"></iframe>

formulaire dessus :

## netifly

bon apparemment c'est comme github pages mais avec + de services... a voir..

- creer un formulaire de contact : https://www.hywel.me/sites/2021/11/15/website-page-with-contact-form-using-html-github-and-netlify.html
- migrer depuis github : https://www.gorillasun.de/blog/migrating-from-github-pages-to-netlify/
