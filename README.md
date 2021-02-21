# evok
EvoK consists of a pair of wearable prototype devices (i.e., sender and receiver). The sender is designed as a headband enabling continuous sensing of heart rate with aesthetic designs to maximize social acceptance. The receiver is designed asa wristwatch enabling unobtrusive receiving of the loved one’s continuous heart rate with multi-modal notification systems.

### Sender Code
> Open this page at [https://eshashandilya.github.io/evoksender/](https://eshashandilya.github.io/evoksender/)

### Receiver Code
> Open this page at [https://eshashandilya.github.io/evokreceiver/](https://eshashandilya.github.io/evokreceiver/)

When the sender’s heart rate is below 60 beats per minute (bpm), the light notification on the wristband would be blue. When the heart rate is between 60bpm and 100bpm, the light would turn green. When the heart rate is beyond 100 bpm, the light would turn red, accompanied by a beep sound. Additionally, to provide more flexibility, the receiver could control whether to receive the data or not by pressing the left button A, on the wristband. They could press the left button on the micro: bit to stop and resume receiving the data and feedback. 


### Acknowledgement
The sender implementation uses https://github.com/JanTadeuszEkiel/homelab to calculate the heart rate from the pulse.
