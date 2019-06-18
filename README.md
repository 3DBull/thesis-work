

# ABSTRACT

Derek Syme (Master of Science in Electrical Engineering)
Implementation of Computer Vision for Railroad Automation Using Convolutional Neural Networks
Directed by Dr. JoonWan Kim

A primary challenge in making the railroads automated is receiving precise sensor information. GPS location is not sufficiently reliable or accurate to tell the train which siding it is on or if a switch is present. As with self-driving cars, a vision system can augment the sensors to aid in precise track and landmark locating. This thesis looks at basic rail detection and how already developed lane detection technology can be adapted for the rail systems. Both a traditional computer vision detection method and a machine learning technique are compared for robustness, speed, and error reduction. The traditional approach uses linear filtering and search algorithms to detect the rails in the image. The machine learning method uses a trained convolutional neural network to segment the pixels belonging to the rails. The two methods are analyzed in terms of strengths and weaknesses to give an understanding of potential rail detection solutions. 
The convolutional neural network is much faster as well as stronger at filtering the images accurately, while the traditional filtering method is stronger at localizing sets of tracks on a larger scale without noise. The combination of the strengths of these two methods could provide a solution that contains both the localized accuracy of the neural network with the generalized speed and tracking of the traditional methods. 

The following images are examples of the Traditional and CNN results respectively. 

![Traditional Detection](TCVF_Prediction.png?raw=true "Traditional Detection")

![CNN Detection](CNN_Prediction.png?raw=true "CNN Detection")


