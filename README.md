# BSC_DPDM23
**Data Preparation and Data Mining 2023** 
> Bachelor of Science Program in Statistics and Data Science, Department of Statistics, Faculty of Science, Khon Kaen University

> [!NOTE]
> SC663403 การเตรียมข้อมูลและการทำเหมืองข้อมูล: แนวคิดของการเตรียมข้อมูล ชนิดและประเภทของข้อมูล เครื่องมือที่ใช้ในการเตรียมข้อมูล การจัดการข้อมูลในรูปแบบต่าง ๆ พื้นฐานของการทำเหมืองข้อมูลและแนวคิดเชิงพรรณนา การสกัดความรู้จากข้อมูล อัลกอริทึมการสร้างตัวแบบเพื่อการทำนายการค้นพบความสัมพันธ์ในการทำเหมืองข้อมูล การจัดกลุ่มข้อมูล เทคนิคการประเมินตัวแบบ การเรียนรู้จากตัวแบบที่หลากหลาย และ กรณีศึกษาที่เกี่ยวข้อง

> [!CAUTION]
> 💪 อาจารย์ผู้สอน: ผศ.ดร.ธนพงศ์ อินทระ

> [!TIP]
> **📖 Ratchanont Thippimanporn ID: 643020515-5**
>
> **👨🏻‍🎓 นายรัชชานนท์ ทิพย์พิมานพร  รหัสนักศึกษา 643020515-5**

> [!IMPORTANT]
> - Data Set to use for this class >> [Click](https://drive.google.com/drive/folders/1XVikUBDEA_mrSnil8DE7i7uWCADmyeqj?usp=sharing)
> - Sheet from Aj. Tohn >> [Click](https://drive.google.com/drive/u/0/folders/1N2rPW5cc8A_tj9f3FdCyPBujePaiBZzx)

## Table of Contents 
- [Scoring](#Scoring)
- [Homework](#homework)
- [Quiz](#quiz)
- [Midterm Test - Data Preprocessing](#midterm-test---data-preprocessing)
- [Project: Data Preparation & Data Mining](#project-data-preparation--data-mining)
- [Chapter 1 - Introduction to Data Mining](#chapter-1---introduction-to-data-mining)
- [Chapter 2 - Getting to Know Your Data](#chapter-2---getting-to-know-your-data)
- [Chapter 3 - Data Preprocessing](#chapter-3---data-preprocessing)
- [Chapter 6 - Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods](#chapter-6---mining-frequent-patterns-association-and-correlations-basic-concepts-and-methods)
- [Chapter 8 - Classification: Basic Concepts](#chapter-8---classification-basic-concepts)
- [Chapter 9 - Classification: Advanced Methods](#chapter-9---classification-advanced-methods)
- [Chapter 10 - Cluster Analysis: Basic Concepts and Methods](#chapter-10---cluster-analysis-basic-concepts-and-methods)

## Scoring

| Activity                  | Score %    | Type         | Note      |
|---------------------------|------------|--------------|-----------|
| Midterm                   |  ![](https://geps.dev/progress/20?dangerColor=800000&warningColor=ff9900&successColor=006600)       | Data Preprocessing | ปฏิบัติ-เดี่ยว
| Final                     | ![](https://geps.dev/progress/20?dangerColor=800000&warningColor=ff9900&successColor=006600)       | Data Mining | ทฤษฎี-เดี่ยว
| Project                   | ![](https://geps.dev/progress/30?dangerColor=800000&warningColor=ff9900&successColor=006600)       |Data Preprocessing + Data Mining | กลุ่ม
| Homework                  | ![](https://geps.dev/progress/20?dangerColor=800000&warningColor=ff9900&successColor=006600)        |Data Mining|แบ่งกลุ่มใหม่ทุกครั้ง
| Quiz                      | ![](https://geps.dev/progress/5?dangerColor=800000&warningColor=ff9900&successColor=006600)         |All Contents|ถามในห้อง-เดี่ยว
| GitHub Contributions      | ![](https://geps.dev/progress/5?dangerColor=800000&warningColor=ff9900&successColor=006600)         |-|-
| Total | ![](https://geps.dev/progress/100?dangerColor=800000&warningColor=ff9900&successColor=006600)|Total Score|**Final Score** = Total Score * %Attendance


## Homework
### HW 1 : หา frequent Item Set และ Association Rules
>1. จัดกลุ่มตาม Transaction (Invoice_No)
>* ของช่วงเวลา Chritmas & New Year ทั่วโลก (1 Dec - 31 Dec)
>* ของประเทศในทวีป Europe
>* ของประเทศในทวีป Asia
>* ของช่วงเวลา ตรุษจีน ในทวีป Asia (15 Jan - 15 Feb)
>* ของช่วงเวลา Chritmas & New Year ในทวีป Europe (1 Dec - 31 Dec)
>* ของวันวาเลนไทน์ (14 Feb)

> 2. โดยจัดกลุ่มตามประเทศ + เดือน (ประเทศ-เดือน ถือเป็น 1 transaction)

- [Slide - Homework 1 ](https://github.com/Ratchanontt/BSC_DPDM23/tree/main/Home_Work/HW1)
- [Code - Homework 1 ](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Frequent_Patterns_(Association_Rules).ipynb)

### HW 2 : Create Decision Tree by hand
- [Homework 2](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Home_Work/HW2/HW2_Decision%20Tree.pdf)

### HW 3 : Create Decision Tree with Parameters (min_samples_split & splitter)
> ให้แต่ละกลุ่ม สร้างต้นไม้ของตัวเอง โดยปรับเปลี่ยน parameters ให้ และ มาอธิบาย parameter ของตัวเอง ว่ามันคืออะไร
> -   แถว 1 criterion, max_leaf_nodes
> -   แถว 2 splitter, min_samples_split
> -   แถว 3 min_samples_leaf, max_features
> -   แถว 4 min_impurity_decrease
> -   แถว 5 min_weight_fraction_leaf
- [Slide - Homework 3](https://github.com/Ratchanontt/BSC_DPDM23/tree/main/Home_Work/HW3)
- [Code - Homework 3](https://colab.research.google.com/github/Ratchanontt/BSC_DPDM23/blob/main/Classification.ipynb#scrollTo=tL_i-KuGJlO7)

### HW 4 : Create Decision Tree with Parameters (min_samples_split & splitter) by hand
- [Slide - Homework 4](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Home_Work/HW4/HW4_DecisionTree_Calculate.pdf)
- [Calculate - Homework 4](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Home_Work/HW4/HW4_Calculate_DecisionTree.pdf)

### HW 5 : Perceptron Learning Example - Function AND
- [Homework 5](https://github.com/Ratchanontt/BSC_DPDM23/tree/main/Home_Work/HW5)


## Quiz
### Quiz 1-2-3
- [Quiz 1 2 3](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Data_Preprocessing.ipynb): เลือกหาที่ Table of contents
1. Q1 : Ignore Missing
- Data หายไปกี่ % 
- mean data รวมหลังจากแก้ missing เป็นเท่าไหร่
2. Q2 : mean ใหม่ หลังจากเติมค่า null ด้วยค่าเฉลี่ย เป็นเท่าไหร่?

3. Q3 : เติมด้วยค่าเฉลี่ยของกลุ่ม
-   mean หลังเติมด้วยค่าเฉลี่ย Clothing
-   mean หลังเติมด้วยค่าเฉลี่ย Cash
-   mean หลังเติมด้วยค่าเฉลี่ย Metrocity
-   mean หลังเติมด้วยค่าเฉลี่ย Cash + Metrocity

### Quiz 4 :  ลบ columns ที่มีค่า correlation เป็น 1 เมื่อเทียบกับ column อื่น
- [Quiz 4](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Dimensionality_Reduction_PCA.ipynb): เลือกหาที่ Table of contents

### Quiz 5-6
- [Quiz 5 6](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Frequent_Patterns_(Association_Rules).ipynb) : เลือกหาที่ Table of contents
5. ข้อมูลมาจากกี่ประเทศ ?
6. รหัสสินค้า 22386 และ 85099B เป็นสินค้าอะไร
### Quiz 8: Naïve Bayes Classifier
- [Quiz 8](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Quiz/Quiz8_Na%C3%AFve%20Bayes%20Classifier.pdf)

### Quiz 9: Confusion Matrix
- [Quiz 9](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Quiz/Quiz9_Classifier_Evaluation%20Metrics_Confusion_Matrix.pdf)


## Midterm Test - Data Preprocessing

- Code >> [เตรียมข้อมูลอุตุนิยมวิทยา](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/midterm_bscdpdm23.ipynb "midterm_bscdpdm23.ipynb")
- Use data set >> [อุตุ](https://drive.google.com/drive/folders/1k6tJcTTv2bKmFz6A5oOWi-sAeTVIQpG4)


## Project: Data Preparation & Data Mining
- Code >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Project.ipynb)
- Presentation >>> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Project%20Element/%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1%20NMN%20%26%20%E0%B8%AB%E0%B8%AD%E0%B8%A2%E0%B8%AB%E0%B8%A5%E0%B8%AD%E0%B8%94%E0%B8%94.pdf)


## Chapter 1 - Introduction to Data Mining
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/01Intro.pdf)
- Code >> [Click]


## Chapter 2 - Getting to Know Your Data
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/02Data.pdf)
- Code >> [Understanding Data](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Understanding_Data.ipynb)


## Chapter 3 - Data Preprocessing
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/03Preprocessing.pdf)
- Code >> [Data Preprocessing](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Data_Preprocessing.ipynb)
- Code >> [Dimensionality Reduction](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Dimensionality_Reduction_PCA.ipynb)


## Chapter 6 - Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/06FPBasic.pdf)
- Code >> [Frequent Patterns (Association Rules)](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Frequent_Patterns_(Association_Rules).ipynb)


## Chapter 8 - Classification: Basic Concepts
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/08ClassBasic.pdf)
- Code >> [Decision Tree](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Classification.ipynb) : Holdout Cross Validation Method


## Chapter 9 - Classification: Advanced Methods
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/09ClassAdvanced.pdf)
- Code >> [Training Framework](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Classification.ipynb) : K-fold Cross Validation Method


## Chapter 10 - Cluster Analysis: Basic Concepts and Methods
- Slide >> [Click](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/10ClusBasic.pdf)
- Add Slide >> [Artificial Neural Network](https://github.com/Ratchanontt/BSC_DPDM23/blob/main/Sheet/ai1.0.2.pdf) 
> [!WARNING]
> ไปที่หน้า 169 ข่ายงานประสาทเทียม > เพอร์เซปตรอน > Perceptron Learning
