The simple python algorith to detect faces, take samples nby taking pictures of faces and identify using LBPHFaceRecognizer. 
The algorithms have been divided into three parts: main.py, face-trainer.py and recognizer.py.. The main.py is the first set of codes which is used to detct the face data with haarcascade trained model. It also captures the 30 frames of the person face and saves the data in the folder datasets in the name with format ("User")+(entered number)+ (image count number).jpg
![User 1 1](https://user-images.githubusercontent.com/61246422/127361498-21796e99-baa7-4d4f-88e4-c7bfd8fd0ffe.jpg)
![User 1 15](https://user-images.githubusercontent.com/61246422/127361552-71f7e06c-0ec4-49fa-ab80-e772378d9de5.jpg)

Then in the trainer set, the captured images are trained using the library LBPHFaceRecognizer. The trained model is stored in the trainer.yml.
Then finally in the recognizer the face is recognized and the name is displayed from the set of array on the face.

![Capture](https://user-images.githubusercontent.com/61246422/127362342-dea9d5a6-25ec-4c47-ab44-03e1de722b3c.JPG)
![capture1](https://user-images.githubusercontent.com/61246422/127362348-a1cc729b-af7d-4387-8745-f98255860be2.JPG)

