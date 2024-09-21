PCB Defect Classification with Random Forest and Gradio


This project implements a machine learning model to classify defects in printed circuit boards (PCBs) using a Random Forest Classifier. The model identifies seven classes of defects, including missing holes, mouse bites, open circuits, shorts, spurs, spurious copper, and non-defective PCBs.

Features:


Image Preprocessing: Images are resized to 100x100 pixels before classification.


Classes:
Non-defective
Missing hole
Mouse bite
Open circuit
Short
Spur
Spurious copper


Model: Random Forest Classifier with 100 estimators.
Training/Testing Split: 80% of images are used for training, 20% for testing.
Evaluation: The model is evaluated with a classification report including precision, recall, and F1-score.


Gradio Interface:
A user-friendly Gradio interface is provided for real-time classification of PCB defect images. Simply upload a PCB image, and the model will return whether the PCB is defective and the type of defect.


Usage:
Upload your PCB images to the respective class directories.
Run the script to train the Random Forest model.
Test the model with new images using the Gradio interface.
