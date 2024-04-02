# Team-Pushpak-Hackathon
Team Name: Team PUSHPAK
Team leader email id:

# Problem Statement: 
**PROJECT VARICE-VISION**: Leveraging deep learning for real-time detection and risk stratification of esophageal varices in endoscopy, revolutionizing diagnosis with improved accuracy and efficiency.

# 1. Context and Background
 Esophageal varices are enlarged, swollen veins in the 
esophagus (the muscular tube connecting the throat to the 
stomach) often caused by portal hypertension. These 
weakened veins can rupture and cause life-threatening 
bleeding. Early detection and risk assessment of esophageal 
varices are crucial for timely intervention and preventing 
complications particularly in cases where banding is required.

![13052023-095113786970](https://github.com/PraneishSAero/Team-Pushpak-Hackathon/assets/119675623/8042d0b3-424d-4cfa-b47f-2f152f235263)


# 2. Problem Definition
 Currently, endoscopy, a visual examination of the upper digestive tract, is the primary method for 
diagnosing esophageal varices. However, accurate assessment of variceal risk (low, medium, high) and 
bleeding probability remains subjective and relies on the expertise of individual endoscopists. If high-risk 
varices are detected, and the decision to move ahead with banding as a treatment is taken. Banding involves 
placing small rubber bands around the varices essentially cutting off the blood supply, causing them to shrink. 
Contrary, not all varices (even the high-risk ones) have a high probability of bleeding. Yet banding – a 
complex and expensive procedure – is preferred to eliminate the benefit of the doubt. Not to mention the 
complications that could arise from banding itself like chest pain and narrowed esophagus.

# 3. Desired Outcome
We aim to develop an Artificial Intelligence (AI) model that can analyze endoscopic data to:
 • Automate the detection and segmentation of esophageal varices.
 • Classify varices into low, medium, and high-risk categories based on established medical criteria.
 • Predict the probability of bleeding for high-risk varices, aiding in treatment decisions like banding.

# 4. Impact
 The AI-powered solution has the potential to:
 • Improve the accuracy and consistency of esophageal varice diagnosis and risk assessment.
 • Reduce the risk of missed diagnoses and delayed interventions.
 • Support early intervention and prevent life-threatening bleeding complications.
 • Enhance clinical decision-making for better patient outcomes.
 • Increase efficiency in endoscopy procedures, allowing healthcare professionals to dedicate more time to 
patient care. 

# Intel One API AIAnalytics toolkit:
The main goal of our project was to fine-tune  an object classification model using our custom datsets. The aim was for the model to classify endoscopic images into high risk and low risk varices with accuracy. The use of AI Analytics Toolkit surprised us with its optimization and performance. We were able to complete our project effectively in less time.

# Description
We used VGG16 model, with custom layers at the end for object classification.
Due to its fixed format for datsets training the model with our custom datset was challenging. Thus, changing our dataset to the required format was time consuming. Intense training was conducted which equipped the model to classify varices with atmost precision.

# Intel AI analytics toolkit in Data preprocessing
Our custom dataset have to be preprocessed before sending it to VGG16 for training. 
