# Tensorflow-implementation-with-epochs-on-parkinson-prediction
Install TensorFlow 2
TensorFlow is tested and supported on the following 64-bit systems:

Python 3.7–3.10
Ubuntu 16.04 or later
Windows 7 or later (with C++ redistributable)
macOS 10.12.6 (Sierra) or later (no GPU support)
WSL2 via Windows 10 19044 or higher including GPUs (Experimental)

# Requires the latest pip
pip install --upgrade pip

# Current stable release for CPU and GPU
pip install tensorflow

# Or try the preview build (unstable)
pip install tf-nightly


Download a package
Install TensorFlow with Python's pip package manager.

TensorFlow 2 packages require a pip version >19.0 (or >20.3 for macOS).
Official packages available for Ubuntu, Windows, and macOS.

Read the pip install guide
Run a TensorFlow container
The TensorFlow Docker images are already configured to run TensorFlow. A Docker container runs in a virtual environment and is the easiest way to set up GPU support.


 docker pull tensorflow/tensorflow:latest  # Download latest stable image
 docker run -it -p 8888:8888 tensorflow/tensorflow:latest-jupyter  # Start Jupyter server 
Read the Docker install guide
Google Colab: An easy way to learn and use TensorFlow
No install necessary—run the TensorFlow tutorials directly in the browser with Colaboratory, a Google research project created to help disseminate machine learning education and research. It's a Jupyter notebook environment that requires no setup to use and runs entirely in the cloud. Read the blog post.

Build your first ML app 
Create and deploy TensorFlow models on web and mobile.
Web developers
TensorFlow.js is a WebGL accelerated, JavaScript library to train and deploy ML models in the browser, Node.js, mobile, and more.
Mobile developers
TensorFlow Lite is a lightweight solution for mobile and embedded devices.
