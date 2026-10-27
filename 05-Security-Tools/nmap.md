# Nmap | เครื่องมือ Nmap

**English:** Nmap is a network discovery and security auditing tool. Only scan systems you own or have explicit permission to test.

**ไทย:** Nmap ใช้สำรวจเครือข่ายและตรวจสอบด้านความปลอดภัย สแกนเฉพาะระบบของตนเองหรือได้รับอนุญาตชัดเจน

**Local-only example / ตัวอย่างเฉพาะเครื่องตัวเอง:**

```bash
nmap -sT -p 22,80,443 127.0.0.1
```

This checks three TCP ports on your own loopback interface. Results vary depending on local services. / คำสั่งนี้ตรวจพอร์ต TCP 3 พอร์ตบนเครื่องตัวเอง ผลลัพธ์ขึ้นกับบริการที่เปิดอยู่

**Reflection / ทบทวน:** What does an `open` port mean? / พอร์ต `open` หมายถึงอะไร?
