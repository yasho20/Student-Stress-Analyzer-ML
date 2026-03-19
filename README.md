# Student-Stress-Analyzer-ML
A machine learning project that predicts student stress levels using data analysis and classification algorithms.
# Student Stress Analyzer (Machine Learning)

## 📌 Overview
This project predicts student stress levels using machine learning techniques based on various academic and lifestyle factors.

## 🚀 Features
- Stress level prediction
- Data preprocessing and analysis
- Visualization of stress patterns

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 📊 Model
Classification algorithms are used to analyze and predict stress levels.

##  Output
Synthetic Student Dataset:

   Student_ID  Attendance (%)  Study_Hours  Sleep_Hours  Screen_Time  Stress_Score
0         S01              88          4.8          4.1          4.4             3
1         S02              78          1.0          7.8          7.6             3
2         S03              64          5.0          6.3          6.4             1
3         S04              92          3.5          5.5          4.0             3
4         S05              57          3.4          4.1          5.4             3
5         S06              70          1.0          4.9          5.1             1
6         S07              88          1.1          5.0          7.8             3
7         S08              68          3.1          6.7          7.1             5
8         S09              72          2.6          6.4          6.5             2
9         S10              60          1.2          7.3          5.2             2
10        S11              60          4.9          4.7          5.5             1
11        S12              73          1.9          5.6          7.8             4
12        S13              85          1.4          4.7          5.6             1
13        S14              89          3.5          7.0          3.7             4
14        S15              73          2.5          5.7          3.8             2
15        S16              52          4.9          4.8          3.0             1
16        S17              71          2.9          6.3          2.1             5
17        S18              51          4.4          4.1          4.5             3
18        S19              73          3.7          7.4          4.4             4
19        S20              93          2.8          5.8          3.8             3

Final Stress & Productivity Analysis with Recommendations:

   Student_ID  Attendance (%) Stress_Level Attendance_Level                                     Recommendation
0         S01              88       Medium             High     Class: 5 hrs | Study: 3 hrs | Maintain balance
1         S02              78       Medium         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
2         S03              64          Low              Low     Class: 5 hrs | Study: 3 hrs | Maintain balance
3         S04              92       Medium             High     Class: 5 hrs | Study: 3 hrs | Maintain balance
4         S05              57       Medium              Low  Class: 4–5 hrs | Study: 2–3 hrs | Gradual impr...
5         S06              70          Low         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
6         S07              88       Medium             High     Class: 5 hrs | Study: 3 hrs | Maintain balance
7         S08              68         High         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
8         S09              72          Low         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
9         S10              60          Low              Low     Class: 5 hrs | Study: 3 hrs | Maintain balance
10        S11              60          Low              Low     Class: 5 hrs | Study: 3 hrs | Maintain balance
11        S12              73         High         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
12        S13              85          Low             High     Class: 5 hrs | Study: 3 hrs | Maintain balance
13        S14              89         High             High   Class: 4 hrs | Study: 2 hrs | Burnout prevention
14        S15              73          Low         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
15        S16              52          Low              Low     Class: 5 hrs | Study: 3 hrs | Maintain balance
16        S17              71         High         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
17        S18              51       Medium              Low  Class: 4–5 hrs | Study: 2–3 hrs | Gradual impr...
18        S19              73         High         Moderate     Class: 5 hrs | Study: 3 hrs | Maintain balance
19        S20              93       Medium             High     Class: 5 hrs | Study: 3 hrs | Maintain balance
Model Accuracy: 0.38461538461538464

Classification Report:
               precision    recall  f1-score   support

           0       0.25      0.25      0.25         4
           1       0.50      0.43      0.46         7
           2       0.33      0.50      0.40         2

    accuracy                           0.38        13
   macro avg       0.36      0.39      0.37        13
weighted avg       0.40      0.38      0.39        13

Predicted Stress Level: Medium
Personalized Recommendation:
Class: 4–5 hrs | Study: 2–3 hrs | Gradual improvement
