---
title: <h1>Robot[ic]<br>Study<br>Companion</h1>
markmap:
  colorFreezeLevel: 5
  initialExpandLevel: -1
---

## **Interaction**

### *Audio*

- [ ] [`PyAudio 0.2.14`](https://pypi.org/project/PyAudio/)
  - [x] (IN) Respeaker 2 Mics HAT
  - [ ] (IN) [AIY Voice Bonnet v2](https://aiyprojects.withgoogle.com/voice)
  - [ ] (IN) USB Mic
  - [x] (OUT) Built-In Speaker
  - [ ] (OUT) BT Speaker

- [ ] Speech
  - [ ] Speech-To-Text
    - [x] [`SpeechRecognition 3.10.4`](https://pypi.org/project/SpeechRecognition/)
    - [ ] [`OpenAI/Whisper v20231117`](https://github.com/openai/whisper/releases/tag/v20231117)

  - [ ] LLM Inference
    - [ ] (Local) [Ollama](https://github.com/ollama/ollama)
    - [x] (Remote) [OpenAI API](https://platform.openai.com/docs/overview)
    - [ ] (Remote) Anthropic API
    - [ ] (Remote) Google Gemini API

  - [x] Text-To-Speech
    - [x] [`pyttsx3 2.91`](https://pypi.org/project/pyttsx3/)
    - [ ] [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech)  

- [ ] RSC Status
  - [ ] loading 
  - [ ] sentiment
  - [ ] error
  - [ ] waiting

### *Visual*

- [x] [16x NeoPixel Ring](https://www.adafruit.com/product/1463): RSC Status
  - [ ] loading 
  - [ ] sentiment
  - [ ] error
  - [ ] waiting

- [x] [NX3224T024: touch display](https://nextion.tech/datasheets/nx3224t024/)
  - [ ] conversations
  - [ ] logs
  - [ ] sentiment
  - [ ] settings
  - [ ] menus


### *Tactile*

- [x] [Arcade Push Button (24mm)](https://www.aliexpress.com/item/1005003651570456.html?spm=a2g0o.productlist.main.21.5abc6d2dMls7ZG&algo_pvid=7bb0f609-660b-4586-bbe4-02c2492670c5&utparam-url=scene%3Asearch%7Cquery_from%3A)
  - [ ] start/stop conversation
  - [ ] quick input
  - [ ] settings control


### *Gestures*

- [x] [SG90: Servo](http://www.ee.ic.ac.uk/pcheung/teaching/DE1_EE/stores/sg90_datasheet.pdf)
  - [ ] greeting
  - [ ] excitement
  - [ ] encouragement

### *Environment*

- [ ] [MR60BHA1: mmWave Radar](https://wiki.seeedstudio.com/Radar_MR60BHA1/) 
  - user presence
  - heart rate
  - respiratory rate
- [ ] [SCD4x: Photoacoustic NDIR CO2 sensor](https://sensirion.com/media/documents/48C4B7FB/64C134E7/Sensirion_SCD4x_Datasheet.pdf) 
  - air quality
  - temperature
  - humidity
- [ ] [TMF882X](https://cdn.sparkfun.com/assets/learn_tutorials/2/2/8/9/TMF882X_DataSheet.pdf) multizone dToF proximity sensor
  - surface albedo 
  - surface slope
  - surface distance 
  - ambient light
- [ ] Mic: ambient noise level


## **Dev**

### [*Docs*](https://github.com/RobotStudyCompanion/Documentation)

- [ ] Assembly
- [ ] Configuration
- [ ] Troubleshooting
- [ ] FAQ

### [*CodeStation*](https://github.com/RobotStudyCompanion/CodeStation)

#### *Interaction Engine*
  -  [ ] LLM inferencing
  -  [ ] sentiment inferencing
  -  [ ] affect recognition inferencing

#### *Device Manager*
  -  [ ] motion control
  -  [ ] environment sensing
  -  [ ] audio control
  -  [ ] display manager
  -  [ ] service server
  -  [ ] web app hosting

#### *Test Suite*
  - [x] mic
  - [x] NeoPixel LED Ring
  - [x] speaker
  - [ ] Touch Display
  - [ ] sensors
  - [x] motor test

### [*(Web) App*](https://github.com/RobotStudyCompanion/WebApp)
  - [ ] profile management
  - [ ] chat interface
  - [ ] study planner
  - [ ] course tracker
  - [ ] progress monitor
  - [ ] device management
  - [ ] troubleshooting
  - [ ] support 

### [*MechDesign*](https://github.com/RobotStudyCompanion/MechDesign)

- modular design
- guide grooves
- snap-fit construction
- 3D printed enclosure

### [*ElectroCircuits*](https://github.com/RobotStudyCompanion/ElectroCircuits)

- [x] expansion board schematic
- [ ] expansion board PCB
- [x] wiring diagram
- [ ] troubleshoot guide


## **Publishing**

### *Publications*
- MDPI repl. pkgs
- ICSR repl. pkgs
- UniTartu MSc repl. pkgs
- UniGuyana BSc repl. pkgs

### *Media*
- Videos 
  - raw, short clips
  - rendered examples
  - video documentation
  - tutorial videos
  - gif clips
- Albums
  - product photos
  - profile photos
- Posters
- Blogs
  - Short articles
  - Reviews

### *Promoting*
- online sharing
  - track reach
    - AdSense
  - plan posts
  - posts catalog
  - platforms
    - LinkedIn
    - YouTube
    - OpenSauced
    - GitHub Education
- RSC - Discussions
- releases 

### *Funding*
- Crowdfunding
  - [ ] crowdsupply
- Sponsorship
  - [ ] Kofi
  - [ ] Patreon
- Donations
