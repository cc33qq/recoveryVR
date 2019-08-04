# Statement of work - Project name: RecoveryVR
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



The front end needs to send messages to Unity that are used to queue up/change scenes.
We will use this Unity plugin to handle the communication https://assetstore.unity.com/packages/tools/network/best-http-10872
This plugin utilizes standard RESTful service requests such as GET requests and POST requests and has extensive documentation. These requests would then be translated from JSON into something we can use in Unity and put into effect from there. 
There will need to be a login for the doctor and some kind of token/identifier process built in at this stage. The users of the front end (doctors) logging into the UI to access a device mac address (or some other unique identifier) which is associated with their profile, and therefore have the rights to control it.
