 # CV Final Project

Hand Gesture Recognition
Instructions on running the models:
YOLOV5: run command in terminal

> python detect.py --weights runs/train/peace.pt --img 160 --source 0 --conf-thres 0.4

to run with TTA, add "--augment" to command above.

to run with TTS, uncomment the following lines in detect.py:
> #engine.say(s)
> 
> #engine.runAndWait()

Mediapipe: run command in terminal

> python app.py
