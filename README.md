# Structural-Damage-Detection
Implementation of ML algorithms that help identify extent of damage in the structure.

Project Contributors - Sumitesh Naithani (sumitesh.ece17@nituk.ac.in) 
					   Md Aarish Siddiqui (mohd.ece17@nituk.ac.in)

Introduction - 
This is ML based project trained on dataset of structure (concrete - building) pertaining to 30 joints. In this project we took dataset of only 3 joints. At every joint there is accelorometer attatched to help fetch the reading of the earthquake sensed at that point.

Description of the dataset - 
merged1.csv - consists of accelerometer readings when the joints are damaged due to earthquake and additional columns are added to distinguish between 3 joints.

merged2.csv - consists of accelerometer readings in both damaged and undamaged condition. Binary classification is used. 0 for undamaged condition and 1 for damaged condition.

Algorithms & Concepts used - 1) Random Forest Algorithm  https://en.wikipedia.org/wiki/Random_forest
				  			 2) Artificial Neural Networks https://en.wikipedia.org/wiki/Artificial_neural_network  

Model is also capable of testing arbitrary accelerometer readings as an input.

Dataset is not uploaded for copyright issues.
For further queries check the earthquakedamage.pptx file. https://github.com/sumitesh9/Structural-Damage-Detection/blob/master/EARTHQUAKE%20DAMAGE.pptx
