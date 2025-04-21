# Dự án Nhận diện Ký hiệu Tay ASL (ASL Handsign Recognition)

## Mô tả dự án
Dự án này tập trung vào việc xây dựng một hệ thống nhận diện ký hiệu tay dựa trên bộ dữ liệu **ASL Handsign Dataset (Grayscaled & Thresholded)**. Dữ liệu được tải từ Kaggle và sẽ được xử lý để sử dụng trong các mô hình học máy.

## Cấu trúc thư mục
- **data/**: Thư mục chứa dữ liệu của dự án.
  - **raw/**: Chứa dữ liệu thô được tải từ [ASL Handsign Dataset trên Kaggle](https://www.kaggle.com/datasets/furkanakdeniz/asl-handsign-dataset-grayscaled-thresholded/data).
  - **processed/**: Chứa dữ liệu sau khi được xử lý (hiện tại đang rỗng, sẽ được cập nhật sau khi xử lý dữ liệu thô).
- **documents/**: Chứa các tài liệu liên quan đến dự án.
  - Báo cáo chi tiết.
  - Slide thuyết trình.

## Nguồn dữ liệu
Dữ liệu thô được lấy từ:  
[ASL Handsign Dataset (Grayscaled & Thresholded)](https://www.kaggle.com/datasets/furkanakdeniz/asl-handsign-dataset-grayscaled-thresholded/data) trên Kaggle.

## Hướng dẫn sử dụng
1. **Tải dữ liệu**: Dữ liệu thô đã được tải và lưu trong `data/raw/`.
2. **Xử lý dữ liệu**: Dữ liệu sau khi xử lý sẽ được lưu trong `data/processed/`.
3. **Tài liệu tham khảo**: Xem báo cáo và slide trong thư mục `documents/` để biết thêm chi tiết về dự án.

## Lưu ý
- Thư mục `data/processed/` hiện đang rỗng và sẽ được cập nhật sau khi hoàn thành bước xử lý dữ liệu.
- Đảm bảo bạn có quyền truy cập vào dữ liệu trên Kaggle trước khi sử dụng.