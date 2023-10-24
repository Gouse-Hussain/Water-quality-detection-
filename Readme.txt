# Arduino Water Quality Detection with pH Sensor

This project enables water quality monitoring using a pH sensor and displays real-time pH values on an LCD screen. The system checks water pH levels and provides a simple water quality indication.

## Components

- Arduino board (e.g., Arduino Uno)
- pH sensor
- LCD display (16x2 or similar)
- Jumper wires

## Features

- Real-time water pH monitoring
- Visual display of pH values
- Water quality indicator (Acidic, Alkaline, or Neutral)

## Setup

1. Connect the components to your Arduino board following the wiring instructions in your Arduino sketch.

2. Upload the provided Arduino code to your board.

## Usage

1. Power on the system.

2. The LCD display shows real-time water pH information, including the pH value and a basic water quality indicator (Acidic, Alkaline, or Neutral).

## Configuration

- The code includes a `readPHValue` function that converts the analog sensor reading into pH values. You need to adjust the mapping in this function based on your specific pH sensor's calibration data.

## Dependencies

- This project uses the Arduino LiquidCrystal library to work with the LCD display. Ensure you have this library installed in your Arduino IDE.

## Authors

- [Gouse Hussian]

