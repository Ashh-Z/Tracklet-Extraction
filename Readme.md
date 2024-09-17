Process video files to detect and track different vehicles in the video, obtain tracklet information for each vehicle

Input to the file should be a json file which contais the path to you videos, in the following format : 
```
{
    "Cam1" : "/path/video1.mp4",
    "Cam2" : "/path/video2.mp4"
}
```

The provided Yolov5s model has been finetuned on the Indian Driving Dataset (IDD) and some other smaller kaggle datasets for the following classes : 
```{0: 'Bicycle', 1: 'Bus', 2: 'Cars', 3: 'LCV', 4: 'Three-Wheeler', 5: 'Two-Wheeler', 6: 'Truck'}```
