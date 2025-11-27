# Tuần 1 – Tổng Quan Nội Dung

Tuần này tập trung tìm hiểu các kiến thức nền tảng về AI, Machine Learning, các thư viện phổ biến trong Python và làm quen với Notebooks cũng như nguồn dữ liệu. Dưới đây là tóm tắt toàn bộ nội dung đã hoàn thành.

---

## 1. Giới thiệu về AI

### **AI là gì?**
- Trí tuệ nhân tạo (Artificial Intelligence) là lĩnh vực nghiên cứu giúp máy móc có khả năng tư duy, học hỏi, suy luận và giải quyết vấn đề giống con người.

### **Các lĩnh vực của AI**
- Machine Learning
- Deep Learning
- Xử lý ngôn ngữ tự nhiên (NLP)
- Thị giác máy tính (Computer Vision)
- Robotics
- Expert Systems
- Speech Recognition

### **Ứng dụng AI trong thực tế**
- Chatbot và trợ lý ảo
- Nhận diện khuôn mặt
- Tự động lái (self-driving cars)
- Hệ thống gợi ý (tiki, shopee, youtube,…)
- Phát hiện gian lận ngân hàng
- Y tế/chuẩn đoán hình ảnh y khoa

### **Dữ liệu là gì & vai trò của dữ liệu trong AI**
- Dữ liệu là tập hợp thông tin thu thập được từ thực tế.
- AI — đặc biệt là Machine Learning — cần dữ liệu để:
  - Học mô hình
  - Dự đoán
  - Cải thiện độ chính xác
  - Giảm sai lệch (bias)

### **3 loại bài toán chính trong Machine Learning**
| Loại bài toán | Mục tiêu | Ví dụ | Đầu ra |
|---------------|----------|-------|--------|
| **Supervised Learning** | Học từ dữ liệu có nhãn | phân loại spam, dự đoán giá nhà | số hoặc label |
| **Unsupervised Learning** | Tìm mẫu trong dữ liệu không nhãn | phân cụm khách hàng | nhóm (clusters) |
| **Reinforcement Learning** | Tác nhân học bằng cách thử–sai | AI chơi game, robot | chuỗi hành động tối ưu |

### **Một số thuật ngữ quan trọng**
- Dataset, Sample, Features
- Label/Target
- Model
- Training / Testing
- Loss function
- Overfitting / Underfitting
- Accuracy, Precision, Recall

---

## 2. Một số thư viện phổ biến trong Python

### **NumPy**
- **Khái niệm:** Thư viện xử lý mảng và phép tính toán khoa học.
- **Ra đời:** 2005 — Người tạo: Travis Oliphant.
- **Ưu điểm:** nhanh, tối ưu, hỗ trợ đại số tuyến tính tốt.
- **Nhược điểm:** không thân thiện với dữ liệu dạng bảng như Pandas.

### **Pandas**
- **Khái niệm:** Thư viện thao tác dữ liệu dạng bảng (DataFrame).
- **Ra đời:** 2008 — Wes McKinney.
- **Ưu điểm:** dễ làm sạch, xử lý dữ liệu, mạnh mẽ.
- **Nhược điểm:** tốc độ chậm hơn NumPy khi xử lý mảng lớn.

### **Matplotlib**
- **Khái niệm:** Thư viện trực quan hóa dữ liệu.
- **Ra đời:** 2003 — John Hunter.
- **Ưu điểm:** mạnh, nhiều biểu đồ.
- **Nhược điểm:** cú pháp dài, hơi khó dùng cho người mới.

### **PyTorch**
- **Khái niệm:** Framework Deep Learning.
- **Ra đời:** 2016 — Facebook AI Research.
- **Ưu điểm:** dễ dùng, dynamic graph, phổ biến trong nghiên cứu.
- **Nhược điểm:** tài liệu nhiều nhưng chưa thống nhất như TensorFlow.

---

## 3. Tìm hiểu về Notebook và nguồn dữ liệu

### **a. Notebook (Jupyter / Colab / Kaggle)**
- Đã chạy thử notebook với python ví dụ:
```python
print("hello world")
# **b. Nguồn dữ liệu**
b. Nguồn dữ liệu

Kaggle: nền tảng thi ML và chia sẻ dataset.

Dataset phổ biến: Titanic, House Prices, MNIST, CIFAR-10,...

Hugging Face: nền tảng chia sẻ mô hình ML/DL.

Có: Models, Datasets, Spaces.

4. Exploratory Data Analysis (EDA)
EDA là gì?

EDA là bước phân tích dữ liệu sơ bộ để hiểu rõ dataset trước khi xây dựng mô hình.

Gồm 3 phần chính:
1. Data Understanding

Kiểm tra số dòng, số cột

Các thuộc tính dữ liệu

Kiểu dữ liệu (int, float, object)

Giá trị thiếu, dữ liệu trùng

2. Data Analysis

Phân bố dữ liệu

Mối quan hệ giữa các biến

Tương quan (correlation)

Thống kê cơ bản: mean, median, std,...

3. Data Visualization

Biểu đồ histogram

Scatter plot

Boxplot

Heatmap

Biểu đồ phân loại/category
