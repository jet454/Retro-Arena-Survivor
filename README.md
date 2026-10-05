# Retro Arena Survivor

## 0) Project Overview (ภาพรวมระบบ)
โปรเจกต์ตู้เกม Arcade สไตล์ Retro 8-bit แนว Action-Survival ที่ขับเคลื่อนด้วยไมโครคอนโทรลเลอร์ ESP32 ประมวลผลและแสดงผลแบบ Real-time บนหน้าจอ TFT LCD (320x480) ควบคุมง่ายด้วย Analog Joystick มีระบบตอบสนองทางฮาร์ดแวร์ครบถ้วน ทั้งไฟ LED แสดงระดับ HP ภายนอก, ตัวปรับความสว่างหน้าจอด้วย Potentiometer และเสียงเอฟเฟกต์ SFX ผ่าน Buzzer โดยตัวโปรแกรมถูกออกแบบบนสถาปัตยกรรม Non-blocking Finite State Machine (FSM) เพื่อประสิทธิภาพและความลื่นไหลสูงสุด[cite: 1]

---
