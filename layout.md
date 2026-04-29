## Short Series Layout (Current)

เฟสปัจจุบันครอบคลุม **M1–M6** เพื่อให้ผู้เรียนเห็นเส้นทางครบจากแนวคิด ไปจนถึงการนำโมเดลเข้าสู่ระบบและคัดเลือกโมเดลเพื่อใช้งานจริง

**Communication style**
- Education Tone (ภาษาทางการแนวบทเรียน/อบรม) แต่เขียนให้ผู้อ่านที่**ไม่ใช่โปรแกรมเมอร์**ติดตามได้ โดยใช้ศัพท์เทคนิคเมื่อจำเป็นและมีคำอธิบายสั้น
- เน้นคุณค่าเชิงธุรกิจและการนำไปใช้จริง
- ไม่เน้นการเขียนโค้ด
- ใช้งานได้ทั้งผ่าน VS Code Extension และ Web Browser (มือถือ/แท็บเล็ต)

| Module | Episode title | Suggested length | Focus |
|--------|----------------|-----------------:|-------|
| **M1** | **Introduction to IoT Immersive and Digital Twin** | 30-45 min | ปูพื้นแนวคิด IoT Immersive + Digital Twin และคุณค่าต่อการเรียนรู้/การพัฒนางาน/ธุรกิจ |
| **M2** | **Introduction to TESAIoT Digital Twin Platform** | 30-45 min | แนะนำแพลตฟอร์ม TESAIoT ทั้งบน VS Code Extension และ Web Browser (มือถือ/แท็บเล็ต), ฟีเจอร์หลัก, การเชื่อมต่อฮาร์ดแวร์จริงและ Cloud Server ผ่าน IoT Protocol, รองรับ MCP + LLM สำหรับการสั่งงานด้วยภาษาคน, และตัวอย่างการใช้งานสำหรับ Product/Business/Marketing, Firmware, Industrial Engineer, และ Education |
| **M3** | **Installation, Connectivity, and Setup Validation** | 45-60 min | เตรียมสภาพแวดล้อมจริงทั้ง VS Code และ Web, ติดตั้ง trust/certificate สำหรับการเชื่อมต่อปลอดภัย, เชื่อมต่อบอร์ด PSoC Edge AI ผ่าน serial/USB, ตั้งค่า Cloud และ MQTT over TLS/WSS, และตรวจสอบความพร้อมแบบ end-to-end |
| **M4** | **Free Loader: Free GitHub Asset Pack** | 25-40 min | ใช้ Free Loader เพื่อซิงค์แพ็กทรัพยากรฟรีจาก GitHub; แยกจาก Model Loader; แท็บ Online/Local; path และการพัฒนาบนเบราว์เซอร์กับ bridge; เชื่อมสู่ Model Catalog และฉากถัดไป |
| **M5** | **Model Loader: Permission-based Asset Access** | 30-45 min | ใช้ Model Loader เพื่อค้นหาและดาวน์โหลดโมเดลจากแหล่งที่ต้องได้รับสิทธิ์เข้าถึง; ตั้งค่า Base URL/API Key/CA cert; ติดตามงานดาวน์โหลด; ตรวจผลใน Local และส่งต่อไป Model Catalog |
| **M6** | **Model Catalog: Organize and Preview Models** | 25-40 min | ใช้ Model Catalog เพื่อรวมโมเดลจากหลายแหล่ง ค้นหา/กรองตามหมวดหมู่ พรีวิว 3D และคัดเลือกโมเดลก่อนใช้งานในฉากจริง |

**Module transition notes**
- M1 -> M2: จาก “เข้าใจแนวคิดและคุณค่า” ไปสู่ “เห็นองค์ประกอบและการใช้งานจริงของแพลตฟอร์ม”
- M2 -> M3: จาก “เห็น workflow และ use case” ไปสู่ “ลงมือเตรียมระบบและเริ่มใช้งานจริง”
- M3 -> M4: จาก “ระบบและคลาวด์พร้อม” ไปสู่ “เติมทรัพยากร 3D/ข้อมูลประกอบฟรีให้พร้อมสำหรับฉากและเดโม”
- M4 -> M5: จาก “Free Loader แบบไม่ต้องขอสิทธิ์พิเศษ” ไปสู่ “Model Loader การอนุญาตเข้าถึง และการใช้งานแหล่งทรัพยากรที่มีเงื่อนไข”
- M5 -> M6: จาก “ดาวน์โหลดโมเดลตามสิทธิ์” ไปสู่ “คัดเลือกและพรีวิวโมเดลในคลังกลางก่อนนำไปใช้จริง”

## Expected outcome of Current phase

เมื่อจบ M1–M6 ผู้เรียนควร:
- เข้าใจภาพรวมแพลตฟอร์มและแนวคิด Digital Twin
- เปิดและใช้งาน TESAIoT Digital Twin ได้ทั้งผ่าน VS Code Extension และ Web Browser (รวมมือถือ/แท็บเล็ต)
- เข้าใจการสื่อสารข้อมูลระหว่างแพลตฟอร์มกับฮาร์ดแวร์จริงและ Cloud Server ผ่าน IoT Protocol ได้
- เข้าใจแนวทางสั่งงานแพลตฟอร์มด้วยภาษาคนผ่าน MCP และ LLM ในระดับแนวคิดได้
- ติดตั้งและตั้งค่าพร้อมสำหรับการเรียนตอนถัดไปได้อย่างมั่นใจ
- ใช้ทั้ง Free Loader และ Model Loader ได้ตามสิทธิ์การเข้าถึงและบริบทงาน
- ใช้ Model Catalog เพื่อคัดเลือกและพรีวิวโมเดลก่อนนำไปใช้งานจริงได้
- เห็นโอกาสการประยุกต์ใช้เชิงงานและเชิงธุรกิจอย่างน้อย 1 แนวทาง

## Next phase note

บท **M7** เป็นต้นไปจะต่อยอดสู่การโหลดฉากขั้นสูง การผูกข้อมูลกับสินทรัพย์ และโครงอบรม onsite ตามลำดับความสำคัญ
