# Wing Project

Drone Project 

# Drone Project

Studio - 6 Seymour Reeves-Boddy


### Problem

Drones Cost a lot of Money

Operating Costs are increadibly high

Dificult to use and training is required

###### 1

###### 2

###### 3


### Solution

Cheap and easily replacable platform

DIY and fixable by user

Minimal knowldge required

###### 1

###### 2

###### 3


##### Plan

```
My main goal for this Studio 6 project is to create a drone that is
both cheap and easy to use, for the end user.
Drones play a big part in surveying and other tasks and i want
them to be easily accessible to farmers and doc for suevrying
operations.
```
```
Currently,most drone projects are done by large scale
operations that use very large and expensive drones to complete
the task. They also require a trained operator that adds to this
cost.
```
```
Once i have a 3 d printed Drone that is cabapale of completing
tasks. I wil begin to work on devloping a Aplication that will
interface with the drone and allow the users to create waypoint
missions for the drone to follow then begin to genrate a map of
the surveyd area
```

##### Research

```
Drones Such as this one are increadibly usefull
for surveying but cost upwards of $40,000 NZD
and this inherit cost can be a big hurdle for users
and i seek to create omething that might not be
as advanced as a $40,000 drone but still give the
user what they need, that be surveying or other
required operations.
```

##### Applications

```
Ardu Pilot is the main aplication that i will be using
for testing and creating missions for the drone
it is an open source project with extensive
documentation on utilizing it to its full potential.
and it easily interfaces with GCS (Ground Control
Software)
that i hope to create
```

##### Applications

```
Open Drone Map is another key software that i am
using to facilitate my project.
It is also a very trusted open source codabaser that
allows for image stiching and creating maps with
captured images it will also interface with my
aplication allowing the users to easily see the
mapped area the drone has been,
I chose this software as it its open source and i can
build on an already devloped and tested platform,
it is also the most full featured drone mapping
solution
```

##### Applications

```
Open Drone Map Also has the WEBODM that can
be used to create a web aplication to my needs for
orgazning jobs for the images to be proccesd and
get multiple types of data from the images.
```

#### Drone

#### Software

For the matek F765-Wing it can run on

two systems Arduplane And i Nav, i

decidec on using i nav due to the fact

that ardulane is more advanced and has

the ability to use the full potential of the

controller.

But its not as simple and user friendly as

i nav and since this is a solo project i

wanted to be able to work on something

quickly and effiecetly.


#### Planning and Timeline

Finish Assembling Wing
See what Parts are required
search how to use web DO

```
1-
Drone software
running
```
10

```
Drone Flying
Demo Software
```
```
15+
Drone Working and
bench test parts
```
5-10 15+

```
New parts arrived and
tested
```
```
GPS syetm working
Radio and Video Link
```


#### I NAV and how it works

I nav is the software for the drone to run on and it is how everything is managed i will go

through how to use the sodtware and what every tab and part does for future students

working on this project.


```
Wiring diagram for the flight controller
al the port marked rx and tx correspond to
```
```
Uart ports in the software for the drone so if
the camera is on rx2 and tx2 this means it will
```
be mapped to uart 2 for all the communication

```
for the drone
same for sevros and gps etc
```

## Vtx and how it connects

```
The vtx is responsible for sending a video link to the drone.
this is sent on an analog signal to goggles followed with other information
displayed on the OSD
see the following diagrams
```


This top info screen lets you know the status

```
of all the functions on the drone
for it to arm we need all blue and green ticjs
```

This is the motor mixer tab and the servos where we control what

servo is addressed to what port


This is the ports tab as later mentioned where we connect and

associate rx2 tx 2 to uart 2 etc depending on what u are connecting

u can select and control what sensors are used,


```
This is the configuration tab where u
can see the alignment of the board as
```
well as enable gps and other functions

```
This is the receiver tab where we
can see what channels are being
sent to the flight controller via
the reciever
```



Further docs and links

https://www.opendronemap.org/webodm/

```
https://github.com/OpenDroneMap/WebODM/
https://github.com/REEVS 3 /DroneProject
```


## Mapping Software



## Mapping Software


Further docs and links

https://www.opendronemap.org/webodm/

```
https://github.com/OpenDroneMap/WebODM/
https://github.com/REEVS3/DroneProject
```

Once we have our mapping software running on a docker container

we will be able to process our images easily for example i will use a demo data set to

import


Further docs and links

https://www.opendronemap.org/webodm/

```
https://github.com/OpenDroneMap/WebODM/
https://github.com/REEVS3/DroneProject
```








## Description

DIY 3d prinmt budget drone for studio 6

![image](https://user-images.githubusercontent.com/53206563/175236682-40b29d21-5ebb-4007-8492-88a8baef9f31.png)

![image](https://user-images.githubusercontent.com/53206563/175236945-88297e97-3720-4789-bab8-07cb349bb0fe.png)
![image](https://user-images.githubusercontent.com/53206563/175236978-a134e915-d7cd-49c3-a2ea-528cb4ad279c.png)
![ima[
](https://youtu.be/i-HCuDbX8DA)ge](https://user-images.githubusercontent.com/53206563/175236993-be06bbd2-b844-4609-8e5d-a7c366986c00.png)


[
](https://youtu.be/i-HCuDbX8DA)

![image](https://user-images.githubusercontent.com/53206563/175904028-fb72b562-12e1-4d78-b1b0-6ac16648411e.png)
https://www.youtube.com/watch?time_continue=2083&v=9ZmGUxCDiU0&feature=emb_logo
![image](https://user-images.githubusercontent.com/53206563/175904112-60a85e8c-1339-4a7a-817e-7476414c6725.png)
![image](https://user-images.githubusercontent.com/53206563/175904143-533850a6-3054-4353-ae6e-f9d7f14962c6.png)
![image](https://user-images.githubusercontent.com/53206563/175904187-93869f71-ff40-44a6-b0b3-752b8543c2c0.png)
![image](https://user-images.githubusercontent.com/53206563/175904231-b1e0d19e-a76c-46d3-a6e2-eb98ac3be7df.png)
