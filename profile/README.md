![QuestEyes Logo](https://github.com/questeyes/.github/blob/main/QUESTEYESLOGO-PURPLE-550x114.png?raw=true)

### Project description:

QuestEyes is an ongoing project to develop Eye Tracking technology using machine learning techniques, and develop that technology into a product that allows accessible Eye Tracking by a unified network of software and hardware.
This project is mainly for VR applications such as Eye Tracking and mapping onto virtual avatars, but the hardware device could be adapted into many other forms for other applications.

#### Please note that all content within this organisation is still under development, and some listed features may be missing or incomplete. Please see the feature matrix to see what features are upcoming but not yet completed.

<br>

### Repos and tool descriptions:

#### QuestEyes_Server (In the process of being replaced with QuestEyes_Server_2.0, thus further development on 1.0 has ceased):
QuestEyes_Server is a cross-platform application for Windows, Mac and Linux that connects to a QuestEyes hardware device to receive camera information and process eye gaze direction. The software also incorporates Over-The-Air update capability for the device, diagnostics tools, communication to other apps and games which can use the eye tracking information via Open Sound Control (OSC), and device calibration.

#### QuestEyes_ESP: 
QuestEyes_ESP is the firmware package for the QuestEyes hardware device that incorporates a camera which streams to the QuestEyes_Server software, it also incorporates a WiFi setup procedure and the ability to be updated by OTA by the QuestEyes_Server.

#### QuestEyes_ClientSimulator:
QuestEyes_ClientSimulator is a console application that emulates a QuestEyes hardware device for developmental purposes when the physical hardware is unavailable. It connects to the QuestEyes_Server exactly like a real hardware device would, and sends a loop of images as if it was capturing frames from the camera.

<br>

### Feature matrix:

#### QuestEyes_Server:
| Feature | Completed before replacement (v1.0) | Complete (v2.0) |
| --- | --- |  --- |
| Communicates with QuestEyes hardware | Yes | Yes |
| Receives camera information from QuestEyes hardware | Yes | In progress (migrating) |
| Processes eye gaze direction | Was in progress | In progress |
| Performs Over-The-Air updates of QuestEyes hardware | Was in progress | In progress |
| Provides diagnostic tools | Yes | In progress (migrating) |
| Communicates to other apps using Open Sound Control (OSC) | No | In progress |
| Calibrates QuestEyes hardware | No | Not yet |
###### Please also note that processing of eye gaze direction may be moved to be processed on the QuestEyes hardware instead of the software in the future, depending on suitability and hardware limitations.

#### QuestEyes_ESP:
| Feature | Complete |
| --- | --- |
| Communicates with QuestEyes software | Yes |
| Transmits camera information to QuestEyes software | Yes |
| Wifi setup procedure | Yes |
| Updates via OTA | In progress |

#### QuestEyes_ClientSimulator:
| Feature | Complete |
| --- | --- |
| Emulates connection of QuestEyes hardware | Yes |
| Transmits fake camera information to software | Not yet |
