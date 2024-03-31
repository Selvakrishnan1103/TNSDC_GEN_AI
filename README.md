Handwritten Digit Recognition
Overview
This project aims to recognize handwritten digits using a feedforward neural network trained on the MNIST dataset. It includes a graphical user interface (GUI) built with Tkinter for user interaction.

Features
Neural network architecture with one hidden layer
Training using the L-BFGS-B optimization algorithm
GUI for drawing digits and predicting handwritten digits
Deployment options for standalone applications or web applications
Requirements
Python 3.x
NumPy
Tkinter (for GUI)
PIL (Pillow) for image processing
scikit-learn (for metrics like confusion matrix)
TensorFlow or Keras (optional, for neural network implementation)
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/username/handwritten-digit-recognition.git
Install dependencies:
Copy code
pip install -r requirements.txt
Train the neural network model using train.py.
Run the GUI application using gui.py.
File Structure
train.py: Script for training the neural network model
gui.py: Script for the graphical user interface
app.py: Contains functions for model prediction and other utilities
file1.txt and file2.txt: Saved parameters of the trained model
README.md: Project overview, instructions, and usage guide
requirements.txt: List of dependencies
License
This project is licensed under the MIT License - see the LICENSE file for details.

Credits
MNIST dataset: Yann LeCun, Corinna Cortes, Christopher J.C. Burges
Neural network implementation: Inspired by "Neural Networks and Deep Learning" by Michael Nielsen
References
MNIST database
Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning. MIT Press.
