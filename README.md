data_dir contains training data divided into two folders apple and other_fruit
data_test contains validation data divided into two folders apple and other_fruit
dir_traversal_tfrecord.py is used to find all tfrecords file in the directory
read_image.py is used to read images from tfrecords file
tfrecord.py is used to convert images into tfrecords
model_cnn.py is the model used for training it has four optimizers (GradientDescent,Adam,Momentum and Adagrad) , each optimizer is trained on 30 learning rates and at the end training time graph is plotted for each optimizer 
model_new.py is the model which have custom activation function, it also has four optimzers (GradientDescent,Adam,Momentum and Adagrad), each optimizer is trained on 30 learning rates and at the end training graph is plotted for each optimizer
