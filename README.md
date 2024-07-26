# Hand controller: control cars using hands, in Games

This project uses the Python OpenCV module to detect hand gestures and control a car, or any entity which can be controlled by the WASD keys for that matter. By utilizing the Computer Vision module, we are building up a model that captures the operator's hand gestures and binds it to each of the four main navigational keys (WASD) in games.
Here we have assigned:
1. W key to opened hand, palm facing cam
2. A key to opened hand tilted to the left, palm facing cam
3. D key to opened hand tilted to the right, palm facing cam
4. S key to closed hand.


## Installation

Run the following command:
```sh
pip install -r requirements.txt
```

## Usage

#### Using PC camera:
- Run `OpenCV PC-cam hand gesture controller.py`

#### Using Mobile camera:
- Download IP Webcam App in your mobile and put the IP in the `url` variable in code
- then simply run `OpenCV mobile-cam hand gesture controller.py`
And put your hand in front of the Camera to control the CAR! 
