#  Ball Balancing Robot with Sense Plate

A DIY project to build a simple yet powerful **ball-balancing robot** using an **Arduino**, **two servo motors**, and a **sense plate**. The system keeps a ball centered on a flat surface by tilting the plate in two directions based on sensor feedback — an excellent demonstration of real-time control systems and PID loops.

---

## 📌 Project Description

This robot uses two servo motors to tilt a square plate along the X and Y axes. A ball is placed on the plate, and its position is monitored using a **sense plate** (IR sensors or a touch grid). An Arduino continuously reads the ball's position and adjusts the plate angles to keep the ball at the center.

---

## 🛠️ Hardware Components

- 🧠 Arduino Uno or Nano  
- 🔄 2x Servo motors (one for X-axis, one for Y-axis)  
- 🧲 Sense plate (IR sensors or touch grid to detect ball position)  
- ⚙️ Ball (e.g., steel or glass marble)  
- 🔌 Jumper wires, breadboard, power supply  
- 🔧 Mounts and plate platform  

---

## 🧠 Features

- 🔁 Real-time ball position control
- 🔧 PID algorithm for smooth and stable movement
- 🎓 Ideal for education, demos, or hobby projects

---

## 💻 Software Requirements

- Arduino IDE
- PID library (`PID_v1.h`)
- Custom Arduino sketch (included in this repo)

---

## 🚀 How It Works

1. Ball moves on the sense plate.
2. Sensors detect the X and Y position of the ball.
3. Arduino processes the position and calculates error from the center.
4. PID controller generates servo commands.
5. Servos tilt the plate to bring the ball back to center.

---

## 📸 Demo
![IMG_0542](https://github.com/user-attachments/assets/9d9e140e-cdcf-4155-8ba6-d327acdda6cd)
![IMG_0539](https://github.com/user-attachments/assets/c83e3b5c-1436-46b5-aefe-a1cf0f48f50e)


---

## 📂 File Structure

```bash
/
├── Arduino_Code/
│   └── ball_balance.ino
├── images/
│   └── demo.gif
├── README.md
