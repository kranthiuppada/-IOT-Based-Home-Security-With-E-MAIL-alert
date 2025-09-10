
## IoT-Based Home Security with Email Alert

This project demonstrates an **IoT-based home security system** using a Raspberry Pi, PIR sensor, and Pi Camera. The system detects motion and sends **email alerts with captured images**, providing real-time notifications for enhanced home security.

---

## **Features**
- Real-time **motion detection** using a PIR sensor.
- Automatic **image capture** using Pi Camera when movement is detected.
- **Email notifications** with the captured image for immediate alerts.
- Easy integration with existing smart home setups.

---

## **Components**
- Raspberry Pi (any model with GPIO pins)
- PIR Sensor
- Pi Camera
- Power supply
- Internet connection for email notifications

---

## **Circuit Diagram**
- Connect the **PIR sensor** to a GPIO input pin on the Raspberry Pi.
- Connect the **Pi Camera** to the camera interface of the Raspberry Pi.
- Power all components via the Raspberry Pi.

---

## **Working**
1. The **PIR sensor** continuously monitors for motion.
2. When motion is detected:
   - The Raspberry Pi triggers the **Pi Camera** to capture an image.
   - Sends an **email alert** with the captured image attached.
3. A **time delay** prevents repeated triggers for the same motion event.

---


## 📜 License

This project is licensed under the [MIT License](LICENSE). 

---
## 👩‍💻 Author

**Kranthi Uppada**  
B.Tech ECE | Digital Design Enthusiast  
[GitHub Profile](https://github.com/kranthiuppada)


---


