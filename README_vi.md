<h1 align="center">Auto Vibes</h1>

<p align="center"><b>Tiện ích Chrome biến Vibes AI (vibes.ai) thành xưởng tạo ảnh và video hàng loạt - dán prompt, bấm Bắt đầu, kết quả tự lưu về máy.</b></p>

<p align="center">
  <a href="README.md">English</a> ·
  <b>Tiếng Việt</b>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/auto-meta-automation-for/bchhcfjoloinebjpbfklckgohpjehdmf"><img alt="Cài từ Chrome Web Store" src="https://img.shields.io/badge/Chrome%20Web%20Store-Th%C3%AAm%20v%C3%A0o%20Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
</p>

> **Tên cũ: "Auto Meta - Tự động hóa cho Meta AI".** Auto Vibes là tên và phiên bản mới của chính tiện ích này, vẫn cùng mục trên Chrome Web Store. Bản hiện tại chạy trên **vibes.ai** (không còn chạy trên meta.ai/media).

---

## Cài đặt

### Bước 1 - Thêm từ Chrome Web Store

Mở **[trang Chrome Web Store](https://chromewebstore.google.com/detail/auto-meta-automation-for/bchhcfjoloinebjpbfklckgohpjehdmf)** bằng Google Chrome rồi bấm **Thêm vào Chrome**. Chrome tự cập nhật tiện ích. Tên đầy đủ hiện trên cửa hàng và trong `chrome://extensions` là **Auto Vibes x G-Labs Automation**.

### Bước 2 - Đăng nhập &amp; chọn gói

Bạn cần hai tài khoản:

- **Tài khoản Vibes AI** (Facebook / Instagram) đăng nhập trên **vibes.ai** trong cùng trình duyệt - ảnh và video do *chính tài khoản Vibes của bạn* tạo, theo hạn mức của tài khoản đó.
- **Tài khoản Google** - bấm **Đăng nhập với Google** trong bảng điều khiển để tiện ích xác định gói bản quyền. Chưa đăng nhập thì không thể bắt đầu.

Gói **Basic** miễn phí **không chạy được việc tạo** trên Vibes AI - cần gói **Lite** trở lên. Gói chỉ trả cho công cụ tự động hoá, **không** có nghĩa là tạo không giới hạn. Gói không tự gia hạn.

| Gói | 1 tháng | 6 tháng | 1 năm | Bao gồm |
|---|---|---|---|---|
| **Lite** | 50.000 ₫ | 250.000 ₫ | 500.000 ₫ | Tạo ảnh &amp; video trên Vibes AI · 10 luồng · không giới hạn prompt · 10 tác vụ trong hàng chờ · 4 ảnh / 4 video mỗi prompt · mọi chế độ tham chiếu · tự thử lại lỗi · chỉ dùng cho tiện ích |
| **Plus** | 100.000 ₫ | 500.000 ₫ | 1.000.000 ₫ | Mọi thứ của Lite + app máy tính G-Labs Studio (gói Plus) |
| **Max** | 200.000 ₫ | 1.000.000 ₫ | 2.000.000 ₫ | Mọi thứ của Plus · hàng chờ không giới hạn, tối đa 1000 luồng · G-Labs Studio gói Max, gồm máy chủ Webhook API |

6 tháng giá bằng 5 tháng, 1 năm bằng 10 tháng. Mua ngay trong tiện ích: bấm **huy hiệu gói** ở thanh trên → **Nâng cấp**, rồi thanh toán bằng chuyển khoản **VietQR** (ngân hàng Việt Nam), **PayPal** hoặc **USDT / Binance** - trả bằng PayPal hoặc USDT thì tính theo giá USD (Lite $3, Plus $5, Max $10 mỗi tháng). Thanh toán xong đợi 1-3 phút rồi bấm **Làm mới trạng thái**. Nâng Plus → Max giữa kỳ chỉ tính phần chênh theo số ngày còn lại.

Đã có gói **Plus / Max của G-Labs Studio**? Đăng nhập cùng tài khoản Google - hai gói này dùng được cả app máy tính lẫn tiện ích. Mỗi bản quyền chạy trên một thiết bị tại một thời điểm: đăng nhập ở nơi khác sẽ đăng xuất phiên này.

---

## Lần chạy đầu tiên

1. **Mở [vibes.ai](https://vibes.ai)** trong Chrome và đăng nhập tài khoản Vibes AI.
2. **Mở bảng điều khiển** - bấm biểu tượng **Auto Vibes** trên thanh công cụ, hoặc nút nổi phát sáng ở góc dưới phải trang vibes.ai (kéo được tới chỗ khác). Bảng điều khiển mở trong một cửa sổ riêng.
3. **Đăng nhập với Google** ở thanh trên. Ô **Tài khoản Vibes** phải hiện *Đã đăng nhập*; nếu chưa, bấm vào ô đó để mở hoặc kiểm tra lại tab vibes.ai.
4. **Chọn trang** - **Vibes Ảnh** hoặc **Vibes Video**.
5. **Dán prompt** (hoặc **Nhập TXT**), chọn **1 dòng / prompt** hoặc **Tách theo dòng trống** cho prompt nhiều dòng. Chỉnh model, tỷ lệ khung, số lượng, độ phân giải (video), số luồng và độ trễ.
6. Bấm **BẮT ĐẦU**. Mỗi prompt thành một dòng trong bảng, kết quả xong tới đâu tự lưu vào thư mục Downloads tới đó.

---

## Tính năng

- **Hai trang tạo, một hàng chờ** - Vibes Ảnh (văn bản → ảnh, ảnh → ảnh) và Vibes Video (văn bản → video, ảnh → video), tối đa 4 kết quả mỗi prompt.
- **Tham chiếu theo vai trò** - ảnh có ô **Nhân vật / Bối cảnh / Phong cách**; video dùng **Ảnh đầu / Ảnh cuối** hoặc **3 ảnh thành phần**.
- **Phân bổ ảnh tự động** - nạp nhiều ảnh rồi rải vào các dòng: *Chỉ ảnh đầu*, *1 Đầu - N Cuối*, *N Đầu - 1 Cuối*, *Nối tiếp (1:2→2:3)*, *Cặp đôi (1:2→3:4)*.
- **Kho ảnh tự khớp prompt** - kho ảnh tham chiếu dùng chung, tự gán ảnh vào dòng **theo từ khoá** hoặc **chính xác** theo tên; tên như `anna_char`, `beach_scene`, `shot1_start` tự vào đúng ô.
- **Hàng chờ nhiều tác vụ** - đặt tên tác vụ, mỗi tác vụ một cấu hình riêng; tạm dừng, tiếp tục, đặt lại hoặc bỏ qua cả tác vụ trong **Quản lý hàng chờ**.
- **Mỗi prompt là một dòng** - sửa, sắp xếp, chạy lại hoặc xoá từng dòng; **Chạy lại lỗi** hoặc **Chạy đã chọn**; lọc theo trạng thái. Từ gói Lite, lỗi tạm thời được tự thử lại.
- **Không mất việc** - engine chạy trong tab vibes.ai nên đóng bảng điều khiển lô vẫn chạy tiếp; prompt, hàng chờ và kết quả được khôi phục khi mở lại.
- **Tự lưu theo tác vụ** - lưu thẳng hoặc mỗi tác vụ một thư mục con, tên file theo mẫu; bấm vào kết quả để mở file.
- **Giao diện 11 ngôn ngữ**, gồm Tiếng Việt và English.

---

## Các trang

### 🖼 Vibes Ảnh

Tạo hàng loạt văn bản → ảnh và ảnh → ảnh. Chọn model, tỷ lệ khung, số ảnh mỗi prompt (1-4), số luồng và độ trễ giữa các luồng. Mỗi dòng có thể gắn ảnh tham chiếu **Nhân vật / Bối cảnh / Phong cách** - thêm từng dòng, lấy từ kho ảnh, hoặc dùng **Nạp ảnh phân bổ**. Ảnh tham chiếu trên 3,8 MB được tự thu nhỏ trước khi tải lên.

### 🎬 Vibes Video

Tạo hàng loạt văn bản → video và ảnh → video ở **480p hoặc 720p**, tối đa 4 video mỗi prompt. Chọn chế độ tham chiếu: **Ảnh đầu / Ảnh cuối** (kèm các kiểu phân bổ ở trên) hoặc **3 ảnh thành phần**. Tên file luôn được thêm hậu tố `_480p` / `_720p`.

### 📋 Quản lý hàng chờ

Bấm **Thêm hàng chờ** để lưu prompt + cấu hình hiện tại thành một tác vụ có tên. Quản lý hàng chờ hiện tên, cấu hình, số prompt, đường dẫn lưu và trạng thái của từng tác vụ; cho phép sửa, đặt lại (xoá kết quả cũ của tác vụ rồi chạy lại từ đầu), bỏ qua hoặc xoá. Gói Lite và Plus giữ tối đa 10 tác vụ; Max không giới hạn.

### 🗂 Kho ảnh tham chiếu

Kho ảnh tham chiếu dùng chung cho cả hai trang. Thêm ảnh, xem đánh giá đặt tên có dễ khớp không, rồi **Thêm vào dòng đã chọn** hoặc bật **Tự động gán ảnh vào dòng theo prompt** (theo từ khoá: gõ ≥3 ký tự đầu của một từ trong tên ảnh là khớp; chính xác: prompt phải ghi đúng nguyên tên ảnh).

### ⚙ Cài đặt

Mẫu **Đặt tên file** - *Mặc định* `{row}_{prompt}_{slot}`, *Thời gian*, *Chỉ số*, *Tiền tố + Số*, *Ngày + Prompt* hoặc *Tùy chỉnh* - kèm tiền tố, số chữ số tối thiểu, ký tự phân cách, độ dài tối đa nội dung và ô xem trước. Ngôn ngữ giao diện chọn ở thanh trên.

---

## Quyền truy cập &amp; quyền riêng tư

| Quyền | Để làm gì |
|---|---|
| `storage`, `unlimitedStorage` | Lưu prompt, hàng chờ, kho ảnh tham chiếu (lưu dạng ảnh), cài đặt và phiên làm việc trong trình duyệt; hạn mức mở rộng giúp kho ảnh không bị mất ngầm. |
| `alarms` | Bộ hẹn giờ nhẹ giữ engine chạy ổn định khi bảng điều khiển ở nền. |
| `downloads`, `downloads.open` | Lưu kết quả vào thư mục Downloads và mở file ngay từ bảng kết quả. |
| `identity`, `identity.email` | Đăng nhập Google và đọc email tài khoản để xác định gói bản quyền. |
| `https://vibes.ai/*` | Chạy việc tạo trên phiên vibes.ai của chính bạn. |
| `https://glab.duckmartians.info/*` | Máy chủ bản quyền - chỉ kiểm tra gói và giới hạn của gói. |
| `https://www.googleapis.com/*` | Đọc email tài khoản Google một lần sau khi đăng nhập. |

Prompt, ảnh, video, hàng chờ, kho ảnh và cài đặt **nằm trong trình duyệt của bạn**; việc tạo đi thẳng từ phiên vibes.ai của bạn. Máy chủ bản quyền chỉ nhận email Google, token đăng nhập (dùng tạm) và một mã cài đặt ngẫu nhiên. Tiện ích không tải mã từ xa.

---

## Nơi lưu dữ liệu

| Dữ liệu | Vị trí |
|---|---|
| Ảnh đã tạo | Mặc định `Downloads/AutoVibes/Image` (lưu thẳng, hoặc mỗi tác vụ một thư mục con) |
| Video đã tạo | Mặc định `Downloads/AutoVibes/Video` (lưu thẳng, hoặc mỗi tác vụ một thư mục con) |
| Prompt, hàng chờ, kho ảnh, cài đặt, phiên làm việc | Bộ nhớ cục bộ của tiện ích trong Chrome (`chrome.storage.local`) |

Hết hạn gói thì tiện ích về gói Basic; dữ liệu trong trình duyệt vẫn giữ nguyên.

---

## Khắc phục sự cố

**"Chưa đăng nhập trên tab vibes.ai"** - đăng nhập Vibes AI trên tab vibes.ai, tiện ích sẽ tự nhận. Bấm vào ô **Tài khoản Vibes** để kiểm tra lại.

**"Không kết nối được với tab vibes.ai"** - tải lại (F5) tab vibes.ai rồi bấm Bắt đầu lại. Đừng đóng tab vibes.ai khi lô đang chạy.

**Bấm Bắt đầu không chạy / hiện yêu cầu nâng cấp** - gói Basic không tạo được trên Vibes AI. Xem huy hiệu gói ở thanh trên; sau khi thanh toán, bấm **Làm mới trạng thái**.

**Bị đăng xuất với "PHÁT HIỆN XUNG ĐỘT"** - bản quyền vừa đăng nhập ở thiết bị khác. Đăng nhập lại để tiếp tục trên máy này.

**Chrome hỏi nơi lưu cho từng file** - vào `chrome://settings/downloads` và tắt **Hỏi vị trí lưu mỗi tệp trước khi tải xuống**.

**Một dòng lỗi vi phạm chính sách** - Vibes AI chặn nội dung (thường do người nổi tiếng, bạo lực, trẻ em hoặc nội dung tình dục trong prompt hoặc ảnh tham chiếu). Sửa lại rồi chạy lại dòng đó.

---

<sub>Auto Vibes là công cụ độc lập, không liên kết, không được Meta hay Vibes AI tài trợ hoặc xác nhận. Meta, Vibes, Facebook và Instagram là nhãn hiệu của Meta Platforms, Inc.</sub>
