![QuestEyes Logo](https://github.com/questeyes/.github/blob/main/QUESTEYESLOGO-PURPLE-550x114.png?raw=true)

### Project description:

QuestEyes is an ongoing project to develop Eye Tracking technology using machine learning techniques, and develop that technology into a product that allows accessible Eye Tracking by a unified network of software and hardware.
This project is mainly for VR applications such as Eye Tracking and mapping onto virtual avatars, but the hardware device could be adapted into many other forms for other applications.

#### Please note that all content within this organisation is still under development, and some listed features may be missing or incomplete.

<br>

### Repos and tools:

#### QuestEyes_Server (note that QuestEyes-Server is in the process of being replaced with QuestEyes_Server_2.0, thus further development on 1.0 has ceased):
QuestEyes_Server is a cross-platform application for Windows, Mac and Linux that connects to a QuestEyes hardware device to receive camera information and process eye gaze direction. The software also incorporates Over-The-Air update capability for the device, diagnostics tools, communication to other apps and games which can use the eye tracking information via Open Sound Control (OSC), and device calibration.

#### QuestEyes_ESP: 
QuestEyes_ESP is the firmware package for the QuestEyes hardware device that incorporates a camera which streams to the QuestEyes_Server software, it also incorporates a WiFi setup procedure and the ability to be updated by OTA by the QuestEyes_Server.

#### QuestEyes_ClientSimulator:
QuestEyes_ClientSimulator is a console application that emulates a QuestEyes hardware device for developmental purposes when the physical hardware is unavailable. It connects to the QuestEyes_Server exactly like a real hardware device would, and sends a loop of images as if it was capturing frames from the camera.
