# Face Recognition Attendance System

This project was design to build an attendance system with computer vision technique.

![image](https://user-images.githubusercontent.com/85855794/126082613-82021c9a-c853-45f6-9a46-293c8a4b190c.png) <img src="https://your-image-url.type" width="100" height="100">


## Method
I used a library called "face-recognition" to detect 128 landmark measurement for a certain face with built in deep learning model.
![image](https://user-images.githubusercontent.com/85855794/126082672-d1a2f768-d2ef-4ee1-8aaf-34afe23feeb5.png)

Detail refers to an article: https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78

What I did here is just compare the face landmark of those people to see if they are the same people or not. If two landmark are similar, it means that they are the same person.

For Attendance System, I create a csv file to store a person's name and the time once he or she was detected. Also, I loop through the csv file once the same person was detected in order to avoid repeat.

The csv file will look like this:

![image](https://user-images.githubusercontent.com/85855794/126082811-5486a256-fbbb-4e2a-8c92-4ee416b33dde.png)
