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

[1] Tenenbaum, J. B., de Silva, V., & Langford, J. C. (2000).
A global geometric framework for nonlinear dimensionality reduction.
*Science*, 290(5500), 2319–2323.

[2] Lorenz, E. N. (2017).
Deterministic nonperiodic flow.
In *Universality in Chaos* (2nd ed., pp. 367–378). Routledge.

[3] Hotelling, H. (1933).
Analysis of a complex of statistical variables into principal components.
*Journal of Educational Psychology*, 24(6), 417.

[4] Roweis, S. T., & Saul, L. K. (2000).
Nonlinear dimensionality reduction by locally linear embedding.
*Science*, 290(5500), 2323–2326.

[5] Van der Maaten, L., & Hinton, G. (2008).
Visualizing data using t-SNE.
*Journal of Machine Learning Research*, 9(11).

[6] Van der Maaten, L., Postma, E. O., Van den Herik, H. J., et al. (2009).
Dimensionality reduction: A comparative review.
*Journal of Machine Learning Research*, 10(1), 1–41.

[7] Coifman, R. R., & Lafon, S. (2006).
Diffusion maps.
*Applied and Computational Harmonic Analysis*, 21(1), 5–30.

[8] LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998).
Gradient-based learning applied to document recognition.
*Proceedings of the IEEE*, 86(11), 2278–2324.

[9] García-Heredia, S., Fernández, Á., & Alaíz, C. M. (2025).
Deep Diffusion Maps.
*arXiv preprint arXiv:2505.06087*.
https://arxiv.org/abs/2505.06087
