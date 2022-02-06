<div id="top"></div>


<!-- PROJECT LOGO -->
<div align="center">
  <h2 align="center">TP3 : La corrélation croisée</h2>
</div>

![logo](https://user-images.githubusercontent.com/80456274/151718182-54d53cc9-69bb-4710-af0e-f2fda10c0743.jpg)

<br />
<div align="center">
  <h3 align="center">Mesure de similarité entre deux signaux</h3>
</div>


<!-- TABLE OF CONTENTS -->

  <summary>Table of Contents</summary>
  <ol>      
      <a href="#about-the-project">About The Project</a>         
      <li><a href="#Objectifs">Objectifs</a></li>
      <li><a href="#Mesure-de-similarité-entre-deux-signaux">Mesure de similarité entre deux signaux</a></li> 
      <li><a href="#Mesure-de-similarité-entre-deux-signaux-en-présence-du-bruit">Mesure de similarité entre deux signaux en présence du bruit</a></li> 
  </ol>

 

<!-- ABOUT THE PROJECT -->
# About The Project
This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

1. [**How to install Matlab**](https://csuf.screenstepslive.com/s/12867/m/48670/l/1263150-matlab-download-installation-for-windows-students)
2. **Clone the repo**
   ```sh
   git clone https://github.com/IlyasKadi/Rapport_TP3-Traitement-de-signal.git
   ```
 
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- Overview -->
# Objectifs

> • Comprendre la notion de la corrélation croisée et évaluer sa capacité dans la
> mesure de dépendance deux signaux.
> 
> • Evaluer l’efficacité de cette mesure en présence du bruit.
> 
> **Commentaires** : Il est à remarquer que ce TP traite en principe des signaux continus.
> Or, l'utilisation de Matlab suppose l'échantillonnage du signal. Il faudra donc être
> vigilant par rapport aux différences de traitement entre le temps continu et le temps
> discret.
> 
> **Tracé des figures** : toutes les figures devront être tracées avec les axes et les
> légendes des axes appropriés.
> 
> **Travail demandé** : un script Matlab commenté contenant le travail réalisé et des
> commentaires sur ce que vous avez compris et pas compris, ou sur ce qui vous a
> semblé intéressant ou pas, bref tout commentaire pertinent sur le TP.


<p align="right">(<a href="#top">back to top</a>)</p>



# Mesure-de-similarité-entre-deux-signaux
En traitement du signal, la corrélation croisée (aussi appelée covariance croisée) est
la mesure de la similitude entre deux signaux. Afin de mieux appréhender cette notion,
on procédera à l’estimation de la corrélation croisée entre un signal sonore
échantillonné et un fragment de ce signal, en utilisant les outils appropriés fournis par
MATLAB. Le signal sonore qui fera l’objet de cet exercice est celui d’un anneau
tournant sur une table.

1- Chargez dans l’espace de travail l’enregistrement correspondant en tapant la
commande load('Ring.mat').

2- Tracez ce signal en fonction du temps, puis écoutez-le.

3- En utilisant deux droites en pointillés rouges, repérez le morceau du signal entre
t=7s et t=8s (Commande : xline).

3- Récupérez ce morceau dans une variable nommée « Fragment », écoutez-le, puis
tracez-le en fonction du temps.

4- Calculez et tracez la corrélation croisée du signal complet et du fragment, puis
Interprétez le résultat obtenu (Commande : xcorr).

5- Déduisez la valeur du décalage pour lequel la corrélation entre les deux signaux est
maximal, puis utilisez ce décalage pour faire apparaitre le fragment dans le signal.


<p align="right">(<a href="#top">back to top</a>)</p>


# Mesure-de-similarité-entre-deux-signaux-en-présence-du-bruit
Dans cette partie, nous chercherons à évaluer le degré de dépendance de deux
signaux en présence du bruit, en utilisant toujours cette notion de corrélation croisée.

1- Ajoutez un bruit blanc gaussien au signal de départ et aussi au fragment, puis
tracez-les en fonction du temps.

2- Appliquez la fonction xcorr afin de calculer la corrélation croisée entre les deux
signaux bruités, puis évaluez la capacité de cette mesure de détecter le fragment dans
le signal en présence du bruit.

3- Retracez la partie du signal détecté. 



<p align="right">(<a href="#top">back to top</a>)</p>



 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Our Team     : [AIT EL KADI Ilyas](https://github.com/IlyasKadi) - [AZIZ Oussama](https://github.com/ATAMAN0)  
 
   Project Link : [Rapport_TP3 : Traitement-de-signal](https://github.com/IlyasKadi/Rapport_TP3-Traitement-de-signal)   
 
  > Encadré par  : [Pr. AMMOUR Alae](https://ma.linkedin.com/in/alae-ammour-583678b2)  
                                                                                             
<p align="right">(<a href="#top">back to top</a>)</p>
