# pixhawk-quadcopter-uav
This project involves the design, setup, and testing of a quadcopter UAV using the CUAV V5+ (Pixhawk) flight controller during my internship at the Arthur C. Clarke Institute for Modern Technologies, Sri Lanka.

## ⚙️ System Features
- Pixhawk (CUAV V5+) flight controller integration  
- GPS-based navigation and positioning  
- Sensor fusion using IMU, compass, barometer, and GPS  
- Multiple flight modes (Stabilized, Position Hold, Position Slow)  
- Real-time tuning and calibration via QGroundControl  
- ESC and motor control using PWM outputs  

---

## 🔌 Hardware Components
- CUAV V5+ Flight Controller  
- Brushless Motors (EMAX 900KV)  
- ESCs (Skywalker 30A)  
- LiPo Battery  
- Pixhawk GPS Module  
- Radio Transmitter & Receiver  
- Telemetry-ready system  

---

## 🧠 Key Learning Areas
- Flight controller calibration using QGroundControl  
- Sensor setup (accelerometer, gyroscope, compass)  
- GPS integration and satellite-based navigation  
- ESC calibration and motor synchronization  
- Flight mode configuration and safety setup  

---

## 🧪 Procedure & Setup
- Installed PX4 firmware via QGroundControl  
- Configured airframe and calibrated sensors  
- Set up transmitter inputs (Throttle, Roll, Pitch, Yaw)  
- Integrated GPS module and configured satellite lock (minimum 8 satellites)  
- Tuned flight parameters and performed test flights  

---

## 🚀 Outcome

![Quadcopter Flight](IMG_3421.jpg)

- Successfully achieved stable quadcopter flight  
- Enabled GPS-based flight modes (Position Hold, Altitude Hold)  
- Improved flight stability through sensor calibration and tuning  
- Completed controlled flight testing under real conditions  

---

## 🎥 Demo Video

[Watch Flight Test](YOUR_VIDEO_LINK_HERE)

---

## ⚠️ Challenges & Engineering Insights

- Receiver compatibility issues (PWM vs PPM vs SBUS) required hardware and configuration adjustments  
- ESC calibration inconsistencies required manual tuning and parameter matching  
- Hardware limitations (damaged motors, mismatched ESCs) affected performance and required component replacement  
- Power module failure required redesign using a step-down buck converter  
- Initial flight instability (drifting) solved through GPS integration and sensor recalibration  

---

## 🔧 Improvements & Future Work
- Integration of telemetry module for real-time ground communication  
- Further PID tuning for optimized flight performance  
- Transition to VTOL system development (next phase project)  
- Improved hardware reliability and modular design  

---

## 🏁 Conclusion
This project provided practical exposure to real UAV systems, bridging theoretical knowledge with hands-on implementation. It laid the foundation for more advanced UAV development, including VTOL systems.
