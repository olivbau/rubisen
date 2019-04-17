<h1 align="center"> Reconnaissance comportementale avec un Rubik's Cube <br></h1>
<div align="center">
  <h3>📦📦</h3>
    <p>
    	Projet de reconnaissance comportementale avec un Rubik's Cube<br>
        ISEN - Avril 2019
    </p>
</div>



## Table des matières
- [Introduction](#Introduction)
- [rubisenNotebooks](#rubisenNotebooks)
- [rubisenMappy](#rubisenMappy)
- [rubisenPOC](#rubisenPOC)
- [Authors](#Authors)


## Introduction

Le but de ce projet est déplorer les possibilitées que nous offre le Rubik's cube connecté [Giiker](http://giiker.cn/). Nous nous sommes principalement penché sur la reconnaissance comportementale. Vous trouverez dans les parties suivantes nos différents travaux.

## rubisenNotebooks

*[https://github.com/olivbau/rubisen/tree/master/rubisenNotebooks](https://github.com/olivbau/rubisen/tree/master/rubisenNotebooks)*<br>
La partie rubisenNotebooks contient des notebooks jupyter montrant comment nous avons mis en place une reconnaissance comportementale avec un Rubik's Cube. Nous pouvons alors reconnaitre un utilisateur d'un autre à sa facon d'utiliser un Rubik's cube. Pour plus de détails techniques rendez-vous dans le github correspondant.

## rubisenMappy

*[https://github.com/JulesMicho/rubisenMappy](https://github.com/JulesMicho/rubisenMappy)*<br>
La partie rubisenMappy est un utilitaire python permettant de mapper des touches de clavier à un mouvement du cube Giiker. Il permet aussi d'utiliser le cube pour iteragir avec tous types de progammes, pour jouer, faire de la musique, bouger la souris, etc. Pour plus de détails techniques rendez-vous dans le github du projet.

## rubisenPOC

*[https://github.com/olivbau/rubisenPOC-API](https://github.com/olivbau/rubisenPOC-API)*<br>
*[https://github.com/olivbau/rubisenPOC-Front](https://github.com/olivbau/rubisenPOC-Front)*<br>
La partie rubisenPOC est un site web composé d'une api et d'une partie front. Ce site web permet à un utilisateur de se créer un compte avec pour mot de passe une séquence qui composera avec le cube Giiker. L'authentification d'un utilisateur en plus de vérifier la séquence (mot de passe) choisit par l'utilisateur, vérifie que l'éxécution de la séquence correspond à celle de l'utilisateur (grâce à un entrainnement réalisé par l'utilisateur à l'inscription). Pour plus de détails techniques rendez-vous dans les github respectifs.

## Authors

* Olivier Baurain
* Romain Ceccoti
* Jules Micho
* Baptiste Millot
* Hao Zhu