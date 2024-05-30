# TerraVision

**TerraVision** is an advanced terrarium monitoring and management system designed for Raspberry Pi. This project combines environmental data collection, timelapse creation, and a comprehensive web-based management interface to provide a complete solution for terrarium enthusiasts.

## Features

- **Environmental Data Collection**: Continuously monitor and record temperature, humidity, and other environmental parameters.
- **Timelapse Creation**: Automatically capture images at specified intervals and generate timelapse videos to observe changes over time.
- **Web-Based Interface**: Manage all aspects of the system through an intuitive web interface built with Django.
  - **Dashboard**: View real-time data and visualizations of environmental conditions.
  - **Camera Control**: Adjust camera settings and capture intervals directly from the web interface.
  - **System Management**: Perform system operations such as rebooting, shutting down, and managing storage devices.
  - **API Integration**: Extend functionality with a robust API for external integrations.
- **Automated Setup**: Deploy a fully configured system using a pre-built Raspberry Pi image, ensuring quick and easy setup.

## Getting Started

### Prerequisites

- Raspberry Pi with an SD card
- [Etcher](https://www.balena.io/etcher/) for flashing the image
- Network connection for accessing the web interface

### Installation

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/turbonoje2k/TerraVision.git
    cd TerraVision
    ```

2. **Prepare the Raspberry Pi**:
    - Ensure you have a Raspberry Pi with an SD card.
    - Download the pre-built image (link to image) and flash it to your SD card using Etcher.

3. **Boot Up**:
    - Insert the SD card into your Raspberry Pi and power it on.

4. **Access the Web Interface**:
    - Open a web browser and navigate to the IP address of your Raspberry Pi to access the TerraVision interface.

## Usage

1. **Configure Settings**:
    - Customize environmental thresholds, camera settings, and other parameters via the web interface.

2. **Monitor and Manage**:
    - Use the dashboard to monitor real-time data and perform system management tasks.

3. **Review Timelapses**:
    - Access and download timelapse videos to review changes over time.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your improvements.

## License

This project is licensed under the MIT License.

