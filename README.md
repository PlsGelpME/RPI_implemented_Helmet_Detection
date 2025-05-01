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

  3. \


  4. GNU Nano \
       Follow rc.local method to run the python script on boot. 

# Instructions for the people who want to use this
  Step 1: Setup a Raspi \
  Step 2: Setup the Raspi Camera and test the camera \
  Step 3: In your main computer or PC, run the training.py file from the other repository (mentioned in the references section) \
  Step 4: Test the main.py on your PC using the test video. \
  Step 5: Copy the main.py, image_to_text.py and the best.pt (pretrained model file) to your Raspi. \
  Step 6: Make necessary changes to main.py, image_to_text.py (changes such as .pt file location, video source to live camera feed). \
  Step 7: Run the main.py on raspi using the camera feed. \
  Step 8: Follow the instructions in the website (link in references section) to make the python code run on startup. \
  
# References

https://github.com/aneesarom/Real-Time-Detection-of-Helmet-Violations-and-Capturing-Bike-Numbers-from-Number-Plates \
https://www.dexterindustries.com/howto/run-a-program-on-your-raspberry-pi-at-startup
