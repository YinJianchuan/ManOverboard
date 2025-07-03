**ManOverboard Benchmark Overview**

The ManOverboard Benchmark is a benchmark proposed by Professor Yin Jianchuan’s team from the Naval Architecture and Shipping College at Guangdong Ocean University, aimed at detecting small targets at sea. The images in this benchmark was collected using the DJI Mavic 2 drone at a beach in Zhanjiang, Guangdong Province, China(+110.54032, +21.01508). 

Table 1. The detail of external factors in the area

|Hour(24)|Wind direction|Wind speed(m/s)|Weather(mm)|Temperature(℃)|Sea wave(m)|
| - | - | - | - | - | - |
|14|southeast|4\.0-4.9|cloudy|30\.2|0\.41|
|15|southeast|5\.1-6.7|cloudy|30\.5|0\.41|
|16|southeast|5\.1-6.8|0\.1|30\.6|0\.41|

**Data Collection Process**

The UAV collected videos by setting different flight conditions, including:

- Flight Altitude: 30m to 80m
- Drone Flight Direction: East, South, West, North
- Camera Angle: 30° to 90°

The video obtained from the UAV acquisition was taken every 5 seconds and filtered to finalize 956 images, and the resolution of the images is 3840 x 2160. The team confirmed that the benchmark contained 956 images and 35119 objects with bounding boxes. In addition, the benchmark was divided into a training set and a test set at a ratio of approximately 9:1, as described below:

- Train Set: 764 images
- Val Set: 96 images
- Test Set: 96 images

Each image has been manually annotated and categorized in both COCO and YOLO formats, and all annotations were reviewed by vision experts.. The annotations are divided into three categories:

- person (person on the beach and person at sea)
- person with buoy (person with a buoy)
- person with jacket (person wearing a life jacket)

This benchmark provides researchers with a comprehensive foundation to advance detection and recognition for maritime small targets.

Table 2. The detail of images and annotations about ManOverboard benchmark

|Item|Train|Test|Sum|
| - | - | - | - |
|Images|860|96|956|
|Annotations|32115|3004|35119|
|person|28719|2665|31384|
|person with buoy|2181|227|2408|
|person with jacket|1216|112|1328|

- The download link below:
通过网盘分享的文件：ManOverboard
链接: https://pan.baidu.com/s/1yyuZYjH4w4zt5DH4t-_FLA?pwd=YJCT 提取码: YJCT

- Reference:
Guokang, Xu, et al. "Maritime Man-Overboard Search Based on MOB-Detector with Modulated Deformable Convolution and Bi-Directional Feature Fusion Network." Frontiers in Marine Science 12: 1547747.





