# Computer Vision (Web App)
This directory includes all the files needed for running the web app. The object detection and classification is done using YOLOv5 (https://github.com/ultralytics/yolov5).

## Instructions to run it locally:
* Clone the repo and move to this directory<br>
`git clone https://github.com/Saksham-Katiyar/Computer-Vision-based-Web-App.git`<br>
`cd Computer-Vision-based-Web-App/Web_App`
* Set the python environment and download the required python libraries<br>
`source app_env/bin/activate`<br>
`pip install -r requirements.txt`
* Run the detection app<br>
`python3 detect.py --source 0`
* Copy the url shown in the terminal and open it in a browser. The output will look like the screenshot attched below.<br>
![ss1](../Screenshots/Screenshot4.png)
![ss1](../Screenshots/Screenshot5.png)

## Improvements
This is not the final output of the project and there are lots of improvements to be done including:<br>
1. Better HTML/CSS template for the output or improving the current one.
2. Adding features like storing the output in a well-organised file.