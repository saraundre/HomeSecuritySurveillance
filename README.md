# HomeSecuritySurveillance

Software Enginerring Course , 3rd Year 2nd Semester 

Software Engineering Course Design Topic from China Telecom Guangdong Company 2022）
             
Topic:  Home security surveillance 

*************************************************
Background: 
*************************************************

 At present, there are more and more safety accidents in families, such as short circuit, fire, gas leakage, illegal intrusion and other scenes. It is worth exploring to methods of home security surveillance based on videos from home installed cameras. It combines with AI analysis and training algorithms to solve the problem of home AI safety monitoring.
 
This system realizes the functions of monitoring, identification and alarm of key areas and specific scenes of the family with video technology, combined with AI analysis and training algorithm:


(1) It detects smoke and flame, and raises the alarm. 

(2) The room entrants are detected within a specified period of time. It raises the alarm when strangers break in.


*************************************************
References:
*************************************************
Video processing, recognition algorithm with AI
Hardware requirements:
PC 1: 2C 16GB memory 100GB hard drive, camera.
Data requirements: not
Test environment: The network is connected


*************************************************
Home Surveillance Security System SETUP 

*************************************************
1. Clone Yolov5 repository: 

git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5


2. In Telegram app, look for Bot Father API, register a new bot and save the token, 


3. copy the following url and replace <TOKEN> with the generated token
https://api.telegram.org/bot <TOKEN>/getUpdates

  
4. Move the "best.pt" weights in the yolov5 folder

  
5. Create a folder named "detected"

  
6. Open the notebook and specify the path of the weight.

  
7. Run the script



