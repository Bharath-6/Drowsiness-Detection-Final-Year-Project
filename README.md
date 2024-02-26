## Real-Time Drowsiness Detection GitHub Repository ReadME

This repository contains the source code and documentation for a real-time drowsiness detection system using eye blinking, developed by students from GITAM School of Technology, Bangalore campus.

### Purpose
The goal of this project is to create a low-cost, accurate, and user-friendly solution for detecting driver drowsiness, thereby reducing traffic accidents caused by fatigued drivers.

### Highlights
- **Technologies**: Python, OpenCV, Scikit-learn, NumPy
- **Machine Learning APIs**: Scikit-learn
- **Hardware**: Webcam, PC

### Key Components
- **Face Detection**: Using OpenCV's Haar Cascades
- **Facial Landmarking**: With OpenCV's DLIB library
- **Features Extraction**: Based on eye aspect ratio, mouth opening ratio, and nose length ratio
- **Classification**: Support Vector Machines (SVM) and Random Forests

### Installation
To set up the environment, follow these steps:

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the directory: `cd real-time-drowsiness-detection`
3. Create a new virtual environment: `python -m venv env && source env/bin/activate`
4. Install required packages: `pip install -r requirements.txt`

### Usage
Run the main script:
```
python main.py --video_path /path/to/your/video
```
or start the application in live mode:
```
python app.py
```

### Results
Experimental results show an average accuracy of 94%.

### Future Work
Potential improvements include integrating additional sensors for better performance and developing mobile apps for smartphones.

### References
Please refer to the PDF document "Real-Time Drowsiness Detection" attached in the repository for detailed information about the project.

For further questions, please contact the authors listed below:

- M V S Bharath (321910306006)
- Sagili Yasaswini Reddy (321910306023)
- G Naveen (321910306051)
- Somaraju Keerthi Amulya (321910306052)
- Sadamsetty Satwik (321910306053)

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/10795943/6c31c6eb-05a9-471d-915e-f746e01b741e/F3 DROWSINESS DETECTION (1).pdf
