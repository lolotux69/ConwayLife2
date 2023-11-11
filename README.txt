# ConwayLife

Code ayant servi à créer les animations de ma vidéo sur le jeu de la vie de Conway :

https://www.youtube.com/watch?v=S-W0NX97DB0

Science étonnante

NB : 
1) Editez le fichier 
GameOfLife_utils.py
Mettre le chemin de votre binaire ffmpeg

# Path of ffmpeg executable for animation
plt.rcParams['animation.ffmpeg_path'] = r'/usr/bin/ffmpeg'

2) Créez un répertoire output
mkdir output

Pour lancer : python GameOfLife.py

3) Visualisez la vidéo créée dans le dossier "output"
