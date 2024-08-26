# Embedded-Systems

Overview
This repository contains two significant projects that I completed during my Emerging Systems Architectures and Technologies course. These projects demonstrate my ability to design and implement software that interacts with hardware components, as well as analyze and work with different hardware architectures.

1. Smart Thermostat Project
Summary:
The Smart Thermostat project involved developing a smart thermostat system capable of interfacing with various hardware architectures, including TI, Microchip, and Freescale. The thermostat reads the room temperature, compares it to the user-set temperature, and activates a heating element if needed. The thermostat also connects to the cloud via Wi-Fi for remote monitoring and control.

What Problem It Was Solving:
The project addressed the need for an efficient, user-friendly thermostat that could be integrated into a smart home environment, offering both local control and remote monitoring capabilities.

What I Did Particularly Well:
I excelled in implementing the architecture-specific peripheral drivers to ensure seamless interaction between the thermostat and the hardware components. The cloud integration was another strength, as I was able to establish a reliable Wi-Fi connection across different architectures.

Where I Could Improve:
While the project was successful, there’s room for improvement in optimizing memory usage, particularly in handling larger data sets when logging temperature over time. Additionally, more rigorous testing across different environmental conditions would enhance the robustness of the system.

Tools and Resources Added to My Support Network:
For this project, I added various architecture-specific development environments (e.g., TI Code Composer Studio) and cloud service APIs to my toolbox. Additionally, I utilized online communities and forums for troubleshooting specific hardware-related issues.

Transferable Skills:
The skills I gained in integrating hardware components and working with different architectures will be highly transferable to other embedded systems projects. My experience with cloud connectivity also provides a strong foundation for future IoT projects.

Making the Project Maintainable, Readable, and Adaptable:
I focused on writing modular code with clear documentation for each module. This structure ensures that the project is easy to maintain and update. The use of configuration files for architecture-specific settings also makes the project adaptable to future hardware changes.

2. Morse Code SOS/OK Command Project
Summary:
This project involved programming a microcontroller to send SOS and OK commands in Morse code, which could be cycled through using a push button. The output was displayed both as LED flashes and as text on an attached screen. This project focused on creating an interactive and simple interface to control the hardware components involved.

What Problem It Was Solving:
The project aimed to create a simple yet effective method of sending distress or acknowledgment signals (SOS and OK) in Morse code using minimal hardware components. This could be particularly useful in emergency communication devices.

What I Did Particularly Well:
I was able to implement a responsive button interface that allowed the user to cycle between the two Morse code signals seamlessly. The display of the Morse code output on a screen, in addition to the LED flashes, was another highlight, as it provided a clear visual representation of the signals being sent.

Where I Could Improve:
While the basic functionality was solid, the project could be enhanced by adding support for custom messages or by integrating a more advanced user interface. Additionally, improving the debouncing algorithm for the push button would make the input more reliable.

Tools and Resources Added to My Support Network:
For this project, I incorporated tools like the Arduino IDE and various libraries for handling input and output on the microcontroller. I also referred to Morse code resources and signal processing techniques to fine-tune the timing of the signals.

Transferable Skills:
This project honed my skills in low-level hardware programming and real-time signal processing, which are valuable for any project involving microcontrollers or other embedded systems. The experience with user interfaces, even on a basic level, is also transferable to more complex projects.

Making the Project Maintainable, Readable, and Adaptable:
The code was structured in a way that separated the Morse code logic from the input/output handling, making it easy to update or expand. I also used comments and modular functions to ensure that the code was understandable and could be easily modified for different signal types or additional features.
