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

* Asie mineure
* Héraclite, Anaxagore, …

* Englobe l’école milésienne

#### École Milésienne
### École Pythagoricienne
### Atomistes
### Sophistes


## Les écoles post-socratiques
### Les Cyniques
![Diogène](https://upload.wikimedia.org/wikipedia/commons/b/b1/Jean-L%C3%A9on_G%C3%A9r%C3%B4me_-_Diogenes_-_Walters_37131.jpg)
Une des Ecoles fondée par un disciple de socrate est l'école des Cyniques. 
En effet, Antisthène est considéré comme le fondateur de l'école Cynique. Il suivit d'abord les leçons de Gorgias, et enseigna même comme sophiste. Avant de suivre celles de Socrate jusqu'a la mort de ce dernier. Après le tragique évènement, il s'installe dans un gymnase, le Cynosarge (d'où le nom "Cyniques", qui provient du grec ancien kuon, chien). C'est la qu'il rencontre Diogène, la figure de proue du Cynisme, que rien ne déstiné à la vie qu'il allait mener. Il lui enseigne une philosophie défénie par l'éthique, la morale et la vertue, une philosophie pratique, où l'on gagne la vertue par une vie simple, morale ascétique, où l'on fait fi des conventions sociales. 
... Tensions avec socrate.

En effet, diogène était le fils d'un banquier, et reçus donc une éducation soignée. Mais lui et son père furent banis d'Athène. C'est là que début sa vocation de philosophe cynique. C'est suite à cette évènement qu'il réussite à convaincre Antishène lui enseigner sa philosophie.
Vie de Diogène:

- "Je cherche un homme"; plume un poulé -> "Voici l'homme selon Platon"
- Enlèvement par des pirate
- rencontre avec Alexandre le grand
  
 Il s'attaque à de nombreuses valeurs du monde grec, il critique la notion du sacré, remet en cause la cité et ses lois. Il rejète la société. Pour lui, nous sommes corrompus par les artifices de la civilisation et esclaves de nos passions. Il condamne les convoitise, le culte, les passions. Il préfère l'action à l'argumentation. Il estime que le seul but de la philosophie est le bonheur. 

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
