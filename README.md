
## Real-Time Color Drawing App


This is a simple real-time color drawing application using OpenCV and Python. With this application, you can draw in various colors using your webcam. It detects the color of an object and allows you to draw with that color on the canvas.

## Features

- ChromaDraw - Color Drawing Application

An interactive drawing application that lets you paint in the air using colored objects detected by your webcam. Simply move a colored object (like a marker cap) in front of your camera to start drawing!

## Features

 Real-time color detection and tracking
 Multiple color options (Blue, Green, Red, Yellow)
 Clear canvas functionality
 Adjustable color detection parameters
 Real-time preview of tracking and drawing

## Requirements

- Python 3.6 or higher
- OpenCV (cv2)
- NumPy

## Installation

1. Clone this repository or download the source code.
2. Install the required packages using pip:

```bash
pip install opencv-python numpy
```

## Quick Start

1. Run the application:

```bash
python main.py
```

2. The application will open two windows:
   - **Tracking**: Shows your webcam feed with color tracking
   - **Paint**: Shows your drawing canvas

3. **Color Selection**:
   - Move the colored object to the top section of the Tracking window
   - Click on the colored buttons to select different colors:
     -  **BLUE** - First color button
     -  **GREEN** - Second color button
     -  **RED** - Third color button
     -  **YELLOW** - Fourth color button
     -  **CLEAR ALL** - Clear the canvas

4. **Adjusting Color Detection**:
   - Use the "Color detectors" window to adjust the HSV values for better color tracking
   - Upper/Lower Hue: Adjust the color range
   - Upper/Lower Saturation: Adjust the color intensity
   - Upper/Lower Value: Adjust the brightness

## Tips for Better Tracking

- Use a brightly colored object (like a marker cap)
- Ensure good lighting in your environment
- Adjust the HSV values if the tracking isn't accurate
- Keep your hand steady while drawing for smoother lines

## Quitting the Application

- Press 'q' on your keyboard or close the windows to exit

## Note

- The application works best with solid, bright colors
- Performance may vary based on your webcam quality and lighting conditions
