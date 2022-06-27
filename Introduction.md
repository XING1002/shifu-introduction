# Welcome to Shifu
Shifu is a Kubernetes-based open-source IoT development and management platform. With Shifu, developers can connect, monitor and control any IoT device more easily. 
(Github page: [http://github.com/Edgenesis/shifu](http://github.com/Edgenesis/shifu). **Note: Shifu is still in preparation for open source, if you are interested in the internal test, please contact info@edgenesis.com to get Github Repo permissions!**)
## IoT Devices
IoT devices are devices that can connect and communicate online or locally with other devices, systems, and services, such as:
- a robotic arm in a manufacturing plant that receives commands from a local automation control system to perform various actions.
- an automated guided vehicle that is remotely cotrolled by its operator. 
- a thermometer on a car that gives commands to turn up or turn down the air conditioner, while sending temperature data to the cloud. 
## Communication
Shifu is compatible with different communication protocols and drivers. It unifies different devices and opens it to users in the form of HTTP, making the functions of the device more accessible for users.

Relationship between Shifu, APP and device:
![screenshot_20220627_211834(1).jpg](WEBRESOURCEbe1c96676bb27b81dec2bba984e07c75)
**Communication** **between** **Shifu** **and** **devices:**  
Shifu is constantly improving campatibility with new protocols and drivers. For the current list of compatibility, see [Protocols](https://cn.docs.shifu.run/zh/home/protocols) and [Drivers](https://cn.docs.shifu.run/zh/home/drivers).

**Communication between Shifu and APPs:**
Shifu is constantly adding new protocols for its communication with user-developed applications. Currently the HTTP communication between Shifu and applications is supported.

## Functions
As an IoT device management and development framework, Shifu provides the following functions: 
- Getting data from the device
- Sending commands to the device
- Various application development tools (finite state machines, etc.)
