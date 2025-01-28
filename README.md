 AIris: Image Classification Project

AIris is an image classification project that identifies hand signals using machine learning. The project is built with Python and leverages common libraries like Scikit-Learn, OpenCV, and others.

 Project Structure

AIris/ │ ├── data/ │ └── images/ Folder for images (will be used for hand signal dataset) │ ├── src/ │ ├── classifier.py Python file for training the image classification model │ ├── process_data.py Python file for processing the dataset │ └── utils.py Helper functions (optional) │ ├── requirements.txt Python dependencies ├── README.md This file └── .gitignore Git ignore file to prevent large files from being pushed

 Dataset

For training the AI model, you can use the [American Sign Language (ASL) dataset](https://www.kaggle.com/grassknoted/asl-alphabet) (or any other suitable hand signal dataset). Here are the details:

- The dataset contains images of hand signs for each letter of the alphabet (A-Z).
- The images should be organized into individual folders, each representing a letter (e.g., `A/`, `B/`, ..., `Z/`).
- You can download the dataset from [this Kaggle link](https://www.kaggle.com/grassknoted/asl-alphabet).
- Once downloaded, place the images into the `data/images/` folder.

 Installation

 1. Clone the repository
    git clone git@github.com:AIcraftByDinesh/AIris.git
    cd AIris
2. Create a Virtual Environment
    python3 -m venv venv
    source venv/bin/activate  On Windows, use `venv\Scripts\activate`
3. Install Dependencies
    pip install -r requirements.txt

 Usage :
Training the Model : 

Place your dataset images in the data/images/ folder.
Run the script to process the data and train the model:

python src/process_data.py
python src/classifier.py

Running the Classifier
After training, you can run the model to classify new images. Modify the classifier script as needed to add functionality for image prediction.

Contributing
If you’d like to contribute to this project, feel free to fork it, create a branch, and submit a pull request. Contributions and feedback are always welcome!

License
This project is open-source and available under the MIT License.


