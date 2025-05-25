---
layout: default
---

<h1 class="!text-[28px] xs:!text-[35px] md:!text-[40px] sm:!bg-red-500 md:bg-blue-500">Vous enseignez l'informatique ou la programmation?</h1>

## Vous êtes vous déjà retrouvé dans la situation suivante ?

Vous avez mis beaucoup d'effort dans les slides de votre cours, beaucoup de temps de préparation de laboratoires, vous tenter d'expliquer votre sujet tant bien que mal. Vous finissez un chapitre.

> Des questions ? ... C'est clair ⁉️

![cours magistral avec une classe et peu d'interactions étudiants vers profs, seulement quelques étudiants qui captent le message, le reste est paumé ou n'ose pas poser de question](schemas/lecture.opti.svg)


*... quelques hôchements de tête 🙂‍↕️, quelques visages faisant la moue 🫤, une partie n'écoute pas 🙉*

### ... et vous ne savez pas si le message passe vraiment ou comment mieux le transmettre !?

Vous avez peut-être remarqué que
- Vous avez de **la peine à capter l'attention** et maintenir une interaction avec vos classes
- Seulement **une faible portion des étudiants posent des questions**, souvent les plus passionnés ou les plus à l'aise
- Une majorité **décroche après 15-30 minutes**
- Une partie de la classe **est paumé mais ne pose pas de question**
- Même les étudiants convaincus d'avoir compris ont parfois mal compris ?
- Ce n'est que très tard à la correction des évaluations que vous vous rendez compte du problème

Les étudiants peinent à suivre une explication trop haut niveau et les enseignants n'arrivent pas à savoir précisement qui comprend vraiment ? **Comment peut-on exclaircir ce brouillard dense ?**

## Et si vous faisiez **pratiquer vos étudiants en cours** pour **comprendre leurs lacunes** en récupérant leurs réponses, afin de *corriger immédiatement leur modèle mental* ?

C'est là qu'intervient notre solution <img src="imgs/delibay-logo.svg" id="delibaylogo" />

**Delibay permet à tous les étudiants d'être actif et engagé** dans leur apprentissage en classe. Vous lancez des exercices, les étudiants y répondent, Delibay syntéthise les réponses et vous permet d'adapter votre cours en temps réel pour adresser les mauvaises conceptions. **Cette pratique régulière et ce feedback immédiat est la clé pour que vos étudiants apprennent profondemment et efficacement !**

![deliberate-flow](schemas/deliberate-flow.png)

> Donc c'est juste une énième plateforme de Quiz ?

Sur Delibay, l'expérience n'a rien à voir avec Socrative, Moodle ou d'autres solutions existantes. **Delibay a pour mission de rédéfinir l'expérience d'apprentissage à l'informatique.** Dans cette plateforme open-source vous trouverez des questions de concepts (réponses courtes ou longues), des vrai/faux et des choix multiples, avec une **colorisation avancée du code**.

<img src="imgs/short-question-nice-code.png" class="nicecode" />

<img src="imgs/mcq.png" class="nicecode" />

En plus, vous avez la possibilité de faire des exercices de code

> Comment ça ? Voir les réponses de *TOUS* les étudiants ? Mais ça fait beaucoup et on ne va pas faire ça par email si ?

Delibay permet de regrouper les réponses et facilement les afficher, voici un exemple avec une question à réponse courte.

<img alt="dashboard résumé des réponses en live" src="schemas/dashboard-short-answer.png" class="mockup" />

> Okay, mais j'ai envie de gérer mon contenu localement et ne pas dépendre d'une autre plateforme web !

Avec Delibay, vous gérez votre contenu localement dans Git via des fichiers textuels, Delibay déploie ensuite votre cours à partir de ce repository et se synchronise à chaque `git push`.

## Nos services

> Intéressant mais j'ai déjà un recueil d'exercices en PDF, j'ai la flemme de passer des heures à les migrer...

> J'aimerai bien mais je n'ai pas le temps de créer tous ces exercices !

> C'est difficile de créer des questions challengeantes pour les étudiants...

> En tant qu'expert, c'est difficile de se mettre dans la peau des étudiants et cerner leurs incompréhensions.

<div class="md:flex md:flex-wrap md:space-x-2 space-y-2 md:space-y-0">

<div class="bloc flex-1 border border-blue-500 p-5 rounded-sm">
    <h3>Migration de votre cours</h3>
    <p>Nous nous chargeons de migrer tous vos exercices à Delibay. Si nécessaire pour vos cours, nous ajouterons le support de nouveaux langages de programmation ou types d'exercices.</p>
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
  <button type="submit" class="gradient border-2 border-gray-300 px-2 rounded-sm">Submit</button>
</form>
</div>
<!-- todo  inclusif ? -->

