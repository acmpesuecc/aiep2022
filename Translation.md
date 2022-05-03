# Real Time Call Translator
A real time translator application – performs translation on voice data for cellular calls, by capturing voice data from an ongoing call and simultaneously streaming them to a CNN Model, which detects several languages; which further translates audio contained in the packets to a chosen language and plays the same back to the listener, all with a minimal possible lag.

[repo link](https://github.com/acmpesuecc/translator)

## Tech Stack
- Kotlin
	- Libraries
		- android.telecom
		- android.telephony
		- android.system
- Python
	- Libraries
		- Librosa, ffmpeg
		- Keras
		-  Numpy
		- Tensorflow

## The Team
+ Team Lead: Manab Kumar Biswas — [ Manab784](https://github.com/Manab784)
+ Mohamed Ayaan — [Mohamed-Ayaan358](https://github.com/Mohamed-Ayaan358)
+ Ujjwal Tiku — [Ujjwal-tiku](https://github.com/ujjwal-tiku)
+ Charan S Gowda — [Charan2308](https://github.com/charan2308)
+ Aditya D Venkatesh Prasanna — [Adityavpd](https://github.com/adityavpd)

## Status: 50% completed
- Start Date: 14-02-2022
- End Date: 15-04-2022

### Planned Timeline
+ **Phase 1:** Building, Training, Validating, & Evaluating the CNN Model; Integrating the NLP Model/API with CNN
	+ **Week 1:** Basic plan on the model & Learning Week  - No of layers, algorithms to be used, dropout rates, etc. Also to get familiarized with NLP and CNN concepts. 
	+ **Week 2:** Trained NLP and CNN Model Phase 1 - Gathering datasets, and forming the basic structure of the model (Input normalization, hidden layers).
	+ **Week 3:** Trained NLP and CNN Model Phase 2 - Creating the complete model (flattening, dense and dropout layers).
	+ **Week 4:** Complete NLP and CNN model - Testing the model for efficiency and tweaking epochs to obtain max efficiency along with accuracy.
+ **Phase 2:** Building the Base App
	+ **Week 5**: Basic Application - Building the base app with different activities, views and UI elements. Also produce a ViewModel for storing call packets.
+ **Phase 3** - Integrating the Translation Layers and other Features
	+ **Week 6** - Obtaining Voice Packets - To access voice packets from an ongoing call (Kernel Perms) and to store it in the ViewModel created.
	+ **Week 7** - Translation Layers - API calls for text-to-text and text-to-speech translation to be made and tested.
	+ **Week 8** - Combining Layers and Testing - Combining the various layers and performing manual and automated tests on the application.

### Completed 
+ **Phase 1**: Model Completed (80%)
	+ **Week 1**: Completed - Model planned and laid out clearly.
	+ **Week 2**: Completed 60% - Model Training not completed due to issues with datasets.
	+ **Week 3:** Completed 80% - Model Training issue resolved to an extent but still not completely resolved.
	+ **Week 4:** Completed 80% - Model Training resolved for 2 languages - Hindi and English.
+ **Phase 2**: Completed 
	+ **Week 5**: Completed - App built with placeholder for translation based options.
+ **Phase 3**: Not done - Not much of an idea on how to proceed with this, accompanied with the lack in time.
	+ **Week 6** - Not completed
	+ **Week 7** - Not completed
	+ **Week 8** - Not completed

## Challenges Faced 
- Lack of planning ahead - Piling up of weekly deadlines.
- Lack of in-depth knowledge in most of the fields chosen.
- Lack of coordination between teammates due to various academic timelines. 

## Learning Points
- Gained loads of insights and an intermediate level of knowledge on how CNN's work.
- Application development through Kotlin loosened up and seemed easier than expected.
- Weekly meetings and e-mails helped keep track of events, even if timelines were different.
- GitHub usage and fluency increased by a large scale.

---
