# Les écoles de philosophie antique
*Date: 6 novembre 2024*
![Raphaël, L'École d'Athènes, 1508-1512, Musées du Vatican](https://upload.wikimedia.org/wikipedia/commons/1/18/The_School_of_Athens.jpg)

## Plan
0. Le début de la philosophie antique
1. Ecole milésiene - Thalès
2. Ecole Pythagoricenne
3. Ecole Eléate
3. Les autres présocratiques: les atomistes (Démocrite), Empédocle, Anaxagore, Héraclite ...

----- Rupture -------

4. Les Sophistes: Protagoras, Gorgias, Prodicos, Antiphon, Calliclès ... 
5. Le triplet gagnant: Socrate, Platon et Aristote
6. Ecole cynique: Diogène et Cratès  
7. Ecole épicurienne
8. Ecoles stoïciennes: le Portique, anetios, Poseïdonios, Epictète, Sénèque, Marc-Aurèle 
9. La fin de la philosophie antique

Tout cela peut être résumé:

1. Intro, début de la philosophie grecque antique
2. Les écoles présocratiques
3. l'école Socratique
4. Les écoles post-socratiques
5. Conclusion, fin de la philosophie grecque antique
6. Ouverture autres philosophies antiques

## Chronologie

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2017</h2>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2016</h2>
      <p>Lorem ipsum..</p>
    </div>
  </div>
   <div class="container left">
    <div class="content">
      <h2>2017</h2>
      <p>Lorem ipsum..</p>
    </div>
  </div>
</div> 

## Intro, début de la philosophie grecque antique
## Les écoles présocratiques
Du VIIè siècle au IVè siècle avant J.C.

### École Ionienne

* Asie mineure (région d’Ionie, capitale Milet)
* Englobe l’école milésienne

#### École Milésienne
* Thalès (Θαλῆς), né entre -625 et -620 et mort entre -548 et -545
* Anaximandre, né vers -610 et mort vers -546

Surnommés «&nbsp;les physiciens&nbsp;», étudient la nature (φύσισ&nbsp;: la
nature). Cherchent l’origine de toutes les choses et de tous les phénomènes.
Pour Thalès, il s’agit de l’eau. Pour Anaximandre, il s’agit de l’ἄπειρον
(infini, indéterminé, illimité, indéfini).

### École Pythagoricienne
### Atomistes
### Sophistes


## Les écoles post-socratiques

## Conclusion, fin de la philosophie grecque antique

## Sources:
- [Philo-lettres.fr, Michèle Tillard](https://philo-lettres.fr/grec-ancien/la-philosophie-grecque/) 



<style>
	* {
  box-sizing: border-box;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
  background-color: #474e5d;
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: white;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}
/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}
/* The actual content */
.content {
  padding: 5px 10px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}
	
	/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
/* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

/* Full-width containers */
  .container {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

/* Make sure that all arrows are pointing leftwards */
  .container::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

/* Make sure all circles are at the same spot */
  .left::after, .right::after {
    left: 15px;
  }

/* Make all right containers behave like the left ones */
  .right {
    left: 0%;
  }
}
</style>
