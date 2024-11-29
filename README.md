Influencer Video Performance Analysis
This project performs influencer video performance analysis by detecting faces in videos and associating them with specific influencers. It uses facial recognition to identify unique faces, extracts embeddings from face images, and evaluates the performance of influencers based on their appearance in videos.


Installation
Clone the repository or download the project files.



python3 -m venv env
source env/bin/activate  # For Mac/Linux
env\Scripts\activate     # For Windows

Install the necessary dependencies:
pip install -r requirements.txt

The main dependencies are:
DeepFace: For facial recognition and generating embeddings.
OpenCV: For extracting faces from video frames.
pandas: For data handling and manipulation.
scikit-learn: For calculating cosine similarity.
tqdm: For displaying progress bars.
Install required libraries:


pip install deepface pandas opencv-python-headless scikit-learn tqdm

Optional: If you face issues with TensorFlow, you can install tf-keras:

pip install tf-keras

Dependencies
Python 3.x
DeepFace (Facial recognition)
OpenCV (Video processing)
pandas (Data handling)
scikit-learn (Similarity calculation)
tqdm (Progress bars)
Optional:
tf-keras (for TensorFlow compatibility issues)
