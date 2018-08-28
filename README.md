# Breast-Cancer-predictions
Classification with sklearn Logistic Regression  
I build a simple model that can predict if a patient has breast cancer. In this model, I used sklearn dataset for breast cancer. The database includes 569 instances (patients) and 30 attributes.  

Attribute information:  

– radius (mean of distances from center to points on the perimeter)  
– texture (standard deviation of gray-scale values)  
– perimeter   
– area  
– smoothness (local variation in radius lengths)  
– compactness (perimeter^2 / area – 1.0)  
– concavity (severity of concave portions of the contour)  
– concave points (number of concave portions of the contour)  
– symmetry  
– fractal dimension (“coastline approximation” – 1)  

After training and feeding new patient information, the model gives a result of 0 or 1. In this case 0 refers to “malignant” class and 1 refers to “benign” class.

The model’s accuracy is 96.5 %. 
