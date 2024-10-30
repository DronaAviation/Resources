# DFU Driver Installation Guide

This guide provides step-by-step instructions to install the DFU (Device Firmware Upgrade) driver required for Cygnus and PlutoBlocks.

---

## DFU Driver Installation Tutorial

1. **Start the Setup**  
   - Open the DFU Driver Installer.
   - A welcome message will appear, asking you to ensure the drone is connected via USB and turned ON.
   - Click **OK** to proceed.

![image](https://github.com/user-attachments/assets/42a23047-3835-47aa-a415-075e3d8d8c36)
         
2. **Ready to Install**  
   - The setup will display a "Ready to Install" screen, indicating that the installation process is ready to begin.
   - Click **Install** to continue.
  
![image](https://github.com/user-attachments/assets/6f3bf801-477d-47e2-b854-7264f7777bca)


3. **Installing the Driver**  
   - The installation process will begin, and a progress bar will be displayed.
   - Wait for the installation to complete.

![image](https://github.com/user-attachments/assets/4e825c81-4de4-4c62-b3cf-05525c7549fc)

4. **Zadig config**  
   - Zadig will be launched automatically once the other drivers are installed.
   - If nothing appears under the **Driver**, **USB ID**, or **WCID** fields, try **reinserting** the USB cable. This should trigger the detection.

![image](https://github.com/user-attachments/assets/4e2fae29-12b9-406c-8c3d-b3605e7a5d75)

5. **Device Detected (STM32 BOOTLOADER)**  
   - Once the USB is reinserted, the device should be detected as **STM32 BOOTLOADER**.
   - Ensure **WinUSB** is selected as the driver, then click **Install Driver** to proceed.

![image](https://github.com/user-attachments/assets/20fc8cdb-100d-4a64-a017-541362077144)

6. **Driver Installation Success**  
   - A confirmation message will appear, indicating that the driver was installed successfully.
   - Click **Close** to exit Zadig.

![image](https://github.com/user-attachments/assets/2e8c9516-887a-46fa-b20e-3fb3777309a0)


7. **Completing the Setup**  
   - Return to the DFU Driver Installer, where you will see a "Completing the Setup Wizard" screen.
   - Click **Finish** to exit the installer.
     
![image](https://github.com/user-attachments/assets/083be905-1f82-44e1-bf6f-8786b876ee66)

---

Your DFU driver should now be installed successfully, and your system is ready for DFU flashing in Cygnus and PlutoBlocks.

If you encounter any issues, try disconnecting and reconnecting your USB cable and ensure that the drone is powered on.
