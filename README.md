<p align="center"><img src="https://i.imgur.com/A6bWGFl.gif"/></p>

# Greetings, Traveller! Welcome to My Cozy Internet Corner!

## Introduction 

I am Ahmed, nice to meet you!

- I am an ECE graduate from the Faculty of Engineering Alexandria University, Egypt (Class 2024)
- I had finished Information Technology Institute (ITI)'s Professional Training Program Embedded Systems Track. 
- You will find repos in my profile ranging from cheatsheets, all the way to large-scale embedded projects.
- Currently, I work as a Software Engineer @ CairoMotive.

## ITI Graduation Project
<p align="center">
  <a href="https://github.com/Coda-ITI">
    <img src="./coda.png" width="350"/>
  </a>
</p>

### About Coda
Coda is a multi-ECU system featuring two screens—for both Instrument Cluster & IVI, road sign detection, a voice assistant, safe distance detection, and intuitive UI that elevates a driver’s experience to a new level. Coda comprises of 4 main nodes:
* Baremetal Node: responsible for direct hardware interfacing for determining doors states, car speed and rpm, and ultrasonic sensors for safe-distance. These readings are sent via CAN. This ECU is based on the NXP S32K148-Q176.
* Detection Node: responsible for detecting road signs from a predefined selection while on the road. The detection model is a YOLOv8 nano model that was trained on a set of road signs. The detected signs are published to the Cluster Node via a CommonAPI service based on vSOME/IP. This ECU is based on NVIDIA Jetson Nano Developer's Kit running a custom Yocto distro.
* Cluster Node: responsible for running the Instrument Cluster app on the first screen and routing CAN traffic towards the IVI Node. The Instrument Cluster app is built using Qt6 framework. The app displays some of the incoming data from CAN and forwards the rest to the IVI Node via a CommonAPI service based on vSOME/IP. This ECU is based on Raspberry Pi 5 16GB running a custom Yocto distro.
* IVI Node: responsible for running the IVI app on the second screen in addition to a Voice Assistant app complying with Google's guidelines for development. The incoming data from Cluster Node is received via a CommonAPI service based on vSOME/IP; this service transfers the readings to the application layer through an AIDL contract that is used for registering callbacks in the application layer. Coda's Voice Assistant features wake word detection and multiply commands.

## Profile Stats 

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=AhmedAlyElGhannam&theme=dark&hide_border=true&include_all_commits=true&count_private=true" alt="Profile Stats" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhmedAlyElGhannam&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />
    </td>
  </tr>
</table>
