# Dự án Dự đoán Kết Quả Bóng Đá Bằng Machine Learning

## Giới thiệu
Dự án này sử dụng Machine Learning để dự đoán kết quả trận đấu bóng đá dựa trên dữ liệu lịch sử. Hệ thống áp dụng hai thuật toán chính: **Random Forest** và **XGBoost**, sau đó kết hợp chúng thành một mô hình **Stacking** để tăng độ chính xác.

## Tính năng chính
- Cập nhập dữ liệu mới nhất từ API mỗi khi chạy lại mô hình.
- Tiền xử lý dữ liệu trận đấu bóng đá.
- Trích xuất các đặc trưng quan trọng từ dữ liệu.
- Huấn luyện mô hình sử dụng **Random Forest** và **XGBoost**.
- Kết hợp các mô hình bằng phương pháp **Stacking** để tối ưu hóa kết quả dự đoán.
- Đánh giá mô hình bằng độ chính xác và ma trận nhầm lẫn.

## Yêu cầu hệ thống
- Python 3.11.3

## Cách chạy dự án
1. **Clone repository**:
   git clone https://github.com/Phuoght/Predict-Result-Football-Machine-Learning.git
2. **Cài đặt thư viện phụ thuộc**:
   pip install -r requirements.txt
3. **Chạy script huấn luyện và dự đoán**:
   - cd Predict-Result-Football-Machine-Learning
   - cd Model_Train
   - python train_model_final.py
   - cd ..
   - python app.py

## Kết quả và Đánh giá
- Độ chính xác trung bình của mô hình: **~84%** trên tập kiểm tra.
- Ma trận nhầm lẫn cho thấy mô hình có thể dự đoán khá tốt kết quả trận đấu.

## Định hướng phát triển
- Cải thiện mô hình bằng cách thử nghiệm thêm các đặc trưng quan trọng.
- Kết hợp thêm các kỹ thuật Feature Engineering để tăng độ chính xác.

