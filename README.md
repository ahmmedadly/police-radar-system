## Police Radar Prototype - Image Processing and Speed Detection

This repository contains a prototype implementation of a police radar system with a focus on image processing and speed detection. The system is designed to capture speeding vehicles, identify them through a database lookup, and automate the process of issuing speed tickets via Twilio.

### Key Features:
- **Signal Processing and Speed Detection:** Utilizing FPGA and UART communication, the system processes signals to determine vehicle speed.
- **Image Processing:** Advanced image processing techniques are implemented to enhance the accuracy of vehicle identification.
- **Database Integration:** A database is created to store information about registered vehicles, allowing for efficient lookup during speed detection.
- **Automated Speed Ticketing:** Upon detecting a speeding vehicle, the system connects to a software application, retrieves the car owner's information, and sends a speed ticket via Twilio.

### Workflow:
1. **Signal Processing:** FPGA processes incoming signals and sends vehicle speed information via UART.
2. **Image Processing:** Advanced image processing enhances the accuracy of vehicle identification.
3. **Database Lookup:** The system searches a database for information about the identified vehicle.
4. **Software Connection:** Connects to a software application containing car owner details.
5. **Twilio Integration:** Sends automated speed tickets via Twilio to the car owner's phone.

### Usage:
To use this prototype, follow the setup instructions in the provided documentation. Ensure that the necessary dependencies, such as Twilio, are configured correctly.

### Project link:
- [Link to File 1 (Large File)]([Google_Drive_Link_To_File_1](https://drive.google.com/drive/folders/1QVX5Veg-9GLaYCdetXt3PNXMIw9OtU3k?usp=sharing)https://drive.google.com/drive/folders/1QVX5Veg-9GLaYCdetXt3PNXMIw9OtU3k?usp=sharing)



