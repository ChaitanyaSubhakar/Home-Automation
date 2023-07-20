# Home-Automation
The project revolves around the development of a smart home automation system that leverages the LPC2129 microcontroller to achieve efficient light and temperature detection and control. The system is designed to enhance user comfort, optimize energy utilization, and promote a sustainable living environment within residential spaces.

To achieve light detection, a Light Dependent Resistor (LDR) sensor is utilized, which measures the surrounding light intensity. The microcontroller's Analog-to-Digital Converter (ADC) converts the analog LDR sensor data into digital values, enabling precise measurement and control. Based on the light intensity, the system dynamically adjusts the brightness of an LED light, providing appropriate illumination in response to changing lighting conditions and saving energy when sufficient ambient light is available.

For temperature monitoring, the system incorporates a dedicated temperature sensor to measure room temperature accurately. Similar to the light sensor, the analog temperature data is converted into digital values using the ADC. When the room temperature exceeds a predefined threshold, the system activates a motor fan to facilitate cooling, maintaining a comfortable indoor environment.

To ensure efficient control and dynamic responsiveness, the project harnesses the Phase-Locked Loop (PLL) feature of the LPC2129 microcontroller. The PLL frequency is adjusted in real-time based on detected light intensity and room temperature, enabling optimized motor fan speed and LED brightness control, leading to energy conservation and enhanced user comfort.

The project showcases the successful integration of embedded systems, sensor technology, and control algorithms to create an intelligent and energy-efficient living space. The smart home automation system exemplifies the potential of IoT-based solutions in enhancing convenience, sustainability, and automation within residential environments.

The project report provides detailed insights into the design, implementation, and evaluation of the system. It outlines the hardware configurations, software algorithms, and calibration processes to ensure accurate sensor readings. Additionally, the report highlights potential future enhancements, such as mobile application integration, machine learning, and interoperability with other smart devices, to further expand the system's capabilities and user experience.

In summary, this smart home automation project offers a practical and innovative solution for improving living conditions, optimizing energy consumption, and paving the way for a smarter, more sustainable future in residential settings.
