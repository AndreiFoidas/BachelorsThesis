# BachelorsThesis
 
•	Created an Android mobile app in Kotlin that classifies user-uploaded images into the seven main plastic types.
•	Created a server using Flask to intercept the photos and process them using tools from Tensorflow2.
•	Combined two enhanced image classification models (based on pre-trained models — VGG19 and EfficientNet-B7) with an OCR algorithm (based on Google’s Vision API) using a weighted version of the sum rule-based fusion method.
•	Modified the pre-trained models (suing data augmentation, k-fold cross validation, fine-tuning, and sum-based fusion) to increase the accuracy and reach 58% on a custom testing dataset, containing 50 images that closely resemble user input data.
•	The app doubles as a way to collect labeled photos from its users — the gathered images can be used to increase the dataset, improving the accuracy.
