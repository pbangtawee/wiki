---
hide:
  - navigation # ซ่อน Sidebar เฉพาะหน้าแรกเพื่อให้แสดงผลเป็น Landing Page เต็มหน้าจอ
---

<!-- 🚀 HERO BANNER SECTION -->
<div style="text-align: center; padding: 2.5rem 1rem; margin-bottom: 2rem; background: radial-gradient(circle, rgba(255,158,0,0.12) 0%, rgba(15,19,28,0) 70%); border-radius: 1rem; border: 1px solid rgba(255,158,0,0.15);">

  <div style="display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.25rem 0.85rem; border-radius: 9999px; background: rgba(255,158,0,0.1); border: 1px solid rgba(255,158,0,0.25); margin-bottom: 1.25rem;">
    <span style="width: 8px; height: 8px; border-radius: 50%; background: #FF9E00; display: inline-block;"></span>
    <span style="font-family: 'Roboto Mono', monospace; font-size: 0.75rem; color: #FF9E00; font-weight: 600; letter-spacing: 0.05em;">HARDWARE &amp; SOFTWARE DOCUMENTATION HUB</span>
  </div>

  <h1 style="font-size: 2.75rem; font-weight: 800; border: none; margin-bottom: 0.75rem; line-height: 1.2;">
    Open Hardware, <span style="color: #FF9E00;">Edge AI</span> &amp; DIY Tech Lab
  </h1>

  <p style="font-size: 1.1rem; color: #94A3B8; max-width: 680px; margin: 0 auto 1.5rem auto; line-height: 1.6;">
    ศูนย์รวมคู่มือเชิงลึก วงจรอิเล็กทรอนิกส์ พินไดอะแกรม และคลังความรู้สำหรับนักประดิษฐ์และวิศวกรยุคใหม่
  </p>

</div>

---

## คู่มือการใช้งาน

<div class="grid cards" markdown>

-   :material-motion-sensor:{ .lg .middle } **Arduino**

    ---

    คู่มือการต่อเซนเซอร์วัดค่า BME680, IMU 9-Axis, Ultrasonic, Time-of-Flight และโมดูล LiDAR อุตสาหกรรม

    [:octicons-arrow-right-24: อ่านคู่มือ (32 DOCS)](hardware/wiki_esp32-guide.md)

-   :material-memory:{ .lg .middle } **ESP32**

    ---

    สถาปัตยกรรมชิป ESP32, STM32 Arm Cortex, Raspberry Pi 5, RP2040 พร้อมแนวทางการคอมไพล์ FreeRTOS และ Zephyr

    [:octicons-arrow-right-24: อ่านคู่มือ (48 DOCS)](hardware/esp32-guide.md)

-   :material-robot-industrial:{ .lg .middle } **Raspberry Pi Pico**

    ---

    การเร่งความเร็วโมเดลบน NVIDIA Jetson Orin Nano, Model Quantization INT8, TensorRT และบอร์ด RDK X5

    [:octicons-arrow-right-24: อ่านคู่มือ (24 DOCS)](hardware/rdk-x5.md)

-   :material-antenna:{ .lg .middle } **STM32**

    ---

    โครงข่ายไร้สายระยะไกล LoRaWAN Class A/C, โพรโทคอล MQTT Broker, Mesh Zigbee, BLE Long Range และ Matter

    [:octicons-arrow-right-24: อ่านคู่มือ (36 DOCS)](#)

</div>

---

## DIY Projects

<div class="grid cards" markdown>

-   ![YOLOv8 Jetson](https://lh3.googleusercontent.com/aida-public/AB6AXuBGb_ul3DOZ7OZc4LWj4Syod517tzbdvH0bKFOE57za5oeRvR_xUarj5JKmF9k6YbZYMMxpUReLu3Uyq0Ctd4GVx6fCRbxkkWGDzh2TvY7VWNm3YBT1tEcurS7w9_bVLJTIu8hBYwE2e9dBWgapmnOm6qZdyCsAzM9VNNpVGAqpteflMkEZRSKAtHdXWIL-Z9R-ysmTLK_brGqiGeO0_ST-_OxBDvsdCxlFTVLbU4iINWgsrNPVVgod)

    ---

    **ระบบตรวจจับวัตถุแบบเรียลไทม์ด้วย YOLOv8 บน Jetson Nano**

    คอมไพล์โมเดลผ่าน TensorRT Engine พร้อมปรับแต่ง DeepStream SDK เพื่อดึงเฟรมเรต 45 FPS แบบ Zero-Drop Frame

    [:octicons-clock-24: 45 นาที · ดูคู่มือการทำ](hardware/rdk-x5.md)

-   ![LoRaWAN Weather Station](https://lh3.googleusercontent.com/aida-public/AB6AXuCvHzfmLPaBE-APfxhUGNuegRw7RHhDXFRVJPDGlXoPXmtxsDLjjGnlaetbJSg-dzwZbIbomNLIaQaD2I5UlChk7ENREpf5OGcFW-nhDdQBf9QLcn8k6iiUAwQdHerfynPGRib-PYjt_TyzuxbA-Ct61t9uiOVXaKHsUni8hPw9Y3YWvanirh3Dn2XuIHpRcvZpAPxZJxnULB3YT7DC32xFW48C6gp6_WYw90YyJZlvNKMrye_ayMeO)

    ---

    **สถานีวัดสภาพอากาศอัจฉริยะส่งข้อมูลผ่าน LoRaWAN & ESP32**

    ออกแบบระบบประหยัดพลังงาน Deep Sleep ส่งค่าความชื้น แสง UV และฝุ่น PM2.5 เข้า The Things Network ได้ไกลกว่า 10 กิโลเมตร

    [:octicons-clock-24: 1.5 ชม. · ดูคู่มือการทำ](hardware/esp32-guide.md)

-   ![ROS2 Robot AMR](https://lh3.googleusercontent.com/aida-public/AB6AXuBiaPIPinIvtcsopvwZFTt5ptiIWz-k-Li-46rur2T4qVHLxE_HV94p2emlShw0_Jak0-dE2PpCb4SY0EWpMTqw_7-6XUnh1_wiYoU5rfEk-Sf9vT7t8i9ggu4JUHeZkdMIe15cs3_-6BRmi5HyhgODFqvnxPJ4tC71OfTuisl6BGvGbpclK56da7isvLol76P7HJ1iaoSxd0xmfHO9sPWNJQAyQ-q-qZBxsnSsNbrmEA1iDxofywxa)

    ---

    **การสร้าง Autonomous Mobile Robot (AMR) ด้วย ROS2 & SLAM**

    ติดตั้ง Nav2 Stack ทำแผนที่อาคาร 2D/3D และระบบหลบหลีกสิ่งกีดขวางแบบอัตโนมัติด้วยกล้อง Depth Sensor

    [:octicons-clock-24: 3 ชม. · ดูคู่มือการทำ](hardware/stm32-swd.md)

</div>

---

## 💻 ตัวอย่างโค้ดและคำสั่งเริ่มต้น (CLI & SDK)

!!! tip "Command Line Interface & Python SDK Quickstart"
    รองรับการตรวจหาชิป ตรวจสอบ Pinout และอัปโหลดเฟิร์มแวร์ทดสอบได้ทันที

=== "Flash with CLI"
    ```bash
    # ติดตั้งเครื่องมือพัฒนาผ่าน Terminal
    curl -sSL [https://get.mytechlab.dev](https://get.mytechlab.dev) | sh

    # ตรวจสอบบอร์ดฮาร์ดแวร์ที่เชื่อมต่อผ่านพอร์ต USB
    techlab-cli probe --verbose

    # เบิร์นเฟิร์มแวร์ทดสอบ
    techlab-cli flash --template lora-mesh-telemetry --baud 921600
    ```

=== "Python SDK"
    ```python
    import techlab_core as lab
    from techlab_sensors import EnvironmentSensor

    # เริ่มต้นเชื่อมต่อ I2C Bus บน GPIO 21 (SDA), 22 (SCL)
    bus = lab.I2C(sda=21, scl=22, freq_khz=400)
    sensor = EnvironmentSensor(bus, addr=0x76)

    while True:
        telemetry = sensor.read_metrics()
        print(f"Temp: {telemetry.temp_c}°C | Hum: {telemetry.humidity}%")
        lab.telemetry.dispatch_mqtt(telemetry)
        lab.sleep_ms(1000)
    ```

---

## Lab Stats

| 📖 บทความฮาร์ดแวร์ | ⚙️ โปรเจกต์ Open-Source | 🔓 ซอร์สโค้ด |
| :---: | :---: | :---: |
| **120+ Docs** | **45+ Projects** | **100% Free** |