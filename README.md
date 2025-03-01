# 🛠 UNIT – Modular Swarm Robotics System

## 📌 Overview  
UNIT is a **small-scale swarm robot** designed for **self-assembly, movement, and energy efficiency**.  
Each UNIT is capable of **autonomous motion, attachment, and energy sharing**, making it ideal for **adaptive structures** and **dynamic swarm behaviors**.  

---

## 📐 Physical Design  

- **Shape:** **Tetragonal Trapezohedron**   
- **Size:** **≤ 5 cm (H) × 3 cm (W) × 3 cm (L)**  
- **Frame Material:** **See-through carbon fiber layering + Transparent polymer casing**  

📌 **Why This Shape?**  
✔ High connection points for **flexible self-assembly**  
✔ **Stable multi-directional movement**  
✔ **Compact and strong for 3D formations**  

---

## ⚡ Power System  

| Component                          | Function                                        |
|-------------------------------------|------------------------------------------------|
| **Solar Panels**                    | Main power source during the day              |
| **RF Energy Harvesters**            | Collects ambient RF energy at night          |
| **Piezoelectric Energy Harvesters** | Converts vibrations into additional power     |
| **Thin-Film Supercapacitors**       | Stores excess energy for quick bursts        |
| **Physical Conductive Pads**        | Enables **direct energy transfer** between UNITs |
| **Deep Sleep Mode**                 | Reduces power consumption when idle          |

📌 **Power Efficiency:** **UNIT can function indefinitely using energy harvesting + energy sharing.**  

---

## 🚀 Hybrid Movement System  

| Movement Type                      | Hardware Used                                  | Purpose                                  |
|-------------------------------------|-----------------------------------------------|------------------------------------------|
| **SMA Micro-Legs**                 | Shape Memory Alloy (SMA) actuators            | **Crawling movement** for precision     |
| **Electromagnetic Rolling**        | Reverse-polarity electromagnets               | Movement on metallic/magnetic surfaces  |
| **Vibration Motor**                | Ultra-small vibration motor                   | Fine-tuned adjustments & minor shifts   |

📌 **Hybrid movement system allows for adaptable terrain traversal and modular reconfiguration.**  

---

## 🔗 Connection & Assembly  

| Component                           | Function                                       |
|--------------------------------------|-----------------------------------------------|
| **Reverse-Polarity Electromagnets**  | Attaches & detaches dynamically              |
| **Physical Conductive Pads**         | Transfers power between connected UNITs      |
| **RFID Module**                      | Allows UNITs to detect and communicate       |
| **9-Axis IMU (Inertial Measurement Unit)** | Tracks motion, position, and orientation |

📌 **UNITs can detect, connect, and reconfigure autonomously.**  

---

## 🧠 Intelligence & Control  

| Component           | Function                                              |
|--------------------|------------------------------------------------------|
| **PIC10F200 Microcontroller** | Controls electromagnets & movement system |
| **9-Axis IMU**     | Helps UNIT determine position & orientation        |
| **Very Small Tracker** | Allows real-time swarm tracking               |

📌 **The software ensures each UNIT makes real-time movement and connection decisions.**  

---

## 💾 Software & AI Logic  

### **1️⃣ Low-Level Control (Embedded C / Assembly for PIC10F200)**  
- **Electromagnet & Movement Control**  
- **Sensor Processing (IMU, RFID, Energy Data)**  
- **Sleep/Wake Modes for Power Efficiency**  

### **2️⃣ Mid-Level Swarm Logic (Python / Rust on External Controller)**  
- **Swarm Command Algorithms** (formation, disassembly, movement strategies)  
- **Energy Management Optimization**  
- **Pathfinding & Obstacle Avoidance**  

### **3️⃣ High-Level Interface (User-Controlled AI or Predefined Commands)**  
- **PC / Mobile App Interface**  
- **AI-Assisted Swarm Optimization**  
- **Simulations & Testing**  

📌 **UNITs function autonomously but can receive external commands for advanced coordination.**  

---

## 📊 Component Table  

| Component                          | Quantity per UNIT | Notes                                  |
|-------------------------------------|------------------|----------------------------------------|
| **Solar Panel**                     | 1                | Small, efficient, layered on the body |
| **RF Energy Harvester**             | 1                | Absorbs ambient energy at night       |
| **Piezoelectric Harvester**         | 1                | Generates power from movement         |
| **Thin-Film Supercapacitor**        | 1                | Stores energy for bursts              |
| **Physical Conductive Pads**        | 4                | Transfers power between UNITs         |
| **SMA Micro-Legs**                  | 2–4              | For precision crawling movement       |
| **Electromagnets (Polarity-Switching)** | 4                | For attachment and rolling movement  |
| **Vibration Motor**                 | 1                | For minor movement adjustments        |
| **9-Axis IMU**                      | 1                | Tracks motion, position, and angle    |
| **RFID Module**                     | 1                | Enables UNITs to detect each other    |
| **Tracker (Very Small)**            | 1                | Allows external swarm tracking        |
| **PIC10F200 Microcontroller**       | 1                | Controls all core functions           |

📌 **Every UNIT is self-sufficient but can form larger, more powerful structures when combined.**  

---

# 🔥 Summary  
✅ **Modular, Self-Assembling, and Energy-Efficient**  
✅ **Hybrid Movement: Crawling, Rolling, and Vibrating Adjustments**  
✅ **Autonomous Swarm Intelligence + User Command Support**  
✅ **Sustainable Power via Solar, RF, Piezoelectric, and Energy Sharing**  

---

