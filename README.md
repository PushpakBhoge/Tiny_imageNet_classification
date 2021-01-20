# Tiny_imageNet_classification

classification of 64x64 images into 200 classes

**Get models [here](https://drive.google.com/drive/folders/1-3snEnRlV8wj3IHmVYsDFEv0DUil_Osp?usp=sharing)**

model naming format = Effnetnet_{image_width}_{initial_epoch}_{end_epoch}.h5
Model with largest "end_epoch" is the best one
put models into Projects/models/

Also you need to change initital directories in each jupyter noptebook to point to Project folder and Train test directory in tiny imagenet dataset
You don't need to download all models!

# Results 
**train_accuracy:**
* Top1 :- 59.89
* Top5 :- 84.12

**Validation  Accuracy:**
* Top1 :- 45.79 
* Top5 :- 72.39

**Model inference time**

for CPU - 37 images/second

for GPU - 1373 images/second
