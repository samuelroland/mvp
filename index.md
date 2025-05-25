---
layout: default
---

<h1 class="!text-[28px] xs:!text-[35px] md:!text-[40px] sm:!bg-red-500 md:bg-blue-500">Vous enseignez l'informatique ou la programmation?</h1>

## Etes vous déjà retrouvé dans la situation suivante ?

Vous avez mis beaucoup d'effort dans les slides de votre cours, beaucoup de temps de préparation de laboratoires, vous donnez votre cours comme d'habitude.

![cours magistral avec une classe et peu d'interactions étudiants vers profs, seulement quelques étudiants qui captent le message, le reste est paumé ou n'ose pas poser de question](schemas/lecture.opti.svg)

> Des questions ⁉️ C'est clair ?

*... quelques hôchements de tête 🙂‍↕️, quelques visages faisant la moue 🫤, une partie n'écoute pas 🙉, quelques questions de temps en temps...*

### ... mais ne savez pas si le message passe vraiment ou comment mieux le transmettre ?
Vous avez peut-être remarqué que
- Seulement une faible portion des étudiants les plus passionnés ou les plus à l'aise posent des questions
- Une majorité décroche après 15minutes
- Une partie de la classe est paumé mais ne pose pas de question
- Même les étudiants convaincus d'avoir compris ont parfois mal compris ?
- Ce n'est que très tard à la correction des évaluations que vous vous rendez compte du problème

Au final, c'est le brouillard des deux cotés, les étudiants peinent à suivre une explication trop haut niveau et les enseignants ne savent pas si ce qu'ils disent atteint sa cible.

**... comment exclaircir ce brouillard dense ?**

### Et si vous faisiez **pratiquer vos étudiants en cours** pour **comprendre leurs lacunes** en récupérant leurs réponses, afin de *corriger immédiatement leur modèle mental* ?

C'est là qu'intervient notre solution <img src="imgs/delibay-logo.svg" id="delibaylogo" />



**Delibay permet à tous les étudiants d'être actif et engagé** dans leur apprentissage en classe. L'enseignant lance des exercices, les étudiants y répondent, Delibay syntéthise les réponses et vous permet d'adapter votre cours en temps réel et d'adresser les mauvaises conceptions. **Cette pratique régulière et ce feedback immédiat est la clé pour que vos étudiants apprennent profondemment et efficacement !**

![deliberate-flow](schemas/deliberate-flow.png)

> Donc c'est juste une énième plateforme de Quiz ?

Sur Delibay, l'expérience n'a rien à voir avec Socrative, Moodle ou d'autres solutions existantes. **Delibay a pour mission de rédéfinir l'expérience d'apprentissage à l'informatique.** Dans cette plateforme open-source vous trouverez des questions de concepts (réponses courtes ou longues), des choix multiples, avec une colorisation avancée du code.

<img src="imgs/short-question-nice-code.png" id="nicecode" />

<img src="imgs/mcq.png" id="nicecode" />

En plus, vous avez la possibilité de faire des exercices de code

> Comment ça ? Voir les réponses de *TOUS* les étudiants ? Mais ça fait beaucoup et on ne va pas faire ça par email si ?


Peut-être que ça ce stade, vous pensez

> J'ai envie de gérer mon contenu localement et ne pas dépendre d'une autre plateforme web !

Delibay a justement été conçu pour n'être qu'une plateforme de déploiement de vos exercices, vous gérez votre contenu localement dans Git via des fichiers textuels.


## Nos services

> Intéressant mais j'ai déjà un recueil d'exercices en PDF, j'ai la flemme de passer des heures à les migrer...

> J'aimerai bien mais je n'ai pas le temps de créer tous ces exercices !

> C'est difficile de créer des questions challengeantes pour les étudiants...

> En tant qu'expert, c'est difficile de se mettre dans la peau des étudiants et cerner leurs incompréhensions.

<div class="md:flex md:flex-wrap md:space-x-2 space-y-2 md:mx-3">

<div class="bloc flex-1 border border-blue-500 p-5 rounded-sm">
    <h3>Migration de votre cours</h3>
    <p>Nous nous chargeons de migrer tous vos exercices, à Delibay et d'ajuster la structure. Si nécessaire pour vos cours, nous ajouter le support de nouveaux langages de programmation ou types d'exercices.</p>
</div>

<div class="bloc flex-1 border border-blue-500 p-5 rounded-sm">
    <h3>Création d'exercices sur mesure</h3>
    <p>Nous nous chargeons de créer des exercices variés qui poussent les étudiants dans leur retranchements. Vous n'avez plus qu'à relire et choisir lesquels sont les plus pertinents à chaque session de cours.<br>
    Les propositions et vos retours se font dans des pull requests sur un repository Git public.
    </p>
</div>

<div class="bloc flex-1 border border-blue-500 p-5 rounded-sm">
    <h3>Amélioration continue de vos exercices</h3>
    <p>Nous nous chargeons d'analyser les statistiques des réponses et de lire les réponses textuels, pour améliorer continuellement la qualité de la pratique de vos étudiants.</p>
</div>

</div>

<h2 class="gradient">Prêt·e à retirer ce brouillard et passer à un cours orienté sur la pratique ?</h2>

Delibay est en cours de développement et conception, nous vous tiendrons au courant quand vous pourrez la tester.

<div class="flex justify-center" >
<form
  action="https://www.formbackend.com/f/15195317ca0eef63"
  method="POST"
  class="w-full md:mx-32 lg:mx-60"
>
  <label for="name" class="">Nom</label>
  <input class="border border-blue-500 rounded-sm" type="text" id="name" name="name" required> <br>
  <label for="email" class="">Email</label>
  <input class="border border-blue-500 rounded-sm" type="email" id="email" name="email" required> <br>
  <label for="email" class="">Remarque (optionnel)</label>
  <textarea class="border border-blue-500 rounded-sm" type="email" id="remark" name="remark" placeholder="Quels challenges avez-vous actuellement dans votre enseignement qui pourrait être résolu par Delibay ? Quels cours enseignez vous et dans quelle école ?" rows="5">
</textarea>
  <br>
  <button type="submit" class="border border-gray-300 px-2 rounded-sm">Submit</button>
</form>
</div>
<!-- todo  inclusif ? -->

