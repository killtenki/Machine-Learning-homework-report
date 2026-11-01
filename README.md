# Data-driven Machine Learning – Homework Report

Repository lưu trữ notebook, dữ liệu và báo cáo lời giải bài tập môn **Phân tích dữ liệu và xây dựng mô hình Data-Driven – Machine Learning ứng dụng trong kỹ thuật**.

Bài thực hành sử dụng dữ liệu giám sát động cơ để khảo sát quy trình phân tích dữ liệu và xây dựng các mô hình học máy phục vụ theo dõi trạng thái vận hành, dự báo nhiệt độ và cảnh báo sự cố.

## Nội dung chính

1. **Khảo sát và tiền xử lý dữ liệu:** kiểm tra bản ghi trùng lặp, giá trị thiếu và điểm nghi nhiễu; phân tích chuỗi thời gian cảm biến; thảo luận cách xử lý giá trị thiếu cho cảm biến nhiệt độ và dòng điện.
2. **Hồi quy nhiệt độ động cơ:** xây dựng và so sánh Ridge Regression, Random Forest và HistGradientBoosting bằng các chỉ số MAE, RMSE và $R^2$; phân tích sai số dự báo.
3. **Phân loại cảnh báo lỗi:** đánh giá bài toán mất cân bằng lớp thông qua confusion matrix, Precision, Recall, F1-score, ROC Curve và Precision–Recall Curve; xem xét khả năng tổng quát hóa của mô hình.
4. **Phân cụm và workflow giám sát:** sử dụng K-Means để nhận diện các chế độ vận hành, đánh giá cụm bằng Inertia, Silhouette Score và Davies–Bouldin Index; đề xuất workflow tích hợp EDA, Regression, Classification và Clustering, đồng thời trình bày các biện pháp hạn chế data leakage.

## Các tệp trong repository

| Tệp | Mô tả |
|---|---|
| `Homework.ipynb` | Notebook chứa mã nguồn và quá trình thực hiện phân tích, huấn luyện và đánh giá mô hình. |
| `Homework_report.pdf` | Báo cáo trình bày phương pháp, kết quả thực nghiệm, biểu đồ và phần giải thích. |
| `motor_integrated_raw.csv` | Bộ dữ liệu cảm biến động cơ ban đầu. |
| `data_clean.csv` | Bộ dữ liệu sau bước làm sạch, được sử dụng trong các phần phân tích tiếp theo. |
| `figures.zip` | Các hình ảnh và biểu đồ sử dụng trong báo cáo. |

## Cách xem và thực thi

- Đọc `Homework_report.pdf` để xem phần trình bày và phân tích kết quả.
- Mở `Homework.ipynb` bằng Jupyter Notebook hoặc JupyterLab để xem và chạy mã nguồn.
- Đặt notebook cùng các tệp dữ liệu cần thiết trong cùng thư mục, hoặc cập nhật lại đường dẫn trong notebook nếu thay đổi cấu trúc thư mục.

Notebook được xây dựng bằng Python và sử dụng các thư viện phân tích dữ liệu, trực quan hóa và học máy. Cần cài đặt các thư viện được import trong notebook trước khi thực thi.

---

**Repository:** [Machine-Learning-homework-report](https://github.com/killtenki/Machine-Learning-homework-report)
