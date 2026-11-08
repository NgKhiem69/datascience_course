# DATA SCIENCE LABS

Các bài lab môn Khoa học dữ liệu, chạy trực tiếp trên **Google Colab**. Dữ liệu được đọc từ thư mục `data/` của repo qua đường dẫn raw GitHub, không cần upload file.

| Lab | Nội dung | Mở trên Colab |
|---|---|---|
| Lab 1 | Data processing & EDA với Pandas | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NgKhiem69/datascience_course/blob/main/labs/01-working-with-data/data-processing-with-pandas.ipynb) |
| Lab 1 | Data visualization với Matplotlib | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NgKhiem69/datascience_course/blob/main/labs/01-working-with-data/visualization-with-matplotlib.ipynb) |
| Lab 4 | Logistic Regression & Naive Bayes | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NgKhiem69/datascience_course/blob/main/labs/04-logistic-regression/Logistic%20Regression.ipynb) |
| Lab 5 | Neural Network (MLP) với Scikit-learn | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NgKhiem69/datascience_course/blob/main/labs/05-neural-network/Neural%20network%20with%20Scikitlearn.ipynb) |
| Lab 6 | Clustering (K-Means, Agglomerative, DBSCAN) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NgKhiem69/datascience_course/blob/main/labs/06-clustering/Clustering%20with%20Scikitlearn.ipynb) |

## Dữ liệu (`data/`)

| File | Dùng trong |
|---|---|
| `final_grades.xlsx` | Lab 1 — điểm thi Tin học đại cương |
| `gold_price_monthly.csv` | Lab 1 — giá vàng theo tháng (line plot) |
| `studyhours.csv` | Lab 1, 4, 5, 6 — giờ học và điểm thi |
| `student_performance_prediction.csv` | Lab 4 — dự đoán đậu/rớt |
| `spam_or_not_spam.csv` | Lab 4 — phân loại email spam |

## Chạy trên máy local

Notebook tự nhận biết môi trường (`IN_COLAB`) và vẫn đọc dữ liệu từ GitHub nên cần kết nối Internet.

```bash
pip install pandas numpy matplotlib scikit-learn scipy openpyxl jupyter
```
