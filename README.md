## Formation: Développeur Web
Organisme de Formation: Openclassrooms

### Projet 5 : Débuggez et optimisez un site de photographe

### Consignes du projet:
  - Lien vers le site existant (et non débuggé, non optimisé): [Site_Photographe](https://nina-carducci.github.io/)
  - Lien vers le dépôt GitHub du code existant (non débuggé, non optimisé): [Dépôt_GitHub](https://github.com/nina-carducci/nina-carducci.github.io)
  - Faire une optimisation globale du site, tant sur les performances que sur le SEO
  - Mettre en place le référencement local en utilisant Schema.org
  - Ajouter les metas pour les réseaux sociaux
  - Faire les modifications liées à l’accessibilité du site
  - Produire un rapport d’optimisation présentant toutes vos actions et leur impact
  - Corriger les bugs existants (navigation dans la modale de la galerie photos, bouton filtre actif pas mis en valeur)

**Projet validé**
Score Lighthouse/GTMetrix avant débuggage/optimisation:
![image](https://github.com/Arnaud-Goguelin/OC_Projet5_Debug_Optimisation_Portfolio_Photographe/assets/124574198/efe72a48-0c74-4c78-a12f-67e01608fd68)
![image](https://github.com/Arnaud-Goguelin/OC_Projet5_Debug_Optimisation_Portfolio_Photographe/assets/124574198/04383aa5-2046-40cf-b47c-6a550955fa00)

Score Lighthouse/GTMetrix après débuggage/optimisation:
![image](https://github.com/Arnaud-Goguelin/OC_Projet5_Debug_Optimisation_Portfolio_Photographe/assets/124574198/f597a049-3608-4915-9af5-5c83dc83371b)
![image](https://github.com/Arnaud-Goguelin/OC_Projet5_Debug_Optimisation_Portfolio_Photographe/assets/124574198/3138ff9d-096c-4216-9862-c6490dcc6fdd)

#### Pistes d'amélioration présentées lors de la soutenance
  - Mettre en cache les ressources statiques,
  - Réécrire le code JS pour le simplifier
  - Réécrire le code CSS pour le simplifier OU utiliser PurgeCSS
    **=> cela permettrait un gain de performance nous autorisant des images de meilleures qualités, critère essentiel pour le site d'une photographe!**
  - Revoir le feedback visuel du formulaire (accessibilité) 

### Commentaires généraux:
  - Livrables complets et soignés
  - Remarques : bonne élocution, prise en compte du rôle, du client et des détails demandés
  - Tour des points attendus bien ciblés. Rebond et retour suite à l'échange avec le rôle Nina au top
**Pour ce projet, j'ai pu avoir accès à mes résultats pour chaque critère d'évaluation:**
*Les 4 optimisations obligatoires suivantes ont été réalisées :*

  - les images sont optimisées (aucune image supérieure à 1 Mo) ; ok
  - une balise meta description est présente avec 50 à 160 caractères ;
  - au moins un Rich Snippet (microdonnées) a été ajouté pour la localisation du photographe ; ok
  - les meta pour les réseaux sociaux, comme les Twitter Cards et données OpenGraph, ont été ajoutées. ok

*Au moins 4 des optimisations optionnelles suivantes ont été réalisées : ok*
  - suppression du jQuery et remplacement de la galerie par une galerie en JS ; TODO
  - minification du code JS et CSS ; ok
  - suppression du code inutile dans les fichiers joints (Bootstrap, etc.) ; TODO
  - la balise title a été ajoutée avec un contenu pertinent ; ok
  - les attributs “alt” des images ont été ajoutés ; ok
  - la structure des titres a été corrigée, et les titres sont exposés dans le bon ordre ; ok
  - des mots clés en rapport avec l’activité du client et/ou sa localisation ont été ajoutés dans le contenu du site. ok
  - L’étudiant est capable d’expliquer ses choix d'optimisations, et comment il les a effectuées. ok

*Le rapport d’intervention peut être validé si :*
  - Il contient une explication des modifications qui ont été effectuées sur chacun des points suivants :
  - l’optimisation des images ; ok
  - l’optimisation du code (minification, retrait de jQuery ou autre) ;ok
  - l’optimisation de l’accessibilité ;ok
  - l’ajout de Rich Snippets ;ok
  - l’ajout de la meta description ;ok
  - les autres modifications que l’étudiant a réalisées.ok

*Le document PDF de l’audit Lighthouse du rapport d'intervention peut être validé si :*
  - Les 4 indicateurs (performance, SEO, accessibilité et “best practices”) sont à 90 % ou plus. ok
  - La taille totale de la page est inférieure à 5 Mo (cf. section “Diagnostic des performances”). ok
  - La capture d’écran de l’audit Rich Snippet du rapport d'intervention peut être validée si :
  - Elle montre au moins un snippet valide : il contient l’adresse de la photographe, et ne présente aucune erreur. ok
  - La capture d’écran du plugin Wave du rapport d'intervention peut être validée si :
  - L’analyse ne montre aucune erreur. ok
  - Débugger un site web grâce aux Chrome DevTools

*Le code du site peut être validé si :*
  - Lors du clic sur une catégorie, la catégorie a bien la couleur de fond dorée, et les images affichées sont bien celles de la catégorie. ok
  - Lorsque l’on clique sur les flèches de la modale, on peut naviguer sur l’image précédente et l’image suivante. ok
  - Rédiger un cahier de recette pour tester un site
  - La section "Cahier de recette" du rapport d’intervention peut être validé si : ok
  - La section “Cahier de recette” est remplie avec des cas d’usage pertinents, avec au moins :
  - un cas d’usage pour tester le clic sur les tags ;
  - un cas d’usage pour tester la navigation dans la galerie.
  - Chaque ligne du cahier de recette est remplie avec les informations précisées sur le modèle : action, résultat initial, résultat après résolution, statut (les commentaires et remarques sont optionnels).
    
### Compétences évaluées:
  - Optimiser les performances d’un site web : **Validé**
  - Débugger un site web grâce aux Chrome DevTools : **Validé**
  - Rédiger un cahier de recette pour tester un site : **Validé**
