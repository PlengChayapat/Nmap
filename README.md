# Nmap
เป็นซอฟต์แวร์ที่เกี่ยวข้องกับทางด้าน Network security ที่ได้รับความนิยมเป็นอย่างสูง และถูกนำไปใช้กันอย่างแพร่หลาย สิ่งที่ทำให้ Nmap ได้รับความนิยมนั้นคือ ฟังก์ชันการทำงานที่มีให้เลือกใช้และสามารถปรับแต่งได้อย่างหลากหลาย รวมถึงสามารถเลือกใช้ได้บนแทบทุกระบบปฏิบัติการที่นิยมใช้กันในปัจจุบัน ไม่ว่าจะเป็น Windows, Linux, Mac OS หรือแม้กระทั่งระบบปฏิบัติการสำหรับอุปกรณ์พกพาอย่างเช่น Android จึงทำให้ Nmap เป็นตัวเลือกแรก ๆ ในบรรดาซอฟต์แวร์ประเภท Network security scanner  

## Program Installation

### Windows, Mac OS และ RPM-based Linux distribution
ระบบปฏิบัติการที่อยู่ในหัวข้อนี้นอกจาก Windows และ Mac OS แล้ว ยังรวมถึง Linux ที่ใช้ RPM เป็นระบบจัดการแพ็คเกจ ผู้ที่ใช้ระบบปฏิบัติการเหล่านี้สามารถดาวน์โหลดตัวติดตั้งจากหน้า [Download](https://nmap.org/download.html)  

### Debian-based Linux distribution
ระบบปฏิบัติการที่อยู่ในหัวข้อนี้ เช่น Debian และ Ubuntu เป็นต้น ผู้ที่ใช้ระบบปฏิบัติการเหล่านี้สามารถติดตั้งผ่านทางโปรแกรมจัดการแพ็คเกจที่มาพร้อมกับระบบปฏิบัติการ เช่น apt-get ได้โดยใช้คำสั่งต่อไปนี้ผ่านทาง Command-line

**`sudo apt-get install nmap`**

**`sudo apt-get install zenmap`** (สำหรับผู้ที่ต้องการใช้โปรแกรม Zenmap)  

## Command Examples
* **`nmap -sn <target>`**  
การตรวจสอบหาระบบที่กำลังทำงาน วิธีนี้เป็นการตรวจสอบหาอุปกรณ์หรือเครื่องคอมพิวเตอร์ที่กำลังทำงานอยู่ในระบบเครือข่ายโดยการ Ping ไปยัง                             เป้าหมายที่ระบุไว้


* **`nmap -sS -sV -O <target>`**  
การตรวจสอบบริการ เวอร์ชันของบริการ และระบบปฏิบัติการ วิธีนี้จะทำการตรวจสอบบริการและเวอร์ชันของบริการที่ตรวจพบ รวมถึงระบบปฏิบัติการของระบบเป้าหมาย


* **`nmap -p <port-range> <target>`**  
การตรวจสอบบริการที่เปิดใช้งานโดยระบุหมายเลขพอร์ตเพื่อจำกัดกลุ่มของบริการที่จะตรวจสอบ  

## Information
**Document link:** https://www.it.kmitl.ac.th/

**Youtube link:** https://www.youtube.com/watch?v=YqG7RkwMstg  

## Authors
* นายชยภัทร พันรอด - 61070036 - [PlengChayapat](https://github.com/PlengChayapat)
* นายพัสกร อรุณสดใส - 61070141 - [erongi](https://github.com/erongi)
* นายวรเชษฐ์ นิ่มเจริญ - 61070196 - [WorachetNimcharoen](https://github.com/WorachetNimcharoen)
* นายศุภชัย จันโท - 61070224 - [Supachaijunto]( https://github.com/Supachaijunto)
* นายสุภัควี สุโพธิ์ - 61070251 - [Supakkavee](https://github.com/Supakkavee)

