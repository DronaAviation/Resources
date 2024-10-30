# DFU Driver Installation Guide

This guide provides step-by-step instructions to install the DFU (Device Firmware Upgrade) driver required for Cygnus and PlutoBlocks.

---

## DFU Driver Installation Tutorial

1. **Start the Setup**  
   - Open the DFU Driver Installer.
   - A welcome message will appear, asking you to ensure the drone is connected via USB and turned ON.
   - Click **OK** to proceed.

2. **Ready to Install**  
   - The setup will display a "Ready to Install" screen, indicating that the installation process is ready to begin.
   - Click **Install** to continue.

3. **Installing the Driver**  
   - The installation process will begin, and a progress bar will be displayed.
   - Wait for the installation to complete.

4. **Open Zadig Application**  
   - Launch the Zadig application, which helps manage USB drivers.
   - If nothing appears under the **Driver**, **USB ID**, or **WCID** fields, try reinserting the USB cable. This should trigger the detection.

5. **Device Detected (STM32 BOOTLOADER)**  
   - Once the USB is reinserted, the device should be detected as **STM32 BOOTLOADER**.
   - Ensure **WinUSB** is selected as the driver, then click **Install Driver** to proceed.

6. **Driver Installation Success**  
   - A confirmation message will appear, indicating that the driver was installed successfully.
   - Click **Close** to exit Zadig.

7. **Completing the Setup**  
   - Return to the DFU Driver Installer, where you will see a "Completing the Setup Wizard" screen.
   - Click **Finish** to exit the installer.

---

Your DFU driver should now be installed successfully, and your system is ready for DFU flashing in Cygnus and PlutoBlocks.

If you encounter any issues, try disconnecting and reconnecting your USB cable and ensure that the drone is powered on.
