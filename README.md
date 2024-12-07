# Dynamic Network Slicing for Enhanced Wi-Fi Performance

This project demonstrates dynamic network slicing for enhanced Wi-Fi performance in 5G networks. It explores techniques to improve resource allocation and network efficiency by simulating and analyzing network slicing in real-time.

## 📑 Table of Contents

- [Group Details](#-group-details)
- [Mentor](#mentor)
- [Video Presentation](#video-presentation)
- [🚀 Project Overview](#-project-overview)
- [📂 Project Structure](#-project-structure)
- [⛳ Objectives](#-objectives)
- [✨ Features](#-features)
- [⚙️ Technologies Used](#️-technologies-used)
- [🔧 Installation](#-installation)
- [Usage](#usage)
- [RESULTS AND OBSERVATIONS](#results-and-observations)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

---

## 🏆 Group Details 
**Group Number:** Gr21EC431  
**Group Members:**
- **Patel Krish** (202151110)
- **Atharv Barde** (202151184)
- **Baraiya Poojan Harishbhai** (202151185)
- **Patel Utkarsh Rameshbhai** (202152329)
- **Sachin Kumar** (202152335)

---

## Mentor
- **Dr. Bhupendra Kumar**

---

## Video Presentation
https://drive.google.com/file/d/16FHd9Gl-wiIx-YjeTItOy8adNHHdUITO/view?usp=sharing

---


## 🚀 Project Overview

Network slicing is a key feature of 5G technology that allows the creation of multiple virtual networks on a shared infrastructure. This project focuses on implementing dynamic slicing to enhance Wi-Fi network performance by allocating resources efficiently based on demand and priority.

## 📂 Project Structure
```bash
Dynamic-Network-Slicing/
├── main.py        # Main script to run the project
├── Graph.py       # Handles visualization and graphing
└── ...            # Other project modules
│
├── example-input.yml  # Example configuration file
├── requirements.txt   # Dependencies required for the project
├── README.md          # Project documentation (this file)
```


## ⛳ Objectives

- Analyze dynamic slicing in 5G networks.
- Optimize resource utilization for Wi-Fi networks.
- Improve overall network performance using open-source tools.

## ✨ Features

- Simulation of network slicing in 5G for Wi-Fi networks.
- Dynamic allocation of resources based on real-time inputs.
- Visual representation of network performance metrics.

---

## ⚙️ Technologies Used

- **Python**: Core language for scripting and simulation.
- **Matplotlib**: Visualization of performance metrics.
- **PyYAML**: Configuration management.
- **Open-source tools**: Built using free and open-source resources.

---

## 🔧 Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Sachin63Kumar/Dynamic-Network-Slicing.git
    cd Dynamic-Network-Slicing
    ```

2. Install the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the main simulation script:

    ```bash
    cd ..
    python -m Dynamic-Network-Slicing.main example-input.yml
    ```

---

## Usage
1. Prepare your configuration file (e.g., example-input.yml) with the required parameters.

2. Run the simulation:
```bash
python -m Dynamic-Network-Slicing.main example-input.yml
```
3. View the generated visualizations for analysis.

---

## RESULTS AND OBSERVATIONS
The simulation results demonstrate the following:
- The spatial representation shows base station coverage areas, with colored circles representing slices (e.g., IoT and data) and dots indicating connected or unconnected clients. A high client coverage ratio (~0.84) demonstrates effective coverage.

- Performance metrics highlight stable network operation: no blocked requests (block ratio 0.000), consistent bandwidth usage (~5.345 Mbps), and balanced load across slices with an average slice load factor of 0.97.

- The simulation summary confirms optimal resource allocation with no handovers (handover ratio 0.000) and no resource constraints, showcasing efficient 5G network slicing for 1,000 simulated clients.
![Network_Slicing_Simulation_output](https://github.com/user-attachments/assets/ad7f0e4c-39e2-4c30-b017-5f9d6e7595b8)



## Future Work

- **AI-Driven Optimization**: Leverage machine learning to predict demand patterns and optimize resource allocation.
- **Edge Computing Integration**: Incorporate Multi-Access Edge Computing (MEC) to further reduce latency.
- **Security Improvements**: Enhance slice isolation and implement secure communication protocols.
- **Interoperability Testing**: Explore integration with legacy networks for smoother transitions to 5G.

---

## Acknowledgments

We would like to express our sincere gratitude to **Dr. Bhupendra Kumar**, our mentor, for his invaluable guidance and support throughout this project. His insights helped us refine our approach and deepen our understanding of 5G. 

---
