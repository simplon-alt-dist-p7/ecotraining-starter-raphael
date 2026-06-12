# Backlog heavy-showcase

## Contexte du projet

Le projet represente un site editorial dense, riche en medias et en scripts non prioritaires.

## Format attendu

Completer au minimum 3 user stories.
Remplacer chaque champ entre crochets par votre contenu.

## Modèle User story 

- Contexte: En tant que [role], je veux [action], afin de [valeur attendue].
- Objectif: [objectif qualitatif ou chiffre]
- Bonne pratique d eco-conception ciblee: [bonne pratique]
- KPI associe: [indicateur de suivi]
- Repo ou ecran concerne: [page, composant, parcours ou endpoint]
- Critere de reussite: [resultat observable ou mesurable]
- Niveau de priorite: [haute, moyenne ou basse]

## User story 1

- Contexte: En tant que utilisateur régulier, je veux que la vidéo en page d'accueil ne se déclanche pas automatiquement, afin de garantir le chargement rapide de la page si ma connexion est lente.
- Objectif: retirer la lecture automatique de la vidéo, voir même l'enlever
- Bonne pratique d eco-conception ciblee: choix le plus sobres entre texte, image, vidéo (RGESN 4.7) et vidéo dont lecture automatique est désactivé (RGESN 4.1)
- KPI associe: Performance de la page 58, Largest Contentful Pain 10,2s
- Repo ou ecran concerne: page d'accueil
- Critere de reussite: augmentation de la performance de la page d'accueil
- Niveau de priorite: haute

## User story 2

- Contexte: En tant que nouvel utilisateur, je veux que la mise en page du site soit mieux structurée, afin de avoir une meilleure expérience de navigation.
- Objectif: optimiser la structure et mise en page du site
- Bonne pratique d eco-conception ciblee: réduire le poids de la page et du CSS
- KPI associe: taille de la page et du DOM sur GreenIT
- Repo ou ecran concerne: accueil et autres pages
- Critere de reussite: mise en page plus sobre, moins d'espace vide, taille de la page et du DOM plus optimisé
- Niveau de priorite: moyenne

## User story 3

- Contexte: En tant que développeur de l'application, je veux réduire la taille du script, afin de alléger le poids des scripts.
- Objectif: retirer les scripts inutiles et optimiser ceux en place
- Bonne pratique d eco-conception ciblee: éviter le chargement de ressources et contenus inutilisés (RGES 6.5)
- KPI associe: Lighthouse, résuire le JS inutilisé et minifier le JS
- Repo ou ecran concerne: accueil
- Critere de reussite: résultat sur Lighthouse 
- Niveau de priorite: moyenne

## Notes

- Vous pouvez ajouter d autres user stories si necessaire.
- Le niveau de detail attendu doit permettre une priorisation exploitable.
