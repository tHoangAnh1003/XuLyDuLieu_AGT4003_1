# Xử lý dữ liệu các chỉ tiêu của cà chua

Dự án này xử lý dữ liệu về các chỉ tiêu của cà chua theo các công thức (CT1, CT2, CT3 và ĐC). Dữ liệu được phân tích để trích xuất những thông tin hữu ích phục vụ nghiên cứu hoặc ứng dụng trong nông nghiệp.

## Tổng quan dự án

Dự án thực hiện các công việc:
- Xử lý và tiền xử lý dữ liệu từ các tệp đầu vào.
- Phân tích thống kê để so sánh các công thức.
- Trực quan hóa dữ liệu giúp dễ dàng theo dõi và phân tích.

## Tính năng chính

- **Nhập dữ liệu:** Đọc và xử lý các tệp dữ liệu phổ biến như Excel hoặc CSV.
- **Phân tích:** Thực hiện phân tích thống kê, chẳng hạn như ANOVA một chiều, để so sánh các công thức.
- **Trực quan hóa:** Tạo các biểu đồ minh họa sự khác biệt giữa các công thức.
- **Tùy chỉnh:** Dễ dàng mở rộng để thêm các chỉ tiêu hoặc công thức mới.

## Yêu cầu

Đảm bảo rằng các thư viện Python sau đây đã được cài đặt:

- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `openpyxl`

Cài đặt các thư viện bằng lệnh sau:
```bash
pip install -r requirements.txt
