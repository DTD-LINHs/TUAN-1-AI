# TỔNG QUAN KIẾN THỨC ĐÃ TÌM HIỂU VỀ AI – MACHINE LEARNING – DATA

---

# 1. Giới thiệu về AI

## AI là gì?
AI (Artificial Intelligence) là lĩnh vực khoa học máy tính giúp máy móc mô phỏng trí thông minh của con người: học, suy luận, nhận thức, giao tiếp, tự ra quyết định.

## Các lĩnh vực chính của AI
- Machine Learning (ML)
- Deep Learning
- Natural Language Processing (NLP)
- Computer Vision (CV)
- Robotics
- Expert Systems
- Speech Recognition
- Planning & Decision Making

## Ứng dụng AI trong thực tế
- Y tế: chẩn đoán bệnh, phân tích ảnh X-ray  
- Giao thông: xe tự lái  
- Doanh nghiệp: phân tích & dự đoán dữ liệu  
- Giáo dục: học cá nhân hóa  
- Giải trí: gợi ý phim/nhạc  
- Nông nghiệp, tài chính, bảo mật…

---

# 2. Dữ liệu và vai trò của dữ liệu trong AI

## Dữ liệu là gì?
Dữ liệu (Data) là tập hợp thông tin dưới dạng:
- Chữ, số
- Ảnh, video
- Âm thanh
- Log, tín hiệu cảm biến

## Tại sao dữ liệu quan trọng trong AI?
- ML học từ dữ liệu → không có dữ liệu thì không thể huấn luyện mô hình.
- Dữ liệu giúp AI nhận ra pattern, dự đoán, giảm lỗi, tăng độ chính xác.
- "Data is the new oil" – dữ liệu là tài nguyên quan trọng nhất trong AI.

---

# 3. Ba loại bài toán chính trong Machine Learning

| Loại bài toán | Đặc điểm | Ứng dụng |
|---------------|----------|----------|
| **Supervised Learning** | Dữ liệu có nhãn | Dự đoán giá nhà, phân loại ảnh |
| **Unsupervised Learning** | Dữ liệu không có nhãn | Phân cụm khách hàng, giảm chiều dữ liệu |
| **Reinforcement Learning** | Học qua thưởng/phạt | Game AI, robot, xe tự lái |

---

# 4. Thuật ngữ và ký hiệu trong AI/ML

## Thuật ngữ quan trọng
- Dataset, Sample, Feature, Label  
- Model, Training, Inference  
- Overfitting / Underfitting  
- Accuracy, Precision, Recall  
- Epoch, Batch  
- Loss Function, Optimizer  
- Neural Network

## Ký hiệu
- `x`: input  
- `y`: output thật  
- `ŷ` : output dự đoán  
- `w`: trọng số  
- `b`: bias  
- `f(x)`: hàm mô hình  
- `L(y, ŷ)`: loss  
- `θ`: tập tham số  

---

# 5. Một số thư viện Python phổ biến

## 1. NumPy
### Khái niệm
NumPy (Numerical Python) là thư viện cung cấp mảng n-dimensional (ndarray) và các phép toán đại số tuyến tính tốc độ cao.
### Thời gian ra đời & Người sáng lập
- Ra đời: khoảng 2005  
- Người sáng lập: Travis Oliphant
### Ưu điểm
- Xử lý mảng nhanh, tối ưu bằng C.  
- Nền tảng cho nhiều thư viện khoa học.
### Nhược điểm
- Không trực quan cho dữ liệu dạng bảng.

## 2. Pandas
### Khái niệm
Pandas hỗ trợ xử lý dữ liệu dạng bảng (DataFrame).
### Thời gian ra đời & Người sáng lập
- Ra đời: ~2008–2009  
- Người sáng lập: Wes McKinney
### Ưu điểm
- Series và DataFrame linh hoạt, dễ dùng.
### Nhược điểm
- Không phù hợp dữ liệu vượt RAM.

## 3. Matplotlib
### Khái niệm
Matplotlib là thư viện vẽ biểu đồ 2D/3D.
### Thời gian ra đời & Người sáng lập
- Ra đời: 2003  
- Người sáng lập: John D. Hunter
### Ưu điểm
- Tùy chỉnh mạnh, xuất đồ họa chất lượng.
### Nhược điểm
- Cú pháp dài, đồ họa mặc định không quá bắt mắt.

## 4. PyTorch
### Khái niệm
PyTorch là thư viện Deep Learning mạnh, dùng dynamic computation graph.
### Thời gian ra đời & Người sáng lập
- Ra đời: 2016  
- Phát triển bởi: Facebook AI Research (FAIR)
### Ưu điểm
- Linh hoạt, debug dễ, cộng đồng nghiên cứu lớn.
### Nhược điểm
- Thay đổi nhanh, tài liệu tiếng Việt ít.

---

# 6. Notebook và nguồn dữ liệu

## Jupyter Notebook
- Môi trường chạy code tương tác, file `.ipynb`.

## Google Colab
- Notebook online, hỗ trợ GPU/TPU miễn phí.

## Kaggle Notebook
- Notebook tích hợp dataset và tiện cho thi đấu.

### Ví dụ code đơn giản
```python
print("Hello world")
# Ví dụ tính tổng
a = 5
b = 7
print("Tổng:", a + b)
```

---

# 7. Nguồn dữ liệu (Data Sources)

## Kaggle
- Nền tảng chia sẻ dataset, thi đấu ML.
### Dataset phổ biến
- Titanic – Machine Learning from Disaster  
- House Prices – Advanced Regression  
- MNIST Digit Classification  
- CIFAR-10 Image Dataset  
- Dogs vs Cats  
- Credit Card Fraud Detection

## Hugging Face
- Nền tảng chia sẻ mô hình ML/DL, đặc biệt NLP.
### Gồm có
- **Models**: kho mô hình (BERT, GPT, T5, Whisper, CLIP...)  
- **Datasets**: nhiều dataset có sẵn (IMDb, SQuAD, commonsense...)  
- **Spaces**: demo app bằng Gradio/Streamlit  
- **Transformers library** và **Datasets library**

---

# 8. Exploratory Data Analysis (EDA)

## EDA là gì?
EDA (Exploratory Data Analysis) là bước phân tích dữ liệu sơ bộ để hiểu rõ dataset trước khi xây dựng mô hình. Mục tiêu: khám phá cấu trúc, phát hiện bất thường, hình thành giả thuyết.

---

## 1. Data Understanding
- Kiểm tra số dòng, số cột (`df.shape`)  
- Xem mẫu dữ liệu (`df.head()`)  
- Kiểu dữ liệu (`df.dtypes`)  
- Giá trị thiếu (`df.isnull().sum()`)  
- Dữ liệu trùng (`df.duplicated().sum()`)  
- Outliers (boxplot, IQR method)

---

## 2. Data Analysis
- Thống kê mô tả (`df.describe()`)  
- Phân bố dữ liệu (histogram, skewness)  
- Tương quan giữa các biến (`df.corr()`)  
- Kiểm tra mối quan hệ (scatter plots, groupby)  
- Tạo giả thuyết để kiểm chứng bằng phân tích tiếp theo

---

## 3. Data Visualization
- **Histogram**: phân phối một biến số  
- **Scatter plot**: mối quan hệ hai biến  
- **Boxplot**: phát hiện outliers  
- **Heatmap**: ma trận tương quan  
- **Bar chart**: so sánh các nhóm (categorical)

---


