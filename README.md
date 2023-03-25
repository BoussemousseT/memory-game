# Jeu de mémoire

## Introduction

Ce jeu a été développé dans le cadre du projet de fin du cours *Javascript*

## Veuillez cliquer sur l'image pour accéder à la vidéo du site

[![Watch the video](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhg8-nwnrxFt-Uq8kckBGmo-qubjqBEb3dVgr_OrSR3G96Gil7glL1EKm1YWYQxOiTJ3_zX0ocOq1hOlpQ-nQiGEPxhFODyk7eQNmt7FNgiuRkNom5H11Cs7G5p6PhxVbBbRr-DjVPdZxJINfYoeJv8OG6J-YB8DCDbUGJGRZA0zMxr-XvbR5E00WJ6/s1600/memoire.png)](https://youtu.be/BJTtNRVanZk)


## Règles du jeu
	- Le jeu consiste à trouver 8 paires d'images en un temps record.
	- Les images cachées par un '?' sont celles dont il faut trouver les paires. 
	- Elles sont placées aléatoirement dans la grille.
	- Une partie débute lorsque l'utilisateur clique sur le bouton "Nouvelle Partie" et se prolonge tant et aussi longtemps que toutes les images n'auront pas été trouvées ou que l'utilisateur n'aura pas cliqué sur le bouton "arrêter la partie"
	- L'utilisateur peut jouer plusieurs parties jusqu'à ce qu'il décide de quitter.

## À chaque nouvelle partie:
    - On réinitialise la position des images aléatoirement.
    - Toutes les images cachées sont affichées un laps de temps puis recouvertes;
    - Le nombre de paires trouvées est remis à zéro ainsi que le temps écoulé.
    - Le bouton affichant "Arrêter la partie" affiche maintenant le message initial "Nouvelle partie"

## À la fin de chaque partie:
    - Un message de félicitations est affiché donnant le temps écoulé.
    - Le meilleur temps est vérifié.
    - Un message est affiché si le meilleur temps est battu.

## Durant la partie:
    - L'utilisateur clique sur deux images;
    - Les images s'affichent un laps de temps;
    - Si les images sont différentes, elles sont cachées de nouveau, sinon elles restent affichées et on incrémente le nombre de paires trouvées.
    - Durant ce temps, le nombre de secondes écoulées depuis le début de la partie courante s'accumule;
    - Le bouton affichant initialement "Nouvelle partie" doit afficher "Arrêter la partie"
    - La fin d'une partie est atteinte lorsque toutes les paires sont découvertes.

## Crédits

Dernière mise à jour le 24/03/2023

------------------

[@Taoufik Boussemousse]
[@CongTai Ho]
