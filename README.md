# Custom-Image-Classifier

# DRIVE LINK
https://drive.google.com/drive/folders/1qWRfwrAkRGwY1DyItX0mTxAXM5JxtdGY?usp=drive_link

---

## 1. Dataset Preparation

**Q1: How did you organize your dataset in Google Drive?**  
I structured the data by creating a folder named `Image_Dataset`, and then inside this folder, I created different folders representing different classes or categories. Each folder contains images related to a specific object or plant.

**Q2: Why is folder structure important for TensorFlow image loading?**  
The names of the folders are used to label the images. TensorFlow can automatically detect the category of the images based on the folder names.

---

## 2. Model Training

**Q1: What is the role of convolutional layers in image classification?**  
The convolutional layers assist in identifying patterns in an image, such as edges and textures, which aid in identifying objects in an image.

**Q2: Why do we split data into training and validation sets?**  
The training data is used to train the model, while the validation data is used to test how well it was trained.

---

## 3. Performance Analysis

**Q1: What accuracy did your model achieve?**  
The model accuracy achieved is **0.6140**.

**Q2: How did the number of images affect the model’s performance?**  
Less number of images might not allow the model to learn all possible patterns, while more images will help the model perform better.

---

## 4. Critical Thinking

**Q1: What challenges did you encounter while using your own dataset?**  
However, while working with my dataset, I found some challenges, for example, having enough images, dealing with poor image quality, including images with watermarks, and having images that looked similar.

**Q2: How can data augmentation improve your model?**  
Data augmentation is the process by which new images are created from the available images. This is done by flipping, rotating, or zooming the images.

---

## 5. Application

**Q1: Suggest a real-world application for your trained model.**  
**Plant identification apps**: The model can be used in plant identification apps. A user takes a picture of a plant, and the system identifies the plant.

**Q2: How can this system be integrated into a mobile or web application?**  
The model can be used in a system where users upload a picture. The system then sends the image to the model. The model then identifies the image and sends the result back.

---

## 6. Visualization & Overfitting

**Q1: What signs indicated overfitting in your first model?**  
Overfitting occurs when training accuracy is high but validation accuracy is low. This means that the model learned the data but cannot make accurate predictions on new data.

**Q2: How did data augmentation affect validation accuracy?**  
Data augmentation helped improve the validation set accuracy since the model was learning from a variety of images.

---

## 7. Model Improvement

**Q1: What is the purpose of dropout layers?**  
The dropout layers disconnect random neurons during training. This helps prevent overfitting.

**Q2: Why does data augmentation improve generalization?**  
It helps the model to see many images of the same type, ensuring it learns to generalize rather than memorize.

---

## 8. Performance Comparison

**Q1: Compare accuracy before and after improvements.**  
The accuracy of the model, during validation, was low. After incorporating the data augmentation and dropout, the accuracy increased, hence an improved model.

**Q2: Which technique contributed most to improvement?**  
Data augmentation had the biggest impact, considering that it increased the variety of images used during training.

---

## 9. Deployment & Application

**Q1: Why is saving the model important?**  
The model can be used by saving it. This will allow it to be reused without retraining. In addition, it can be incorporated into an application.

**Q2: How can this model be deployed in a real-world system?**  
The saved model can be included in an application, website, or AI system. The user will upload an image, and the model will automatically classify it.

---
