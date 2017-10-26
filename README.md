#EasyCarbage Game Design and Development 

## Section I - Game Overview

## Game Concept
1. รณรงค์ให้ผู้เล่นรู้จักการคัดแยกขยะอย่างถูกต้อง เพื่อช่วยกระตุ้นให้ทุกคนหันมาสนใจรักษาสิ่งแวดล้อม ซึ่งเป็นเรื่องที่ใกล้ตัวของทุกคน
2. เพื่อสร้างความบันเทิงให้กับผู้เล่น โดยการนำความรู้มาสร้างเป็นเกม เพื่อช่วยกระตุ้นจิตสำนึกให้คนหันมารักโลกมากขึ้น

## Feature Set
พัฒนาบนระบบปฏิบัติการ Android โดยใช้ Adobe AIR ในการพัฒนา

## Genre
ประเภท Platform Game ใช้การเคลื่อนที่ซ้ายและขวาเพื่อทำการเก็บขยะ ด้วยเวลาที่จำกัดมากขึ้น และขยะที่มีมากขึ้น

## Target Audience
เด็กนักเรียนระดับชั้นประถมศึกษาปีที่ 3 อายุ 9-10 ปี

## Look and Feel
-What is the basic look and feel of the game?
การออกแบบเกม เราได้กำหนดตัวละครไว้ 2 ตัวละคร และการออกแบบ Texture เรากำหนดไว้ด้วยโทนสีเขียว
-What is the visual style?
การออกแบบด่าน กำหนดไว้ 4 ด่าน โดยเราจะเน้นการจับเวลาและนับ Score โดยที่เวลาจะเร็วขึ้นและ Object จะมีมากขึ้น

## Project Scope - A summary of the scope of the game.
-Number of Locations : 1 Location
-Location Number of levels : 4 Levels 
-Number of NPC's : 1 Player แล้วสะสมแต้ม
-Number of Weapons : ไม่มีอาวุธ แต่ใช้ลักษณะการเก็บของ

## Section II - Gameplay and Mechanics
-Gameplay 
	-Gameplay Progression : เกมจะมีการจำกัดเวลาและเพิ่มความเร็วในการ Random Enemy ให้มากขึ้น
	-Mission/challenge Structure : เกมจะมีการกำหนดในแต่ละด่านว่าจะให้เก็บขยะประเภทไหน ซึ่งจะไม่ซ้ำกันในแต่ละด่าน
	-Puzzle Structure and Objective : ถังขยะประเภทต่างๆ ซึ่งมีทั้งหมด 4 ถัง คือ ถังขยะ Recycle Toxin, Biological และ Garbage
-Mechanics 
	-Physics : เกมจะใช้กฏการเคลื่อนที่ตามแนวแกน X,Y ตามกฏของนิวตั้น
	-Movement : ตัวละครจะเคลื่อนที่ซ้ายขวา ส่วนวัตถุจะตกลงสู่พื้นด้วยความเร็วคงที่ที่ตำแหน่งที่ต่างกัน
	-Objects : ขยะจะเข้ามาชนกับถังขยะ โดยผู้เล่นจะทำการเลื่อนถังขยะเข้ามาเพื่อเก็ยขยะแล้ว Score จะขึ้น
	-Actions 
		-Switches and Buttons : จะมี Button ให้เลือกเริ่มเกม (Start) และ สอนการเล่นเกม (Tutorial)
		-Picking Up, Carrying and Dropping : เกมจะหยุดเมื่อเวลาหมดและจะผ่านไปสู่ด่านต่อไป

##Section III - Story, Setting and Character
	-Story and Narrative
		-Back Story : มีการกำหนดหัวข้อเกมที่เกี่ยวข้องกับสิ่งแวดล้อม โดยทำการศึกษาข้อมูลพื้นฐานการคัดแยกขยะจากเว็บไซต์ แล้วนำมาจัดทำเป็นเกม
		-Plot Elements : ศึกษาการออกแบบและ Design ตัวละครด้วยโปรแกรม Adobe Illustrator และศึกษาการเขียน Actionscript 3.0 ด้วย Adobe Flash CS5.5
		-Game Progression : เราได้ออกแบบด่านไว้ทั้งหมด 4 ด่านโดยการใช้ Random Code และ Timer ในการออกแบบ เพื่อเพิ่มความยากง่ายให้กับเกม
	-Game World (Area) : ฉากที่ได้ทำการออกแบบ ก็คือ พื้นที่ชานเมืองที่มีการทิ้งขยะ
	-Characters : ลักษณะตัวละครก็จะเป็นเด็กที่มีความน่ารัก มีความอ่อนหวาน

##Section IV - Levels 
	- เราได้ทำการสร้างตัวหลอกเพื่อให้ผู้เล่นได้คิดและคัดแยกขยะได้อย่างถูกต้องในแต่ละด่าน
	- เพื่อฝึกสายตาของผู้เล่นให้มีความไว และช่วยรณรงค์การแยกขยะอย่างถูกวิธีด้วย
	Sound : เสียงที่ใช้จะเป็นเสียงที่กระตุ้นให้ผู้เล่นรู้จักที่จะต่อสู้เพื่อตัวเองและโลกที่สวยงาม

##Section VII - Technical
	-Target Hardware : Android Tablet and Mobile
	-Development hardware and software : การพัฒนาด้วย Adobe Flash Professional CS5.5 และ CS6 โดยใช้ภาษา Actionscript 3.0
	-Development procedures and standards 
		-ศึกษาการเขียนเกมโดยใช้ภาษา Actionscript 3.0 
		-ศึกษาการออกแบบเกมและการสร้าง Interface ให้กับเกม
		-ศึกษาการ Debug ของเกมโดยใช้ภาษา Actionscript 3.0
		-ศึกษาการ Export เกมเพื่อใช้งานระบบปฏิบัติการ Android 
	-Game Engine
		-Adobe Flash Professional CS5.5 and CS6
		-Adobe AIR for Android 
	-Script Language
		-Actionscript 3.0

##Section IX - Secondary Software
	-Editor : การปรับปรุง Source Code โดยใช้เทคโนโลยี AI เข้ามาช่วยให้เกมเกิดความฉลาดมากยิ่งขึ้น
	-Installer : การติดตั้งลงบน Windows และการเล่นผ่านระบบปฏิบัติการ Android 
	-Update software : การพัฒนา Interface และปรับปรุงด่านให้มีความหลากหลายมากยิ่งขึ้น

##Section X - Management
	-Budget : Software ที่ใช้ เราพยายามนำ Open Source มาใช้งาน อย่างเช่น โปรแกรม FlashDevelop ซึ่งใช้ในการเขียน Package ให้กับเกม 
	-Risk Analysis : การบริหารการทำงานภายในกลุ่ม เนื่องจากเพื่อนสมาชิกในกลุ่มส่วนใหญ่มีความสามารถทางด้านการออกแบบมากกว่าการพัฒนา Source Code ดังนั้น ทางทีมพัฒนาจึงต้องใช้เวลาในการพัฒนาเกมค่อนช้างนาน
	-Localization Plan : เราได้กำหนดเครื่องที่จะใช้ทดสอบไว้จำนวน 2-3 เครื่อง เพื่อทดสอบ Script และตัวเกม
	-Test Plan : มีการทดสอบเกมบน PC และ Mobile 

##Appendices 
	-Asset List 		
		-Model and Texture List : ใช้ภาพ Vector โดยการ Sketch และ Draft ลงไปใน Adobe Illustrator Program แล้ว Import ลง Adobe Flash 
		-Animation List : ใช้ Motion Tween ในการกำหนดการเคลื่อนไหวของเกม
	-Sound : ใช้เสียงที่แสดงถึงความมีพลัง และใช้ Effect พื้นฐานประกอบ เช่น เสียงเก็บของ, เสียงตกใจ, Victory (เสียงแห่งชัยชนะ), Defeat (เสียงความพ่ายแพ้)