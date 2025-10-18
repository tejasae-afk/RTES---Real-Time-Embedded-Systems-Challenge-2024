# RTES Real Time Embedded Systems Challenge 2024

A real-time embedded systems project built using **PlatformIO** and the **STM32F429ZI Discovery Board**, developed in **VS Code** using the **Mbed framework**.  
This repository showcases the design, implementation, and testing of an embedded control application for the GY6483 RTES Challenge 2024.

---

## 🧩 Features

- Built on the **Mbed OS** framework for STM32
- Developed using **PlatformIO** in **VS Code**
- Target Board: **STM32F429ZI Discovery**
- Modular and scalable source code structure
- Ready for deployment on SM (Smart) Board hardware

---

## 🛠️ Requirements

### Software
- [Visual Studio Code](https://code.visualstudio.com/)
- [PlatformIO IDE Extension](https://platformio.org/install/ide?install=vscode)
- [Git](https://git-scm.com/)

### Hardware
- STM32F429ZI Discovery (DISCO_F429ZI)
- USB cable (micro USB)
- Optional peripherals (depending on your RTES setup)

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/<your-username>/RTES-Embedded-Systems-Challenge-2023.git
   cd RTES-Embedded-Systems-Challenge-2024
## 🧭 Quick Start Guide (VS Code + PlatformIO)

### 1️⃣ Open in VS Code
- Launch **Visual Studio Code**
- Open the folder you just cloned:

### 2️⃣ Install PlatformIO Extension
- Go to the **Extensions** panel:  
Press `Ctrl + Shift + X`
- Search for **PlatformIO IDE**
- Click **Install**

### 3️⃣ Build the Project
- Open the **PlatformIO Home** tab (house icon on the left sidebar)
- Click the **Build** button (✓ icon in the bottom toolbar)
- PlatformIO will compile your project using the configuration from `platformio.ini`

### 4️⃣ Upload to Board
- Connect your **STM32F429ZI** board via USB
- Click the **Upload** button (→ icon in the bottom toolbar)
- PlatformIO will automatically detect and flash your board

### 5️⃣ Monitor Serial Output
- Open the **Serial Monitor** (plug icon on the bottom bar)
- Set the correct **baud rate** (e.g., `9600`, or your configured value)
- Observe your program output and debugging information in the terminal
