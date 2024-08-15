# Home Assistant Sensor Widget for Scriptable

This Scriptable widget provides a visual interface inspired by the Tesla Solar Panel widget, but it presents information from Home Assistant. The widget displays energy usage, solar production, and current home energy consumption with an AI-generated image of a house. The icons dynamically change based on real-time data from your Home Assistant setup.
![image](https://github.com/user-attachments/assets/d01f54df-65be-4eab-a060-0f4a07b43532)


## Features

- Displays solar production in kW.
- Shows current home energy usage with dynamic icons indicating energy sourcing or injection.
- Includes daily energy consumption and injection summaries with associated icons.
- Customizable colors and fonts.

## Setup

1. Replace `hassUrl` with your Home Assistant URL.
2. Replace `hassToken` with your Home Assistant long-lived access token.
3. Replace the image URL with your desired image.
4. Customize colors, fonts, and other settings as needed.

## Image

The image of the house is AI-generated and included in the `source` folder.

## Usage

Copy the script to Scriptable and configure it with your Home Assistant credentials. The widget can then be added to your home screen to display live energy data.

## License

MIT License
