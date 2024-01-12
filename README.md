This is the fundamental use for weed clasifier.

1. Label the pictures you want to train in Labelling Program
      - [labelImg](https://github.com/HumanSignal/labelImg)
      - [labelme](https://github.com/labelmeai/labelme)
      - Others
  
2. Arrange the folder for training and validation the model (See Weed_Picture)
3. Add the YAML file for Yolov5 Configuration (See test.yaml)
4. Download YoloV5 (See [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)) for more information)
5. copy test.yaml to data folder inside yolov5 folder
6. Use the command "python3 train.py --img 640 --batch 8 --epoch 50 --data ./data/test.yaml --weights yolov5s.pt" to train and validate the data
