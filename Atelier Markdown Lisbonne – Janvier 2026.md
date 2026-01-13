# Atelier Markdown Lisbonne -- Janvier 2026

Dans codiMD, on écrit en Markdown. Le markdown est un langage de balisage. Comme le html ou LaTeX (dont nous parlerons tout à l'heure). On utilise donc des balises pour mettre en forme le texte, ajouter des images, créer des tableaux, graphiques ou autre.

## Quelques exemples basiques

On peut écrire du texte simplement. On peut aussi le mettre en forme.

Par exemple, du texte en italique. Un autre en gras et si je veux le texte en gras ET en italique il sera donc comme cela.

On peut ajouter des emojis. Quand on fait :, une liste nous apparaît.
Les 3 premiers sont 

On peut ajouter du code. Par exemple si je veux montrer un programme python.


def sommeEntiers(n):
    for i in range(n+1):
        resultat += i
return resultat


On peut faire différents "niveaux" de titre en utilisant plus ou moins de #

Titre de niveau 1
Niveau 2
Niveau 3
Niveau 4

## Listes

On peut construire une liste non ordonnée : 
Premier élément
Deuxième
Troisième

On peut faire des listes dans des listes : 
Premier élément : 
Sous élément :
Sous sous élément
2
Deuxième

Ordonnée : En plaçant n'importe quel nombre pour commencer.

Premier
Deuxième
Troisième


## Lien, images et vidéos

Il est possible de créer des liens vers une page. Comme wikipedia par exemple : lien vers wikipedia(https://www.wikipedia.fr)

Il est possible de faire un lien vers une image : schéma de la photosynthèse(https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Photosynth%C3%A8se_fr.svg/500px-Photosynth%C3%A8se_fr.svg.png?20160602100313)

Ou l'afficher directement en ajoutant un point d'exclamation devant :
schéma de la photosynthèse(https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Photosynth%C3%A8se_fr.svg/500px-Photosynth%C3%A8se_fr.svg.png?20160602100313)

On peut insérer une vidéo youtube simplement : 



## mermaid

Mermaid est un outil permettant de faire plein de choses : 

Des diagrammes : 


sequenceDiagram
    Alice->>Bob: Bonjour. Ça va ?
    Bob-->>Alice: Très bien !
    Alice-)Bob: À plus !


Des camemberts : 


pie title Élements dans l'univers
    "Hydrogène" : 73.9
    "Hélium" : 24
    "Reste" : 2.1



pie title Hommes/Femmes au stage
    "Hommes" : 12
    "Femmes" : 4


Des cartes mentales : 



mindmap
  root((Transformation))
    Physique
      Changement d'état
      Même espèce chimique
    Chimique
      Modification des espèces
      Exemples
        Combustion
        Oxydation
        Réaction acide-base
      Lois
        Conservation de la masse
        Conservation des atomes
    Nucléaire
      Modification des éléments chimiques
      Lois
        Conservation du nombre de nucléons
        Conservation de la charge


Ou

mindmap
  root((Cellule))
    Types
      Cellule eucaryote
        Animale
        Végétale
      Cellule procaryote
        Bactérie
    Membrane plasmique
      Bicouche lipidique
      Protéines
      Rôle
        Protection
        Échanges
    Cytoplasme
      Cytosol
      Réactions chimiques
    Noyau
      ADN
      Chromosomes
      Nucléole
      Rôle
        Information génétique
        Commande cellulaire
    Organites
      Mitochondries
        Respiration cellulaire
        Production d'ATP
      Réticulum endoplasmique
        Rugueux
          Synthèse des protéines
        Lisse
          Synthèse des lipides
      Appareil de Golgi
        Modification
        Transport des protéines
      Lysosomes
        Digestion cellulaire
      Ribosomes
        Synthèse des protéines
      Vacuole
        Réserve
        Cellule végétale
      Chloroplastes
        Photosynthèse
        Cellule végétale
    Cycle cellulaire
      Interphase
      Mitose
    Fonctions
      Se nourrir
      Se reproduire
      Communiquer






Des frises chronologiques : 


timeline
    title Grandes découvertes en chimie jusqu'au XVIIIème

    section Antiquité
        Aristote : Théorie des quatre éléments (IVe siècle av. J.-C.)

    section XVIIe siècle
        Robert Boyle (1661) : Définition moderne de l'élément chimique 

    section XVIIIe siècle
        Priestley : Découverte du dioxygène (1774)
        Lavoisier : Respiration végétale (1780) : Loi de conservation de la masse (1789)


## Mettre en évidence des paragraphes






## Tableaux


 
## Formules mathématiques : 

