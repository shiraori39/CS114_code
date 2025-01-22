# CS114.P11 - Máy Học

## Giảng viên
- Lê Đình Duy
- Nguyễn Phạm Trường An

## Sinh viên
- Trần Thanh Tùng - 21522771
- Nguyễn Trần Hoàng Quân - 21522500

## Báo cáo đồ án cuối kỳ môn học Máy Học
### Car Classification
- Car Classification
### Đồ án dự đoán điểm của sinh viên
- WeCode Machine Learning

## Cấu trúc thư mục
### Car Classification (Đồ án Phân loại xe)
- `Car Classification/yolo_training_results/train full dataset` (thư mục kết quả huấn luyện)
- `Car Classification/yolo_training_results/train full dataset/weight` (thư mục weight mô hình đã huấn luyện)
- `Car Classification/script.ipynb`: Chứa các bước tiền xử lý dữ liệu, chuẩn bị dataset và sao chép hình ảnh vào các thư mục phù hợp để huấn luyện mô hình.
- `Car Classification/vgg16.ipynb`: Mã nguồn huấn luyện mô hình phân loại hình ảnh sử dụng kiến trúc mạng VGG16.
- `Car Classification/yolo_subset.ipynb`: Mã nguồn huấn luyện mô hình YOLO trên tập dữ liệu con gồm 500 hình ảnh mỗi lớp, kiểm tra hiệu quả mô hình trên tập dữ liệu nhỏ.
- `Car Classification/yolo_full.ipynb`: Mã nguồn huấn luyện mô hình YOLO trên toàn bộ tập dữ liệu, nhằm đạt độ chính xác cao nhất.
- **Dataset**: [Kaggle Car Brand Dataset](https://www.kaggle.com/datasets/ntdquan2003/car-brand)

### WeCode Machine Learning (Dự đoán điểm sinh viên)
- `WeCode Machine Learning/dataset`: Thư mục chứa dữ liệu liên quan.
- `WeCode Machine Learning/source.ipynb`: Mã nguồn xử lý dữ liệu và huấn luyện mô hình.

## Hướng dẫn chạy lại source code
### Đồ án phân loại xe
- Chỉnh lại đường dẫn dữ liệu tương ứng.
- Chạy lần lượt các cell code trong các file notebook được đề cập ở trên.

### Dự đoán điểm sinh viên
- Chỉnh lại đường dẫn dữ liệu tương ứng.
- Chạy lần lượt các cell code trong `source.ipynb`.
