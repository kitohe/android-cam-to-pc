## Android Camera to PC

### This allows you to use your Android phone as webcam on your PC without installing any shady stuff.
<br>

1. Requrements

	On your PC:
	- OBS - https://obsproject.com/
	- OBS VirtualCam Addon - https://obsproject.com/forum/resources/obs-virtualcam.949/
	- Python3

	On your Phone:
	- IP Webcam app - https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en

2. How to use:

	- Run `pip install -r requirements.txt`
	- Go to `webcam.py` and change url to your url from IP Webcam app
	- Change `img_width` and `img_height` to desired values if you want to resize original camera output
	- Run IP Webcam app and then start `webcam.py`
	- Open OBS and add new `Window Capture` and add camera window
	- Go to `Tools -> VirtualCam -> Start`
	- Now go to app that you want to use camera with and just select `OBS-Camera`

3. Notes:
   
	- 5GHz WiFi can yield smoother camera output
