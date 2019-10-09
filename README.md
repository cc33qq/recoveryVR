# RecoveryVR - Techlauncher Project Landing Page
![image](https://github.com/cc33qq/recoveryVR/blob/master/pic/head-pic.PNG)

## !!Our work has been transferred to Gitlab
https://gitlab.com/cc33qq/recoveryvr

------------------------------------------------------
## Overview
RecoveryVR is a start-up business operating out of the Griffin Accelerator. Our work on increasing the functionality of the system will make a huge difference not only to the success of the company but also to the ability of a doctor to help their patient and increase recovery rates from neurological injury. 

RecoveryVR is designed to help stroke survivors but our initial market research shows that this system will be hugely beneficial to people with complex regional pain, parkinsons, multiple sclerosis, spinal cord injury and motor neuron disease. Plus assist with fall prevention and phantom limbs. 
## Members
- Dian Lu u6493098 - Spoke person, Team manager, backup Implementation
- Xin Kan u6655676 - Spoke person, Testing, backup Team manager
- Ilya Sergeev u6050215- Analysis, backup Testing
- ZhiZhen Huang u6728618 - Implementation, backup Analysis
- Qiao Yu u6706067- Analysis, backup Implementation
## Main Tasks
- VR App Control - Build server with a front end UI
- Profile Data - Build Database of Users
- Metrics - Graphical display of recovery
- Tokens - Multiple connections
## Statement of Work
[Statement of Work](https://github.com/cc33qq/recoveryVR/blob/master/docs/Statement%20of%20work.md)

## Key stakeholders
### Client:
Christian Doran would like to get a RESTful web server that can send and receive data to a program built in Unity operating on a Oculus Quest VR HMD, and a separate front-end web UI, so that a doctor can use the UI to control the Unity program inside the HMD remotely.
### Deverlopers:
The development team expects to produce a product that is accpeted by the clinet, set up a web server with a front-end web UI for doctors and  patients. Using version conrtol tool (Github) to collaborate with my colleagues and record every commits to the project.
### Users:
- Doctors: Be able to see the patients’ recovery data so they can adjust trainning plan according to the progress being made.
- Patients: Safely use the system to gain better recovery from their mobile ability lost, with their informations stored securely.

## User Story
| As A       | I want to     |      So That |
-------------|---------------|--------------
|Doctor User|Get access to the system |I can login on the website by using my ID and password.|
|Doctor User|Arrange exercise for a specific patient|I can systematically guide the patien's recovery.|
|Doctor User|View my patient’s recovery progress|I can adjust trainning plan according to the progress being made.|
|Patient User |Easily play the games in the application|I can gain better recovery from mobile ability lost. |
|Patient User |Make sure all my personal informations are secured|I am not going to worry about confidential information leaks. |

## Deliverables schedule
![image](https://github.com/cc33qq/recoveryVR/blob/master/pic/time.png)
## Risk Evaluation
Recovery aims to help patients to recover from complex regional pain. We plan to design VR "games" for patients and build a web server for doctors to monitor how patients recover. During the treatment, it may rise information disclosure issues. Besides our projects may rise risks on our schedule.

Information disclosure issues are the main risks of our project. By using our products, patients' data are collected by VR devices and those data will be transmitted to a web server. Although our team tries to use the safest way to pass information, there is still possible that patients' information is leaked by hack attacks. If patients' data are disclosed, their' privacy is invaded. And the hospital would be involved in the scandal. However, the information exchange is inevitable in this project. The only thing we can do is to build the safest connection between devices and web servers.

Another risk would be our project timeline. Our project is a startup project and our members have little experience with our jobs. So our team can not give a concrete schedule of the work which means our team can not use the waterfall design method. Instead, our team would use agile development to perform the project. Our clients are actively involved in the project and the project does not have a large workload. Also, our developers are excellent. In this way, our team suits with the agile method. However, the agile method does not have a tight plan and sometimes may not able to finish the project on time. If our project fails to be finished on time, our clients would put off the publish of the product and lose money. Our team members do not demonstrate the competence which is against ACS ethics. Our team is more suitable to use agile way to do the project and we would do our best to conquer the problems of agile method.

Our project would face risks in data disclosure and project plan. They will be minimized by the efforts of the whole team.

## Constraints
The information transferred between VR equipment and our server is very critical, we have to make sure the information exchange is secure, safe, and reliable.

## Other documentations
[Feedback log](https://github.com/cc33qq/recoveryVR/blob/master/docs/Feedback_log.md)

[Decision log](https://github.com/cc33qq/recoveryVR/blob/master/docs/Decision_log.md)

[ANU Student Project Industry Client Agreement RecoveryVR](https://github.com/cc33qq/recoveryVR/blob/master/docs/ANU_Student_Project_Industry_Client_Agreement_RecoveryVR.docx)

[Ethical statement](https://github.com/cc33qq/recoveryVR/blob/master/docs/Ethical%20Review%20Application.pdf)

[Risk plan](https://github.com/cc33qq/recoveryVR/blob/master/docs/risk%20plan.xlsx)
