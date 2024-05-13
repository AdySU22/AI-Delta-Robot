# AI-Delta-Robot

The AI Delta Robot project is a sophisticated application of artificial intelligence (AI) aimed at enabling a robotic system to detect and interact with objects in its environment. At its core, the project harnesses the power of convolutional neural networks (CNNs), a deep learning algorithm particularly effective for image recognition tasks. The CNN model is trained on a diverse dataset comprising images of three-dimensional objects: spheres, cubes, and cylinders. This dataset is meticulously curated and preprocessed using the OpenCV library to ensure optimal training results. The training process involves splitting the dataset into training and testing sets, followed by the creation of a CNN model architecture using TensorFlow, a powerful machine learning framework. The model architecture consists of convolutional layers for feature extraction, max-pooling layers for spatial downsampling, and fully connected layers for classification. The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function, with performance evaluated using metrics such as accuracy, loss, and validation accuracy. Once trained, the model is saved for deployment onto the Delta Robot system. During deployment, the Haar cascade classifier is employed for initial object detection in real-time camera feeds. Detected objects are then passed through the trained CNN model for accurate classification and localization. This seamless integration of multiple algorithms allows the Delta Robot to intelligently perceive and interact with objects, making it a versatile and adaptive solution for a variety of tasks.






