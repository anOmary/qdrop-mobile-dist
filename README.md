# QDrop Mobile — Distribution Channel

Distribution repository ของแอป **QDrop Android** (และ iOS ในอนาคต)

แอปจะดึงเวอร์ชันล่าสุดจาก [GitHub Releases](https://github.com/anOmary/qdrop-mobile-dist/releases) อัตโนมัติ — ผู้ใช้กดอัปเดตได้จาก dialog ภายในแอป

## ติดตั้งครั้งแรก (Sideload)

1. ดาวน์โหลด `qdrop-android-vX.Y.Z.apk` จาก [Latest Release](https://github.com/anOmary/qdrop-mobile-dist/releases/latest)
2. เปิดไฟล์บนเครื่อง Android — ระบบอาจถาม "อนุญาตติดตั้งจากแหล่งนี้" → กดอนุญาต
3. หลังติดตั้งเปิดแอปได้ทันที — เวอร์ชันถัดไปจะอัปเดตอัตโนมัติในแอป

## ช่องทาง

- **Stable** — `vX.Y.Z` (เช่น v1.0.0) — ปล่อยให้ผู้ใช้ทุกคน
- **Beta** — `vX.Y.Z-beta.N` (มาร์ค pre-release) — เฉพาะผู้ใช้ที่เปิด "ทดลอง beta" ใน Settings

## Mandatory Update

หาก release body มี tag `[MANDATORY]` → แอปจะบังคับให้ผู้ใช้อัปเดตก่อนใช้งานต่อ (ใช้ตอน critical bug fix หรือ API breaking change เท่านั้น)

## Source code

Private — `anOmary/qdropandroid`
