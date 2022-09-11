# lane-detect-no-curve-fitting
Autonomous vehicles (AVs) can help future mobility become more economical, safer, cleaner, and inclusive.  According to the Annual report 2020-21 by the Ministry of Roads and Transport, the percentage of surfaced roads to total road length was only 66.8 per cent. And the data is not indicative of the fact of the proper lane markings and the road signs, the lack of which is a major cause of mishaps. Unfortunately, the road coverage in hilly areas and the state of roads in the normal streets are disdainful for the driving of the autonomous vehicle. But the Autonomous Vehicles need to identify the proper path and safe limits on roads without lane markings and bad roads.

Module 1:  Series of Frames
Open Data Set consisting of recorded videos of driving on hilly roads and street roads and convert it into a series of frames using the video to image converter 

Module 2: Prediction
Feeding of series of Frames into deep learning CNN model which identifies the path and the safe limits for the vehicle
It consists of convolutional layer->pooling layer->connection layer to produce the output

Module 3: Visual representation
The series of frames are merged using the image to video converter and shown for visual representation
![lane](https://user-images.githubusercontent.com/68988574/189522351-5e85058b-bc9b-48d0-8234-2eeb417480cd.jpg)
![Lane-detect](https://user-images.githubusercontent.com/68988574/189522355-2874dbf0-0ab0-4ab3-b270-53adcdeef486.jpg)

To RUN :

python lane_lines.py -i challenge.mp4 -o make.mp4

OUTPUT : 

Moviepy - Building video make.mp4.; Moviepy - Writing video make.mp4; Moviepy - Done !; Moviepy - video ready make.mp4
