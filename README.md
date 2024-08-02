# JPEG-Artifact-Generator

- JPEG Artifact Generator คือเครื่องมือที่ใช้ในการสร้างหรือเพิ่มความผิดเพี้ยนของภาพ (artifacts) ที่เกิดจากการบีบอัดไฟล์ JPEG ซ้ำๆ โดยปกติแล้ว artifacts จะเป็นสิ่งที่ไม่พึงประสงค์ในภาพถ่าย แต่ในบางกรณีก็อาจถูกนำมาใช้เพื่อสร้างสรรค์ผลงานศิลปะหรือเอฟเฟกต์ภาพที่น่าสนใจ

หลักการทำงาน:

JPEG เป็นรูปแบบการบีบอัดภาพแบบ lossy ซึ่งหมายความว่าข้อมูลบางส่วนของภาพจะสูญหายไปในการบีบอัด เพื่อลดขนาดไฟล์ การบีบอัดซ้ำๆ จะทำให้ข้อมูลสูญหายมากขึ้น และทำให้เกิด artifacts มากขึ้นตามไปด้วย

JPEG Artifact Generator จะใช้หลักการนี้ในการสร้าง artifacts โดยการบีบอัดภาพ JPEG ซ้ำๆ ด้วยระดับคุณภาพที่ต่ำลงเรื่อยๆ ซึ่งจะทำให้เกิดความผิดเพี้ยนของภาพในรูปแบบต่างๆ เช่น

Blockiness: ภาพแตกเป็นบล็อกๆ
Color banding: สีเพี้ยนเป็นแถบๆ
Ringing: เกิดขอบสีรุ้งรอบวัตถุ
ประโยชน์:

การศึกษา: ศึกษาผลกระทบของการบีบอัด JPEG ต่อคุณภาพของภาพ
การทดลอง: ทดลองสร้างเอฟเฟกต์ภาพที่น่าสนใจจาก artifact
ศิลปะ: สร้างสรรค์ผลงานศิลปะที่ใช้ artifact เป็นองค์ประกอบ
