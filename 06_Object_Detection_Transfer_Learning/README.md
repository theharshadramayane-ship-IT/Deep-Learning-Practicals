Aim: To detect objects in images using a pre-trained CNN model and Transfer Learning.

Short explanation: Transfer Learning mein hum pehle se trained model ka use karte hain. Model image mein objects identify karta hai aur unke around bounding boxes, class labels aur confidence scores show karta hai.

Important: Object detection aur image classification alag hain. Object detection ek image mein multiple objects ki location bhi detect karta hai. Is practical mein hum actual object detector use karenge, sirf image classifier nahi.


Complete Python Code — One Jupyter Notebook Cell
This practical uses YOLO26n, a lightweight pre-trained CNN-based object detector. It fine-tunes the model on the small COCO8 dataset and freezes the first 10 layers during training

Expected output--
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/0dc70e3d-bd9a-48d5-a27d-b7d18c7fd371" />

Pre-trained model loading and training output.
Validation mAP50 score.
Image with bounding boxes around detected objects.
Object names and confidence scores.
