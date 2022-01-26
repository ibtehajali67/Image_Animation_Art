# painting-animation
Animating paintings using CNN:

## 1. Motion prediction

Recurrently computed on each frame to predict the next frame.

## 2. Color transfer

Applied independantly to each frame.
## Download model file:
- The model file is located at
  http://www.cgg.cs.tsukuba.ac.jp/~endo/projects/AnimatingLandscape/models.zip
## To try on any .png image:
- put your image in the inputs directory
- go to your terminal and type: 

```
python test.py --gpu 0 -i ./inputs/your_image.png -o ./outputs  
```
- the videos (motion loop, color loop, final video) will be generated in the outputs directory
## RUN 
- Run command in this file 'Image_animation.ipynb' which is made custom on image.

