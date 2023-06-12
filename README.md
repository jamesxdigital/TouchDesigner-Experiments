# TouchDesigner-Experiments

## Weather Visualiser

This project demonstrates the implementation of a weather API in TouchDesigner to fetch and display current weather conditions for any location. Additionally, it showcases a generative visual effect that updates based on the current weather data.

## Project Overview

The project consists of the following key components and features:

- Weather API integration: Utilizes the Visual Crossing API for fetching current weather conditions. The API offers metered pricing and user-friendly documentation.
- Parameterized functionality: Customizable parameters for location, API key, and update frequency allow users to configure the weather data fetching process.
- JSON parsing: TouchDesigner's JSON DAT is used to parse the received weather data and extract specific elements of interest.
- Generative visual effect: A placeholder effect is created using noise and color palettes. The effect is dynamically updated based on the current weather data, with temperature as an example.
- User-friendly interface: The location, weather information, and visual effect parameters are displayed on-screen, providing a user-friendly and interactive experience.

## Requirements

To run this project, you need the following:

- TouchDesigner: Install [TouchDesigner](https://www.derivative.ca/099/Downloads/) if you haven't already.
- Visual Crossing API key: Create an account on the Visual Crossing website and obtain an API key.

## Usage

1. Clone or download the project repository.
2. Open the project in TouchDesigner.
3. Customize the location, API key, and update frequency parameters according to your requirements.
4. Run the project by executing the necessary nodes and operators.
5. The visual effect will be displayed, overlaid with the current location and weather information.
6. The effect will update automatically based on the specified update frequency and current weather conditions.

