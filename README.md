ชื่อ-นามสกุล: นายอภิสิทธิ์ สุมาวรรณ์

การศึกษา: นักศึกษาภาควิชาวิทยาการคอมพิวเตอร์ คณะศิลปศาสตร์และวิทยาศาสตร์ มหาวิทยาลัยเกษตรศาสตร์

ทักษะ (Skills): Java, Assembly (RISC-V), SQL / Database, HTML/CSS/JavaScript, and Computer Graphics Algorithms

Project Title: 24-bit Sprite Low-Level Transformation System

โครงสร้างพิกเซลระดับต่ำ: โปรแกรมทำการจอง Buffer บนหน่วยความจำผ่านหน้าจอโครงสร้าง ctx.createImageData
เพื่อเข้าถึงและควบคุมค่าสีแต่ละเม็ดพิกเซลบน Canvas ได้โดยตรง
ในรูปแบบ Array ผืนผ้าใบเดี่ยว [R, G, B, A, ...]  การคำนวณสีระบบ 24-bit (True Color): ผ่านฟังก์ชัน putPixel(x, y, r, g, b)
ที่รับพิกัดแผงสกรีนและทำการแยกพิกเซลย่อยแบบช่องสีละ 8-bit (Red 8-bit, Green 8-bit, Blue 8-bit)
ทำให้สามารถประมวลผลการผสมสีที่มีความลึกของสีแบบ 24-bit ได้สูงสุดถึง 16.7 ล้านสีอย่างอิสระ
