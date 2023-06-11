# VR Solar System

Welcome to the VR Solar System project! This project creates an interactive virtual reality experience where you can explore the solar system and its celestial bodies.

## Getting Started

To run the VR Solar System project, follow these steps:

1. Clone the repository or download the project files to your local machine.

2. Open the `index.html` file in a web browser that supports WebVR.

3. Put on your VR headset for an immersive experience, or use your mouse and keyboard to navigate the scene.

4. Enjoy exploring the solar system! Look around to observe the planets and their details.

## Requirements

- Web browser with WebVR support
- VR headset (optional)

## Project Structure

The project structure is as follows:

- `index.html`: The main HTML file that renders the VR scene and includes the necessary A-Frame library.

- `aframe.min.js`: The A-Frame library, which provides the framework for building VR experiences.

- `universe.jpg`: The background image used to create the universe ambiance.

- `sun.jpg`, `mercury.jpg`, `venus.jpg`, `earth.jpg`, `mars.jpg`, `jupiter.jpg`, `saturn.jpg`, `uranus.jpg`, `neptune.jpg`, `pluto.jpg`: Textures for each planet in the solar system.

- `README.md`: This README file providing information about the project.

- Other assets: Additional assets, such as 3D models or textures, can be added as needed.

## Customization

You can customize the VR Solar System project by modifying the following aspects:

- Position, scale, and rotation of the planets and their rings in the `index.html` file. Adjust the `position`, `scale`, and `rotation` attributes of each entity to change their placement and appearance.

- Textures of the planets: Replace the planet texture files (`sun.jpg`, `mercury.jpg`, etc.) with your desired images. Make sure to update the `material` attribute of each `<a-sphere>` element to use the new texture file.

- Background image: Replace the `universe.jpg` file with your preferred background image. Update the `src` attribute in the `background` property of the `<a-scene>` element to use your new image.

## Contributing

Contributions to the VR Solar System project are welcome! If you have any improvements, bug fixes, or new features to propose, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as permitted by the license.

