# 🎙️ **Voice Driven Motor Controller**

Welcome to the Voice Driven Motor Controller project repository! 🚀

## **About ℹ️**

This project aims to create a motor controller that can be controlled using voice commands. It utilizes Arduino and voice recognition technology to achieve this functionality.

## **Description 📝**

This Arduino code allows you to control motor devices via voice commands using the SinricPro library. The code sets up Wi-Fi connectivity, initializes relay pins, and establishes communication with the SinricPro cloud service.

## **Features ✨**

- Control multiple devices using voice commands.
- Utilizes the SinricPro library for seamless integration with voice assistants.
- Supports Wi-Fi connectivity for remote control.

## **Getting Started 🚀**

To get started with this project:

1. Upload the provided Arduino code to your Arduino board.
2. Configure the Wi-Fi credentials and SinricPro API keys in the code.
3. Connect the necessary components as per the circuit diagram.
4. Power on the system and initiate voice commands to control the motor(s).

## **Configuration ⚙️**

- `WIFI_SSID` and `WIFI_PASS`: Set your Wi-Fi credentials.
- `APP_KEY` and `APP_SECRET`: Obtain API keys from the SinricPro website.
- Configure device IDs and GPIO pins for relays and switches according to your setup.

## **Usage 🖥️**

Once configured, the motor controller can be controlled using voice commands through a compatible voice assistant linked to the SinricPro service.

## **Contributing 🤝**

Contributions to this project are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

### Things to note while implimenting this project :

1. Wi-Fi Credentials and API Keys: Make sure to replace "YOUR_WIFI_SSID", "YOUR_WIFI_PASS", "de0bxxxx-1x3x-4x3x-ax2x-5dabxxxxxxxx", and "5f36xxxx-x3x7-4x3x-xexe-e86724a9xxxx-4c4axxxx-3x3x-x5xe-x9x3-333d65xxxxxx" with your actual Wi-Fi SSID, password, SinricPro API key, and secret respectively.

2. Device IDs: Replace "SWITCH_ID_NO_1_HERE", "SWITCH_ID_NO_2_HERE", "SWITCH_ID_NO_3_HERE", and "SWITCH_ID_NO_4_HERE" with the actual IDs of your switches.

3. GPIO Pins: Make sure the GPIO pins specified for relays and switches match your hardware setup. You can adjust the pin numbers as needed.

4. Commented Sections: If you want to enable additional devices beyond the first one, uncomment the lines for device IDs, relay pins, and switch pins accordingly.

5. Tactile Button: If you're using toggle switches instead of tactile buttons, comment out the #define TACTILE_BUTTON 1 line.

6. Debounce Time: You can adjust the debounce time (#define DEBOUNCE_TIME 250) as needed to handle switch bouncing more effectively.

7. Functionality: Ensure that any edits made to the code do not alter the core functionality, such as handling power state changes and communicating with the SinricPro service.


## For ANY doubts feel free to contact me chetanjain281@gmail.com
