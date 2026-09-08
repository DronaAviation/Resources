# DronaAviation Resources 📚

Welcome to the resources repository for DronaAviation! Here, you'll find a collection of downloads, guides, manuals, and tutorials to help you explore and maximize your drone experience.

---

## 🛍️ Store Page

- **[Buy a Drone](https://www.dronaaviation.com/store/)**: Explore and purchase the latest Pluto drones.

---

## 📑 Manuals

- **[Pluto X Manual](<Manual/Pluto X_Manual.pdf>)**: A detailed user manual for Pluto X.
- **[Pluto 1.2 Manual](<Manual/Pluto 1.2_Manual.pdf>)**: A detailed user manual for Pluto 1.2.

---

## 🚀 PlutoBlocks

PlutoBlocks is a visual block-based programming tool that lets you control and program your drone with ease. Below are the download links and resources to start using PlutoBlocks on different platforms.

### 📥 Downloads

<!--
  MAINTAINERS: these two desktop links are pinned to a specific release tag because the
  uploaded asset filenames contain the version number, so they must be bumped on every release.
  If the build is changed to publish version-free filenames (e.g. PlutoBlocks-Setup.exe /
  PlutoBlocks.dmg), swap them for these permanent links, which never need updating:
    https://github.com/DronaAviation/Resources/releases/latest/download/PlutoBlocks-Setup.exe
    https://github.com/DronaAviation/Resources/releases/latest/download/PlutoBlocks.dmg
-->

| Platform             | Link                                                                                                                                |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Windows (64-bit)** | [Download PlutoBlocks for Windows](https://github.com/DronaAviation/Resources/releases/download/v4.1.1/PlutoBlocks.Setup.V4.1.1.exe) |
| **Mac OS**           | [Download PlutoBlocks for Mac](https://github.com/DronaAviation/Resources/releases/download/v4.1.1/PlutoBlocks.4.1.1.dmg)            |

> 🔄 **Always get the newest build:** [Resources → Releases](https://github.com/DronaAviation/Resources/releases/latest)

### 📘 Guides and Tutorials

- **[PlutoBlocks Web Book](https://dronaaviation.github.io/Plutoblocks-web-book/)**: Interactive online documentation for PlutoBlocks.
- **[Guide Book (PDF)](<PlutoBlocks/PlutoBlocks Guide Book v2.pdf>)**: A comprehensive guide to help you get started with PlutoBlocks.
- **[Online Courses](#-online-courses)**: Guided PlutoBlocks courses on the Drona Aviation learning platform.

---

## 🎓 Online Courses

Guided, self-paced courses on the Drona Aviation learning platform.

| Course                                                                                                             | About                                                                    |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **[Learn Drone Technology using Pluto](https://learn.dronaaviation.com/l/pdp/drone-technology-for-beginners)**          | Drone technology from the ground up, for absolute beginners.              |
| **[Introduction to PlutoBlocks](https://learn.dronaaviation.com/l/pdp/introduction-to-plutoblocks)**                    | Your first step into drone programming — no prior coding experience needed. |
| **[PlutoBlocks Block-by-Block](https://learn.dronaaviation.com/l/pdp/plutoblocks-block-by-block)**                      | A walkthrough of the PlutoBlocks blocks, one at a time.                   |

> 📚 **Browse the full catalogue:** [learn.dronaaviation.com](https://learn.dronaaviation.com/l/products)

---

## 💻 Pluto IDE

**Pluto IDE** is the current development environment for programming your Pluto drone in C++ — it replaces the discontinued Cygnus IDE. It ships as a **Visual Studio Code extension**, so it runs on Windows, macOS, and Linux, and it manages the toolchain, build, flashing (USB/WiFi), and serial monitoring for you.

### 📥 Installation

1. Install **[Visual Studio Code](https://code.visualstudio.com/)**.
2. Install the **[Pluto IDE extension](https://marketplace.visualstudio.com/items?itemName=Drona-Aviation.pluto-ide)** from the VS Code Marketplace.

Or install it from a terminal:

```bash
code --install-extension Drona-Aviation.pluto-ide
```

| Resource                   | Link                                                                                                    |
| -------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Extension (Marketplace)** | [Drona-Aviation.pluto-ide](https://marketplace.visualstudio.com/items?itemName=Drona-Aviation.pluto-ide) |
| **Extension Info Page**     | [Pluto IDE Extension](https://dronaaviation.github.io/Pluto-IDE-Extension-Info-Pages/)                   |
| **Toolchain Essentials**    | [Pluto-IDE-Essentials](https://github.com/DronaAviation/Pluto-IDE-Essentials/releases/latest)            |
| **Starter Library Project** | [PlutoIDE-Lib-Project](https://github.com/DronaAviation/PlutoIDE-Lib-Project/releases/latest)            |

### 📘 Guides and Tutorials

- **[Pluto IDE Web Book](https://dronaaviation.github.io/PlutoIDE-web-book/)**: Setup guide, hardware/software reference, and 19 step-by-step C++ projects for Pluto X and Pluto 1.2.
- **[MagisV2 API Wiki](https://github.com/DronaAviation/MagisV2/wiki)**: Full API reference for the MagisV2 firmware.
- **[MagisV2 API Reference (offline)](https://github.com/DronaAviation/MagisV2-API-Wiki)**: Single-page HTML copy of the API reference.

### ⚙️ Working with Firmware and Source Code

- **[MagisV2](https://github.com/DronaAviation/MagisV2)**: Current flight-controller firmware for the Pluto platform — [latest release](https://github.com/DronaAviation/MagisV2/releases/latest).
- **[MagisV2 Add-Ons](https://github.com/DronaAviation/MagisV2-Add-On)**: Example code and prebuilt `.hex` firmware for external modules (sensors, motors, and other peripherals).
- **[Magis (legacy)](https://github.com/DronaAviation/Magis)**: Older firmware, kept for reference.

> ⚠️ **Cygnus IDE is discontinued.** Please migrate to Pluto IDE — it is actively maintained and required for MagisV2 firmware development.

---

## 🔧 DFU Drivers for PlutoBlocks / Pluto IDE

- **[DFU Drivers for DFU Flashing](<DFU Drivers>)**: Required for DFU flashing in Pluto IDE and PlutoBlocks. Includes a step-by-step installation guide.

---

## 🖨️ 3D Printing Files

- **[3D Printing Files](<3D Printing Files>)**: Printable `.stl` mounts and holders for sensors and modules — buzzer holder, card holder, LED light holder, MQ gas sensor mount, PIR sensor mount, and sound sensor mount.

---

## 🐍 Python Libraries and Projects

Explore drone projects and control drones with Python using the following libraries:

- **[plutocam](https://pypi.org/project/plutocam/)**: Library for controlling the Pluto drone camera.
- **[plutocontrol](https://pypi.org/project/plutocontrol/)**: Library for drone control via Python ([source](https://github.com/DronaAviation/plutocontrol)).
- **[Projects with Python](https://github.com/DronaAviation/PROJECTS_WITH_PYTHON/tree/main)**: Collection of various drone projects with Python.
- **[Camera Projects](https://github.com/DronaAviation/PROJECTS_WITH_PYTHON/tree/main/PlutoCam)**: Specific Python projects for controlling and using the drone camera.

---

## 🤖 ROS Packages

- **[pluto_ros2_package](https://github.com/DronaAviation/pluto_ros2_package)**: Control Pluto from ROS 2.
- **[pluto_cam_ros2](https://github.com/DronaAviation/pluto_cam_ros2)**: Pluto camera stream for ROS 2.
- **[pluto_camera_ros_package](https://github.com/DronaAviation/pluto_camera_ros_package)**: Pluto camera stream for ROS 1 (Linux 64-bit).
- **[pluto-ros-package](https://github.com/DronaAviation/pluto-ros-package)**: Control Pluto with keyboard, joystick, or rostopic (ROS 1).

---

## 🌐 Join Our Community

<div style="display: flex; gap: 15px; align-items: center;">
  <a href="https://www.linkedin.com/company/drona-aviation-pvt-ltd-/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" width="30" style="margin-right: 10px;">
  </a>
  <a href="https://www.youtube.com/@Dronaaviation" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube" width="30" style="margin-right: 10px;">
  </a>
  <a href="https://www.instagram.com/plutodrones/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" width="30" style="margin-right: 10px;">
  </a>
  <a href="https://discord.com/invite/hJfxVCdb6z" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord" width="30" style="margin-right: 10px;">
  </a>
  <a href="https://github.com/DronaAviation" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111432.png" alt="GitHub" width="30" style="margin-right: 10px;">
  </a>
  <a href="https://www.facebook.com/dronaaviation" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" width="30" style="margin-right: 10px;">
  </a>
</div>

📧 Support: [support@plutodrones.com](mailto:support@plutodrones.com) · 🌐 [dronaaviation.com](https://www.dronaaviation.com)

Feel free to explore, download, and get hands-on with these resources to make the most of your Pluto drone experience!
