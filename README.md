# RF-Based Environmental Detection and Object Classification System 🚧 [IN PROGRESS]

[![Status: In Progress](https://img.shields.io/badge/Status-In%20Progress-orange.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Simulation: Wokwi](https://img.shields.io/badge/Simulation-Wokwi-blueviolet.svg)](https://wokwi.com/)
[![Hardware: ESP32](https://img.shields.io/badge/Hardware-ESP32-blue.svg)](https://www.espressif.com/en/products/socs/esp32)
[![AI: PyTorch](https://img.shields.io/badge/AI-PyTorch-ee4c2c.svg)](https://pytorch.org/)

An edge computing solution designed to provide real-time environmental awareness for visually impaired individuals using Radio Frequency (RF) signals and Machine Learning. **This project is prototyped and simulated interactively using Wokwi.**

## 🚀 Project Overview

This system acts as an "RF-based Ultrasound" (Radar/Sonar hybrid) that "sees" the environment by analyzing the reflection patterns of emitted RF signals. Unlike traditional camera-based systems, it works in various lighting conditions and respects privacy while maintaining high accuracy in object classification.

### Key Features
- **RF-Based Perception:** Detects and classifies objects by analyzing reflected signals.
- **Interactive Simulation:** Fully simulated ESP32 environment on Wokwi, allowing anyone to test the hardware logic right from their browser without physical components.
- **Real-Time Edge Processing:** Low-latency inference designed for embedded hardware.
- **Blind-Friendly Feedback:** Designed to provide haptic or auditory feedback based on real-time environmental data.

## 🛠 Tech Stack

- **Embedded Simulation:** Wokwi Simulator, ESP32 Virtual Environment.
- **AI/ML:** Python, PyTorch/TensorFlow, Scikit-Learn.
- **Hardware Design (Simulated):** Virtual RF Sensors, Signal Conditioning.
- **Concepts:** Edge Computing, Machine Learning on Microcontrollers, Low-Latency Optimization.

## 📐 System Architecture

1.  **Virtual Sensor Data:** Simulated reflection data is generated within the Wokwi environment.
2.  **Signal Conditioning:** Raw signals are processed through simulated filters to eliminate noise.
3.  **Feature Extraction & Classification:** An optimized ML model processes the data to identify object types and proximity.
4.  **User Feedback:** The system provides simulated immediate feedback to the user.

## 📂 Project Structure

```text
├── simulation/         # Wokwi project files (diagram.json)
├── firmware/           # ESP32 source code (C++/C) running on Wokwi
├── ml_models/          # Training scripts and exported model weights
├── data_processing/    # Signal processing and filtering algorithms
└── docs/               # Technical documentation and research notes
```

## 🔧 Getting Started

### Prerequisites
- A modern web browser.
- Python 3.8+ (only if you want to train/test the AI models locally).

### Running the Simulation
1.  **Open the Wokwi Project:**
    Click the link below to open the interactive ESP32 simulation directly in your browser without any installation:
    *👉 **[Add Your Wokwi Project Link Here]***
2.  **Start Simulation:**
    Click the **"Play"** button in the Wokwi interface to boot up the virtual ESP32 and start the system.
3.  **Local ML Environment (Optional):**
    If you wish to explore the machine learning pipeline on your local machine:
    ```bash
    git clone https://github.com/BurakCANKURT/RF-Environmental-Detection.git
    cd RF-Environmental-Detection
    pip install -r ml_models/requirements.txt
    ```

## 🤝 Contributing

This project is open for collaboration! Whether it's optimizing the DSP algorithms, improving model accuracy, or enhancing the Wokwi simulation, feel free to open an issue or submit a pull request.

## 👤 Author

**Burak CANKURT**
- Email: [burakcankurt37@gmail.com](mailto:burakcankurt37@gmail.com)
- LinkedIn: [Burak CANKURT](https://www.linkedin.com/in/burak-cankurt-545262222)
- GitHub: [@BurakCANKURT](https://github.com/BurakCANKURT)

---
*Developed as part of an end-to-end engineering approach to AI and Hardware integration.*