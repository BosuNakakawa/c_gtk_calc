# โปรแกรมเครื่องคิดเลขด้วยภาษา C

## วิธีคอมไพล์ด้วยตนเอง
ใช้ [gtk](https://gtk.org) บน macOS หรือ Linux (คุณไม่สามารถใช้งาน gtk บน Windows ได้)

รันคำสั่งต่อไปนี้บน Terminal ของคุณ
```bash
gcc -o calculator main.c `pkg-config --cflags --libs gtk+-3.0`
```

## วิธีใช้งาน
เปิด Directory ของ Project ขึ้นมาแล้วรันคำสั่งต่อไปนี้
```bash
cd bin
./calculator
```

สำหรับการใช้งานบน Windows ให้เปิดไฟล์ calculator.exe เพื่อใช้งานโปรแกรม

## ผู้สร้าง
สร้างโดย BosuNakakawa
