
#### Automated Waste Segregation and Mananagement System 




## Tech Stack
- Deep Multiple Instance Learning 
- 3D ResNets for Object Recognition
- python Backend
- Arduino 




# About Smart-BIN
 The world is sinking into the sea of waste. Every narrow nooks and corner of the streets are being piled up with waste.Currently, there is no system of automatic waste segregation or collection implemented at the commercial level.Also, no such system exits whose purpose is to collect, segregate, manage waste as well as monitoring the whole process with minimum space and that is capable of being implemented in the general public. 
 
 **Smart-BIN**  is capable of doing all the above mentioned tasks. Our invention is an IoT based automatic waste segregation and management system. This is specifically a waste collection and management bin which is capable of automatically collecting and segregating up to various different types of waste namely organic, cloth, plastic, e-waste, metallic, glass and paper. The bin automatically segregates the waste put into it. 
 
The bin also measures the live status of the compartments,when the bin is full it deposits the waste in the underneath vaccum waste pipelines. The consumer using an application can get reward points by dumping waste into our bin which can be redeemed for public transport tor any other commercial purpose. Also, he is able to navigate to the nearest bin by using this application and also view the status of the individual compartments. 
 
**Smart-BIN** is fully automated and hence the user doesn’t need to worry about the selection of the type of waste that he puts into the bin. The bin **automatically** detects the type of waste and puts it into the corresponding compartment. This is done using artificial intelligence with an accuracy of **90.34%**. There is also a proper monitoring and reporting system within the app.

# WORKING METHOD

As mentioned above, this is an IoT based automatic waste segregation, collection and, management system in the form of a smart bin. 
+ The bin has 6 hexagonal shaped individual modular compartments in which 6 different types of waste can be put ergonomically. 
+ The compartments are attached to a shaft which is in turn attached to a Stepper motor. 
+ When the user comes to dumps the waste, it activates the sensing module consisting of a camera, ultrasonic, capacitive, inductive and IR sensor and the sensors detect the type of waste using a novel algorithm using a combination of image recognition using artificial intelligence and the array of physical sensors.
+ Then the system turns the detected category bin to the opening and the waste is dumped in that compartment. 
+ After the waste is dumped the bin asks if the user wants a reward. 
+ User can claim the reward in terms of reward points which are calculated based on the amount and type of waste dumped by the user.After this an array of ultrasonic sensors located over each compartment measures the levels of each bin . 
+ The users are provided with an RFID card which they can scan over the RFID reader placed on the bin. The system then measures the level and type of waste he has put and calculates the reward points required to give out. The system gets the users name, collected points from the online server-side database and updates it with the current points he has earned. After this process is completed the GPRS module collects the location of the bins along with the data from the ultrasonic sensor and updates it to the server. 
+ The whole bin is powered by solar panels and a battery which gets recharged by these solar panels. When there more power generated than required, the system shifts the power to the grid. 
+ When a compartment of the bin is full it dumps the waste in the underlying vaccum tube network which will trnsport the waste to the appropriate waste treatment plan via a pipeline network that runs all over the city.
