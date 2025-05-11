# FCSC 2025 Intro to pwntools

Ceci n’est pas une vraie épreuve, mais plutôt un exemple d’utilisation de Python pour communiquer avec les services distants du FCSC, de Hackropole, et plus généralement de n’importe quelle service exposant un port TCP.

Si vous n’êtes pas familier avec ces concepts, commencez par installer le package Python pwntools sur votre machine. Celui-ci est extrêmement utile en CTF et permet de simplifier l’écriture de beaucoup de choses.

Dans notre cas, nous allons uniquement nous en servir pour communiquer avec un service exposant un port TCP.

Bien qu’il soit possible de résoudre cette épreuve à la main ou directement à partir du fichier ```template.py``` fourni, nous vous conseillons d’étudier les différentes fonctions utilisées dans ```template.py```. Celles-ci sont les principales fonctions utilisées dans ```pwntools``` pour communiquer avec les services distants, et elles pourront vous être utiles pour les épreuves du FCSC ou de Hackropole.


Fichiers :
- [template.py](template.py)



Auteur : [Cryptanalyse](https://twitter.com/Cryptanalyse)

Origine : [Intro to pwntools](https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-intro-to-pwntools/)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc intro-to-pwntools.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000

-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-misc-intro-to-pwntools.git

> cd fcsc2025-misc-intro-to-pwntools


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-intro-to-pwntools/