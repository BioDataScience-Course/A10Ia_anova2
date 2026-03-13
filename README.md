# Analyse de variance à deux facteurs

Avant d'aborder ce projet, assurez-vous d'avoir bien compris le contenu du module [10](https://wp.sciviews.org/sdd-umons/?iframe=wp.sciviews.org/sdd-umons-2025/variance2.html) jusqu'à la section 10.5 comprise du cours de SDD I et d'avoir effectué les tutoriels learnr de ce même module 10. Ce projet correspond template <https://github.com/BioDataScience-Course/A10Ia_anova2>. Il est distribué sous licence [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Objectifs

Ce projet est individuel et cadré. Il permet de démontrer que vous avez acquis les compétences suivantes :

-   être capable de réaliser et d'interpréter correctement une ANOVA à deux facteurs de type modèle complet croisé et modèle croisé sans interactions.

-   être capable de choisir entre un modèle complet croisé et un modèle croisé sans interactions.

-   être capable de réaliser et d'interpréter un modèle ANOVA en parcelles divisées (split-plot)

## Consignes

-   Complétez le document `penguins_notebook.qmd`. Ce bloc-notes s'intéresse à la différence de masse entre trois espèces de manchots, également en fonction de leur sexe.

-   Complétez le document `oats_notebook.qmd`. Votre étude concerne le rendement de cultures d'avoine en fonction de différentes conditions.

À la fin de votre travail, assurez-vous que les documents Quarto compilent sans erreur en fichiers HTML (bouton "Rendu"), sinon, corrigez les erreurs éventuelles avant soumission finale. Il n'est pas possible de donner des points pour un document qui ne compile pas, donc, vérifiez-le bien. Vous avez une batterie de tests à votre disposition pour des vérifications plus poussées de vos résultats (onglet "Construire"/"Build" -\> bouton "Construire tout"). Vérifiez également que votre dernier commit a bien été pushé sur GitHub avant la la date limite de soumission.

## Utilisation de l’IA

Dans le cadre de votre travail, vous pouvez utiliser l’intelligence artificielle. Il est toutefois impératif de préciser, dans la section « Matériel et méthodes » du projet, que l’IA a été utilisée, en indiquant le contexte et la manière dont elle a été employée. Voici un exemple de formulation :

```
La relecture (orthographe et syntaxe) a été réalisée à l’aide de Microsoft Copilot (basé sur GPT-5), consulté le 12 janvier 2026.
```
Attention, vous devez néanmoins employer le dialecte SciViews-R afin de garantir votre compréhension du cours de Science des données biologiques 2 lors de la production de code R dans votre projet.

Un chatbot SciViews est également disponible dans RStudio (Saturn Cloud), via l’addin Help. Il répond aux questions relatives au langage R, aux statistiques et à la science des données.
