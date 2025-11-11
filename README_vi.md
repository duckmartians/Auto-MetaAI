# 🎨 Auto Meta - Tự động hóa cho Meta AI [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 

Auto Meta là một tiện ích mở rộng (extension) cho trình duyệt Chrome, giúp tự động hóa quy trình tạo video hàng loạt trên Meta AI Media (`meta.ai/media`), tiết kiệm thời gian và tăng tốc khả năng sáng tạo của bạn.

## ✨ Tính năng chính

* **Hai chế độ hoạt động thông minh**:
    1.  **Image-to-Video**: Tự động chạy khi bạn có chọn ảnh. Lấy 1 ảnh + 1 prompt để tạo video.
    2.  **Text-to-Video**: Tự động chạy khi bạn *không* chọn ảnh. Chỉ lấy 1 prompt để tạo video.
* **Tải ảnh hàng loạt**: Chọn nhiều ảnh cùng lúc để đưa vào hàng đợi.
* **Sắp xếp ảnh**: Sắp xếp danh sách ảnh theo A-Z, Z-A, Mới nhất, Cũ nhất.
* **Nhập Prompt từ file**: Hỗ trợ nhập hàng loạt prompt từ file `.txt`.
* **Tự động tải về**: Tự động quét và tải video mới được tạo ra.
* **Tùy chỉnh linh hoạt**: Cài đặt thời gian chờ và vị trí bắt đầu theo ý muốn.
* **Giao diện đa ngôn ngữ**: Hỗ trợ Tiếng Việt và Tiếng Anh.

## 🚀 Cài đặt

1.  Truy cập Cửa hàng Chrome trực tuyến.
2.  Tìm kiếm với từ khóa "**Auto Meta - Tự động hóa cho Meta AI**".
3.  Nhấp vào "Thêm vào Chrome" (Add to Chrome).

[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com)

## 📖 Hướng dẫn sử dụng

### Bước 1: Điều hướng

Mở trình duyệt Chrome và truy cập trang Meta AI Media:
**`https://www.meta.ai/media`**

Tiện ích sẽ chỉ hoạt động trên trang này. Nếu bạn đang ở trang khác, giao diện tiện ích sẽ hiển thị nút "Chuyển đến Meta AI".

### Bước 2: Mở Tiện ích

Nhấp vào biểu tượng Auto Meta (con vịt) trên thanh công cụ của Chrome để mở giao diện điều khiển.

### Bước 3: Chọn Chế độ và Nhập liệu

Bạn có hai cách để chạy tool:

#### Cách 1: Chế độ Image-to-Video (Ảnh sang Video)

Chế độ này được kích hoạt tự động khi bạn có chọn ảnh.

1.  Tại tab **Điều Khiển**, nhấp vào nút **"Chọn nhiều ảnh"** và chọn tất cả các ảnh bạn muốn tạo video.
2.  **Sắp xếp** (tùy chọn): Chọn thứ tự xử lý ảnh (A-Z, Mới nhất, v.v.).
3.  Tại ô **Danh sách prompt**, nhập các prompt của bạn.
    * **Lưu ý:** Tool sẽ lấy 1 ảnh + 1 prompt. Nếu danh sách prompt ngắn hơn danh sách ảnh, các prompt sẽ được sử dụng lặp lại (tuần hoàn).
4.  Nhấp **"Bắt đầu"**.

#### Cách 2: Chế độ Text-to-Video (Chỉ dùng Prompt)

Chế độ này được kích hoạt tự động khi bạn **KHÔNG** chọn bất kỳ ảnh nào.

1.  Đảm bảo ô "Đã chọn: 0" (không có ảnh nào).
2.  Tại ô **Danh sách prompt**, nhập các prompt của bạn.
    * **Lưu ý:** Mỗi prompt phải được cách nhau bằng một **dòng trống**. Tool sẽ tạo 1 video cho mỗi prompt.
3.  Nhấp **"Bắt đầu"**.

### Bước 4: Cài đặt (Tùy chọn)

Truy cập tab **Cài Đặt** để tinh chỉnh:

* **Bắt đầu từ...**: Nhập số thứ tự (Ảnh hoặc Prompt) mà bạn muốn tool bắt đầu chạy.
* **Thời gian chờ**: Tool sẽ tự động đề xuất thời gian chờ (giây) khác nhau cho mỗi chế độ (10-20 giây cho Image-to-Video, 15-30 giây cho Text-to-Video). Bạn có thể tự điều chỉnh nếu muốn.
* **Tự động tải video**: Bật tính năng này để tool tự động quét và tải video mới về máy.

### 💡 Mẹo quan trọng (Để Tải tự động)

Để video tự động tải về mà không bị hỏi, bạn cần tắt cài đặt "Hỏi vị trí lưu..." của Chrome:
1.  Truy cập `chrome://settings/downloads`.
2.  Tắt tùy chọn **"Hỏi vị trí lưu mỗi tệp trước khi tải xuống"**.

## 👨‍💻 Tác giả

Phát triển bởi **Đặng Minh Đức (duckmartians)**.

## 📜 Giấy phép

Mã nguồn này được cấp phép theo các điều khoản của Giấy phép MIT. Vui lòng xem file `LICENSE.md` để biết chi tiết.
