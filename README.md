# Scrapyard-Car-Classifyer
This system uses a YOLOv5 classifyer trained on a custom dataset,  
with Deepsort to track the cars and some simple lines of code to  
display my name and the numer of recorded cars.  

Run the code put these lines of code into your google colab notebook  
or terminal!

!git clone --recurse-submodules https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch.git     
%cd /content/Yolov5_DeepSort_Pytorch  
!pip install -r requirements.txt  
!git clone https://github.com/RCFiretbt/Scrapyard-Car-Classifyer.git    

%cd /content/Yolov5_DeepSort_Pytorch     
!python track.py --yolo_weights /content/Yolov5_DeepSort_Pytorch/Scrapyard-Car-Classifyer/best.pt --source /content/Yolov5_DeepSort_Pytorch/Scrapyard-Car-Classifyer/test.mp4 --save-vid   

The code which makes this all work is the file track.py which can be found  
in the main folder
