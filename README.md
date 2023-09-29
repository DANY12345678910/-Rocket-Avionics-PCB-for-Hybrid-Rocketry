# -Rocket-Avionics-for-Hybrid-Rocketry
In the exciting world of aerospace engineering, we've taken on a thrilling project at our engineering school ESTACA: building a hybrid rocket with roll control. At the heart of this rocket, there's a critical piece of technology called the avionics system. In this article, we'll break down the avionics system for you, explaining its key components, design choices, and how it helps make our rocket mission a reality. The rockets name is the Estaca Space Launcher (ESL), It is the most ambitious rocketry project from our aerospace student association Estaca Space Odyssey (ESO), it will seek to reach 30Km of altitude using a hybrid (solid and liquid) student made rocket engine. The Rocket participating in the International C'space event, it will need to carry an experiment, we choose to carry a cold gaz thruster roll stabilizer.


<img width="197" alt="Photo2" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/00f8ccb5-fc93-4943-8d02-5267ddbf0906">

<img width="229" alt="photo4" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/1d254c2c-96f8-4f6d-ad88-f90bedf0ae48">

<img width="331" alt="Photo3" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/ad1ce7df-8c7b-4233-8fcc-68da5664fbbc">



# Meet the Components

    Before we get into the details, let's get acquainted with the important players in our avionics setup:

    Teensy 4.1: This small but mighty board serves as the brain of our rocket. It's responsible for processing data and making decisions during the flight.

    GPS: Neo M9N: Imagine it as our rocket's GPS navigator, ensuring we stay on the right path and gather important location data.

    IMUS: BMI088: These sensors help us keep track of our rocket's orientation and movement, crucial for stability.

    High G Accelerometer: Think of this as our rocket's fitness tracker. It measures high-speed movements and forces.

    Barometer: BMP388: Like a weatherman for our rocket, it helps us measure altitude and atmospheric pressure.

    Current and Voltage Sensor: These keep an eye on the rocket's power consumption and health.

    Mosfets for Pyro Charges: These are our rocket's "fireworks control." They ignite pyrotechnic charges at the right moment.

    PWM Ports: These are like our rocket's digital arms, used for precise control.

    Connectors for LoRa Radio and GSM SIM 800L: They help us stay connected and send data back to Earth.

    Headers for UI Connection: These connectors allow us to communicate with and control the rocket.

    Indicators (LEDs and Buzzer): These provide visual and auditory cues about what the rocket is doing.

    USB Type B Port: A direct link to the GPS for configuration and data retrieval.

  
<img width="252" alt="photo1" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/eb17c4b3-c7de-4c98-8681-fcc4dcf78507">
<img width="254" alt="Photo9" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/7620f059-f8d2-494a-b4cb-768d0eb21dc0">

# PCB Schematics and Materials List

    We believe in transparency and sharing the journey that is why we've linked the Gerber, CPL and BOM files.
    To access the Schematics and altium PCB files please send your request to this e-mail: daniel.devy@estaca.eu. 
    To help you understand our avionics system better, we've included clear pictures of our PCB design, showcasing how all these components come together on the board. 
    Additionally, we've prepared a detailed Bill of Materials (BOM) that lists all the materials used in our avionics setup. 
    This BOM serves as a valuable resource for anyone looking to replicate or understand the technology behind our rocket project. So, whether you're a fellow aerospace enthusiast or simply curious about the tech that powers rockets, these visual aids will provide you with an inside look at our avionics system's construction. 

    
<img width="604" alt="BOM1" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/3ca21cf9-272c-40f7-ba89-be9a26b964e2">


# Bringing it to Life https://jlcpcb.com/HAR


![photo11](https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/86f41a3c-8fa5-4d55-aea2-329ffe6fd5b3)


    Now that we've finalized our PCB design, it's time to bring it to life. 
    Ordering your PCBs is a straightforward process with our trusted partner, JLCPCB.
    JLCPCB, a proud sponsor of our project, is a renowned name in the field of PCB manufacturing.

    Here's how it works: You can order a minimum of 5 PCBs for an incredibly low price of just $2. 
    To start the manufacturing process, simply visit JLCPCB's website (https://jlcpcb.com/HAR) and click on 
    the "QUOTE NOW" button. 
    Then, upload the Gerber file that you generated in the previous step. 
    You can either upload the .zip file or simply drag and drop your Gerber files. 
    Once your files are uploaded, a success message will confirm that your design has been received.

    For peace of mind, you can review your PCB design using JLCPCB's Gerber viewer to ensure everything is in order.
    You'll have the opportunity to inspect both the top and bottom layers of your PCB, making sure it
    matches your specifications.

    Now, here's the best part: You can order 5 PCBs for just $2, and if this is your first order with JLCPCB, 
    you'll receive a fantastic offer of 10 PCBs for the same price of $2.
    To proceed, click on the "SAVE TO CART" button, and you're on your way to having your PCBs manufactured.

    Our experience with JLCPCB has been exceptional. 
    Within just 2 days, our PCBs were expertly manufactured and dispatched.
    Thanks to the efficient DHL delivery option, they arrived at our doorstep within a week.
    Not only were the PCBs well-packaged, but the quality also exceeded our expectations, 
    ensuring that our avionics system operates flawlessly in our rocket project.
    Go to https://jlcpcb.com/HAR , and Follow them at JLC FB & PM to get coupon: https://www.facebook.com/jlcpcb.

# The Ground Station: Staying Connected with Our Rocket

![331384431_751270403297985_6367673124233890936_n(1)](https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/b0e3a647-3929-4c33-8f04-4cdc72f8cf20)


    In any aerospace endeavor, communication is key, especially when your rocket is soaring to new heights.
    Our avionics system wouldn't be complete without a robust ground station. 
    This essential component serves as the bridge between our rocket and mission control on Earth.

    Our ground station features a high-performance Yagi antenna, carefully selected for its excellent 
    reception capabilities.
    Paired with a microcontroller (Arduino), this setup forms the backbone of our communication system. 
    The Yagi antenna allows us to maintain a strong link with the rocket even when it's at a considerable distance 
    from the launch site.

    To ensure seamless data monitoring and control, our ground station boasts a user-friendly Graphical User Interface
    (GUI) developed in Python using the customtkinter library (https://customtkinter.tomschimansky.com/). 
    This GUI provides real-time data visualization, telemetry monitoring, and the ability to send commands to the 
    rocket as needed. With this ground station, we can closely track the rocket's flight path, receive vital data, 
    and make adjustments in real-time, ensuring a successful mission from launch to recovery.
    It has also options to visualize the Kalman Filter IMU position tracking and quaternion filtering.
    

<img width="584" alt="Photo13" src="https://github.com/DANY12345678910/-Rocket-Avionics-PCB-for-Hybrid-Rocketry/assets/107304619/a6b3c4d4-2789-433f-9bf6-5ae02b7f453a">
