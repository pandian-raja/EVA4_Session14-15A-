# EVA4_Session14-15A-

1. Create this dataset and share a link to GDrive (publicly available to anyone) in this readme file. 
  
2. Add your dataset statistics:

  2.1 fg
  
   I took 100 images of persons and fliped to get another 100 images. SO totally 200 images. All bg images arer in .png format
      
  2.2 bg 
  
   I took 100 images of rooms with table and chair. All bg images arer in .png format
 
 2.3 fg_bg
 
   fg_bg images set is created from 100 bg images and 200 fg images are placed 20 times randomly on bg images. Totally 400k images
  ```
  Mean: 0.5373, 0.4887, 0.4405
  Std: 0.1111, 0.1161, 0.1190
  ```
  2.4 masks
  
   The masks images are created while creating fg_bg. The fg images are placed on same position as fg_bg placed while creation.
   ```
  Mean: 0.0352, 0.0353, 0.0353
  Std: 0.0178, 0.0179, 0.0180
  ```
  2.5 depth
  
  The depth images are created using https://github.com/ialhashim/DenseDepth.git repo.
  ``` 
    Mean: 0.3627, 0.3627, 0.3627
    Std: 0.0827, 0.0827, 0.0827
  ```
    
  Total dataset size is 3.6 GB. All the images are in 224x224 size.
  
 3. Dataset
 
 ![dataset](https://github.com/pandian-raja/EVA4_Session14-15A-/blob/master/dataset.png)
 
 4. Creation of Dataset
    4.1 fg images is created with transparent by using https://www.remove.bg/ website.
    4.2 Masks are created when fg_bg is created. 
 
  
  
  
