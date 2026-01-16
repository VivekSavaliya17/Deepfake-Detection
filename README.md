Deepfake Detection System :

Deepfake Detection System is a full-stack web application designed to detect manipulated or fake images using deep learning models. The system uses a FastAPI backend for model inference and a modern React frontend built with Vite and Tailwind CSS.
This project is developed for academic, research, and learning purposes in the areas of Artificial Intelligence, Cyber Security, and Digital Forensics.


Project Overview :

Deepfakes are AI-generated images or videos that can convincingly imitate real people. Such manipulated media pose serious threats including misinformation, identity fraud, and digital media tampering.

This project focuses on detecting deepfake images using pretrained deep learning models and provides a web-based interface for easy testing and demonstration.


Features :

* Deep learning based deepfake image detection
* Image upload and prediction functionality
* FastAPI backend for inference
* React frontend using Vite and Tailwind CSS
* Suitable for academic projects and demonstrations


Tech Stack :

Backend - 

* Python
* FastAPI
* TensorFlow and Keras
* OpenCV
* NumPy

Frontend -

* React
* Vite
* Tailwind CSS
* JavaScript


Project Structure :

```
Deepfake_Detection/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── README.md
│
├── models/
│   ├── deepfake.h5
│   ├── deepfake.keras
│   └── deepfake2.keras
│
├── venv/
│
├── app.py
├── features.py
├── training.ipynb
├── test.ipynb
├── requirements.txt
├── runtime.txt
├── Procfile
├── image.jpg
└── README.md
```


Installation and Setup :

Prerequisites - 

* Python 3.8 or above
* Node.js and npm
* Git


How to Run the Project :

Step 1 Clone the repository - 

```
git clone https://github.com/Pooja-1504/Deepfake_Detection.git
cd deepfake-detection
```

Step 2 Create a virtual environment - 

```
python3 -m venv ./venv
```

Step 3 Activate the virtual environment on Windows - 

```
.\venv\Scripts\activate
```

Step 4 Install backend dependencies -

```
pip install -r requirements.txt
```

Step 5 Run the FastAPI backend -

Go to the directory where app.py is located and run:

```
uvicorn app:app --host 0.0.0.0 --port 8000 --reload
```

Backend will be available at:

```
http://localhost:8000
```

Step 6 Run the frontend application -

Open a new terminal, navigate to the client directory, and run:

```
cd client
npm install
npm run dev
```

Frontend will be available at:

```
http://localhost:5173
```


How the System Works :

* The user uploads an image through the frontend interface
* The image is sent to the FastAPI backend
* The backend preprocesses the image
* The deep learning model analyzes visual artifacts
* The prediction result is returned to the frontend


Use Cases :

* Academic and final year projects
* Cyber security and digital forensics learning
* Artificial intelligence demonstrations
* Awareness against media manipulation


Limitations :

* The system supports image based detection only
* Model accuracy depends on the training dataset
* Not optimized for real time or large scale deployment


Author :

Vivek Savaliya
Cyber Security Enthusiast

GitHub profile
https://github.com/VivekSavaliya17


License :

This project is intended strictly for educational and research purposes.
It is not recommended for production use without further testing and validation.

