# ProjectAppDocTruyenMB

![App Banner](link-to-your-banner-image) <!-- Thêm ảnh minh họa nếu có -->

## Mô tả
ProjectAppDocTruyenMB là ứng dụng Android cho phép người dùng đọc truyện tranh dạng văn bản (text-manga). Ứng dụng hỗ trợ xem danh sách truyện, chi tiết truyện, danh sách chương và lọc/sắp xếp truyện.

## Tính năng
- Xem danh sách truyện và chi tiết từng truyện.
- Xem danh sách chương.
- Lọc và sắp xếp truyện theo các tiêu chí khác nhau (Strategy Pattern).
- Quản lý dữ liệu truyện tập trung (Singleton Pattern).

## Kiến trúc
- **Singleton**: Quản lý dữ liệu truyện và trạng thái ứng dụng, đảm bảo dữ liệu đồng nhất.
- **Strategy**: Xử lý các thuật toán lọc và sắp xếp truyện mà không cần thay đổi mã nguồn chính.

## Công nghệ
- Ngôn ngữ: Java/Kotlin
- Môi trường: Android Studio
- Quản lý dữ liệu: SQLite hoặc JSON nội bộ
- Thiết kế: Singleton, Strategy

## Cài đặt
1. Tải tệp `ProjectDocTruyenMB(final).rar` từ kho GitHub.
2. Giải nén và mở bằng Android Studio.
3. Chạy ứng dụng trên thiết bị Android hoặc trình giả lập.

## Ghi chú
- Dự án hiện chưa có dữ liệu trực tuyến, chỉ sử dụng dữ liệu nội bộ.
- Có thể mở rộng các tính năng: bình luận, đánh giá, lưu chương đã đọc.
