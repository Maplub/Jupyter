# Jupyter
**Air Quality Explore** นำข้อมูลรายวันของจุฬามาแสดงในรูปแบบ heatmap กับกราฟ จะได้ทราบว่าวันไหนมีข้อมูล วันไหนข้อมูลหาย และวันไหนมีค่าฝุ่นสูงผิดปกติ จะได้วิเคราะห์ละเอียดต่อไป<br />
**Chiangmai** นำข้อมูลดิบที่จดไว้ที่เชียงใหม่มาเปลี่ยนเป็นข้อมูลรายชั่วโมง จะได้เอาไปเทียบกับข้อมูลคอพ.ที่เป็นชั่วโมงได้<br />
**Compare คอพ and จุฬา at เฉลิมพระเกียรติ** นำข้อมูลที่ผ่านการแปลงให้เทียบกันได้แล้วมาพล๊อตกราฟ<br />
**Haze Data Preparation for Comparison** แปลงข้อมูลรายชั่วโมงของคอพกับจุฬาฯให้เทียบกันได้ เนื่องจากข้อมูลจุฬาฯถ้าหายไปจะไม่มีวันนั้นขึ้นมาเลย แต่คอพ.มีทุกวันถึงแม้ว่าข้อมูลจะไม่มีบ้าง (ข้อมูลหายจะแสดงด้วย -)<br />
**2018 Analysis.ipynb** ทำ heat map กับ animation จากข้อมูลที่มาจาก grafana เป็นข้อมูลปี 2018 จะมี PM2.5 กับ PM10 แยกกัน
**ST_Variogram** ทำ variogram ข้อมูลรายวันในปี 2018
**ST_Variogram_hourly** ทำ variogram ข้อมูลชั่วโมงในปี 2018
ทั้งหมดนี้ใช้ภาษา R บน Jupyter Notebook
