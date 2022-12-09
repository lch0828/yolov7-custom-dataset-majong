# Pure Augmented Data on Object Detection — Predicting Majong Tiles in Real Games with YOLOv7
### 



* This is a project using YOLOv7.

* See ```cl4335_final.pdf``` for details.

## Dataset

* This research uses the [***Majong datset***](https://app.roboflow.com/dlcv2022/dlcv_majong/5) built by me.

* Make sure to download and unzip the dataset. Then move it under the ```yolov7``` path, rename it to **Majong**.

## Run

1. Clone the official yolov7 github repo to your target path.
    ```
    git clone https://github.com/WongKinYiu/yolov7.git
    ```

2. Prepare the dataset via above steps and make sure it is under the ```yolov7/Majong``` path.

3. For my case the running is done on colab and the dataset is saved to drive. So run the code cells accordingly in the ```yolov7.ipynb``` file.
    
4. The ran models and detections are saved to ```./run```.
