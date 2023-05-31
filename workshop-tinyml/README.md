# TinyML Workshop — from the IoT to the Cloud

*This is a "canned" workshop that utilizes existing resources from Blues, Datacake, and Edge Impulse to build a compelling end-to-end ML + IoT + Cloud workshop experience.*

- [Topics Covered](#topics-covered)
- [Hardware Requirements](#hardware-requirements)
- [Software Installations](#software-installations)
- [Workshop Agenda](#workshop-agenda)

## Topics Covered

1. Creating a TinyML model with Edge Impulse.
1. Building a custom cloud-based dashboard with Datacake.
1. Connecting to the cloud with Cellular IoT from Blues.
1. Wiring up all of the above with Arduino on an STM32 host MCU.

The goal is for participants to walk away from this workshop with fundamental knowledge of TinyML, Cellular IoT, cloud dashboards, and a practical understanding of how to build their own connected ML/IoT project.

## Hardware Requirements

- Blues Starter Kit for [North America](https://shop.blues.io/products/blues-starter-kit-for-north-america) or [EMEA](https://shop.blues.io/products/blues-starter-kit-for-emea)
- [STLINK-V3MINI](https://shop.blues.io/collections/accessories/products/stlink-v3mini) (SWD Programmer & Debugger)
- [Adafruit LIS3DH Triple-Axis Accelerometer](https://www.adafruit.com/product/2809)
- Qwiic Cable ([example](https://shop.blues.io/collections/accessories/products/male-to-male-qwiic-connector-cable))
- Two Micro USB cables (e.g. [USB-A to Micro USB](https://www.adafruit.com/product/2185) or [USB-C to Micro USB](https://www.adafruit.com/product/3878) depending on your computer).
  - Charge-only Micro USB cables will NOT work!

> Be sure to check country compatibility for the [North America](https://dev.blues.io/hardware/notecard-datasheet/note-wbna-500/#cellular-service) or [EMEA](https://dev.blues.io/hardware/notecard-datasheet/note-wbex-500/#cellular-service) starter kit! The Wi-Fi Notecard is included in the starter kit as a backup.

## Software Installations

Attendees only need some very basic knowledge of Arduino development and understanding of 101-level C coding concepts. Some (free) software installations are required:

- [Visual Studio Code](https://code.visualstudio.com/)
- [PlatformIO Extension for VS Code](https://platformio.org/install/ide?install=vscode)
- [Install the Edge Impulse CLI](https://docs.edgeimpulse.com/docs/edge-impulse-cli/cli-installation)
- Create a free [Blues Notehub account](https://notehub.io/)
- Create a free [Edge Impulse Studio account](https://studio.edgeimpulse.com/signup)
- Create a free [Datacake account](https://app.datacake.de/signup)

## Workshop Agenda

All of the resources needed to present the workshop are available in the embedded links below.

- Welcome and Introductions [10 mins]
- Introduce the Blues Hardware [10 mins]
- **Hands-on:** [Blues Swan Quickstart](https://dev.blues.io/quickstart/swan-quickstart/) [30 mins]
- Slides: [Cellular IoT with Blues](https://github.com/blues/blues-amplifiers/tree/main/presentation) [10 mins]
- **Hands-on:** [Notecard + Notecarrier Standalone Quickstart](https://dev.blues.io/quickstart/notecard-quickstart/notecard-and-notecarrier-f/) [30 mins]
- **Hands-on:** [Sensor Data Tutorial](https://dev.blues.io/guides-and-tutorials/collecting-sensor-data/notecarrier-f/blues-wireless-swan/c-cpp-arduino-wiring/) [30 mins]
- Slides: Introduction to Datacake [10 mins]
- **Hands-on:** [Route Sensor Data from Notecard/Notehub to Datacake](https://dev.blues.io/guides-and-tutorials/routing-data-to-cloud/datacake/) [30 mins]
- Slides: Introduction to Machine Learning and Edge Impulse [10 mins]
- **Hands-on:** [Create a TinyML Model with Sensor Data](https://dev.blues.io/guides-and-tutorials/building-edge-ml-applications/blues-wireless-swan/) [45 mins]
- **Hands-on:** [Visualizing Generated Inferences in Datacake](https://dev.blues.io/guides-and-tutorials/building-edge-ml-applications/blues-wireless-swan/#sending-inference-data-to-the-cloud-with-the-notecard) [30 mins]
