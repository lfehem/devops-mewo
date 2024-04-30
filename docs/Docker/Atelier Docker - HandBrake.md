# Atelier Docker - HandBrake

## Quelle commande utiliseriez-vous pour télécharger l'image Docker de HandBrake?
docker run jlesage/handbrake

docker run -d --name=handbrake -p 5800:5800 -v C:\Users\HP\devops-mewo:/storage:ro -v C:\Users\HP\devops-mewo/HandBrake/watch:/watch:rw -v C:\Users\HP\devops-mewo/HandBrake/output:/output:rw jlesage/handbrake

## Comment lanceriez-vous un conteneur HandBrake pour traiter une vidéo située sur votre machine hôte?
docker run -d --name=handbrake -p 5800:5800  -v C:\Users\HP\devops-mewo/HandBrake/watch:/watch:rw
## Quelles commandes permettent d'inspecter les détails et les logs d'un conteneur actif?

## Comment arrêter, redémarrer, et finalement supprimer un conteneur et une image?

