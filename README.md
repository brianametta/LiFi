# LiFi
Final project for my Wireless Networks course.

YouTube video explaining the project: https://www.youtube.com/watch?v=BWuD7X9XvEY

My group chose to implement Light Fidelity (or LiFi) for our final project, which is similar to WiFi but instead uses visible light as a medium. We set up two Raspberry Pis, a transmitter and a receiver. The transmitter sends a message encoded using a flashing LED, and the receiver contains a photocell that charges a capacitor. A python script tracks the time it takes for the photocell to charge, which is then converted into data against a timing sequence and threshold (20ms). This data is decoded using an algorithm that averages the time taken for the capacitor to charge and a threshhold to differentiate a 0 versus a 1. A lot of tuning had to be done to get the timing right and to successfully send data, and there were still errors. The rate of transmission was 10bps. Even though the implementation wasn't perfect, it was a great learning experience to implement a cutting edge technology.

My main role on the project was scheduling meetings and algorithm development. In addition, a lot of the project was a collaborative effort in library meetings with the team in which we discussed the code, the hardware, and our goals before the next meeting.
