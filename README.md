# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development

## รายละเอียด
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels

## git command used in this lab
```bash
git add README.md
git commit -m "เพิ่ม README.md"
git push origin main

git checkout -b development
git add .
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
git push origin development

git checkout -b feature/homepage
# แก้ไข index.html
git add .
git commit -m "เพิ่ม header และ nav ในหน้าหลัก"
git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก"
git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"
git push origin feature/homepage

git checkout -b feature/contact
# แก้ไข contact.html
git add .
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
git commit -m "เพิ่มฟอร์มติดต่อ"
git commit -m "เพิ่ม validation ในฟอร์มติดต่อ"
git commit -m "เพิ่ม ARIA Labels ให้ฟอร์มติดต่อ"
git push origin feature/contact

git checkout development
git merge feature/homepage
git merge feature/contact
git push origin development
