# FLStudioASIO

FL Studio ASIO is an ASIO driver developed by **Image-Line**, offering significant improvements over other drivers. Unlike ASIO4ALL, this driver seamlessly integrates audio playback from your DAW or music software (e.g., foobar2000 with the ASIO Output plugin) with other applications, enabling concurrent audio output.

Say goodbye to the inconvenience of manually disabling the driver whenever you want to play audio from different sources!

## Usage

Follow these steps to get started:

1. **Download / Clone the Repository:**
    - Click on **Code > Download ZIP** on the master branch.

    - Alternatively, run the following command in your terminal to **clone the repository**:
      ```
      git clone https://github.com/julcioo/FLStudioASIO.git
      ```

2. **Create the installation folder:**
    - Place the downloaded files into `C:\Program Files\Image-Line\FL Studio ASIO`. Create the folder/subfolder manually if it doesn't exist.

3. **Install / Remove the driver:**
    - Run the `registerAsioDriver.bat` script to install/register the driver.
    - Run the `unregisterAsioDriver.bat` script to remove/unregister the driver.

## Disclaimer

Please note that this is a third-party driver, and its stability might vary depending on the hardware it's used with. While every effort has been made to ensure its functionality, there is no guarantee of its performance on all devices.

We appreciate any feedback. Thanks! ;)
