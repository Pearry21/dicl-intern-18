﻿### DICL Internship Program 2018

สวัสดีน้องๆที่ให้ความสนใจมาฝึกงานที่บริษัท ดิจิตอล อินไซด์เดอร์ จำกัด ในปี 2018 นี้ทุกๆคนนะครับ ก่อนที่จะเข้ามาฝึกงานกับเรา พี่มีบททดสอบเล็กน้อยเพื่อวัดทักษะพื้นฐานสำหรับนักพัฒนา Mobile Developer น้องๆไม่จำเป็นต้องตอบหรือต้องรู้ทุกเรื่องในบททดสอบนี้ เพราะเรามาสามารถมาเรียนรู้กันภายหลังได้ เพียงแต่เราอยากให้น้องๆทุกคนลองทำด้วยตัวเอง ค้นคว้าเอง ทั้งหมดก็เพื่อประโยชน์ของตัวน้องๆเองและบริษัท หากใครสนใจส่งคำตอบกันมานะได้เลยนะครับ ปิดรับสมัครวันที่ 8 เมษายน 18 เวลา 23:59 น.

## 1. Code in Swift or Java / Kotlin
แบบทดสอบนี้จะดูทักษะความรู้ความเข้าใจเกี่ยวกับเรื่อง Collection เช่น Array, Dictionary เป็นต้น

ดาวน์โหลดข้อมูล [data.json](https://github.com/memogames/dicl-intern-18/blob/master/data.json) และเขียนโค้ดเพื่อหาคำตอบ
- 1.1 หาคะแนนเฉลี่ย **score** ของนักเรียน
- 1.2 แสดงชื่อและเกรดของนักเรียนที่ได้คะแนนมากว่า 70 ขึ้นไป
- 1.3 ค้นหาชื่อนักเรียนที่มีคะแนนมากที่สุดและต่ำที่สุด **score**

คำตอบ:
```
?
```

## 2. Create Simple Mobile Application

แบบทดสอบนี้จะดูทักษะความรู้ความเข้าใจสำหรับการพัฒนาแอปพลิเคชั่น และการใช้ UI พื้นฐานของแต่ละ Platform

### Features
- GET ข้อมูล JSON จาก [movie.json](https://github.com/memogames/dicl-intern-18/blob/master/movie.json)
- แสดงรายชื่อและรูปภาพใน ListView หรือ TableView
- ผู้ใช้สามารถกดเพื่อดูข้อมูลรายละเอียดได้ในหน้าถัดไป
- ผู้ใช้สามารถแชร์ข้อมูลชื่อหนังที่สนใจให้กับเพื่อนๆได้
- ออกแบบ UI ได้ตามความต้องการ
- ใช้ Library เพิิ่มเติิมได้

### Technical
- ดาวน์โหลดข้อมูล JSON
- เครื่องมือที่ใช้ Android Studio หรือ Xcode.

## 3. Tiny Question

Q1: Firebase คืออะไร มีฟังก์ชั่นที่น้องๆชื่นชอบนอะไรบ้างและเพราะอะไร (อย่างน้อย 3 ฟังก์ชั่น)

```
A1: คือ API และ Cloud storage ที่มีไว้สำหรับพัฒนา Application ฟังก์ชั่นที่ชื่นชอบ
- Firebase Analytics เพราะเป็นการวิเคราะห์ข้อมุล
- Firebase Storage เพราะเป็นการเก็บข้อมูลหรือไฟล์ขนาดใหญ่ที่สร้างอยู่บน กูเกิ้ล
- Firebase Test Lab for Android เพราะบริการทดสอบแอพบนฮาร์ดแวร์จริง
Ps.หนูก็ไม่ทราบว่าข้อมูลที่หามาลองศึกษาดูนั้นมากพอหรือถูกต้องไหมเพราะยังไม่เคยใช้ แต่จะลองศึกษาข้อมูลอย่างละเอียดดูค่ะ และหากได้ฝึกงานที่บริษัทพี่ตั้มก็อยากเก็บเกี่ยวประสบการณ์ในส่วนนี้เพราะน่าจะได้นำมาใช้ในการทำโปรเจคจบค่ะ
```

Q2: REST API คืออะไร

```
A2: คือ Web Service รูปแบบนึงที่อาศัย HTTP Method (GET, POST, PUT, DELETE) ในการทำงาน และส่งผลกลับมาในรูปแบบของ JSON 
```

Q3: หากต้องสร้างแอปพลิเคชั่น 1 ตัว เพื่อให้รองรับทั้งระบบ iOS และ Android วิิธีไหนที่น้องๆอยากเลือกใช้พัฒนาระหว่าง Native App กับ Cross Platform และเพราะอะไร 

```
A3:Native App เพราะจากที่ลองหาข้อมูลมาศึกษาดูแล้วดูจะใช้ง่ายกว่า Cross platform และอีกอย่างคือตัวโค้ดนั้นทำงานเข้ากับ ซีพียูโดยไม่ต้องอาศัย virtual machine
```

Q4: ถ้าให้เลือกได้ 1 บ้าน น้องๆอยากอยู่บ้านไหนระหว่าง Apple , Google และ Microsoft

```
A4:Google ค่ะเพราะมีความชื่นชอบในกูเกิ้ลดูไม่มีอะไรแต่กลับเป็นบ้านที่มีของ
```

Q5: เวลาว่างสิ่งที่ชอบทำที่สุดคืออะไร 2 อันดับแรก

```
A5:1.เล่นเกมส์   2.ดูการ์ตูน
```

Q6: แอปพลิเคชั่นไหนบนมือถือที่ชอบที่สุดและเกียจที่สุดตั้งแต่เคยใช้งานมา (ไม่รวมเกมส์) เพราะอะไร

```
A6: ที่ชอบที่สุดคือ AutoSurver เพราะแอปพลิเคชั่นที่ใช้ง่าย รวดเร็วเป็นแอปที่มีไว้เก็บข้อมูลการทำวิจัยแอปสามารถรวบรวมและสรุปข้อมูลให้เราไว้ผ่านกล้องเราไม่ต้องมานั่งกรอกข้อมูลอีกรอบหลังจากสำรวจมาแล้ว
ที่ไม่ชอบที่สุดคือ wePAY ไม่ใช่ว่าไม่ชอบมากเพราะรู้สึกว่าแอปพลิเคชั่นที่มีการพัฒนาขึ้นมานั้นดีหมด แต่พอดีแอปพลิเคชั่นตัวนี้มีความใช้ยากนิดนึง อาจจะทำให้ งงๆและไม่ค่อยสวยงามแค่นั้นค่่ะ
```

Q7: อะไรบ้างที่น้องๆคาดว่าจะได้รับในขณะที่ฝึกงานกับพวกเรา?

```
A7:ประสบการณ์การทำงานร่วมกับผู้อื่นในบริษัทจริง ความรู้เกี่ยวกับงานทำงานว่าถ้าเรามาทำงานในบริษัทจริงๆแล้วนั้นเราต้องวางแผนงานยังไง ทำงานยังไง ถึงจะได้ตามเป้าหมายที่เราตั้งไว้ ตัวอย่างงานที่เราจะต้องทำหากเราเลือกที่จะทำงานสายนี้ และอีกมากมายเลยค่ะที่หนูอยากจะเก็บเกี่ยวจากการฝึกงานครั้งนี้ไม่เฉพาะเรื่องโปรแกรมแต่อาจจะเป็นด้านอื่นๆด้วยเช่นธุรกิจ
```

## Submitting

ให้น้องๆ fork repo นี้แล้วตอบคำถาม จากนั้นส่ง repo มาที่ อีเมลล์ memo.games@gmail.com
