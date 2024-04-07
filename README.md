## Dancing-Detection
Multi-person dancing detection and segmentation is a collaboration project.
In this project, We focused on detecting people dancing and performance various movements. Leveraging a custom-trained YOLOv8 segmentation model, it was able to achieve remarkable results in both detection and segmentation tasks.


## Description
### Dancing-Detection
Multi-person dance detection is a computer vision task aimed at identifying and tracking the movements of multiple individuals within a dance sequence.
Utilizing advanced algorithms, multi-person dance detection analyzes video frames to identify unique body poses and movements associated with dancing.

### Calculate Binary Mask Area (Remove Noise)
For some of the false detections, We filtered out these false detections by calculating the binary mask area.


## Table of Contents
- [Installation](#installation)
- [Author](#author)
- [License](#license)


## Installation
1. Clone the repository:
```
git clone https://github.com/WaiHninEaindrarMg/Dancing_Detection.git
```

2. Install Ultralytics , check here for more information (https://docs.ultralytics.com/tasks/segment/) :
I used pretrained YOLOv8 Model from (https://github.com/ultralytics/assets/releases/download/v8.1.0/yolov8n-seg.pt) : 
```
pip install ultralytics
```


## Instruction
1. Run this file yolo_custom_train.ipynb
```
Run yolo_custom_train.ipynb
```
2. Run this file https://github.com/WaiHninEaindrarMg/Dancing_Detection/custom_detection.py
```
python custom_detection.py
```

After run this custom_detection.py, video output will be showed.
This is result video (multi-person dancing detection and segmentation results)
![Result](https://github.com/WaiHninEaindrarMg/Dancing_Detection/blob/main/output/output_video.gif)

##
## Author
👤 : Wai Hnin Eaindrar Mg  
📧 : [waihnineaindrarmg@gmail.com](mailto:waihnineaindrarmg@gmail.com)
👤 : San Chain Tun
📧 : [sanchaintunucsy@gmail.com](mailto:sanchaintunucsy@gmail.com)


## License

This project is licensed under the [MIT License](LICENSE.md) - see the LICENSE.md file for details.

