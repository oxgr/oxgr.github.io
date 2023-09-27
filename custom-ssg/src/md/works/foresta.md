# Foresta-Inclusive Data Visualisations



#### Interactive screen-based visualisations of data retrieved from custom sensor hubs attached to trees in different locations.
- - -

## [CAFKA](https://janetingley.com/cafka)

![foresta-cafka-3](/assets/images/foresta-cafka-3.png)

Based on a previous work developed by Scott Grunerud and Marius Kintel with Jane Tingley, this piece is a port for the web as part of an online exhibition at CAFKA. A particle flowfield depicts live sensor data retrieved from a sensor hub stationed on the physical grounds of CAFKA. Alongside the visualisation is a timelapse of the previous 24 hours of the hub itself.

![foresta-cafka-4](/assets/images/foresta-cafka-4.png)

The most interesting thing to me about porting to web will always be making sure it is accessible to a diverse array of devices. My grandmother still uses an Android from 2010 and I want her to still be able to experience her grandkid's computer things. To do this, I built a dynamic calibration algorithm that ensures a steady framerate by balancing hardware capabilities, computation complexity, HTML Canvas drawing techniques.

See the work [here](https://janetingley.com/cafka).

## Ongoing work
![foresta-rings-2](/assets/images/foresta-rings-2.png)


Developing on the theme of a flowfield, the visualisation was iterated into 3D. With the extra dimension, it was now possible to convey sensor data over the element of time.  

A series of 24 tree rings depict the previous 24 hours of data. Each individual ring is comprised of a particle flowfield which responds to data received in the ring's hour of the day. Since tree rings are most notably affected by changes in water intake and heat, related sensors such as humidity and light are translated.

*Developed alongside Jane Tingley with guidance of Marius Kintel.*

==![foresta-rings-3](/assets/images/foresta-rings-3.png)


![foresta-rings-1](/assets/images/foresta-rings-1.png)==

