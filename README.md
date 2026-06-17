🎨 Neural Style Transfer Web Application (Flask + PyTorch)
📌 Project Description

This project is a deep learning-based Neural Style Transfer (NST) web application that allows users to generate artistic images by combining the content of one image with the artistic style of another image. The system is built using PyTorch for deep learning model inference and Flask for web deployment, providing an interactive and user-friendly interface to perform real-time style transfer.

Neural Style Transfer is a computer vision technique that uses convolutional neural networks (CNNs) to separate and recombine the content representation of one image and the style representation of another. In this project, a pre-trained encoder-decoder architecture is used to generate high-quality stylized images efficiently.

The encoder extracts deep feature representations from the content image using a pre-trained VGG-based network, while the decoder reconstructs the final stylized image by applying the style characteristics learned during training. The system leverages optimized PyTorch models (vgg_normalised.pth and decoder_final.pth) for fast inference

🧠 How It Works
1. The user uploads a content image and a style image
2. The content image is passed through a pre-trained VGG encoder
3. Feature representations are extracted from deep CNN layers
4. A decoder network reconstructs the image by applying style features
5. The output is a stylized image combining both content and style
6. The final result is displayed on the web interface

🏗️ Model Architecture

-> This project uses a simplified encoder-decoder architecture:

1. Encoder: Pre-trained VGG network (vgg_normalised.pth)
2. Decoder: Custom trained CNN decoder (decoder_final.pth)
3. Loss Functions:
   a. Content Loss
   b. Style Loss (Gram Matrix-based)
4. Optimization: Pretrained model inference (no training required during runtime)

🛠️ Tech Stack
1. Python 
2. PyTorch 
3. Flask 
4. NumPy
5. Pillow (PIL)
6. HTML / CSS (Frontend)
7. Pre-trained CNN models

👨‍💻 Future Improvements
1. Add real-time webcam style transfer
2. Deploy on cloud (AWS / Render / HuggingFace Spaces)
3. Improve UI using React frontend
4. Add multiple style blending options
5. Optimize model for faster inference

🏆 Learning Outcome

This project demonstrates practical implementation of:

1. Deep Convolutional Neural Networks (CNNs)
2. Feature extraction using VGG networks
3. Encoder-decoder architectures
4. Flask-based ML deployment
5. Real-world AI application development

👤 Author
Sujal Kalamkar
