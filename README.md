# 🤖 Dual-Mode Robotic Control System  
### *Precision Control for Robotic Operations*

<div align="center">
  <img src="assets/robot_main.jpg" alt="Main Robotic Unit" width="85%">
</div>

## ✨ Key Features

<div style="display: flex; justify-content: space-between;">
  <div style="width: 48%;">
  
  **🎮 Controller Integration**  
  - Full DS4 button mapping  
  - Analog stick precision control  
  - Dual-mode operation (Drive/Auger)  

  </div>
  <div style="width: 48%;">
  
  **📶 Network Communication**  
  - UDP socket transmission  
  - Real-time data streaming  
  - Robust packet formatting  

  </div>
</div>

---

## 🖼️ System Overview

<div align="center">
  <img src="assets/robot_detail.jpg" alt="Robotic Components" width="85%">
  <br>
  <em>Detailed view of auger and drive systems</em>
</div>

---

## 🛠️ Installation & Usage

```bash
# Clone and install
git clone https://github.com/yourusername/Remote-Control-System-for-Robot-Operation.git
pip install pygame
```

| System          | Command                     | Key Features                |
|-----------------|-----------------------------|-----------------------------|
| **Drive**       | `python Drive_System_Controller.py` | Tank movement, pitch/roll control |
| **Auger**       | `python Auger_System_Controller.py` | Material deposition, sensor suite |

---

## 📋 Control Reference

### Common Controls
| Button          | Function        | Visual Feedback |
|-----------------|-----------------|-----------------|
| <kbd>L1</kbd>  | Gear down       | LED indicator   |
| <kbd>R1</kbd>  | Gear up         | Haptic feedback |

### Drive-Specific
| Input           | Response       |
|-----------------|----------------|
| Left Stick      | Base movement  |
| <kbd>Y</kbd>   | Pitch down     |

---

## ⚙️ Technical Specs
```python
# Data Packet Example
"M3X512Y-256A0S0R0E"  # Gear 3, X=512, Y=-256
```

| Component       | Specification           |
|-----------------|-------------------------|
| Protocol        | UDP @ 5005              |
| Resolution      | 10-bit (1024 steps)     |
| Update Rate     | 100Hz                   |

---

<div align="center">
  📄 [MIT License](https://choosealicense.com/licenses/mit/) • 
  🛠️ Contribute via PRs • 
  🐛 Report issues
</div>
```
