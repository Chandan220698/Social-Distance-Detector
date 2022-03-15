# Social Distance Detection
Social distancing detection using deep learning to evaluate the distance between people to mitigate the impact of this coronavirus pandemic. The detection tool was developed to alert people to maintain a safe distance with each other by evaluating a video feed. The video frame from the camera was used as input, and the open-source object detection pre-trained model.

## Project Output
#### Sample Output 1
![Output avi gif](https://github.com/Chandan220698/Social-Distance-Detector/blob/main/sample_output_1.gif)
#### Sample output 2
![Output avi gif](https://github.com/Chandan220698/Social-Distance-Detector/blob/main/sample_output_2.gif)


### Important Note:
* Github doesn't support files with size larger than 25 Mb.You can find the yolo weights in [google drive](https://drive.google.com/file/d/1zZPnKXB0RKnVsgjzfehfjmb_AwGAnNl6/view?usp=sharing) 
* Download and paste it to yolo-coco folder

## Steps to run project in the terminal:
* **Open your terminal**
* **Change directory to project directory**
* **Execute** ` pip install -r requirements.txt ` ***to install the project dependencies***
* **Run the command** ` python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1 ` ***to run your social distance detection project***
* After you run the last line of command,a window eill pop up and after execution of the file a `output.avi` file will be showing up in your directory

## Contacts:
* **Created by: [Chandan Kumar](https://github.com/Chandan220698)**
* **Email: [ck220698@gmail.com](ck220698@gmail.com)**
* **LinkedIn: [Chandan Kumar](https://www.linkedin.com/in/chandan-kumar-ck111/)**


## License
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

