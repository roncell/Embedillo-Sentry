# Embedillo-Sentry

A gesture-based locking system using the STM32F429I Discovery board. Records and recognizes motion sequences via IMU for secure authentication. Features real-time motion processing, visual feedback, and data persistence. Press **"Record"** to save a gesture, then **"Unlock"** to authenticate.

This project is our final submission for the **Real-time Embedded Systems** course at **NYU Tandon**. It implements a gesture-based locking mechanism using an STM32F429I Discovery board, leveraging its IMU sensor to record and recognize motion patterns for secure authentication.

---

## 📌 Overview

In an era where **data security** is paramount, this project explores an **alternative authentication mechanism** using **motion-based gesture recognition**. By recording a unique hand movement sequence, a user can securely **lock and unlock** a system, offering a **hack-resistant and intuitive authentication method**.

---

## 🛠 Features

- **Gesture-based locking system** using an IMU sensor (accelerometer/gyroscope).
- **Record & Unlock Mode:**
  - **Record** a motion sequence as a unique key.
  - **Unlock** by replicating the recorded gesture with sufficient accuracy.
- **Visual feedback** via an LCD interface and LED indicators.
- **Real-time motion data processing** with **Dynamic Time Warping (DTW)** correlation.
- **Data persistence**: Gestures are stored on the microcontroller’s flash memory.

---

## 🎮 How to Use

1. Upload the code to an **STM32F429I Discovery board**.
2. Power on the board via **USB (PC or power bank)**.
3. Interact via touchscreen:
   - **Press “Record”**: Capture a gesture to lock the system.
   - **Press “Unlock”**: Perform the same gesture to unlock.
4. **Unlock Successful?** ✅ **Green LED**
5. **Unlock Failed?** ❌ **Red LED**

---

## 👨‍💻 Team Members

- **Ali Aslanbayli** *(aa12947)*
- **Nevin Mathews Kuruvilla** *(nm4709)*
- **Rohan Subramaniam** *(rs9194)*

---

## 📜 Technical Details

- **Microcontroller**: STM32F429ZI (ARM Cortex-M4).
- **Programming Environment**: PlatformIO (**C++ with Mbed**).
- **Motion Processing Algorithms**:
  - **Euclidean Distance Calculation**.
  - **Dynamic Time Warping (DTW)** for gesture correlation.
  - **Correlation-based validation** for authentication.

---

## 🏆 Project Grading Criteria

- ✅ **Functionality**: Gesture recording & recognition (**40%**)
- ✅ **Robustness & Repeatability** (**20%**)
- ✅ **Ease of Use** (**10%**)
- ✅ **Creativity** (**10%**)
- ✅ **Code Quality** (**10%**)
- ✅ **Complexity** (**10%**)

---

## 🎥 Demo

A demonstration video showcasing the working project will be uploaded soon! Stay tuned! 📽️

---

