# CS313 - Dự báo thời tiết 7 ngày tại Việt Nam

## Tổng quan

Đây là dự án môn học CS313, xây dựng hệ thống dự báo thời tiết 7 ngày tại các tỉnh, thành phố Việt Nam. Hệ thống sử dụng ngôn ngữ lập trình Python, lấy dữ liệu thời tiết từ API OpenWeatherMap và sử dụng các phương pháp học máy cơ bản để dự đoán.

**Thành viên nhóm 2:**
- Hà Tuấn Anh
- Nguyễn Bi Anh
- Trần Hải Đăng
- Phạm Phú Bảo
- Trần Tiến Đạt

## Mục tiêu dự án

- Dự báo các thông số thời tiết (nhiệt độ, độ ẩm, lượng mưa, trạng thái...) cho 7 ngày tiếp theo tại một tỉnh/thành phố Việt Nam.
- Xây dựng giao diện nhập thông tin địa phương và hiển thị kết quả dự báo.

## Các chức năng chính
- Truy vấn dữ liệu thời tiết thực tế từ OpenWeatherMap API.
- Tiền xử lý và huấn luyện mô hình dự báo.
- Đưa ra kết quả dự báo 7 ngày, trực quan trên giao diện (bảng, biểu đồ hoặc file xuất).
- Xem báo cáo phân tích, đánh giá độ chính xác dự báo.

## Công nghệ sử dụng

- Ngôn ngữ: Python (>=3.7)
- Thư viện: requests, pandas, numpy, matplotlib, scikit-learn,...
- API: OpenWeatherMap
- Giao diện: [streamlit/tkinter/console] (tùy chọn thực tế project)

## Hướng dẫn cài đặt

1. Clone repo về máy:
```bash
git clone https://github.com/tuananhpa/CS313-Predict-weather-7-days-in-VietNam.git
cd CS313-Predict-weather-7-days-in-VietNam
```
2. Cài đặt các thư viện yêu cầu:
```bash
pip install -r requirements.txt
```
3. Tạo file lưu API KEY của OpenWeatherMap (ví dụ: `config.py`):
```python
API_KEY = "YOUR_API_KEY"
```
4. Chạy file main:
```bash
python main.py
```

## Hướng dẫn sử dụng

- Nhập tên tỉnh/thành phố hoặc tọa độ địa lý vào giao diện.
- Chọn "Dự báo" để nhận kết quả dự báo thời tiết 7 ngày tiếp theo.
- Xem bảng dữ liệu, biểu đồ hoặc xuất file kết quả.
- Đọc báo cáo chi tiết trong file `Report_Nhóm_2.pdf`.

## Kết quả & Đánh giá

- Độ chính xác trung bình dự báo: ... (điền từ báo cáo)
- Hình minh họa, ví dụ ảnh màn hình giao diện, bảng dự báo (thêm ảnh nếu có).
- Phân tích lỗi, điểm mạnh/điểm yếu của mô hình.

## Báo cáo chi tiết

Vui lòng xem file [Report_Nhóm_2.pdf](./Report_Nhóm_2.pdf) để biết chi tiết về giải pháp, phương pháp dự báo, dữ liệu và kết quả thực nghiệm.

## Tài liệu tham khảo

- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- Các bài báo, nguồn học thuật sử dụng trong phần mô tả phương pháp.

## Liên hệ

- Email nhóm, thông tin giảng viên hướng dẫn nếu cần.

---

> **Lưu ý:** Vui lòng bổ sung tên thành viên, mã sinh viên, thông số/hình ảnh minh họa phù hợp với đồ án thực tế khi hoàn thiện báo cáo.

