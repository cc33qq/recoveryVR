# Statement of work - RecoveryVR
## Purpose
RecoveryVR is a start-up business operating out of the Griffin Accelerator. Our work on increasing the functionality of the system will make a huge difference not only to the success of the company but also to the ability of a doctor to help their patient and increase recovery rates from neurological injury. 

RecoveryVR is designed to help stroke survivors but our initial market research shows that this system will be hugely beneficial to people with complex regional pain, parkinsons, multiple sclerosis, spinal cord injury and motor neuron disease. Plus assist with fall prevention and phantom limbs. 
## Scope
We are going to set up a RESTful web server that can send and receive data to a program built in Unity operating on a Oculus Quest VR HMD, and a separate front-end web UI, so that a doctor can use the UI to control the Unity program inside the HMD remotely. The VR program will also be collecting movement data on the patient and we need that data to be stored against the patient’s profile and displayed to the doctor in simple metrics and a graphical representation. In time this system will be used in hospitals and the front end UI will need to be connected to multiple headsets at once using a token system.

- VR App Control - Build server with a front end UI
- Profile Data - Build Database of Users
- Metrics - Graphical display of recovery
- Tokens - Multiple connections
## Location
The project development would be taken place both in the office and remotely.

Office address: 1 Moore St, Level 5, Canberra Innovation Network
## Tasks
### VR App Control - Build server with a front end UI (for doctors)
Example first stage front end UI - 
![image](https://github.com/cc33qq/recoveryVR/blob/master/pic/pic1.PNG)

The front end needs to send messages to Unity that are used to queue up/change scenes.

We will use this Unity plugin to handle the communication https://assetstore.unity.com/packages/tools/network/best-http-10872

This plugin utilizes standard RESTful service requests such as GET requests and POST requests and has extensive documentation. These requests would then be translated from JSON into something we can use in Unity and put into effect from there. 

There will need to be a login for the doctor and some kind of token/identifier process built in at this stage. The users of the front end (doctors) logging into the UI to access a device mac address (or some other unique identifier) which is associated with their profile, and therefore have the rights to control it.
### Profile Data - Build Database of Users (patients)
- Each patient will need to input their name to create a user profile on the server that the unity program and the UI can access and update with personal information.
- Each profile has static data associated with it i.e. username, height & arm length.
- Each session gives data to the user profile that is stored on the server that is used to map progress and recovery over time.
### Metrics - Graphical display of recovery
Example addition to UI - 
![image](https://github.com/cc33qq/recoveryVR/blob/master/pic/pic2.PNG)

For the data points of Reach, Sit Stand, Rotation, Wrist and Twist that will be updated in the user profile once per session, we need the values to be plotted visually on a graph on the UI. This is for the supervising user to view and compare session data of the user to help gauge progress and recovery over time. 
### Tokens - Multiple connections
Example Addition to UI
![image](https://github.com/cc33qq/recoveryVR/blob/master/pic/pic3.PNG)

If the UI on the tablet or web needed to operate multiple headsets we would need a token system that allowed for that. As previously mentioned it would likely just be grabbing a part of MAC address or other unique identifier we can find to differentiate between each separate headset that is connecting to the server.
## Deliverables schedule
As we are using Agile development method, we will have a MVP to be delivered at Week 7 of semester 2, 2019.

The MVP contains: 
- A server built
- The server can receive json package from VR equipment successfully
- The data received can be shown on the server
## Period
The project will be finished within 2 semesters, and the end date would be officially 30th of July, 2020. After that date, the project would be terminated and hand over to the client.
## Acceptance
All the tasks have been done.

