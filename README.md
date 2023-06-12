# 🧰 TouchDesigner Experiments

## 1️⃣ 🌤️ Weather Visualiser
This project demonstrates the implementation of a weather API in TouchDesigner to fetch and display current weather conditions for any location. Additionally, it showcases a generative visual effect that updates based on the current weather data.
<details>

### Project Overview

The project consists of the following key components and features:

- Weather API integration: Utilizes the Visual Crossing API for fetching current weather conditions. The API offers metered pricing and user-friendly documentation.
- Parameterized functionality: Customizable parameters for location, API key, and update frequency allow users to configure the weather data fetching process.
- JSON parsing: TouchDesigner's JSON DAT is used to parse the received weather data and extract specific elements of interest.
- Generative visual effect: A placeholder effect is created using noise and color palettes. The effect is dynamically updated based on the current weather data, with temperature as an example.
- User-friendly interface: The location, weather information, and visual effect parameters are displayed on-screen, providing a user-friendly and interactive experience.

### Requirements

To run this project, you need the following:

- TouchDesigner: Install [TouchDesigner](https://www.derivative.ca/099/Downloads/) if you haven't already.
- Visual Crossing API key: Create an account on the Visual Crossing website and obtain an API key.

### Usage

1. Clone or download the project repository.
2. Open the project in TouchDesigner.
3. Customize the location, API key, and update frequency parameters according to your requirements.
4. Run the project by executing the necessary nodes and operators.
5. The visual effect will be displayed, overlaid with the current location and weather information.
6. The effect will update automatically based on the specified update frequency and current weather conditions.


</details>



## 2️⃣ 🔥 Texture Generation with Noise and Feedback

This project demonstrates how to create a texture using noise and feedback in TouchDesigner. The generated texture is then used to create particles with instancing in a 3D space. Mmanipulating the noise texture, adding feedback and processing techniques to enhance the visual output.

<details>

### Usage

- Press the `1` key to reset the feedback and seed values.
- Experiment with different parameters to modify the appearance of the texture and particles.
- Explore the options for noise, feedback, slope, blur, limit, and post-processing to create unique visual effects.

</details>




## 3️⃣ 🎥 Motion Detection using Web Camera and TouchDesigner + Interactive Art

This project demonstrates a method of detecting motion using a web camera and TouchDesigner. The approach eliminates the need for specialized motion detection devices like Kinect or dedicated sound technology. By following the steps outlined below, you can easily set up motion detection using a web camera and interact with the detected motion in various ways.

<details>


### Motion Detection Setup

1. Add a "Video Device In" TOP to your TouchDesigner project.
2. Create a "Texture 3D" TOP with a buffer of 20 frames.
3. Add a "Time Machine" TOP and a "Constant" TOP to the project.
4. Adjust the parameters of the "Time Machine" TOP:
   - Set the black offset to 0.
   - Set the white offset to -20.
5. Connect the "Video Device In" TOP to the "Texture 3D" TOP.
6. Connect the "Texture 3D" TOP to both the "Time Machine" TOP and the "Constant" TOP.
7. Add a "Composite" TOP and connect the camera and delayed video inputs:
   - Connect the "Video Device In" TOP to the first input.
   - Connect the output of the "Time Machine" TOP to the second input.
   - Set the operation to "Subtractive."
8. Add a "Threshold" TOP and adjust the threshold value (e.g., 0.07).
9. Optionally, apply a blur effect to enhance the motion detection.
10. You now have a motion detection system in place!

### Usage and Limitations

- The motion detection system can be used to interact with other elements in your TouchDesigner project, such as a reaction diffusion feedback loop or particle effects.
- The method works best with inputs that have a fair amount of contrast and a static background.
- Please note that there may be a slight lag of about a second, which can be reduced by adjusting the white offset parameter.





