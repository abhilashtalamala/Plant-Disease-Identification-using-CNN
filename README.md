Plant-Disease-Identification-using-CNN
Plant Doctor: AI Disease Detector
Ever looked at a plant leaf and wondered if those spots were normal or a sign of trouble? I built this project to solve that. It’s a Deep Learning tool that "looks" at photos of plants and identifies diseases automatically.

##What this does
Think of this as a digital specialist for farmers. I trained a Convolutional Neural Network (CNN)—essentially a brain for images—to recognize patterns in leaves. It can tell the difference between a healthy plant and one suffering from specific bacterial or fungal issues.

### The "Secret Sauce" inside:
Smart Learning: The model doesn't just memorize; it learns shapes and textures using layers of "filters."

Image Buffing: Since AI likes clean data, I wrote a script to resize every photo and normalize the colors.

Fake it 'til you make it: I used Data Augmentation to flip and twist the images during training. This teaches the AI to recognize a disease even if the photo is blurry or taken at a weird angle.

## How I built it
I used Python and TensorFlow/Keras to build the architecture. For the eyes of the project, I used OpenCV to process the images.

## How to run it
Grab the data: You'll need the PlantVillage dataset.

Install the gear: ```bash
pip install tensorflow opencv-python matplotlib

Fire it up: Run the script, grab a coffee, and watch the AI learn. It’ll save a cnn_model.pkl file when it's done—that's the "trained brain" you can use later.

## 📈 Results
At the end of the run, the script pops out a graph showing how well the AI performed. It's satisfying to see the accuracy line climb up as it gets smarter!
