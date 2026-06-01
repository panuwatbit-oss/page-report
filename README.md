# Page Report Structure

จัดระเบียบรายงานสำหรับ GitHub Pages แบบแยกตามลูกค้า แพลตฟอร์ม และช่วงวันที่

## โครงสร้างหลัก

```text
clients/
  vive-clinic/
    2026-05-22-28/
      index.html
      ads.html
      admin.html
  wonder/
  soyou/
  youme/
  vive-salon/
  vertex/
    google-ads/
  vitalsleep/
    google-ads/
  clearisma/
  vthbiodent/
    google-ads/
  tcsmiledental/
    google-ads/
  smilescape/
    google-ads/
  brain-and-life-center/
    google-ads/
```

## Platform convention

- `google-ads/` = รายงาน Google Ads แบบครบวงจร ไม่จำกัดเฉพาะ Search
- `meta/` = รายงาน Meta/Facebook Ads
- `messenger/` = รายงานแอดมิน/Inbox

## Naming convention

- ลูกค้า: ใช้ slug ภาษาอังกฤษตัวเล็ก เช่น `vive-clinic`, `vthbiodent`
- ช่วงรายงาน: ใช้ `YYYY-MM-DD-DD` เช่น `2026-05-22-28`
- รายงานแอด: `ads.html`
- รายงานแอดมิน: `admin.html`
- หน้ารวมของช่วงนั้น: `index.html`

## หมายเหตุ

ไฟล์ใน local repo นี้ยังไม่ได้ push ขึ้น GitHub Pages จนกว่าจะได้รับคำสั่งจากคุณเบนซ์
