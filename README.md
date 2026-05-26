# SNAILab_dataCollectionFrame

The data collection frame primarily mounts the sensor system comprising a ZED2i camera, TI IWR1443, and TI DCA1000 to its front. All of the parts were used and or redesigned from the <a href="https://radarml.github.io/red-rover/">RadarML Red Rover</a>.

Before committing to any hardware work, first, the following software applications must be downloaded:
  1. <a href="https://www.stereolabs.com/developers/release">ZED SDK 5.3</a> - Software development kit to analyze ZED function and data collection
  2. <a href="https://www.ti.com/tool/UNIFLASH">Uniflash</a> - App to flash firmware onto the board
  3. <a href="https://www.ti.com/tool/MMWAVE-STUDIO">mmWave Studio</a> - TI's GUI for configuring and visualizing radar data
  4. <a href="https://www.ti.com/tool/CCSTUDIO">Code Composer Studio (CCS)</a> - VSC for those who want to develop firmware themselves
  5. <a href="https://www.ti.com/tool/MMWAVE-SDK">mmWave SDK</a> - Software development kit for radar that includes demos, API documentation, and example firmware (install after CCS)

The first app pertains to the ZED2i, and the latter four are used for the TI IWR1443 and DCA1000 radar system.

## Software Installation
After downloading, for each of these apps, go through the installation process and accept all prompts. You can follow the RadarML Red Rover <a href="https://radarml.github.io/xwr/setup/">XWR Hardware Setup</a>, as the AWR1843 and IWR1443BOOST are very similar hardware-wise, but below are more in-depth walkthroughs for setting this data collection system up.

### ZED SDK
The ZED SDK includes calibration, video preview, data capturing, and more. To test, plug in the ZED2i using the given USB cable and open ZED Explorer, one of the apps included in the SDK. Explorer should detect the 2i quickly, and from there, just ensure that the tracking and depth can be seen in the preview.

### Uniflash
TBA

### mmWave Studio
TBA

### Code Composer Studio
TBA

### mmWave SDK
TBA

## Hardware Assembly
Download and 3D print all .STL parts. Like before, the <a href="https://radarml.github.io/red-rover/roverc/assembly/">Red Rover Hardware Assembly</a> can be used to guide through this assembly process. Just ignore any steps related to the IMU, NUC, or Blackmagic Camera, as these components are either substituted or omitted, within our assembly.
