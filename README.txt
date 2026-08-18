งบประมาณรายจังหวัด 77 จังหวัด ปี 2570 — Interactive Dashboard

ไฟล์หลัก
- index.html : Dashboard แบบ self-contained เปิดได้ทันทีใน browser
- province_category_long.csv : Long format 693 แถว เหมาะกับ Flourish/analysis
- province_category_wide.csv : Wide format 77 แถว พร้อม budget/items/percent ของ 9 หมวด
- data.json : ข้อมูลที่ dashboard ใช้

ตรวจสอบข้อมูล
- จังหวัด: 77
- หมวด: 9
- งบรวม 77 จังหวัด: 544,762.0529 ล้านบาท
- จำนวน Direct rows: 62,814
- ทุกจังหวัด category total reconcile กับ SUMMARY_77
- ทุกจังหวัด item count reconcile กับ SUMMARY_77
- QA Status ใน SUMMARY_77: PASS

การเปิดใช้งาน
1) แตก ZIP
2) ดับเบิลคลิก index.html
3) ใช้ Heatmap / Stacked bar / Dropdown ได้ทันที โดยไม่ต้องต่ออินเทอร์เน็ต

การแชร์ให้คนอื่นเล่น
A) แบบ Flourish
- ใช้ province_category_long.csv หรือ province_category_wide.csv เป็นข้อมูล
- สร้าง visualization/story ใน Flourish แล้วกด Export & publish > Publish to share and embed
- ส่ง public Flourish URL ให้ผู้ชม หรือ copy embed code ไปวางบนเว็บไซต์

B) แชร์ Dashboard HTML นี้โดยตรง
- อัปโหลดโฟลเดอร์นี้ขึ้น static web hosting (เช่น GitHub Pages / Cloudflare Pages / Netlify หรือเว็บของคุณ)
- ต้องให้ index.html อยู่ที่ root ของเว็บ
- เมื่อเปิดผ่าน https:// ปุ่ม “แชร์” ใน dashboard จะ copy/share URL ได้

หมายเหตุ
Dashboard ใช้เฉพาะงบตรงจังหวัดตาม Frozen V3.3 จากไฟล์ต้นทาง ไม่รวม Multi-province / Regional / National / Unknown ในยอดจังหวัด
