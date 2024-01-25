# Simulink Pacemaker Controller


This project focuses on the development of a Simulink-based pacemaker model to regulate the activity of four heart chambers on an NXP FRDM-K64F microcontroller. The pacemaker model implements eight distinct modes of autonomous heartbeat functionality.

Additionally, a Python-based Graphical User Interface (GUI) serves as a Device Configuration Manager (DCM). This GUI allows users to manipulate Simulink parameters of the pacemaker and monitor heart chambers through an electrogram display. Communication with the microcontroller is established serially via UART.

## Key Features

- **Autonomous Heartbeat Functionality:** The Simulink-based pacemaker model implements eight modes to autonomously regulate the activity of four heart chambers on the NXP FRDM-K64F microcontroller.

- **DCM GUI:** A Python-based GUI functions as a Device Configuration Manager, providing users with the ability to manipulate Simulink parameters of the pacemaker.

- **Electrogram Display:** The GUI includes an electrogram display for monitoring heart chambers, enhancing the user's understanding of the pacemaker's behavior.

- **Serial Communication:** The pacemaker model communicates with the microcontroller serially via UART, facilitating the exchange of information between the Simulink model and the hardware.

## Project Components

- **Simulink Pacemaker Model:** The core of the project, implemented using Simulink, regulates the heartbeat modes and activities of the heart chambers.

- **Python GUI (DCM):** The GUI, developed in Python, serves as a Device Configuration Manager, allowing users to interact with and modify Simulink parameters.

- **UART Communication:** Serial communication is established between the Simulink model and the NXP FRDM-K64F microcontroller using UART.

## Project Workflow

1. **Pacemaker Model Implementation:** Develop the Simulink-based pacemaker model with eight distinct modes for regulating heart chambers.

2. **DCM GUI Development:** Design and implement the Python-based GUI for users to configure pacemaker parameters and monitor heart chambers.

3. **UART Communication Setup:** Establish serial communication between the Simulink model and the NXP FRDM-K64F microcontroller.

4. **Hardware Integration:** Deploy the pacemaker model on the microcontroller, ensuring seamless communication with the DCM GUI.

5. **User Interaction:** Users can interact with the DCM GUI to manipulate pacemaker parameters and visualize heart chamber activities through the electrogram display.

## Dependencies

- **Simulink:** Developed using MathWorks Simulink for the pacemaker model.

- **Python:** The GUI is implemented using Python for the Device Configuration Manager.

- **UART:** Serial communication is utilized for communication between the Simulink model and the NXP FRDM-K64F microcontroller.

## Getting Started

1. Clone the repository: `git clone [repository-url]`

2. Open the Simulink model using MathWorks Simulink.

3. Run the Python GUI by executing: `python pacemaker_gui.py`

4. Connect the NXP FRDM-K64F microcontroller and ensure UART communication is established.

5. Interact with the GUI to configure pacemaker parameters and monitor heart chambers.

## Acknowledgments

This project combines Simulink modeling, Python GUI development, and microcontroller programming to create an integrated system for regulating heart chambers and providing a user-friendly interface for configuration.
