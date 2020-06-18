# EA-HAM_Covid_Hackathon
Deep_learning_Sign_language_data_classification

Context:-
Sign languages (also known as signed languages) are languages that use manual communication to convey meaning. This can include simultaneously employing hand gestures, movement, orientation of the fingers, arms or body, and facial expressions to convey a speaker's ideas. 

Content:-

Details of dataset:-
	Image size: 100 x 100
	Color space: RGB
	File format: png
	Number of classes: 10 (Digits: 0-9)
	Number of participant students: 218
	Number of samples per student: 10

Details of datasets in GitHub Repo:
	Repo: github.com/ardamavi/Sign-Language-Digits-Dataset

Model used:-
        First layer:                  resnet50 transfer learning model from Imagenet challenge
        Fully Connected layers: 2 linear layers with Relu activation and Log likelihood 
			 loss functions.
        Optimizer used:	 Adam with a learning rate of .003
        Python Module:	 PyTorch

Testing Results:-
        As per results of final epoch:
        Train loss: 0.387  Test loss: 0.743  Test accuracy: 0.793
        
Code for training and testing on Github:

https://github.com/akbc1221/EA-HAM_Covid_Hackathon/blob/master/EA%26HAM4.ipynb

