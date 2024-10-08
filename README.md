# How to Turn On Ultimate Performance in Windows

This guide shows you how to make your computer run faster using the Ultimate Performance power plan.

## What You Need

- Works on Windows 10 Pro, Enterprise, and Education. You can also do it on Windows Home.
- You need to be the **admin** (the boss) on your computer.

## Steps to Follow

### 1. Open Command Prompt as Admin
- Press `Win + X` or right-click the **Start** button.
- Click on **Windows Terminal (Admin)** or **Command Prompt (Admin)**.

### 2. Type the Command
- In the window that opens, type this:
  ```
  powercfg -duplicatescheme 4f976c1d-8b86-4e36-9a6e-1b9f4d150c59
  ```
- Press **Enter** on your keyboard. 

### 3. Close the Command Prompt
- Once you see a message saying it worked, you can close the window.

## Check If It’s On

### 1. Open Power Options
- Press `Win + R` to open the Run box.
- Type `control panel` and hit **Enter**.
- Go to **Hardware and Sound**, then **Power Options**.

### 2. Look for Ultimate Performance
- You should see **Ultimate Performance** listed there.
- Click on it to turn it on.

## Extra Tips

- **Switching Back:** If you want to go back to the Balanced plan, just select it from the Power Options.
- **Energy Use:** The Ultimate Performance plan may use more power, so it’s best for desktops or powerful laptops plugged in.
- **Check Performance:** Use Task Manager or Resource Monitor to see how your computer is doing.
