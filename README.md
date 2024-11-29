ManOverboard Benchmark Overview
The ManOverboard Benchmark is a benchmark proposed by Professor Yin Jianchuan’s team from the Naval Architecture And Shipping College at Guangdong Ocean University, aimed at detecting small targets at sea. The images in this benchmark was collected using the DJI Mavic 2 drone at a beach in Zhanjiang, Guangdong Province, China.
Data Collection Process
The UAV collected videos by setting different flight conditions, including:
Flight Altitude: 30m to 80m
Drone Flight Direction: East, South, West, North
Camera Angle: 30° to 90°
The video obtained from the UAV acquisition was taken every 5 seconds and filtered to finalize 956 images, and the resolution of the images is 3840 x 2160. The team confirmed that the benchmark contained 956 images and 40,000 objects with bounding boxes. In addition, the benchmark was divided into a training set and a test set at a ratio of approximately 9:1, as described below:
Train Set: 860 images
Test Set: 96 images
Each image has been manually annotated and categorized in both COCO and YOLO formats, and all annotations were reviewed by vision experts.. The annotations are divided into three categories:
person (person on the beach and person at sea)
person with buoy (person with a buoy)
person with jacket (person wearing a life jacket)
Table 1. The detail of images and annotations about ManOverboard benchmark
Item	Train	Test	Sum
Images	860	96	956
Annotations	32115		
person	28719		
person with buoy	2181		
person with jacket	1216		
This benchamark provides researchers with a comprehensive foundation to advance detection and recognition for maritime small targets.

