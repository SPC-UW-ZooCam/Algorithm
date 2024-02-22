# Algorithm
ResNet Algorithms for training a model

# Overview
Residual Network (ResNet) is a deep learning model. It is a convolutional Neural Network (CNN) designed to support a variety of convolutional layers. The number trailing ResNet represents the number of convolutional layers each script contains. The higher the number of layers the deeper the architecture and learning capabilities of the algorithm. Determining which algorithm to utilize depends on the amount of computational resources, memory, and time availible. 

# Using the algorithm
Reguardless of the version of ResNet you decide to go with, you will need to do the following: 
- Update the "folder_path" on line 23 with the correct directory where your (augmented and balanced) training dataset it located
- Update the "num_epochs" on line 222


# ResNet-18.py
ResNet-18 is a relatively lightweight version of ResNet making it faster to train and deploy. It tends to gereralize well on small to medium-sized datasets. It is the algorithm we use most freqently when training our model and is recommended to start with. 

# ResNet-50.py
ResNet-50 captures more complex features and patterns in data compared to ResNet-18. It is more robust and achieves a higher accuracy on large-scale datasets with complex structures. Training ResNet-50 requires more computational resources (e.g., memory, GPU/CPU power, training time) compared to ResNet-18. 

# ResNet-152.py
ResNet-152 is the deepest ResNet variant, providing the highest capacity for learning complex representations from data. It can capture fine-grained details and subtle features in teh data making is suitable for tasks requiring high precision. Training and fine-tuning ResNet-152 requires significant computations resources, including high-end GPUs and large amounts of memory. 
