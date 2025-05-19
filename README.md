# Pizza-Sales-Data-Analytic-Project

## Project Canvas
![Project Canvas_2](https://github.com/user-attachments/assets/a34564db-43fd-477c-8571-7ed62893deca)


## Data Preparation
colab link
https://colab.research.google.com/drive/1nMtah_ABQGwAeaacqiCl4ZoKORMj-XSD?usp=sharing 
เราได้ทำการตรวจหา null value ใน data แต่ไม่พบ และนอกจากนั้นยังมีการทำ data enginerring เพิ่ม column และ sheet เพิ่มเติมเพื่อใช้ในการนำไป visualize 

## Exploratory Data Abakysis 
เราได้ใช้ Tableau แสดงข้อมูลที่เราสนใจต่างๆ ดังนี้

 ยอดขายรวมในแต่ละเดือน
![Screenshot_2025-05-18_142230](https://github.com/user-attachments/assets/41abadc7-6519-4983-830a-b2bcf591fc96)

ยอดขายรวมในแต่ละ quarter
![Screenshot_2025-05-18_142239](https://github.com/user-attachments/assets/5064b9fc-4732-4fb8-b87b-d0930e62412f)

ยอดขายพิซซ่าแต่ละหน้าในแต่ละช่วงเดือน
![Screenshot_2025-05-18_142213](https://github.com/user-attachments/assets/ea7f8384-b7fd-4586-a575-45d634b371e8)

ยอดขายทั้งหมดของแต่ละหน้าพิซซ่า
![Screenshot_2025-05-18_142349](https://github.com/user-attachments/assets/c1af1cc9-e3d3-4539-8886-bf9d679f4ab8)

จำนวน order ในแต่ละ bill 
![Screenshot_2025-05-18_142146](https://github.com/user-attachments/assets/bb9c3a71-1ff6-46fa-9a7e-4cc16fe04d87)

## In-Depth Analysis
### Analytical Question
1.สินค้าที่มียอดขายดีอย่างต่อเนื่องมีอะไรบ้าง
2.สินค้าที่ยอขายต่ำที่สุดคืออะไร
### Statistic test
เราได้ทำการวิเคราะห์ดูว่าสินค้าที่ยิ่งมีราคาสูงขึ้นจะส่งผลให้ยอดขายของสินค้านั้นๆ น้อยลงด้วย
โดนผลที่ได้เป็นดังนี้

![Screenshot_2025-05-18_142253](https://github.com/user-attachments/assets/3cd82278-45bb-418c-a803-06e4bb869605)

จากภาพคือ จำนวนยอดจำนสนการทำรายการของสินค้าที่มีราคาต่างๆ โดยเส้น trendline เป็น linear แบบ  downtrend ซึ่งหมายความว่า  
ยิ่งราคาแพงขึ้นความต้องสั่งก็เพิ่มขึ้นซึ่งหักล้างกับสมมติฐานไว้ แต่อย่างไรก็ตามความชันของเส้นนี้นน้อยมากทำให็ตัดสินทางสถิติได้อย่างแน่นอน

##Link to public tableau dashboard
https://public.tableau.com/shared/2496J2TH8?:display_count=n&:origin=viz_share_link



