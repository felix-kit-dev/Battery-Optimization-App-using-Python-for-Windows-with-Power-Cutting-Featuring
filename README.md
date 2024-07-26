# Battery-Optimization-App-using-Python-for-Windows-with-Power-Cutting-Feature

# Battery Optimization App

## Overview

This Battery Optimization App is designed for Windows 10 and Windows 11. It displays battery charging progress, remaining charge, and provides an option to cut power once the laptop’s battery is fully charged. The app also sends notifications when the battery is low and when it's fully charged.

## Features

- Display battery charging progress and remaining charge.
- Option to cut power when the battery is fully charged.
- Notifications when the battery is low or fully charged.

## Requirements

- **Python 3.x**: Ensure you have Python 3.x installed on your system.
- **Python Packages**:
  - `pywin32` for interacting with Windows APIs.
  - `tkinter` for the graphical user interface (GUI).

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/battery-optimization-app.git
   cd battery-optimization-app

## Create a Virtual Environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## Install Dependencies:

pip install pywin32


# Building and Running the Application
## Save the Script:

Save the provided Python script to a file named battery_optimization_app.py.

## Run the Application:

python battery_optimization_app.py

This will start the application and display the GUI.

## How It Works
- **Battery Status Check:** The app periodically checks the battery status using Windows APIs.
- **GUI:** The tkinter library is used to create the graphical interface.
- **Notifications:** The app uses Windows message boxes to display notifications.
- **Power Management:** The power-cutting feature is simulated for demonstration purposes. Actual implementation may require specific hardware support.
  
## Notes
The power-cutting functionality is simulated and may not work on all hardware. For real implementations, consult hardware documentation or drivers.
The app updates battery status every 60 seconds. Adjust this interval in the self.root.after method if needed.

## Contributing
Feel free to submit issues or pull requests. If you want to contribute, please make sure your code adheres to the existing style and includes tests if applicable.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
