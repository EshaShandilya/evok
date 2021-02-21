# evok
EvoK consists of a pair of wearable prototype devices (i.e., sender and receiver). The sender is designed as a headband enabling continuous sensing of heart rate with aesthetic designs to maximize social acceptance. The receiver is designed asa wristwatch enabling unobtrusive receiving of the loved one’s continuous heart rate with multi-modal notification systems. The project is coded on Microsoft's makecode platform (https://makecode.microbit.org/) using Microbit and Pulse sensor (https://pulsesensor.com/). 

Please find a detailed report about the concept at 

### Sender Code
> Open this page at [https://eshashandilya.github.io/evoksender/](https://eshashandilya.github.io/evoksender/)

### Receiver Code
> Open this page at [https://eshashandilya.github.io/evokreceiver/](https://eshashandilya.github.io/evokreceiver/)

When the sender’s heart rate is below 60 beats per minute (bpm), the light notification on the wristband would be blue. When the heart rate is between 60bpm and 100bpm, the light would turn green. When the heart rate is beyond 100 bpm, the light would turn red, accompanied by a beep sound. Additionally, to provide more flexibility, the receiver could control whether to receive the data or not by pressing the left button A, on the wristband. They could press the left button on the micro: bit to stop and resume receiving the data and feedback. 

## Notification Logic
Three ranges of heart rate with corresponding feedback: Blue LED represents less than 60. Green LED represents the normalrange between 60 and 100. Red LED and alarming sound represents over 100. According to Mayo Clinic, the normal resting heartrate of an individual ranges between 60 and 100; other factors such as, age, fitness level, emotions could also influence the heartrate. The heartbeat value of the sender is displayed on the Microbit’s screen; refer Notification Output image.

![Notification Logic](https://github.com/EshaShandilya/evokreceiver/blob/master/notification_logic.png?raw=true)

## Notification Output
![Notification Output](https://github.com/EshaShandilya/evokreceiver/blob/master/notification_output.png?raw=true)


### Acknowledgement
The sender implementation uses https://github.com/JanTadeuszEkiel/homelab to calculate the heart rate from the pulse.
The project was in collaboration with two HCI students Yiwen Wang and Xuan Zhao, and Professor Dr. Mingming Fan.
