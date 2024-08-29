---
title: <h1>Robot[ic]<br>Study<br>Companion</h1>
markmap:
  colorFreezeLevel: 6
---

## Interaction

### Audio: Speech

- PyAudio 0.2.14
  - (IN) Respeaker 2 Mics HAT
  - (IN) AIY Voice Bonnet v2
  - (IN) USB Mic
  - (OUT) Built-In Speaker
  - (OUT) BT Speaker

- Speech
  - Speech-To-Text
    - `SpeechRecognition 3.10.4`
    - `OpenAI/Whisper v20231117`

  - LLM Inference
    - (Local) Ollama
    - (Remote) OpenAI API
    - (Remote) Anthropic API
    - (Remote) Google Gemini API

  - Text-To-Speech
    - `pyttsx3 2.91`  

- Audio Tone: RSC Status
  - loading 
  - sentiment
  - error
  - waiting

### Visual

- Neopixel RGB LED Array: RSC Status
  - loading 
  - sentiment
  - error
  - waiting

- touch-enabled display
  - conversations
  - logs
  - sentiment
  - settings
  - menus


### Tactile Button

- start/stop conversation
- quick input
- settings control


### Flipper Gestures

- greeting
- excitement
- encouragement
- support

### Environment

- [MR60BHA1: mmWave Radar](https://wiki.seeedstudio.com/Radar_MR60BHA1/) 
  - user presence
  - heart rate
  - respiratory rate
- [SCD4x: Photoacoustic NDIR CO2 sensor](https://sensirion.com/media/documents/48C4B7FB/64C134E7/Sensirion_SCD4x_Datasheet.pdf) 
  - air quality
  - temperature
  - humidity
- [TMF882X](https://cdn.sparkfun.com/assets/learn_tutorials/2/2/8/9/TMF882X_DataSheet.pdf) multizone dToF proximity sensor
  - surface albedo 
  - surface slope
  - surface distance 
  - ambient light
- Mic: ambient noise level


## Dev


### MechDesign

- modular design
- guide grooves
- snap-fit construction
- 3D printed enclosure

### ElectroCircuits

- expansion board schematic
- expansion board PCB
- wiring diagram
- troubleshoot guide

### CodeStation

- Interaction Engine
  - LLM inferencing
  - sentiment inferencing
  - affect recognition inferencing
- Device Manager
  - motion control
  - environment sensing
  - audio control
  - display manager
  - service server
  - web app hosting
- Test Suite
  - Component Tests
    - mic
    - speaker
    - sensors
    - motor test
    - 


### (Web) App
- profile management
- chat interface
- study planner
- course tracker
- progress monitor
- device management
- troubleshooting
- support 


## Docs

- Assembly
- Configuration
- Troubleshooting
- FAQ

## Media

- publications
  - MDPI repl. pkgs
  - ICSR repl. pkgs
  - UniTartu MSc repl. pkgs
  - UniGuyana BSc repl. pkgs
- demo footage

