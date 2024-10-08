---
title: Startup 01 # une majuscule et pas d'acronymes
mission: Accéder aux conseils de professionnels à proximité pour trouver un logement # infinitif, pas de point ; compléter la phrase « En investissant dans ce produit l'État cherche à… »
sponsors:
 - /organisations/dinum # Liste des administrations sponsors, les valeurs possibles sont définies dans /content/_organisations/
incubator: dinum # le nom du fichier de l'incubateur de la startup
phases: # les différentes étapes de la vie des startups - les phases possibles sont définies dans /content/_phases/
  - name: investigation
    start: 2020-03-16 # date au format ISO (AAAA-MM-DD)
events: # les évènements marquants de la startup - les noms possibles sont définies dans /content/_events/
  - name: committee
    date: 2020-03-16 # date au format ISO (AAAA-MM-DD)
    comment: Premier comité de financement # Informations complémentaires
link: https://mes-aides.gouv.fr
repository: https://github.com/betagouv/mes-aides-ui # ou page de description des dépôts s'il y en a plusieurs
stats: false # mettre à true pour renvoyer vers ta page de stats. Attention, elle doit se trouver sur [url du site]/stats !
stats_url: # optionnel, si stats est à true, alors tu peux indiquer vers quelle URL pointer vers tes stats.
contact: contact@mes-aides.gouv.fr # sera visible de tous
---

Incubée par [[incubator/dinum]].

technos (récupérées de github) : lister (peut etre ne garder que celles qui ont un pourcentage suffisant?)
- [[techno/TypeScript]]
- [[techno/Vue]]
- [[techno/JavaScript]]
- [[techno/CSS]]
- [[techno/HTML]]
- [[techno/Python]]
- [[techno/Other]]
- [[techno/Ansible]]
- [[techno/Docker]]
- [[techno/MongoDb]]

## Fiche produit

Texte libre au format [Markdown](http://ricostacruz.com/cheatsheets/markdown.html).


## Rappels

- [ ] Supprimer les commentaires dans le front-matter : supprimer les croisillons et le texte qui les suit dans la partie entre tirets
- [ ] Modifier le nom du fichier `nom-startup.md` dans le champ ci-dessus (attention à bien inclure l'extension `.md`)
- [ ] Assurez-vous que le fichier est bien dans le dossier `/content/_startups/`
- [ ] Screenshot : ajouter une image en 1280x720px dans /img/startups/$nom-startup.png (ou .jpg)
- [ ] Créer une nouvelle branche pour l'ajout de ce fichier, et la nommer du même nom que le fichier `nom-startup`.
- [ ] Ouvrir une pull request pour valider l'intégration.
- [ ] Effacer ce texte une fois que vous l'avez lu 😉
