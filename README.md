## Table des matières
- [Introduction](#Introduction)
- [rubisenNotebooks](#rubisenNotebooks)
- [rubisenMappy](#rubisenMappy)
- [rubisenSandbox](#rubisenSandbox)
- [rubisenPOC](#rubisenPOC)
- [Authors](#Authors)


## Introduction

Le but de ce projet est d'explorer les possibilités que nous offre le Rubik's cube connecté [Giiker](http://giiker.cn/). Nous nous sommes principalement penchés sur la reconnaissance comportementale. Vous trouverez dans les parties suivantes nos différents travaux.

## rubisenNotebooks

*[https://github.com/olivbau/rubisen/tree/master/rubisenNotebooks](https://github.com/olivbau/rubisen/tree/master/rubisenNotebooks)*<br>
La partie rubisenNotebooks contient des notebooks jupyter montrant comment nous avons mis en place une reconnaissance comportementale avec un Rubik's Cube. Nous pouvons alors reconnaître un utilisateur d'un autre à sa facon d'utiliser un Rubik's cube. Pour plus de détails techniques, rendez-vous dans le github correspondant.

## rubisenMappy

*[https://github.com/JulesMicho/rubisenMappy](https://github.com/JulesMicho/rubisenMappy)*<br>
La partie rubisenMappy est un utilitaire python permettant de mapper des touches de clavier à un mouvement du cube Giiker. Il permet aussi d'utiliser le cube pour interagir avec tous types de progammes, pour jouer, faire de la musique, bouger la souris, etc. Pour plus de détails techniques, rendez-vous dans le github du projet.

## rubisenSandbox

*[https://github.com/olivbau/rubisenSandbox](https://github.com/olivbau/rubisenSandbox)*<br>
La partie rubisenSandbox est un site web qui nous a permis de faire tous types d'expérimentation avec le cube, notamment pour la connectivité. Ce site est disponible [ici](https://olivbau.github.io/rubisenSandbox/#/)

## rubisenPOC

*[https://github.com/olivbau/rubisenPOC-API](https://github.com/olivbau/rubisenPOC-API)*<br>
*[https://github.com/olivbau/rubisenPOC-Front](https://github.com/olivbau/rubisenPOC-Front)*<br>
*[Vidéo de présentation](https://youtu.be/8QRXt5uRwvI)*<br>
[![POC rubisen](https://img.youtube.com/vi/8QRXt5uRwvI/0.jpg)](https://youtu.be/8QRXt5uRwvI)<br>
La partie rubisenPOC est un site web composé d'une API et d'une partie front. Ce site web permet à un utilisateur de se créer un compte avec pour mot de passe une séquence qu'il composera avec le cube Giiker. L'authentification d'un utilisateur, en plus de vérifier la séquence (mot de passe) choisie par l'utilisateur, vérifie que l'éxécution de la séquence correspond à celle de l'utilisateur (grâce à un entraînement réalisé par l'utilisateur à l'inscription). Pour plus de détails techniques, rendez-vous dans les github respectifs.

## Authors

* Olivier Baurain
* Romain Ceccotti
* Jules Michaud
* Baptiste Millot
* Hao Zhu
