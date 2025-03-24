# ResNet_50 full implementation   

-----

## 1. Introduction   
Full implementation of ResNet_50 using Pytorch

## 2. Environment & Setup   
Python (Pytorch)   

## 3. Reference Paper
This project is based on the paper  
**[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)**  
by Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun

## 4. Workflow
- We used the **Food101** dataset, which contains **101,000 food images** categorized into **101 different classes**.  
  Each class includes 750 training images and 250 test images, offering a rich and diverse dataset for food recognition tasks.

- The images were preprocessed (resized, normalized) and split into training and validation sets.

- A convolutional neural network (CNN)-based architecture was implemented.  
  To enhance feature learning and gradient flow, **skip connections** (inspired by ResNet) were incorporated into the model.

- The model was trained using cross-entropy loss and evaluated using top-1 accuracy on the test set.

- Inference was conducted on unseen food images, demonstrating the model's ability to generalize to new inputs.

## 5. Results
- The model was evaluated on the test set of the Food101 dataset.
- A total accuracy of **56.61%** was achieved by aggregating the prediction accuracy across all 101 food categories.
