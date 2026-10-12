# Downiverse: downloads

Installers for **Downiverse**, a desktop app for downloading videos and music with yt-dlp, and its browser extension.

**➡ [Download the latest version](https://github.com/itsnotthetim/downiverse-releases/releases/latest)**

| System | File |
|---|---|
| Windows 10/11 | `Downiverse_<version>_x64-setup.exe` (or `.msi`) |
| Ubuntu / Debian | `Downiverse_<version>_amd64.deb` (`sudo apt install ./Downiverse_<version>_amd64.deb`) |
| Other Linux | `Downiverse_<version>_amd64.AppImage` (`chmod +x`, then run it) |
| Chrome, Edge, Brave | `Downiverse_<version>_chrome-extension.zip`: unzip, open `chrome://extensions`, turn on Developer mode, **Load unpacked** |
| Firefox | `Downiverse_<version>_firefox-extension.zip`: `about:debugging` → This Firefox → **Load Temporary Add-on** |

The Windows installer isn't code-signed yet. If SmartScreen warns, click **More info → Run anyway**.

**Updates.** Downiverse checks this page for new versions and installs them when you agree (Settings → About). Every update is signed, and the app refuses files without a valid signature.

## ติดตั้ง Downiverse และส่วนขยายเบราว์เซอร์ (ภาษาไทย)

**ตัวแอป (Windows):** โหลด `Downiverse_<เวอร์ชัน>_x64-setup.exe` จาก[หน้าเวอร์ชันล่าสุด](https://github.com/itsnotthetim/downiverse-releases/releases/latest) แล้วเปิดไฟล์ ถ้า Windows ขึ้นเตือน (SmartScreen) ให้กด **More info → Run anyway**

**ส่วนขยายสำหรับ Chrome, Edge, Brave** (ยังไม่อยู่ใน Chrome Web Store จึงติดตั้งแบบ Developer mode):
1. เปิด Downiverse → **Settings → Browser extension → Prepare extension** แอปจะเตรียมโฟลเดอร์ `Downiverse extension\Chrome` ในโฟลเดอร์ผู้ใช้ให้ และแสดงขั้นตอนพร้อมปุ่มคัดลอก
2. ในเบราว์เซอร์ เปิด `chrome://extensions` (Edge: `edge://extensions`, Brave: `brave://extensions`)
3. เปิด **Developer mode** (มุมขวาบน)
4. กด **Load unpacked** แล้วเลือกโฟลเดอร์จากข้อ 1 (วาง path ที่คัดลอกมาได้)
5. กดไอคอน Downiverse ในแถบเครื่องมือ (ปักหมุดได้จากเมนูรูปจิ๊กซอว์) → **Connect** แล้วกด **Allow** ในแอป Downiverse

ห้ามลบโฟลเดอร์ส่วนขยาย เพราะส่วนขยายอยู่ในนั้น เมื่ออัปเดตแอปแล้ว ให้กด **Update files** ในหน้าเดิม แล้วกดปุ่มรีโหลด ↻ ของส่วนขยาย
จะติดตั้งเองจากไฟล์ zip ก็ได้ ในไฟล์ zip มีวิธีติดตั้งภาษาไทยอยู่แล้ว (`HOW-TO-INSTALL.txt`)

Only download what you're allowed to keep.
