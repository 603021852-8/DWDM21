# DWDM21
Data Warehouse &amp; Data Mining 2021

กรกนก สังฆพันธ์ 603021852-8

Group Name : แมวส้มสร้างตัว

1 กรกนก สังฆพันธ์ 603021852-8

2 นางสาววานิตา สมเด็จ 623020536-5	

3 นายคำแสน แก้วพิภพ 623020761-8

4 นายจิตรกร จันทะสี 623021044-1

5 นางสาวอาธิติยา ธรรมวงษา 623021058-0

# สารบัญเนื้อหา

## วิชา Data Mining and Data Warehouse

- บทที่ 1 Introduction https://github.com/603021852-8/DWDM21/blob/main/Data101(Chapter2).ipynb

  - Short Note 1 https://github.com/603021852-8/DWDM21/blob/main/Chapter1
  - Why Data Mining ? (ทำไมต้องมีการทำเหมืองข้อมูล)
  - What is Data Mining ? (อะไรคือการทำเหมืองข้อมูล)
  - Knowledge Discovery (KDD) Process
  - กระบวนการจัดการข้อมูล
  - Data Mining in Business Intelligence
  - เนื้อหาหลักของ Data Mining ประกอบด้วย 3 เรื่อง
    - Pattern Discovery (หารูปแบบที่ซ่อนในข้อมูล)
    - Classification (จำแนกข้อมูล)
    - Clustering (จัดกลุ่มข้อมูล)
  - How the data suppose to look like ประกอบไปด้วย
    - Columns(แนวตั้ง) = Attributes,Fields,Features (คำอธิบายคุณสมบัติของข้อมูล)
    - row (แถว) = Records,Data point (ข้อมูลแต่ละตัว)
  - เทคนิคของ Data Mining ประกอบด้วย 3 เรื่อง
    - Data Mining Functions:(2) Pattern Discovery
    - Data Mining Functions:(3) Classification
    - Data Mining Functions:(4) Cluster Analysis


- บทที่ 2 Getting to Know Your Data https://github.com/603021852-8/DWDM21/blob/main/Data102_(Chapter2).ipynb

  - Short Note 2 https://github.com/603021852-8/DWDM21/blob/main/Chapter2.pdf
  - Basic Python https://github.com/603021852-8/DWDM21/blob/main/Data101(Chapter2).ipynb
    - Casting
    - Data Structure
      -วิธีสร้าง list ว่าง
        -การชี้ค่าใน list (Indexing)
      -list slicing
      -list + list
       -fomat string
    - Loop
       -Nested loop (loop ซ้อน Loop)
    - Condition (if statement)
    - Function
      -Example 1
      -ลักษณะของ input (parameter,argument)
  - Plot Data https://github.com/603021852-8/DWDM21/blob/main/Data102_(Chapter2).ipynb
    - Basic Data
    - การใช้ .head() .tail() ในการเรียกดูตาราง
    - Boxplot
    - Time Series Plot
  - Visualization https://github.com/603021852-8/DWDM21/blob/main/Data_Visualization.ipynb
    - Scatter plot
    - Plot
    - Bar chart
      -Grouped Barchart
      -Stacked Barchart
    - Histogram
  - Distance Numpy https://github.com/603021852-8/DWDM21/blob/main/Distance_Numpy.ipynb
    - Numpy Array
      - สร้าง numpy array
      - matrix transpose
      - สร้าง matrix เริ่มต้น (zeros,ones)
      - สร้าง matrix random ค่าเเบบมั่วๆ
        - matrix properties
      - Indexing & Slicing
      - Useful functions
        - วนลูปเอง
        - summation รวมค่าทุกค่าใน array
    - Distance Matrix
      - Euclidean Distance (L2-norm)
      - Distance function
      - Manhattan Distance (L1-norm)
      - Distance of Binary Value
 


- บทที่ 3 Data Preprocessing https://github.com/603021852-8/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb

  - Short Note 3
  - Meta Data (Data ที่ใช้อธิบาย Data)
  - ชี้ข้อมูลในตาราง
    - ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
    - ชี้เเบบ .iloc[] (มองข้อมูลเป็น matrix)
  - Missing Values
    - Handling Missing Value 1 (ลบค่า Missing )
    - Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
    - Handling Missing Value 2 (เเทนด้วย class ใหม่(Unknown))
    - Handling Missing Value 3 (เเทนด้วย class ใหม่ (ค่าที่เหมาะสม))
    - Handling Missing Value4(เเทนด้วย ค่ากลาง)
    - Handling Missing Value 5 (เเทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
  - เติมด้วยค่าของ column ใกล้เคียง
  - Select data by values [PD]
    - สร้าง list ของ boolean
    - นำ list ของ boolean มาเลือกค่าในตาราง
    - การเรียงข้อมูล [PD]
  - Outlier
    - Pandas' looping(.iterrows)
  - การรวมตาราง Data Integration (ต่อตารางในเเนวเเกน x)
    - รวม 2 ตาราง (.merge())
    - เลือกเฉพาะ column ที่ต้องการมาเเปะ (.map())
    - ตารางรอง(ตารางข้างขวา)ต้องไม่มี index ซ้ำ*
    - Group by (pandas)
    - [PD] save ตารางเอาไปใช้ที่อื่น
    - [PD] การสร้างตาราง


- บทที่ 4 Data Warehousing and On-line Anaalytical Processing 
  - Short Note 4 
  - What is a Data Warehouse?
  - From Tables and Spreadsheets to Data Cubes
  - Conceptual Modeling of Data Warehouses
  - Star Schema: An Example
  - Snowflake Schema: An Example
  - Fact Constellation: An Example
  - Typical OLAP Operations
  - Roll up (drill-up)
  - Drill down (roll down)
  - Slice and dice
  - Pivot (rotate)
  - Drill across
  - Drill through


- บทที่ 5 Association_Rules https://github.com/603021852-8/DWDM21/blob/main/Chapter6_Association_Rules.ipynb
  - Shot Note 5
  - [Q] มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
  - ลบ records ที่ถูก cancel ออกไป
  - เพิ่มคอลัมน์ ยอดขาย (Quantity*UnitPrice)
  - เพิ่ม column ราคารวม
  - เตรียม Data สำหรับ (Frequence Pattern) Association Rule
  - Apriori




- บทที่ 6 Classification Association  https://github.com/603021852-8/DWDM21/blob/main/Chapter6_Association_Rules.ipynb

  - Shot Note 6
  - ลบ records ที่ถูก cancel ออกไป
  - การบ้านครั้งที่ 13 วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
  - เตรียม Data สำหรับ (Fequence Pattern) Association Rule
  - Apriori
  - (Quiz 7)


- บทที่ 7 Classification  https://github.com/603021852-8/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb

  - Shot Note 7
  - Load Data
  - train (ฝึกสอนตัวแบบ)
  - plot tree
  - Evaluation
  - Random
  - Advanced Tree
  - TEST
  - Start here
  - Train - Test
  - Train - Validation
  - การบ้านครั้งที่ 16


- บทที่ 8 Chap_8_Clustering https://github.com/603021852-8/DWDM21/blob/main/chapter8_Clustering.ipynb

  - K-means
  - Generat Data
  - Explole data
  - Clustering
  - ตัวอย่าง
  - นับจำนวนสี
  - จัดกลุ่มสีให้เหลือ 16 สี
  - แปลงข้อมูลให้อยู่ในรูป row-column
  - ใช้ centroid เป็นตัวแทนของสี
  - แทนสีคืนลงไป
  - Hierachical Clustering
  - Clustering Evaluation
  

- สอบมิดเทอม MiniExam https://github.com/603021852-8/DWDM21/blob/main/MiniExam.ipynb

- โปรเจค Project https://github.com/603021852-8/DWDM21/blob/main/Group_Project.ipynb
  - Slide นำเสนอ https://github.com/603021852-8/DWDM21/blob/main/%E0%B8%99%E0%B8%B3%E0%B9%80%E0%B8%AA%E0%B8%99%E0%B8%AD_PROJECT_DWDM21.pdf
