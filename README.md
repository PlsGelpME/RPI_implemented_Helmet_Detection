# Aim
  To develop an intelligent helmet detection system that identifies two-wheeler riders without helmets and reports violations to a connected system using IoT-based communication.

# Objective
  *To design a real-time monitoring system that captures video of two-wheeler riders. \
  *To extract and transmit violator details to an external system for enforcement. \
  *To create a scalable and cost-effective solution for automated traffic monitoring.

# Abstract
  Road safety is a major concern, especially for two-wheeler riders, where helmets play a crucial role in preventing injuries. \
  This project focuses on an automated helmet detection system that monitors traffic in real-time, identifies riders without helmets, and reports violations to a central system. \
  The system consists of a camera unit, a processing unit, and an IoT-based communication setup to transmit violation details. \
  By leveraging computer vision and AI, it ensures efficient and automated enforcement, reducing the need for manual intervention. \
  The solution is designed to be scalable, adaptable, and suitable for smart traffic management systems, making it a valuable tool for improving road safety compliance.

# Implementation
  The detection model is sourced from this github repository \
  **https://github.com/aneesarom/Real-Time-Detection-of-Helmet-Violations-and-Capturing-Bike-Numbers-from-Number-Plates**

  The code in this repository includes
  1. main.py \
       It runs the helmet detection model and the number plate recognition model. 

  2. image_to_text.py \
       It runs the number plate text recognition model.

  3. GNU Nano \
       Follow rc.local method to run the python script on boot. 

# References

https://github.com/aneesarom/Real-Time-Detection-of-Helmet-Violations-and-Capturing-Bike-Numbers-from-Number-Plates \
https://www.dexterindustries.com/howto/run-a-program-on-your-raspberry-pi-at-startup
