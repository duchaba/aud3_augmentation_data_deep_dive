# 1.0 |-- Introduction | Augmentation Data Deep Dive (AUD3)

Welcome to the “Augmentation Data Deep Dive” (AUD3) project. It is a new journey in the “Demystify AI” series. 

The only thing these journeys have in common is the problems are taken from the real-world Artificial Neural Network (ANN) project. I have worked on them, coded them, cried over them, and sometimes had a flash-of-insight or an original thought about them.

The journeys are a fun and fascinating insight into the daily working of an AI Scientist and Big-Data Scientist. They are for colleagues and AI students, but I hope that you, a gentle reader, would enjoy them too. 

The logic behind data augmentation is uncomplicated. You need more pictures to increase the ANN model accuracy, and data augmentation gives you more images. 

The AUD3 is a hackable, step-by-step Jupyter Notebook. It is for learning about data augmentation and selecting the correct parameters in the ANN image-classification and image-segmentation projects. You can skip ahead to the result-cells and not read the math and the code-cells. The math is elementary, and coding is straightforward logic, so try it out. You might enjoy “hacking” along the journey. 

Data augmentation increases the training images by a factor of 2 to 16 or more. For ANN, that means the model achieves better accuracy with more epoch and without overfitting. 

For example, I was working on an AI project for a large casino hotel. The goal is to classify every customer into one of the 16 categories as they walk through the door. In other words, it is not to identify that guy walking through the door is “Duc Haba,” but to classify him as a “whale (A-1)” category, i.e., a big spender. 

As you have guessed, the first and most significant problem is the lack of labeled pictures. I need millions of tagged photos because of human diversity in race, ethnicity, clothing, different camera angle, and so on. 

ANN is not a ruled-based expert system. For example, a person wearing a Rolex watch is an “A-1”, or a guy with no shoe and no shirt is a “D-4” category. ANN does not use rules, so it needs millions of labeled images to train and to generalize so the ANN model can classify a guy who enters the casino for the first time correctly. In ANN’s lingual, it means the ANN model is not overfitting. 

I classify the AUD3 as a "sandbox" project. In other words, it is a fun, experimental project focusing on solving one problem.

><center><h2><i>So if you are ready, let's take a collective calming breath …  … and begin.</i></h2></center>

# 2.0 |-- The Journey

...Continue on the Jupyter notebook, https://github.com/duchaba/aud3_augmentation_data_deep_dive/blob/main/AUD3_augmentation_data_deep_dive.ipynb
