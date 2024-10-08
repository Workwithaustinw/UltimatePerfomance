
---

# How to Enable Ultimate Performance Power Plan on Windows

This guide will walk you through the steps to enable the **Ultimate Performance** power plan on Windows without needing a specific licensing tier. This power plan optimizes your system's performance by minimizing power management overhead.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Steps to Enable Ultimate Performance](#steps-to-enable-ultimate-performance)
3. [Verifying the Power Plan](#verifying-the-power-plan)
4. [Additional Tips](#additional-tips)

---

## Prerequisites

- This method is suitable for Windows 10 Pro, Enterprise, and Education editions. However, it can also be enabled on Windows Home editions using the command line.
- Ensure you have **administrator privileges** on your system.

---

## Steps to Enable Ultimate Performance

1. **Open Command Prompt as Administrator**:
   - Press `Win + X` or right-click the Start button.
   - Select **Windows Terminal (Admin)** or **Command Prompt (Admin)** from the menu.

2. **Enter the Command**:
   - In the command prompt window, type the following command and press **Enter**:

     ```bash
     powercfg -duplicatescheme 4f976c1d-8b86-4e36-9a6e-1b9f4d150c59
     ```

   - This command creates a duplicate of the Ultimate Performance scheme.

3. **Close the Command Prompt**:
   - Once the command executes successfully, you can close the Command Prompt window.

---

## Verifying the Power Plan

1. **Open Power Options**:
   - Press `Win + R` to open the Run dialog.
   - Type `control panel` and press **Enter**.
   - In the Control Panel, navigate to **Hardware and Sound** > **Power Options**.

2. **Select the Ultimate Performance Plan**:
   - In the Power Options window, you should see the **Ultimate Performance** plan listed.
   - Select it to enable this power plan.

---

## Additional Tips

- **Reverting to Balanced**: If you want to switch back to the Balanced plan, simply select it from the Power Options menu.
- **Impact on Energy Consumption**: Keep in mind that the Ultimate Performance plan may increase energy consumption, so it is recommended for desktop computers or high-performance laptops connected to power sources.
- **Monitoring Performance**: You can use tools like **Task Manager** or **Resource Monitor** to monitor your system's performance while using this power plan.

---
