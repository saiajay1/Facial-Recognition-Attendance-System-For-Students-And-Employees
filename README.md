# Facial-Recognition-Attendance-System-For-Students-And-Employees
This is an Attendance System to mark the Attendance of Employees Or students Using Facial Recognition Technology

# Face-Recognition-Attendance-System
Smart Attendance system to mark the in/out time of Employees.

The cascade_classifier is obtained from opencv github repository.

Download the classifier (data/haarcascades/haarcascade_frontalface_default.xml) from the above github and place it the folder along with main.py.

## Don't Rename it ##

Install the dependencies:
     
     pip3 install -r requirements.txt

Running the Program:
    
    python3 main.py camera_rstp_http_link IN/OUT

Create a folder named Images.
Create a folder named Data and Move the user_list.txt to that folder

    mkdir Images
    mkdir Data
    mv user_list.txt Data/


