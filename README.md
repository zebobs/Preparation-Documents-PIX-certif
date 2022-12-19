# Exploitation automatique de pix-certif pour générer des documents

## Objectif
- Fournir les documents pour les surveillants des certifications Pix :
  - les indispensables : numéro de session, code d'accès, mot de passe surveillant, code pour les non certifiables
  - la liste d'émargements imprimable sans manipulation
  - les instructions de surveillance

- Fournir ces documents sous forme d'un pochette pouvant contenir les instructions à distribuer aux élèves et un PV vierge.

## Prérequis
- Nécessite d'avoir le fichier exploitation_auto_pix_orga.py du dépôt https://github.com/zebobs/Resultats-Campagne-PIX-orga dans le même répertoire.
- Le fichier consignessurveillants.html contient les consignes pour les surveillants. C'est un fichier contenant des bouts de html basique. Il est peut être modifié. Il doit être présent dans le même répertoire

## Fonctionnement
- Lancer le programme python exploitation_auto_pix_certif.py puis renseigner vos identifiants pix-certif qui sont les mêmes que ceux de pix-orga.
- Répondre aux quelques questions : 
  - Le code pour les non certifiables
  - Création d'une page de garde par session. Si la page de garde n'est pas créée, les codes sont fournis sur la liste d'émargements.
- La liste d'émargement obtenue peut être imprimée en A3 ou en A4. En A3 avec page de garde, on obtient une pochette pouvant contenir le PV d'inciden et le document à distribuer aux élèves.


## Tests
- Le programme est utilisé pour une structure d'une centaine de classes.
- Il a été testé sans problèmes notables à l'aide de l'ide thonny : https://thonny.org/ (Il suffit d'installer thonny qui contient python, puis installer les bibliothèques en passant par "Tools" puis "Manage plugs-in...")

## Astuces
- Les consignes se modifient à l'aide d'un éditeur de texte.
- Si vous préférez utilisez du A4, pensez à diminuer le texte des consignes.

## Bilbiothèques python
Les bibliothèques requises sont les mêmes que celle de exploitation_auto_pix_orga.py

## Licence
Ce projet est sous licence GPL v3

## Exemples
4 pochettes obtenues en imprimant en A3 Recto-Verso.
          
![Pochettes A3 page de garde](Pochette%20A3%20page%20de%20garde.jpg)
