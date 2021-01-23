![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```
 npm i -g vercel

4)vercel -v

5)vercel init -->choisir angular

6) vercel deploy angular

7) vercel ls angular ou vercel list angular

8) vercel logs https://angular-seven-swart.vercel.app/

9) vercel inspect https://angular-seven-swart.vercel.app/
Affiche les arborances des fichiers.

10) Les variables d'environnement sont accessibles à la fois pendant l'étape de construction et pendant l'exécution 
et peuvent être configurées individuellement pour les environnements de production, de prévisualisation et de développement.

Cela vous permet d'injecter des valeurs que vous ne souhaitez pas placer directement dans votre code source 
et de modifier son comportement en fonction de l'environnement dans lequel il s'exécute.

Pour déclarer une variable d'environnement pour votre déploiement, 
rendez-vous à la page Variables d'environnement de vos paramètres de projet.

11) vercel env add plain EnvPlain production

12) vercel env list

13) Les Secrets sont cryptées et fournissent un moyen sûr de stocker et de partager des informations sensibles entre les déploiements.

14)

15) vercel secrets add new_secret2 42

16) production, preview et developpement. Elles correspondent au différentes fases d'avancement dans le projet.

17)

18) 

19) pull request: ramener les fichier d'une branche annexe sur la branche principale. Faciliste le travail de groupe.
	l'environnement preview est triggered par vercel qui déploie automatiquement les modifications apportés.

20) On voit un déployment réalisé par vercel sur l'environnement de production.

21) Lors du merge sur la branche principale on a triggerred l'environnement de production donc branche main = production.
travailler avec plusieur branche permets de protéger la branches principale, de tester des choses sur les branches adjasantes 
de pouvoir plus facilement savoir d'où proviens un problème.Le pull resquest permet donc d'aider protogé la branche principale.

22) Permet de déployer des fonctions sans serveur(utilisation de cloud), écrits avec des langages backend qui acceptent une requête HTTP et fournissent une réponse.
 Cette utilisation permet d'implémenter des fonctions spécifiques sans serveur (comme gérer l'authentification d'utilisateurs, les formulaires, des requêtes BDD...)

23)



Doc vercel: https://vercel.com/docs/cli
	  : https://vercel.com/docs/environment-variables
