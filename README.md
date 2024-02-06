### Tomato Disease Detection System Using Deep Learning CNN with Streamlit UI

#### Introduction:
This project presents an AI-based system for detecting various diseases in tomato plants using deep learning techniques. It comprises a convolutional neural network (CNN) model trained on a dataset of tomato leaf images and a user-friendly Streamlit-based interface for easy interaction.

#### Dataset Description and Preparation:
The dataset, a subset of the PlantVillage dataset, focuses on tomato leaf images and consists of 18,103 images categorized into 10 disease classes and a healthy class. Data preparation involved organizing images into train and validation folders, with each disease class represented in separate directories. Images are RGB with a resolution of 256 x 256 pixels.
![image](https://github.com/Zemedkun-Abebe/Automated-Detection-of-Tomato-Plant-Diseases-Using-Deep-Learning-Technique/assets/99493026/fd0fc195-5cae-4a80-bef6-f4ad778ea091)

#### Model Architecture:
The CNN architecture features three convolutional layers followed by max-pooling layers, a flatten layer, and two dense layers. ReLU activation is used in the first dense layer, while softmax activation produces class probabilities in the second layer. Dropout regularization minimizes overfitting.

#### Justification of Architecture Choice:
The selected architecture balances complexity and simplicity, allowing effective hierarchical feature learning. Dense layers with ReLU activation capture complex patterns, while dropout regularization prevents overfitting.

#### Model Training and Evaluation:
The model is trained for 20 epochs using Adam optimizer and categorical cross-entropy loss. Performance is evaluated on training and validation sets, with satisfactory accuracy achieved.
![image](https://github.com/Zemedkun-Abebe/Automated-Detection-of-Tomato-Plant-Diseases-Using-Deep-Learning-Technique/assets/99493026/9c6d4cf3-050b-4047-92bc-f287f566df7d)
![image](https://github.com/Zemedkun-Abebe/Automated-Detection-of-Tomato-Plant-Diseases-Using-Deep-Learning-Technique/assets/99493026/216bcd34-3cea-4983-8de6-1eefbe84bb9a)

#### Streamlit User Interface:
The Streamlit interface enables users to upload tomato leaf images for disease prediction. The predicted class is displayed alongside the uploaded image, offering a straightforward user experience.
![image](https://github.com/Zemedkun-Abebe/Automated-Detection-of-Tomato-Plant-Diseases-Using-Deep-Learning-Technique/assets/99493026/c3e8cd05-c522-4251-9bbe-24a9b71bcdd9)

#### Conclusion:
This integrated system provides an accessible solution for tomato disease detection, benefiting farmers and agricultural experts in disease management and crop yield improvement. Future enhancements may involve dataset expansion, model fine-tuning, and additional UI features.
