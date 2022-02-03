# MakeHarvard-HapPI
A device which can express the emotions of a plant
Project hapPI
Inspiration
When one of our teammates forgot to water his plants and saw them drying out because of his negligence and he came up with an idea for a smart plant. We know plants are living creatures, they are born and they grow just like human beings do. So doesn’t it seem unfair for them not to be able to express their emotions?

What it does
hapPI (we make the plants happy using a Raspberry PI) is an IoT based device that measures various parameters such as soil moisture content, humidity, and temperature level and compares them to ideal values to decide if our plant is happy or upset! We display vital information such as the temperature, humidity, and soil moisture levels on the hapPI web app.

How we built it
For our hardware, we are using a DHT11(temperature and humidity sensor) and a Moisture sensor. The values from the sensors are being processed using PI 4 and ARDUINO UNO. All the data is processed on Node-red and accordingly, the emotions(happiness) of the plant are displayed to the user on the web app and through the led.

Challenges we ran into
The global pandemic seemed to be the biggest challenge while making the project because of which, time seemed even more limited since only one of us could work on the hardware aspect. On technical grounds, the biggest challenge was to set-up the communication between the various elements of the project such as the sensors, Raspberry PI 4, ARDUINO UNO, and the software aspect comprising our web app.

Accomplishments that we're proud of
We worked as a team even while we were struggling and were able to prepare a proper working model of hapPI. We were successfully able to make all the elements of hardware and software communicate and last but not least we learned a lot through the process.

What we learned
Time management and resource management were two very important things that we learned throughout this process. But the most important one has to be communication. Even though it felt awkward asking for help from our mentors, due to this virtual mode, it was probably the most important part of the process.

What's next for hapPI
We will implement a chatbot that would be able to update the user about the status of the plant. An option to water the plants through the app will also be implemented if the user is not able to reach his plants in time. The user will also be able to request updates whenever he feels so. We plan on implementing an ML-based model to identify exactly which type of plant is being dealt with so that the parameters can be judged accordingly to sense the emotion of the plant. We have also planned to move from a web app to a complete UI/UX based android app which would be working on the google firebase data.

Design of the mobile app:
![image](https://user-images.githubusercontent.com/55589910/152401016-aa04b5e4-0e85-426e-9d26-21b619aa426a.png)

https://www.figma.com/file/AG28B2XVUcUPH9Psu2onsM/Make-Harvard-Project-HapPI?node-id=0%3A1

