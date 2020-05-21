# face_mask_detection
A model based on computer vision, to help you identify whether the subject is wearing a face mask or not.

# The dataset
If you cant get a data set on your own, there is nothing to worry about. You can create your own data set by running the file named as "capture_images.py". This will help you create your own dataset.
After this, place the images in the specific directory structure as : "dataset/with_mask" and "dataset/without_mask".
There is no need of worry about labellin of the data, it will be taken care by the ImageGenerator.

# Running and saving the model
After completion of the dataset you can train you model by executing the file "train.py" the file requires two arguments:
1. The directory path of the dataset.
2. The directory path where you want to save your model.
Example : python train.py -d F:\test\face-mask\dataset -m F:\test\face-mask

# Final
After building your model you can run your model using your webcam by executing the file detect_mask.py.
