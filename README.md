# 🤖 Machine Learning Project

> 📊 Dự án nghiên cứu và ứng dụng các mô hình học máy để giải quyết bài toán thực tế

---

## 📖 Mục lục

- [1. Tổng quan](#1-tổng-quan)
  - [1.1 Giới thiệu và phân tích bài toán](#11-giới-thiệu-và-phân-tích-bài-toán)
    - [1.1.1 Giới thiệu bài toán](#111-giới-thiệu-bài-toán)
    - [1.1.2 Phân tích dữ liệu](#112-phân-tích-dữ-liệu)
  - [1.2 Các mô hình học máy](#12-các-mô-hình-học-máy)
  - [1.3 Phương pháp tránh Overfitting](#13-phương-pháp-tránh-overfitting)
    - [1.3.1 Dropout](#131-dropout)
    - [1.3.2 Early Stopping](#132-early-stopping)
    - [1.3.3 L1 Regularization](#133-l1-regularization)
  - [1.4 Giải pháp cải thiện độ chính xác](#14-giải-pháp-cải-thiện-độ-chính-xác)
    - [1.4.1 Tăng độ phức tạp mô hình](#141-tăng-độ-phức-tạp-mô-hình)
    - [1.4.2 Ensemble Learning](#142-ensemble-learning)
    - [1.4.3 Oversampling & Undersampling](#143-oversampling--undersampling)

- [2. Giải quyết bài toán](#2-giải-quyết-bài-toán)
  - [2.1 Mô hình học máy cơ bản](#21-mô-hình-học-máy-cơ-bản)
  - [2.2 Neural Network](#22-neural-network)
    - [2.2.1 Feed Forward Neural Network](#221-feed-forward-neural-network)
    - [2.2.2 Recurrent Neural Network](#222-recurrent-neural-network)
    - [2.2.3 So sánh mô hình](#223-so-sánh-mô-hình)
    - [2.2.4 Tránh Overfitting](#224-tránh-overfitting)
    - [2.2.5 Cải thiện độ chính xác](#225-cải-thiện-độ-chính-xác)

---

## 1. Tổng quan

### 1.1 Giới thiệu và phân tích bài toán

#### 1.1.1 Giới thiệu bài toán
Mô tả bài toán Machine Learning cần giải quyết, mục tiêu và ý nghĩa thực tiễn.

#### 1.1.2 Phân tích dữ liệu
- 📌 Nguồn dữ liệu  
- 📌 Đặc trưng dữ liệu (features)  
- 📌 Tiền xử lý dữ liệu (data preprocessing)  
- 📌 Trực quan hóa dữ liệu  

---

### 1.2 Các mô hình học máy
Các mô hình được áp dụng:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

---

### 1.3 Phương pháp tránh Overfitting

#### 1.3.1 Dropout
Giảm overfitting bằng cách ngẫu nhiên loại bỏ neuron trong quá trình huấn luyện.

#### 1.3.2 Early Stopping
Dừng huấn luyện khi mô hình bắt đầu overfit trên tập validation.

#### 1.3.3 L1 Regularization
Thêm penalty vào hàm loss để giảm độ phức tạp của mô hình.

---

### 1.4 Giải pháp cải thiện độ chính xác

#### 1.4.1 Tăng độ phức tạp mô hình
- Tăng số lớp (layers)  
- Tăng số neuron  

#### 1.4.2 Ensemble Learning
- Bagging  
- Boosting  
- Stacking  

#### 1.4.3 Oversampling & Undersampling
- Xử lý mất cân bằng dữ liệu  
- Cải thiện hiệu suất mô hình  

---

## 2. Giải quyết bài toán

### 2.1 Mô hình học máy cơ bản
Áp dụng các mô hình cơ bản để xây dựng baseline:
- Huấn luyện mô hình  
- Đánh giá hiệu suất (accuracy, precision, recall, F1-score)  

---

### 2.2 Neural Network

#### 2.2.1 Feed Forward Neural Network
- Kiến trúc mạng truyền thẳng  
- Áp dụng cho bài toán phân loại/dự đoán  

#### 2.2.2 Recurrent Neural Network
- Xử lý dữ liệu chuỗi (sequence data)  
- Áp dụng trong NLP hoặc time-series  

#### 2.2.3 So sánh mô hình
| Tiêu chí | FFNN | RNN |
|----------|------|-----|
| Dữ liệu  | Tĩnh | Chuỗi |
| Hiệu suất | Trung bình | Cao hơn với sequence |
| Độ phức tạp | Thấp | Cao |

---

#### 2.2.4 Tránh Overfitting
Áp dụng:
- Dropout  
- Early Stopping  
- Regularization  

---

#### 2.2.5 Cải thiện độ chính xác
- Tuning hyperparameters  
- Tăng dữ liệu  
- Ensemble mô hình  

---

## 📊 Kết quả
- Accuracy: XX%  
- Precision: XX%  
- Recall: XX%  

> 👉 (Bạn nên cập nhật số liệu thực tế)

---

## 📁 Cấu trúc thư mục

```bash
project/
│── data/
│── notebooks/
│── models/
│── src/
│── README.md
