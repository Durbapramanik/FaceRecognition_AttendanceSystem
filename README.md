In colleges, universities, organizations, schools, and offices, taking attendance is one of the most 
important tasks that must be done on a daily basis. The majority of the time, it is done manually, 
such as by calling by name or by roll number. The main goal of this project is to create a Face 
Recognition-based attendance system that will turn this manual process into an automated one. 
This project meets the requirements for bringing modernization to the way attendance is handled, 
as well as the criteria for time management. This device is installed in the classroom, where and 
student's information, such as name, roll number, class, sec, and photographs, is trained. The 
images are extracted using Open CV. Before the start of the corresponding class, the student can 
approach the machine, which will begin taking pictures and comparing them to the qualified 
dataset. Logitech C270 web camera and NVIDIA Jetson Nano Developer kit were used in this 
project as the camera and processing board. The image is processed as follows: first, faces are 
identified using a Harassed classifier, then faces are recognized using the LBPH (Local Binary 
Pattern Histogram) Algorithm, histogram data is checked against an established dataset, and the 
device automatically labels attendance. An Excel sheet is developed, and it is updated every hour 
with the information from the respective class instructor. Keywords: Face Detection, Face 
Recognition, Harassed classifier, NVIDIA Jetson Nan 
