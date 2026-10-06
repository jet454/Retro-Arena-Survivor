# 🎮 Retro Arena Survivor (ESP32)

## 0) Project Overview (ภาพรวมระบบ)
โปรเจกต์ตู้เกม Arcade สไตล์ Retro 8-bit แนว Action-Survival ที่ขับเคลื่อนด้วยไมโครคอนโทรลเลอร์ ESP32 ประมวลผลและแสดงผลแบบ Real-time บนหน้าจอ TFT LCD (3.8") ควบคุมง่ายด้วย Analog Joystick มีระบบตอบสนองทางฮาร์ดแวร์ครบถ้วน ทั้งไฟ LED แสดงระดับ HP ภายนอก, ตัวปรับความสว่างหน้าจอด้วย Potentiometer และเสียงเอฟเฟกต์ SFX ผ่าน Passive Buzzer โดยตัวโปรแกรมถูกออกแบบบนสถาปัตยกรรม Non-blocking Finite State Machine (FSM) เพื่อประสิทธิภาพและความลื่นไหลสูงสุด[cite: 1]

---

## 📂 รายการเอกสารและไฟล์โปรเจกต์ (01 - 08)

* **01) Project Title & Overview:** [`01_Project_title_and_overview/Project_title_and_overview.md`](./01_Project_title_and_overview/Project_title_and_overview.md)
* **02) Picture of Actual Hardware:** [`02_picture_of_actual_hardware/picture_of_actual_hardware.png`](./02_picture_of_actual_hardware/picture_of_actual_hardware.png)
* **03) Block Diagram & Circuit Diagram:** 
  * 📊 Block Diagram: [`03_block_diagram_and_circuit_diagram/Block_Diagram.png`](./03_block_diagram_and_circuit_diagram/Block_Diagram.png)[cite: 3]
  * ⚡ Circuit Diagram: [`03_block_diagram_and_circuit_diagram/Circuit_Diagram.png`](./03_block_diagram_and_circuit_diagram/Circuit_Diagram.png)
  * 📑 Datasheets: [`03_block_diagram_and_circuit_diagram/datasheets/`](./03_block_diagram_and_circuit_diagram/datasheets/)
* **04) Codes:** 
  * 💻 Main Code: [`04_codes/main.cpp`](./04_codes/main.cpp)
  * ⚙️️ PlatformIO Configuration: [`04_codes/platformio.ini`](./04_codes/platformio.ini)
* **05) Demonstration VDO:** [`05_demonstration_VDO/google_drive_demo_vid_link.txt`](./05_demonstration_VDO/google_drive_demo_vid_link.txt)
* **06) Manual Report:** [`06_Manual_report/manual-report.pdf`](./06_Manual_report/manual-report.pdf)
* **07) Presentation File:** 
  * 📄 PDF File: [`07_Presentation_file/presentation.pdf`](./07_Presentation_file/presentation.pdf)
  * 📊 PPTX File: [`07_Presentation_file/presentation.pptx`](./07_Presentation_file/presentation.pptx)
* **08) Presentation Clip:** [`08_Presentation_clip/google_drive_Presentation_clip_link.txt`](./08_Presentation_clip/google_drive_Presentation_clip_link.txt)