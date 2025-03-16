# AI Local Server Providers

These are the Python scripts in order to set up local AI servers for image, speech and sound generation.

- 1. **Image generation:** 
	- Follow the instructions to install the AI Image Generator [Flux](https://github.com/black-forest-labs/flux)
 	- Run the script `python ServerImagesFlux.py`
  	- Use a tunneling service to get an URL to redirect the calls to your local server (ngrok, tunnelmole, cloudfare)
  	- Set the URL inside the AI Server Settings page of the application
- 2. **Speech Generation**
	- Follow the instructions to install [Coqui TTS](https://github.com/coqui-ai/TTS)
 	- Run the script `python ServerSpeechGeneration.py`
  	- Use a tunneling service to get an URL to redirect the calls to your local server (ngrok, tunnelmole, cloudfare)
  	- Set the URL inside the AI Server Settings page of the application
- 3. **Audio Generation**
	- Follow the instructions to install [Audiocraft](https://github.com/facebookresearch/audiocraft)
 	- Run the script `python ServerAudioGeneration.py`
  	- Use a tunneling service to get an URL to redirect the calls to your local server (ngrok, tunnelmole, cloudfare)
  	- Set the URL inside the AI Server Settings page of the application

