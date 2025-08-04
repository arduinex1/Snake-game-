# Snake-game-

👉 **Components jo yahan lage hain:**
✅ Arduino Uno
✅ OLED Display (jo snake game dikhayega)
✅ Joystick module (jo aap use karoge snake ko control karne ke liye)
✅ 9V battery (power supply ke liye)

---

### **Connections samjho:**

✅ **OLED Display:**

* GND → Arduino ke GND
* VCC → Arduino ke 5V
* SCL → Arduino ke A5 (yeh I2C communication ke liye)
* SDA → Arduino ke A4 (I2C ke liye)

---

✅ **Joystick module:**

* GND → Arduino ke GND
* 5V → Arduino ke 5V
* VRx → Arduino ke A0 (X-axis movement read karega)
* VRy → Arduino ke A1 (Y-axis movement read karega)
* SW → Arduino ke pin D2 (joystick button press detect karega)

---

✅ **9V Battery:**

* Positive terminal → Arduino ke VIN pin
* Negative terminal → Arduino ke GND

---

### **Kaise kaam karta hai?**

* Joystick se aap snake ko left, right, up, down move kara sakte ho
* OLED display par snake ka game dikh raha hota hai
* Arduino saara logic handle karta hai, jaise snake ki movement aur collision detection
* Joystick ke button ko use karke aap game reset ya pause bhi kar sakte ho

---
