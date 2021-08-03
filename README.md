# Curator Drone

## Final video
[![self-walking_robot](http://img.youtube.com/vi/J8ql7rU-jMM/0.jpg)](https://www.youtube.com/watch?v=J8ql7rU-jMM)

## Procedure

### Tracking

* Used Yolo framework to recognize people.
* Using red box and simple algorithm, I was able to track people.

  
![ex_screenshot1](./img/1.png)

### AR-Marker

* Used AR-Marker to recognize the paintings.
* Each painting is designated to certain AR-Marker.

![ex_screenshot2](./img/2.png)


### crawling (This wasn't my part of the project.)

* When the painting is recognized, drone automatically searches for the painting in Wikipedia.
* Then it sends an information and its audio file via email to the user.

![ex_screenshot3](./img/3.png)


## Limitations
* I wasn't able to make drone rotate around the user, since the yolo-tiny wasn't accurate enough.
* Drone and laptop have to be nearby, since they are connected by wifi. So I need to find a new way to connect the drone and server.
* When drone searches for information drone stops until the searching is finished. Which may occur problem.


## What I've learned
* How to use Yolo framework in embedded system.
* How to cooperate with other developers.
* How to combine others' work and make it work!





