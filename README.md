# Leaf-Disease-Detection-and-Health-Grading-System

Objective:

Developed an algorithm using deep learning, Image Processing and Fuzzy Inference system that allows the user to identify a disease caused by a particular micro-organism that is infested on the leaf of a plant and also successfully shows estimated health severity of the leaf based on how much of a leaf is infected.

![flow chart](https://user-images.githubusercontent.com/73630123/119841897-d5ffbe00-bf23-11eb-8b50-85d662d42d7a.jpg)

Methodology:

I. Neural Network Classifier

The deep learning algorithm studies the different dataset images and classifies into one of the 5 categories: Bacteria, Fungi, Virus, Nematode and Normal Leaf (Not infected at all)

![Conf matrix](https://user-images.githubusercontent.com/73630123/119843157-e7959580-bf24-11eb-8ae5-c4a86d16a89a.jpg)

After classifying feature extraction of the infected leaf has been done using Digital Image Processing technique.

II. Image processing

Studied the images in the dataset and understanding the different patterns in which the organisms infect the leaf. Thus, the main objective of the technique of image processing is to extract the infected area of the leaf and isolating the background and the green part of the leaf. This would help us to highlight the only the infected area.

![result img1 for rp](https://user-images.githubusercontent.com/73630123/119842682-8372d180-bf24-11eb-8e96-302e4cff284c.jpg)

III. Fuzzy Rule Base System

Finally after the feature extraction , to determine the health severity of the leaf in terms of percentage, a set of rules have been aggregated by using Fuzzy Inference System in MATLAB

![Fuzzy logic](https://user-images.githubusercontent.com/73630123/119842741-938ab100-bf24-11eb-8e9d-0a819c20b297.jpg)

Result:

![result discussion img1](https://user-images.githubusercontent.com/73630123/119840931-04c96480-bf23-11eb-957d-14e49c01d3d9.jpg)
