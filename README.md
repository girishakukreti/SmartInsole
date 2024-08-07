# Smart Insole Project

## Overview

The Smart Insole project leverages pressure distribution data to revolutionize footwear design and selection. This project integrates both hardware and software components to analyze foot pressure patterns during various activities, providing solutions for optimized footwear selection and customization.

## Features

1. **Smart Filter for Footwear Selection:**
   - Analyzes pressure distribution data to recommend suitable footwear for specific activities.
   - Utilizes a web-based platform to filter and select shoes based on pressure data.

2. **Custom Shoes:**
   - Offers personalized footwear solutions based on individual pressure distribution profiles.
   - Aims to enhance performance, comfort, and injury prevention, especially for athletes and individuals with specific foot-related conditions.

## Hardware Components

- **FSR Pressure Sensors:** Embedded in silicon insoles to capture pressure data from different foot regions.
- **BOLT Wi-Fi Module:** Reads and transmits data from the sensors for visualization.
- **Silicon Insole:** Houses FSR sensors and minimizes discomfort.

### Circuit Setup

- FSR sensors connect to an analog-to-digital converter (ADC) through a voltage divider circuit for accurate data acquisition.

## Software Components

1. **Smart Insole:**
   - **Sensor Configuration:** Configures sensors within the insoles to collect real-time pressure data.
   - **Data Collection:** Captures and processes pressure readings from foot regions.
   - **Data Visualization:** Converts sensor data into live graphs and heat maps using the BOLT IoT platform.

2. **Doctor Foot (Web-Based Platform):**
   - Manages and retrieves footwear data based on pressure distribution profiles.
   - Developed using PHP and SQL for database management.
   - Features an interactive user interface for selecting suitable footwear.

### Database Structure

- **Shoes Table:** Stores shoe details, images, and purchase links.
- **Region Table:** Contains pressure distribution data and related images.
- **Size Table:** Links shoe sizes with pressure data.

## Setup Instructions

1. **Hardware Setup:**
   - Connect FSR sensors to the BOLT Wi-Fi module and silicon insole according to the provided circuit diagram.

2. **Software Setup:**
   - **Backend:** Set up the PHP and SQL database to manage and store footwear data.
   - **Frontend:** Create the user interface using HTML, connecting it to the backend with PHP and SQL queries.

3. **Running the Application:**
   - Deploy the web-based platform on a server.
   - Test the real-time data visualization and footwear recommendations functionality.

## Future Improvements

- **Machine Learning Integration:** Enhance recommendation accuracy with advanced algorithms.
- **Additional Sensors:** Use more sensors for comprehensive pressure analysis.
- **Gait Analysis:** Improve recommendations by analyzing walking patterns.
- **Manufacturer Collaboration:** Partner with footwear manufacturers for custom production.
- **Real-Time Feedback:** Implement mechanisms for immediate footwear adjustments.



![setup](https://github.com/user-attachments/assets/7876271d-338b-4406-b8ca-56dee24386df)
