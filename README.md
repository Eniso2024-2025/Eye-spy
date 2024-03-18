# Spy-Eye

Spy-Eye is an intelligent system designed to detect if a driver is dizzy or not. It utilizes artificial intelligence models to analyze facial expressions and movements, determining the driver's condition. If the system detects dizziness, it triggers an alert using Raspberry Pi connected to a camera and a sound sender, notifying the appropriate authorities or individuals.

## Features

- **Dizziness Detection:** Spy-Eye employs advanced AI algorithms to analyze facial expressions and movements in real-time to detect signs of dizziness in drivers.
- **Alert System:** When dizziness is detected, the system triggers an alert using a Raspberry Pi connected to a camera and a sound sender.
- **Real-time Monitoring:** The system continuously monitors the driver's condition, providing real-time updates to ensure prompt intervention if necessary.
- **Customizable:** Spy-Eye is highly customizable, allowing users to adjust sensitivity levels and alert mechanisms based on their preferences and requirements.

## Installation

### Prerequisites

- Raspberry Pi (Model X or higher)
- Camera module compatible with Raspberry Pi
- Sound sender module compatible with Raspberry Pi
- Python 3.x

### Installation Steps

1. Clone the Spy-Eye repository to your Raspberry Pi:

   ```bash
   git clone https://github.com/Eniso2024-2025/Eye-spy.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Connect your camera and sound sender modules to the Raspberry Pi.

4. Run the Spy-Eye system:

   ```bash
   python main.py
   ```

## Usage

1. Start the Spy-Eye system by running `main.py`.
2. Ensure that the camera has a clear view of the driver's face.
3. The system will continuously analyze the driver's facial expressions and movements.
4. If dizziness is detected, an alert will be triggered through the connected sound sender module.
5. Respond promptly to the alert to ensure the safety of the driver and others on the road.

## Contributing

Contributions to Spy-Eye are welcome! If you have any ideas for improvements, feature requests, or bug reports, please open an issue or submit a pull request on GitHub.

## License

[MIT License](LICENSE)

## Acknowledgements

- Special thanks to ------ for providing the powerful AI capabilities used in this project.


## Contact

For any inquiries or support, feel free to contact the project maintainer at [chamsabdelwahed42@gmail.com].
