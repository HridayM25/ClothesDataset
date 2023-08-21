# ClothesDataset
This dataset contains 11,070 images and their corresponding labels manually annotated by me. 
I have used makesense.ai to annotate these images, and have ordered them in 27 classes corresponding to the clothes. I have applied 10 augmentations to the images.

There will be an images and labels folder inside the branch. Inside each there will be train and val. You may change the number of datapoints (images) in the folders, but make sure to do so for both the images and labels.
In accordance to conventions, each image will have a label with the same name in the folder order mentioned. I have also provided the corresponding .yaml file that can be fit into YOLOv5 or YOLOv7 model.

The novelty here is to include "Indian" clothes that are worn by the people, in addition to the already widespread availability of the conventional clothes. I have included Kurtis, Kurtas, Nehru Jackets, Lehengas, etc in the process of annotations. 

Here is the exhaustive list of classes used : 


  0: tshirt
  
  1: shortsleeveshirt
  
  2: longsleeveshirt
  
  3: blazer
  
  4: lehengas
  
  5: jeans
  
  6: trousers
  
  7: shorts
  
  8: capris
  
  9: sarees
  
  10: kurtis
  
  11: kurtas
  
  12: skirts
  
  13: tunic
  
  14: leggings
  
  15: croptop
  
  16: salwaar
  
  17: vests
  
  18: hoodies
  
  19: joggers
  
  20: nehrujackets
  
  21: jumpsuit
  
  22: playsuit
  
  23: dresses
  
  24: shrugs
  
  25: jacket
  
  26: top
