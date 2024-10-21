This project tested multiple face detection algorithms such as Face recognition python module, the CNN, the SVC, and MediaPipe prototypes with the usage of python, flask and opencv or real time webcam capture.

With the intention of creating an employee attendance system with less complication face registration, during the test it is found that face recognition is less complicated and suitable in terms of time efficiency and effectiveness.

In conducting the test I believe that the CNN and other algorithms alike requires more face training dataset in order to get better accuracy. Though we believe among face detection algorithms CNNs are known to be the most accurate rather better than the face recognition module.

To simplify, the face recognition module does not require to run epochs or training, but rather just one sample picture of a person to detect them on camera.


How to use:
make sure to create new subfolder under static called faces and create another subfolder inside it respectively to their prototype names
for example make sure to have the following subfolders:

1. static/faces/CNNalgo
2. static/faces/MediaPipealgo
3. static/faces/SVCalgo

then run app.py
for facereco prototype, make sure to click on reload dataset after image capture then you may click on take attendance to start detecting

Do not worry about requirements.txt as you try to run the app.py you will see what module you are short on and simply type 'pip install <name of module/can find on google>'
the other prototype.py you are seeing is just backup to run on app.py. For instance if you want to update a prototype algorithm, copy and replace all in app.py as at the moment app.py has its backup in the file name 'prototypefacereco.py'

Test was conducted on python v3.12

Images of faces are saved in different folders based on their respective name of the protoype. for example face recognition project, i save the image files under the subfolder face_rec
while the rest under the subfolder static

you are free to use and update my codes especially the prototypes for other algorithms than facereco. this does not require further update anymore.

Facereco prototype:
![image](https://github.com/user-attachments/assets/65f319f2-9f1c-4528-8282-d7003b115cfc)

Uses iphone camera because of no built-in webcam. you may try as well with the app 'droidcam' can find in appstore
![image](https://github.com/user-attachments/assets/eed6b28f-b0f3-40f2-bbdd-aa6f80fd08cc)
![image](https://github.com/user-attachments/assets/fbf672f9-0102-4694-a08a-c89e79843cca)
