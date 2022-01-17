# Exploitation automatique de pix-certif pour générer des documents

## Objectif
- Fournir les documents pour les surveillants des certifications Pix :
  - les indispensables : numéro de session, code d'accès, code pour les non certifiables
  - la liste d'émargements imprimable sans manipulation
  - les instructions de surveillance

- Fournir ces documents sous forme d'un pochette pouvant contenir les instructions à distribuer aux élèves et un PV vierge.

## Prérequis
- Nécessite d'avoir le fichier exploitation_auto_pix_orga.py du dépôt https://github.com/zebobs/Resultats-Campagne-PIX-orga dans le même répertoire.
- Le fichier consignessurveillants.html contient les consignes pour les surveillants. C'est un fichier contenant des bouts de html basique. Il est peut être modifié. Il doit être présent dans le même répertoire

## Fonctionnement
- Lancer le programme python exploitation-auto-pix-orga.py puis renseigner vos identifiants pix-orga.
- Répondez aux quelques questions : 
  - Le code pour les non certifiables
  - Format (A4/A3). Préférez le format A3. Attention les consignes fournies sont longues et correspondent au format A3
  - Création d'une page de garde par session. Si la page de garde n'est pas créée, les codes sont fournis sur la liste d'amrgements.
  - Remarque : En tapant sur Entrée directement le format par défaut est A3 avec page de garde.

## Tests
- Le programme est utilisé pour une structure d'une centaine de classes.
- Il a été testé sans problèmes notables à l'aide de l'ide thonny : https://thonny.org/ (Il suffit d'installer thonny qui contient python, puis installer les bibliothèques en passant par "Tools" puis "Manage plugs-in...")

## Bilbiothèques python
Les bibliothèques requises sont les mêmes que celle de exploitation_auto_pix_orga.py

## Licence
Ce projet est sous licence GPL v3
