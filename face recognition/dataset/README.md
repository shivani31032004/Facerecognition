# Face Recognition using Haar-Cascade Classifier, OpenCV, and Python
Simple Face Recognition algorithm using Python and OpenCV

# Blog
http://utpcc.blogspot.com/2017/05/facial-recognition-machine-learning.html

## Requirement
- Python 3.6
- `pip install opencv-contrib-python`

## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)
2. Train the model (training.py)
3. Face Recognition (face_recognition.py)

## How to run ?
1. Make sure have executable permission. (chmod 777 .)
2. `pip install -r requirements.txt`
3. Please make sure that you have folders called 'datasets' and 'trainer' in the same directory. (Optional, I have put the code so it will create if it's not exist.)
4. Run in the command line the face_datasets.py for taking your face image as datasets. Don't forget to set each person's face to unique ID (You need to edit the code everytime, or maybe just change the id variable to raw_input[OPTIONAL])
5. If you have more face to be include, change the ID and run the program again
6. Train your datasets by running training.py
7. Lastly, run face_recognition.py



