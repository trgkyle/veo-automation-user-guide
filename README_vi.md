[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb)

# 🎬 VEO Automation v2.1.2 - Tự động hóa Google Flow AI VEO [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**VEO Automation** là một tiện ích mở rộng Chrome mạnh mẽ giúp tự động hóa việc tạo video và hình ảnh hàng loạt trên Google Flow AI VEO3. Xử lý nhiều prompt cùng lúc, cấu hình quy trình làm việc và tự động tải xuống nội dung đã tạo một cách dễ dàng.

-----

## ✨ Tính năng chính

* **🚀 Hỗ trợ hàng đợi:** Thêm nhiều prompt vào danh sách chờ thay vì phải thao tác thủ công từng prompt. Công cụ sẽ tự động xử lý lần lượt từng tác vụ.
* **📝 Văn bản thành Video:** Hỗ trợ nhập file `.txt` chứa hàng trăm prompt tạo thành video từ văn bản.
* **🖼️ Hình ảnh thành Video:** Tạo video bằng khung hình đầu và cuối (start frame, end frame). có thể chọn 1 hoặc 2 mỗi prompt trong phần cài đặt
* **🎨 Thành phần thành Video:** Tạo video bằng các ảnh tham chiếu nhân vật
* **🖼️ Văn bản thành Hình ảnh:** Tạo hình ảnh từ mô tả văn bản.
* **🔄 Hình ảnh thành Hình ảnh:** Tạo hình ảnh từ ảnh tham chiếu nhân vật
* **💾 Tự động tải xuống:** Tự động lưu video và hình ảnh vào máy của bạn ngay sau khi render xong. Hỗ trợ tổ chức thư mục theo tên dự án.
* **🛡️ Cơ chế thử lại:** Tự động thử lại khi gặp lỗi mạng hoặc Google tạo lỗi.
* **⚙️ Tùy chỉnh sâu:**  
   * Chọn Mô hình (Veo 3.1 Fast, ...).  
   * Chọn Tỷ lệ khung hình (16:9, 9:16, 1:1).  
   * Đặt số lượng video tải về chô mỗi prompt (1-4 video).
   * Cấu hình chạy đồng thời (1-6 prompt cùng lúc).
   * Đặt độ trễ mỗi lần tạo prompt (0-300 giây).

-----

## 📥 Cài đặt

### Phương pháp 1: Chrome Web Store (Khuyến nghị)
1. Truy cập [Chrome Web Store](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb)
---

## 📖 Hướng dẫn sử dụng

### Bắt đầu

1. **Điều hướng đến Google Flow**
   - Mở [Google Labs Flow](https://labs.google/fx/tools/flow)
   - Tiện ích chỉ hoạt động trên trang dự án Flow

2. **Mở tiện ích**
   - Nhấp vào biểu tượng tiện ích trong thanh công cụ Chrome và ghim lại để lần sau sử dụng chỉ cần ấn vào tiện ích rồi sử dụng luôn sẽ thuận tiện hơn

3. **Chọn chế độ**
   - Chọn từ 5 chế độ tạo trong tab Điều khiển
   - Mỗi chế độ có tính năng và yêu cầu cụ thể

### 1. Chế độ Văn bản thành Video

1. Chọn chế độ **Văn bản thành Video** trong tab Điều khiển.
2. Nhập prompt vào ô nhập (mỗi prompt phân tách bằng dòng trống) HOẶC nhấp nút **Tải lên file (.txt)** để tải lên danh sách prompt.
3. Cấu hình cài đặt thời lượng (8s hoặc Nối tiếp).
4. Nhấp **Chạy** để bắt đầu xử lý hàng loạt.
5. Theo dõi tiến độ trong phần tiến độ.

**Ví dụ Prompt:**
```
Hoàng hôn yên bình trên đại dương êm đềm với sóng nhẹ.
Máy quay từ từ quét ngang đường chân trời.

Phố phường nhộn nhịp vào ban đêm với đèn neon.
Xe cộ và người đi bộ di chuyển qua khung cảnh.
```

### 2. Chế độ Hình ảnh thành Video

1. Chọn chế độ **Hình ảnh thành Video**.
2. Nhấp **Chọn hình ảnh** để tải lên (hỗ trợ chọn nhiều hình ảnh cùng lúc).
3. Nhập prompt cho mỗi hình ảnh (phân tách bằng dòng trống).
4. Cấu hình cài đặt thời lượng (8s hoặc Nối tiếp).
5. Nhấp **Chạy** để xử lý.

**Mẹo:**
- Hình ảnh được xử lý với mỗi prompt
- Sắp xếp hình ảnh theo tên, ngày hoặc thứ tự tùy chỉnh bằng cách kéo thả các ảnh
- Sử dụng 1-2 hình ảnh mỗi prompt (có thể cấu hình trong cài đặt)

### 3. Chế độ Thành phần thành Video

1. Chọn chế độ **Thành phần thành Video**.
2. Tải lên hình ảnh thành phần.
3. Nhập prompt mô tả hoạt ảnh.
4. Bật "Tự động thêm ảnh nhân vật" (tùy chọn) - tự động khớp ảnh nhân vật dựa trên tên file. Ví dụ prompt: dog.png, cat.png, duck.png prompt: dog playing with cat, thì ảnh dog.png và cat.png sẽ được thêm vào prompt
5. Nhấp **Chạy** để tạo video.

**Tính năng:**
- Tự động khớp ảnh nhân vật dựa trên tên file
- Hỗ trợ tối đa 3 hình ảnh mỗi prompt
- Sử dụng tốt cho việc đồng bộ nhân vật

### 4. Chế độ Văn bản thành Hình ảnh

1. Chọn chế độ **Văn bản thành Hình ảnh**.
2. Nhập mô tả hình ảnh chi tiết.
3. Cấu hình tỷ lệ khung hình và mô hình hình ảnh trong Cài đặt.
4. Nhấp **Chạy** để tạo hình ảnh.

**Tính năng:**
- Hỗ trợ tải ảnh 4k/2k/1k

### 5. Chế độ Hình ảnh thành Hình ảnh

1. Chọn chế độ **Hình ảnh thành Hình ảnh**.
2. Tải lên hình ảnh nguồn.
3. Nhập prompt chuyển đổi.
4. Cấu hình cài đặt (tối đa 10 hình ảnh mỗi prompt).
5. Bật "Tự động thêm ảnh nhân vật" (tùy chọn) - tự động khớp ảnh nhân vật dựa trên tên file. Ví dụ prompt: dog.png, cat.png, duck.png prompt: dog playing with cat, thì ảnh dog.png và cat.png sẽ được thêm vào prompt
6. Nhấp **Chạy** để tạo ảnh dựa trên ảnh tham chiếu

**Tính năng:**
- Hỗ trợ tải ảnh 4k/2k/1k

### Quản lý Hàng đợi

* Xem danh sách tác vụ đang chờ trong phần Hàng đợi Prompt.
* Bạn có thể **Xóa** tác vụ đã chạy hoặc **Dừng** tác vụ đang chạy.
* Theo dõi tiến độ theo thời gian thực cho mỗi prompt.

---

## ⚙️ Cấu hình Cài đặt

Truy cập tab **Cài đặt** để tùy chỉnh:

### Cài đặt chung
- **Chế độ mặc định**: Đặt chế độ tạo bạn hay dùng để mở tiện ích tự chọn cho bạn
- **Tỷ lệ khung hình mặc định**: Chọn 16:9, 9:16
- **Số đầu ra mỗi prompt**: 1-4 số lượng ảnh hoặc video bạn muốn tạo mỗi prompt
- **Prompt đồng thời**: 1-6 prompt cùng lúc
- **Độ trễ Prompt**: Thời gian chờ giữa các prompt (0-300 giây)

### Chọn mô hình
- **Mô hình Video**: Chọn từ các biến thể Veo 3.1 hoặc Veo 2
- **Mô hình Hình ảnh**: Chọn mô hình AI cho văn bản thành hình ảnh

### Cài đặt tải xuống
- **Chất lượng tải xuống tự động (Video)**: 720p, 1080p hoặc Không tải xuống
- **Chất lượng tải xuống tự động (Hình ảnh)**: 1k, 2k, 4k hoặc Không tải xuống
- Video được lưu vào thư mục Tải xuống của Chrome
- Mỗi dự án có thư mục riêng

### Cài đặt nâng cao
- **Số lần thử lại tối đa**: 1-20 lần thử lại khi thất bại
- **Khung hình video mặc định**: 8 giây hoặc Nối tiếp
- **Số hình ảnh tối đa mỗi prompt**: Cấu hình cho mỗi chế độ
- **Ngôn ngữ**: Tiếng Anh, Tiếng Việt hoặc Tiếng Trung

---

## 💡 Mẹo & Thực hành tốt nhất

1. **Viết Prompt**
   - Cụ thể về phong cách, thời lượng và yếu tố hình ảnh
   - Nên sử dụng prompt tiếng anh
   - Để chạy nhiều prompt mỗi prompt cách 1 dòng trống

2. **Xử lý hàng loạt**
   - Các bác nên để tầm 3 prompt đồng thời nếu flow ít bị lỗi và để là 2 nếu vào giờ cao điểm
   - Điều chỉnh độ trễ khoảng 30s

3. **Quản lý hình ảnh**
   - Đặt tên hình ảnh rõ ràng để tự động khớp
   - Sử dụng định dạng được hỗ trợ (PNG, JPG, GIF)

4. **Hiệu suất**
   - Ít prompt đồng thời = ổn định hơn
   - Độ trễ cao hơn = ổn định hơn
   - Sử dụng cài đặt chất lượng phù hợp cho tải xuống

---

## 🔧 Khắc phục sự cố

| Vấn đề                     | Nguyên nhân & Giải pháp                                                                                                                                                     |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tiện ích không hoạt động** | Đảm bảo bạn đang ở trang dự án Google Flow. Kiểm tra xem tiện ích đã được bật chưa. Làm mới trang và thử lại.                                                               |
| **Lỗi không thể tạo được video**    | Google Flow thi thoảng bị quá tải. **Đừng lo**, Tiện ích sẽ tự động chờ và thử lại mỗi 30s cho đến khi có chỗ trống.                            |
| **Video không tải xuống** | Đi tới Cài đặt Chrome -> Tải xuống -> **Tắt** _"Hỏi nơi lưu mỗi file trước khi tải xuống"_. Kiểm tra cài đặt tải xuống trong tab Cài đặt.                                    |
| **Lỗi "Chính sách"**      | Prompt hoặc hình ảnh của bạn vi phạm chính sách nội dung của Google. Công cụ sẽ tự động bỏ qua tác vụ này và tiếp tục với tác vụ tiếp theo.                                   |
| **Tạo thất bại**           | Kiểm tra kết nối internet của bạn. Xác minh prompt hợp lệ. Xem lại cài đặt thử lại. Kiểm tra console trình duyệt để tìm lỗi.                                                 |
| **Màn hình bị thu nhỏ**    | Đây là tính năng tự động của công cụ để bao phủ giao diện và định vị nút chính xác. Vui lòng không điều chỉnh zoom thủ công khi công cụ đang chạy.                         |

---

## 🔒 Quyền riêng tư & Dữ liệu

* **Hoạt động cục bộ:** VEO Automation chạy hoàn toàn trên trình duyệt của bạn.
* **Không thu thập dữ liệu:** Chúng tôi không thu thập prompt, hình ảnh hoặc video của bạn. Tất cả dữ liệu chỉ được lưu trong `Chrome Local Storage` của bạn để ghi nhớ cài đặt.
* **Quyền:** Tiện ích chỉ yêu cầu quyền truy cập vào các trang `labs.google/*` để thực hiện tác vụ tự động hóa.

---

## 📞 Hỗ trợ

- **Tác giả**: Trường Nguyễn
- **Trang web**: [kylenguyen.me](https://kylenguyen.me)
- **Báo lỗi**: Sử dụng liên kết "Báo lỗi" trong tiện ích

---

## 📦 Phiên bản

Phiên bản hiện tại: **2.1.2**

---

## 📜 Giấy phép

Bản quyền © 2025 **Trường Nguyễn**. Mọi quyền được bảo lưu.

Phần mềm này là tài sản độc quyền. Việc sao chép, sửa đổi, phân phối mã nguồn trái phép hoặc bán lại dưới bất kỳ hình thức nào mà không có sự cho phép bằng văn bản của tác giả đều bị nghiêm cấm.

---

_Tuyên bố miễn trừ trách nhiệm: Tiện ích mở rộng này là một dự án độc lập và không liên kết, được xác nhận hoặc kết nối với Google hoặc nhóm Google Flow._

**Được tạo với ❤️ bởi Trường Nguyễn**

