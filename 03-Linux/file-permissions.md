# Linux File Permissions | สิทธิ์ไฟล์ในลินุกซ์

`r` = read / อ่าน, `w` = write / เขียน, `x` = execute / เรียกใช้งาน.

Permissions are grouped for owner, group, and others. / สิทธิ์แบ่งตามเจ้าของ กลุ่ม และบุคคลอื่น

```bash
ls -l hello.txt
chmod 600 hello.txt  # owner read/write only / เจ้าของอ่านและเขียนได้เท่านั้น
```

**Exercise / แบบฝึกหัด:** What does `600` mean? / `600` หมายถึงอะไร?

**Answer / เฉลย:** Owner read/write; group and others no permissions. / เจ้าของอ่านเขียนได้ กลุ่มและคนอื่นไม่มีสิทธิ์
