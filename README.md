# Scrapyard-Car-Classifyer
This system uses a YOLOv5 classifyer trained on a custom dataset,  
with Deepsort to track the cars and some simple lines of code to  
display my name and the numer of recorded cars.  

Run the code put these lines of code into your google colab notebook  
or terminal!

!git clone https://github.com/RCFiretbt/Scrapyard-Car-Classifyer.git

%cd /content/Scrapyard-Car-Classifyer  
!pip install torch==1.7.1+cu101 torchvision==0.8.2+cu101 torchaudio==0.7.2 -f https://download.pytorch.org/whl/torch_stable.html  
!pip install -r requirements.txt  

%cd /content/Scrapyard-Car-Classifyer  
!python track.py --yolo_weights yolov5/weights/best.pt --source test.mp4 --save-vid  
