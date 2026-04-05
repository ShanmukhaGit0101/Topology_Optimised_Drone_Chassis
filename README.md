# 🚁 Topology Optimized Drone CHassisusing Additive Manufacturing

## 📌 Overview

This project focuses on the design and development of a **lightweight quadcopter frame** using **generative design and additive manufacturing techniques**.

The objective is to create a structurally efficient drone frame that:

* Supports a **1 kg payload**
* Maintains **frame weight under 250 g**
* Is manufacturable using **FDM (ABS)** and **SLS (Nylon)**

---

## 🎯 Design Objectives

* High **strength-to-weight ratio**
* Efficient **load transfer through topology optimization**
* Integration of **internal wiring channels**
* Compact **central hub for avionics**
* Compatibility with **standard drone hardware**

---

## ⚙️ System Specifications

| Parameter           | Value                 |
| ------------------- | --------------------- |
| Frame weight        | ≤ 250 g               |
| Payload capacity    | 1 kg                  |
| All-up weight (AUW) | ~2 kg                 |
| Propeller size      | 10 inch               |
| Battery             | 4S LiPo               |
| Configuration       | Quadcopter (X layout) |

---

## 🧠 Design Approach

1. **Load Case Definition**

   * Static payload load
   * Dynamic maneuver loads
   * Motor thrust and torque
   * Landing impact

2. **Thrust Calculation**

   * Required thrust ≥ 2 × AUW
   * Per motor thrust ≈ 1 kg

3. **Component Selection**

   * 2216 class brushless motors
   * 10×4.5 propellers
   * 4-in-1 ESC
   * F7 flight controller

4. **Generative Design (Fusion 360)**

   * Preserve geometry: hub, motor mounts, base plate
   * Obstacle geometry: electronics space, wiring channels
   * Applied constraints and loads

5. **Iterative Refinement**

   * Initial topology results analysis
   * Addition of missing constraints (bending, torque)
   * Manufacturability improvements

---

## 🔩 Hardware Stack

* **Motors:** 2216 920KV
* **Propellers:** 10×4.5
* **ESC:** 35A 4-in-1
* **Flight Controller:** F7 (30.5×30.5 mm)
* **Receiver:** ELRS / SBUS
* **Battery:** 4S 3500–4000 mAh LiPo

---

## 🧱 Mechanical Design Features

* **Central cylindrical hub** for electronics integration
* **Topology-optimized arms** for efficient load transfer
* **Internal wiring channels** (10 mm diameter)
* **Standard 16×16 mm motor mounts**
* **Slotted base plate** for thermal dissipation

---

## 🖨 Manufacturing

* **Primary Method:** FDM (ABS)
* **Alternative Method:** SLS Nylon (PA12)

### Printer Constraints

* Printer: Mingda Magician X
* Build volume: 230 × 230 × 260 mm

### Design Considerations

* Minimum wall thickness (FDM): 3 mm
* Minimum wall thickness (SLS): 2 mm
* Overhang constraints applied
* Filleted joints for stress reduction

---

## 📊 Performance Considerations

* Thrust-to-weight ratio > 2
* Optimized for **efficient payload flight**, not aggressive maneuvering
* Structural design driven by **bending and torsional loads**
* Vibration isolation provided for avionics

---



## 🔄 Design Iterations

The project includes multiple iterations:

* Initial concept geometry
* First generative design output (unconstrained result)
* Refined topology with improved load cases
* Final manufacturable design

---

## 🚀 Future Work

* Flight testing and validation
* Modal and vibration analysis
* PID tuning and control optimization
* Payload-specific mounting system

---

## 👨‍💻 Author

**Shanmukha Vinayak M**
**Karna Kranthi Koushik Reddy**
Automation & Robotics Engineering Student
Amrita Vishwa Vidyapeetham

---

## 📌 Note

This project emphasizes a **load-driven design philosophy**, where geometry is derived from structural requirements rather than predefined shapes.
