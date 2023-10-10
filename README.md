# Fish Detection with ESP32-CAM and Edge Impulse

This project aims to detect Oscar fish in images using an ESP32-CAM device and the Edge Impulse platform. The detection model employed is the FOMO (Faster Objects, More Objects) MobileNetV2 0.1 provided by Edge Impulse.

## Overview

- **Project Type:** Image Classification
- **Platform:** Edge Impulse
- **Hardware:** ESP32-CAM
- **Model:** FOMO MobileNetV2 0.1

## Project Description

Oscar Fish detection in aquarium images is a valuable task in various applications, including environmental monitoring and aquaculture. This project demonstrates how to use an ESP32-CAM, an affordable and compact camera module, to capture images and send them to the Edge Impulse platform for fish detection using the FOMO MobileNetV2 0.1 model.

## Dependencies

To run this project, you'll need the following components and software:

- ESP32-CAM board
- Edge Impulse account and project set up
- Appropriate firmware for ESP32-CAM to capture and transmit images
- Edge Impulse project with the FOMO MobileNetV2 0.1 model trained for Oscar fish detection
- And of course a Oscar fish 😅

## Installation and Setup

1. Set up your ESP32-CAM with the necessary firmware to capture images and transmit them to your preferred communication method (e.g., Wi-Fi).

2. Create an Edge Impulse account and set up a new project for image classification.

3. Train the FOMO MobileNetV2 0.1 model in your Edge Impulse project for fish detection. Collect and label a dataset of fish images for training.

4. Configure your ESP32-CAM to capture images and send them to Edge Impulse for inference.

5. Implement the necessary code for the ESP32-CAM to communicate with Edge Impulse and receive classification results.

6. Once the ESP32-CAM is operational, it should send captured images to Edge Impulse, which will classify them using the FOMO MobileNetV2 0.1 model.

7. Retrieve and use the classification results to identify fish in the captured images.

## Usage

The ESP32-CAM will continuously capture and transmit images to Edge Impulse for fish detection. You can access the results from your Edge Impulse project dashboard or integrate them into other systems as needed.

## Contributing

We welcome contributions to improve and extend this project. If you have any ideas or suggestions, please open an issue or submit a pull request.

## Acknowledgments

- Edge Impulse for providing the FOMO MobileNetV2 0.1 model and platform for machine learning.
- The ESP32-CAM community for firmware and hardware support.
