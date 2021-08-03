# Scrapyard-Car-Classifyer
This system uses a YOLOv5 classifyer trained on a custom dataset,  
with Deepsort to track the cars and some simple lines of code to  
display my name and the numer of recorded cars.  

Run the code put these lines of code into your google colab notebook  
or terminal!

!git clone https://github.com/RCFiretbt/Scrapyard-Car-Classifyer.git  
%cd /content/Scrapyard-Car-Classifyer    
!pip install -r requirements.txt    

%cd /content/Scrapyard-Car-Classifyer  
!python track.py --yolo_weights yolov5/weights/best.pt --source test.mp4 --save-vid  

The code which makes this all work is the file track.py which can be found  
in the main folder
