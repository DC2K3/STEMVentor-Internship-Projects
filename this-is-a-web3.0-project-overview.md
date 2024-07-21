
## WEB3.0 distributed app

This project is the confluence of various domains like IoT , Blockchain , Cloud Computing , ML and Web development. The IoT part of the domain consists of three circuits:-

### 1. The vehicle circuit

This circuit is responsible to measure the transport parameters - Loaded quantity ,temperature , humidity and vibration and send them to AWS with the help of MQTT using GPRS

### 2. The Loading location circuit

This circuit is responsible to capture the image of the number plate of a vehicle upon detection using ultrasonic sensor. The captured image is sent to AWS for further image rekognition via HTTP and the time of detection of vehicle is also sent to AWS with the help of MQTT.

### 3. The Unloading location circuit

This circuit is also responsible to capture the image of the number plate of a vehicle upon detection using ultrasonic sensor. The captured image is sent to AWS for further image rekognition via HTTP and the time of detection of vehicle is also sent to AWS with the help of MQTT. This ciruit also has a load sensor to weigh the deleivered goods and send it to AWS with the help of MQTT

NOTE: All the data being sent to AWS is stored in AWS dynamoDB and in private blockchain as well.
