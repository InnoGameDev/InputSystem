# Unity Input System  Example Project




## Overview

**Description**

This Unity example project has been created to demonstrate a variety of tools and functionality with Unity's Input System.



**Input System Demonstrated Scenarios**
- Input Action Control Scheme for basic Player Controls (Directional Axis for Movement, Button press for Attack)
- Setting up Keyboard and Generic Gamepad bindings to the Control Scheme
  - Tested with the follwing controllers: PlayStation Dualshock 4, Xbox One and Nintendo Switch Pro
- Instancing multiple Player Controllers for a local multiplayer setup
- UI Input (Virtual Joystick and Virtual Button) for Touchscreen Controls
- Runtime switching between Player Control and Menu Control Action Maps
- UI for rebdining action controls to new buttons and joysticks
- Displaying connected device data in both Screen Space and World Space UI
- Callbacks for an Input Device runtime disconnecting and reconnecting

**Other Demonstrated Scenarios**
- Universal Render Pipeline's Camera Stacking for Overlay UI
- Universal Render Pipeline's Scriptable Render Pass for Scene Blur UI Overlay
- Universal Render Pipeline's Integrated Post-Processing for Tonemapping
- Nested UI Prefab for Displaying Input Device Information
- Shader Graph for filtering a Mask Map for Team Colors
- TextMesh Pro for rendering Screen Space and World Space UI Text
- Scriptable Object for storing Device Display Colors and Display Names

## Project Versions and Branches
*Important:* The project is in continuous development and improvement! Branches are used as 'time-stamps' for project states for Webinars.


## Tech Info

**Unity Version**
- Current: [2019.4.13f1](https://unity.com/releases/2019-lts)

**Packages**
- com.unity.inputsystem: 1.0.0
- com.unity.textmeshpro: 2.0.1
- com.unity.render-pipelines.universal: 7.3.1

**Hardware**

This example project has been developed and tested with the following input devices:
- Keyboard
- PlayStation 4 Dualshock Controller
- Xbox One Controller
- Nintendo Switch Pro Controller
- Android Samsung Galaxy S9 (Touchscreen for Virtual Joystick and Virtual Button)
- Mouse (For simulating touchscreen input in the Unity Editor)

**Software**

This example project was developed and tested on Windows 10.

## Usage

This example project is publicly available for you to:
- Use as a learning resource for the Input System or any other implemented feature & tool
- Use as a foundation for building your own projects
- Extract code, assets and information for your own projects

If you do use this example project in some form, please feel free to contact Andy Touch (andyt[at]unity3d.com); he'd love to hear from you about your your experience with it!

## Credits & Feedback

This example project is developed by Unity Technologies and has involvement from R&D, Product Management, Product Marketing and Evangelism.


If you have any issues, errors or feedback about the example project; you can open an issue on this repository or send an email to andyt[at]unity3d.com

## Technical Disclaimers & Known Issues

- The GameManager script has a toggle for spawning a group of Warriors at Runtime.
  - The number of warriors that is spawned is based on a fixed integer variable (manually set in the Inspector), and is not based on the number of input devices connected and detected.

