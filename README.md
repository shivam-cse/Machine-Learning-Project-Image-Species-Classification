# Machine-Learning-Project-Image-Species-Classification
#### Machine Learning Project - Task: Images classification (17 Category Flower Dataset) . The data was obtained from the University of Oxford’s Department of Engineering Science.

You can download Dataset from given link : https://www.robots.ox.ac.uk/~vgg/data/flowers/17/

### For Details(more) Information and experiment, You can refer my ppt which i made during it(I put my ppt (also pdf and result excel sheet) ./Project_Analysis/Flower_Species_Classification.ppt).
As we know its having 17 classes, i have applies multiple algorithm (like : logistic regression , Single layer perceptron, multi layer perceptron, perceptron learning algorithm ect).

##  Feature Extraction from imageses
1. Features are the information or list of numbers that are
extracted from an image.
2. When deciding about the features that could quantify
plants and flowers, we could possibly think of Colour,
Texture and Shape as the primary ones.
3. In this Project I will be used three inbuilt libraries for
features extraction :  
    • Colour Histogram that quantifies colour of the flower  
    • Hu Moments that quantifies shape of the flower.  
    • Haralick Texture that quantifies texture of the flower.

## Finally I compared the accuracy of every algorithm which i have written here in brief : 

### Logistic Regression: (Inbuilt - sklearn)  
    • With MinMaxScaler normalization technique, its able to achieve 64.5% accuracy  
    • With StandardScaler normalization technique, its able to achieve 72% accuracy  
    • It’s performing best compared to all other algorithms that are evaluated. 
    
### Perceptron Learning Algorithm(PLA) : (Inbuilt - sklearn)  
    • Train Accuracy : 88.83% & Test Accuracy : 60.41% 
    
### Single Layer Perceptron:  
    • For 5-fold it’s able to achieve an accuracy of 57% with my own code (No inbuilt)  
    • without k-fold ( train : 95% ; test : 45 %) with my own code (No inbuilt )
    
### Muli Layer Perceptron:  
    • For 5-fold it’s able to achieve an accuracy of 63.23% with 1 hidden layer of 20 hidden neurons and max iterations of 500 with my own code (No inbuilt )  
    • It can be observed that as the number of hidden neurons increases, the more linearity the trained dataset will tend to and increases the accuracy. Which is described by the cover’s theorem
    
### Accuracy Comparison: Logistic Regression > MLP > PLA > SLP


