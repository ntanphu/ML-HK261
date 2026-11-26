# PHÂN TÍCH VÀ ĐÁNH GIÁ PHƯƠNG PHÁP GIẢM CHIỀU DIFFUSION MAPS

## 1. Thông tin chung

**Môn học:** Học máy & Ứng dụng

**Giảng viên hướng dẫn:**
- PGS.TS. Lê Hồng Trang
- PGS.TS. Nguyễn An Khương
- PGS.TS. Trương Vĩnh Lân

## 2. Giới thiệu

Đề tài tập trung phân tích cơ sở toán học, triển khai và đánh giá
phương pháp giảm chiều phi tuyến Diffusion Maps (DM). Kết quả
thực nghiệm được so sánh với PCA và t-SNE trên hai tập dữ liệu
Swiss Roll và MNIST.

Ngoài ra, đề tài khảo sát khả năng mở rộng embedding đối với
các mẫu ngoài tập dữ liệu ban đầu bằng phương pháp Nyström
và Deep Diffusion Maps (DDM).

## 3. Nội dung thực hiện

- Phân tích cơ sở toán học của Diffusion Maps.
- Xây dựng và phân tích toán tử khuếch tán.
- Triển khai và so sánh Diffusion Maps, PCA và t-SNE.
- Thực nghiệm mở rộng embedding với Nyström và DDM.
- Đánh giá kết quả thông qua trực quan hóa, MRE và
  khoảng tin cậy bootstrap 95%.
- Phân tích ưu điểm, hạn chế và hướng phát triển.

## 4. Tập dữ liệu

| Dataset | Description | Input Dimension |
| :--- | :--- | :---: |
| Swiss Roll | Synthetic manifold data | 3 |
| MNIST | Handwritten digit images | 784 |

## 5. Kết quả thực nghiệm

Diffusion Maps có khả năng biểu diễn cấu trúc phi tuyến của
dữ liệu. Nyström đạt sai số tái tạo embedding thấp hơn DDM
trong các cấu hình được khảo sát. DDM có tiềm năng giảm
chi phí tính toán trong giai đoạn suy luận thông qua ánh xạ
của mạng nơ-ron đã huấn luyện.

## 6. Công nghệ sử dụng

- Python
- Jupyter Notebook
- NumPy
- SciPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## 7. Tài liệu tham khảo

1. Coifman, R. R., & Lafon, S. (2006).
   Diffusion Maps. Applied and Computational Harmonic Analysis,
   21(1), 5–30.
   https://doi.org/10.1016/j.acha.2006.04.006

2. Van der Maaten, L., & Hinton, G. (2008).
   Visualizing Data using t-SNE.
   Journal of Machine Learning Research, 9, 2579–2605.

3. García-Heredia, S., Alaíz, C. M., & Fernández, Á. (2025).
   Deep Diffusion Maps.
   https://arxiv.org/abs/2505.06087
