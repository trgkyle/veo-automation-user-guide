[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb)

# 🎬 VEO Automation v3.1.7 - Tự động hóa Google Flow AI VEO [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**VEO Automation** là một tiện ích mở rộng Chrome mạnh mẽ giúp tự động hóa việc tạo video và hình ảnh hàng loạt trên Google Flow AI VEO3. Xử lý nhiều prompt cùng lúc, cấu hình quy trình làm việc và tự động tải xuống nội dung đã tạo một cách dễ dàng.

-----

## ✨ Tính năng chính

* **🚀 Hỗ trợ hàng đợi:** Thêm nhiều prompt vào danh sách chờ thay vì phải thao tác thủ công từng prompt. Công cụ sẽ tự động xử lý lần lượt từng tác vụ.
* **🧩 Workflow (giao diện kéo thả trực quan):** Nối prompt, ảnh và các bước tạo trên một bảng vẽ — ví dụ tạo ảnh rồi tự động dùng chính ảnh đó để tạo video. Lưu nhiều workflow, chạy từng node hoặc chạy tất cả, nhập/xuất workflow thành file.
* **📝 Văn bản thành Video:** Hỗ trợ nhập file `.txt`, `.xlsx`, hoặc `.csv` chứa hàng trăm prompt tạo thành video từ văn bản.
* **🖼️ Khung hình thành video:** Tạo video bằng khung hình tĩnh và thêm hiệu ứng chuyển động tự động. Hỗ trợ chỉ dùng frame bắt đầu hoặc dùng cả frame bắt đầu và kết thúc cho mỗi prompt.
* **🎨 Thành phần thành video:** Tạo hoạt ảnh cho các thành phần UI, giao diện hoặc nhân vật thành video. Hỗ trợ tự động thêm ảnh nhân vật dựa trên tên file.
* **🖼️ Văn bản thành hình ảnh:** Tạo hình ảnh từ mô tả văn bản.
* **🔄 Hình ảnh thành hình ảnh:** Chuyển đổi và nâng cấp hình ảnh bằng AI với prompt văn bản.
* **🤖 Tự động hóa Agent:** Tự động hóa các tác vụ bằng các kiểm soát agent nâng cao với AI agent của Google Flow.
* **📂 Nhập từ bảng tính:** Trực tiếp nhập danh sách prompt từ file bảng tính (`.xlsx` hoặc `.csv`) với giao diện xem trước sheet và cột.
* **💾 Tự động tải xuống:** Tự động lưu video (720p, 1080p, 4K) và hình ảnh (1k, 2k, 4k) trực tiếp vào máy của bạn. Hỗ trợ tổ chức thư mục theo tên dự án.
* **🛡️ Cơ chế thử lại:** Tự động thử lại khi gặp lỗi mạng hoặc Google tạo lỗi (có thể tùy chỉnh lên đến 20 lần).
* **🌐 Giao diện đa ngôn ngữ:** Hỗ trợ 20 ngôn ngữ bao gồm tiếng Anh, tiếng Việt, tiếng Trung và nhiều ngôn ngữ khác.

-----

## 📥 Cài đặt

### Phương pháp 1: Chrome Web Store (Khuyến nghị)
1. Truy cập [Chrome Web Store](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb) và bấm **Thêm vào Chrome**.

---

## 📖 Hướng dẫn sử dụng

### Bắt đầu

1. **Điều hướng đến Google Flow**
   - Mở [Google Labs Flow](https://labs.google/fx/tools/flow)
   - Tiện ích chỉ hoạt động trên trang dự án Flow.

2. **Mở tiện ích**
   - Nhấp vào biểu tượng tiện ích trong thanh công cụ Chrome và ghim lại để truy cập nhanh chóng hơn.

3. **Chọn chế độ**
   - Chọn từ 6 chế độ tạo trong tab Điều khiển.

---

### 1. Chế độ Văn bản thành Video

1. Chọn chế độ **Văn bản thành video** trong tab Điều khiển.
2. Nhập prompt vào ô nhập (mỗi prompt phân tách bằng một dòng trống) HOẶC nhấp nút **Tải lên .txt** hoặc **Tải lên .xlsx / .csv** để nhập prompt.
3. Cấu hình cài đặt thời lượng trong Cài đặt (ví dụ: 4s, 6s, 8s, 10s hoặc các chế độ Nối tiếp).
4. Nhấp **Chạy** để bắt đầu xử lý hàng loạt.

**Ví dụ Prompt:**
```
Hoàng hôn yên bình trên đại dương êm đềm với sóng nhẹ.
Máy quay từ từ quét ngang đường chân trời.

Phố phường nhộn nhịp vào ban đêm với đèn neon.
Xe cộ và người đi bộ di chuyển qua khung cảnh.
```

---

### 2. Chế độ Khung hình thành Video (trước đây là Hình ảnh thành Video)

1. Chọn chế độ **Khung hình thành video**.
2. Nhấp khu vực tải lên để chọn hình ảnh (hỗ trợ chọn nhiều hình ảnh cùng lúc).
3. Nhập prompt cho mỗi hình ảnh (phân tách bằng dòng trống).
4. Trong phần Cài đặt, chọn chỉ sử dụng frame bắt đầu hoặc cả frame bắt đầu và kết thúc cho mỗi prompt.
5. Nhấp **Chạy** để xử lý.

---

### 3. Chế độ Thành phần thành Video

1. Chọn chế độ **Thành phần thành video**.
2. Tải lên hình ảnh thành phần/nhân vật.
3. Nhập prompt mô tả hoạt ảnh.
4. **Tự động thêm ảnh nhân vật** (tùy chọn): Bật tính năng này để khớp và tự động thêm ảnh nhân vật vào prompt dựa trên tên file.
5. **Tự động thêm nhân vật (Tính năng Google Flow ⭐)**: Tự động chọn nhân vật dự án nếu tên của họ được đề cập trong prompt (bấm **Quét nhân vật** để đồng bộ).
6. **Tự động thêm giọng nói theo diễn giả**: Tự động chọn giọng nói của diễn giả khi tên diễn giả được đề cập trong prompt.
7. Nhấp **Chạy** để tạo.

---

### 4. Chế độ Văn bản thành Hình ảnh

1. Chọn chế độ **Văn bản thành hình ảnh**.
2. Nhập mô tả hình ảnh chi tiết (mỗi prompt cách nhau một dòng trống).
3. Cấu hình tỷ lệ khung hình và mô hình hình ảnh trong Cài đặt.
4. Nhấp **Chạy** để tạo hình ảnh.

---

### 5. Chế độ Hình ảnh thành Hình ảnh

1. Chọn chế độ **Hình ảnh thành hình ảnh**.
2. Tải lên hình ảnh nguồn.
3. Nhập prompt chuyển đổi.
4. **Tự động thêm ảnh nhân vật** (tùy chọn): Khớp ảnh nhân vật vào prompt tự động dựa trên tên file.
5. Nhấp **Chạy** để tạo.

---

### 6. Chế độ Tự động hóa Agent

1. Chọn chế độ **Tự động hóa Agent**.
2. Nhập các prompt mô tả hướng dẫn cho Agent.
3. Hỗ trợ kiểm soát nhân vật (Google Flow feature ⭐) và tự động thêm giọng nói theo diễn giả dựa trên đề cập trong prompt.
4. Nhấp **Chạy** để thực thi các tác vụ tự động bằng Agent.

---

### 📁 Lưu trữ & Đặt tên file (Hỗ trợ ở tất cả chế độ)

Bên dưới các ô nhập prompt/hình ảnh ở mỗi chế độ, bạn có thể thiết lập cách lưu trữ tệp tin tải về:
* **Lưu vào thư mục**: Chỉ định tên thư mục con bên trong thư mục Tải xuống mặc định của Chrome (ví dụ: `project-1`) để tự động sắp xếp các tệp đã tạo.
* **Tự động đổi tên file**: Bật tùy chọn để tiện ích tự động đổi tên các tệp đã tải xuống với tiền tố rõ ràng và đường dẫn thư mục dự án, hoặc tắt đi để giữ nguyên hành vi đặt tên mặc định của trình duyệt.

---

### 📂 Nhập từ bảng tính Spreadsheet & File

- Để nhập hàng loạt prompt, nhấp nút **Tải lên .xlsx / .csv** hoặc **Tải lên .txt** trong bất kỳ chế độ nào.
- Đối với bảng tính, một hộp thoại xem trước sẽ xuất hiện cho phép bạn chọn **Sheet** và **Cột** chứa prompt cần nhập.
- Bấm **Nhập prompt** để đưa vào hàng chờ.

---

### Quản lý Hàng đợi

* Xem danh sách tác vụ đang chờ trong phần **Hàng đợi prompt**.
* Bấm **Xóa** để hủy các tác vụ hoặc **Dừng** để dừng toàn bộ hàng đợi đang chạy.
* Thời gian chờ đếm ngược giữa các prompt được hiển thị trực quan theo thời gian thực.

### 🧩 Workflow (Giao diện kéo thả trực quan)

Workflow là giao diện kéo thả trực quan cho các quy trình nhiều bước — ví dụ: tạo vài ảnh, dùng chính các ảnh đó để tạo video, rồi nối tiếp mỗi video bằng một prompt khác. Workflow mở trong cửa sổ riêng và chạy trên tab Google Flow bạn đang mở.

#### Mở Workflow

* Nhấn **Workflow** trong tab Điều khiển (hàng nút dưới cùng).
* Đã nhập prompt hoặc tải ảnh ở side panel? Rê chuột vào **Workflow** rồi nhấn **Chuyển sang workflow**: prompt, chế độ của từng prompt và ảnh sẽ thành các node trong workflow, sẵn sàng để chạy.

#### Màn hình

| Khu vực | Gồm những gì |
| :--- | :--- |
| **Bên trái** | **Node** (bấm hoặc kéo vào bảng vẽ) và **Workflow của bạn** (danh sách workflow đã lưu) |
| **Thanh trên cùng** | Công cụ bảng vẽ: Hoàn tác/Làm lại, **Tự sắp xếp**, vừa khung nhìn, **Ví dụ**, xoá. Bên phải: nút **Chi tiết**, **Phím tắt** và trạng thái tab Google Flow |
| **Bảng vẽ** | Các node của bạn. Góc trên trái: **Chạy tất cả** (và **Dừng** khi đang chạy) và **Bật chạy nền** |

Nút **Chi tiết** cho biết điều cần chú ý: **Vấn đề (n)** màu đỏ/vàng khi có gì chặn việc chạy, **Đang chạy 3/8** khi đang tạo. Bấm vào để mở bảng gồm các vấn đề (bấm một vấn đề để nhảy tới node), tiến độ, kế hoạch chạy và cài đặt đang dùng.

#### Các loại node

| Node | Chức năng |
| :--- | :--- |
| **Nhập prompt** | Một hoặc nhiều prompt, tách nhau bằng **dòng trống** |
| **Tải ảnh lên** | Ảnh của bạn (thả file vào node). Rê chuột vào ảnh: 🔍 để xem lớn, ✕ để xoá, nút kéo ở góc để đổi thứ tự. Thứ tự (hoặc menu sắp xếp) quyết định prompt nào nhận ảnh nào |
| **Tạo ảnh** | Văn bản thành Hình ảnh, hoặc Hình ảnh thành Hình ảnh khi có ảnh nối vào. Tuỳ chọn: **Chế độ ảnh theo prompt**, **Số ảnh đầu vào tối đa mỗi Prompt**, **Tự động thêm ảnh nhân vật** |
| **Tạo video** | Văn bản thành Video, hoặc khi có ảnh nối vào: **Khung hình thành Video** / **Thành phần thành Video**. Tuỳ chọn: **Chế độ video theo prompt**, số ảnh mỗi prompt (dùng chung cài đặt với side panel), **Tự động thêm ảnh nhân vật** (Thành phần thành Video) |

Node Tạo ảnh / Tạo video tự đặt tên theo prompt đầu tiên (`image_…` / `video_…`). Mỗi dòng prompt hiển thị các ảnh mà prompt đó sẽ nhận, để bạn kiểm tra trước khi chạy. Khung xem trước theo **tỉ lệ khung hình** trong cài đặt (node 9:16 hẹp và cao hơn).

**Khung hình thành Video** có thể chỉ dùng khung hình đầu, hoặc **khung hình đầu và khung hình cuối** (dùng chung cài đặt với side panel). Với khung đầu và khung cuối, mỗi prompt lấy 2 ảnh theo thứ tự (prompt nối tiếp video trước lấy 1 ảnh); nếu không đủ ảnh, node hiện cảnh báo và không chạy được.

#### Nối các node

Kéo từ chấm tròn bên phải của một node và **thả vào bất kỳ chỗ nào trên node kia** — cổng phù hợp sẽ được chọn tự động. Trong lúc kéo, node nào nối được sẽ sáng viền.

| Từ | Đến | Ý nghĩa |
| :--- | :--- | :--- |
| Nhập prompt | Tạo ảnh / Tạo video | Các prompt cần tạo |
| Tải ảnh lên | Tạo ảnh / Tạo video | Ảnh tham chiếu, khung hình bắt đầu hoặc thành phần |
| Tạo ảnh | Tạo ảnh / Tạo video | **Ảnh vừa tạo** trở thành ảnh đầu vào của node đó (node đó chạy khi ảnh đã sẵn sàng) |
| Tạo video — cổng **khung cuối** | Tạo video | Video sau **nối tiếp từ khung hình cuối** của video trước |
| Tạo video — cổng **khung cuối** | Tạo ảnh | **Khung hình cuối** của mỗi video trở thành ảnh đầu vào (chạy khi video đã sẵn sàng) |

#### Chạy

* **Chạy tất cả** (góc trên trái, hoặc `Ctrl/⌘ + Enter`) chạy cả workflow theo đúng thứ tự: node nào cần ảnh được tạo sẽ tự chạy khi ảnh đã có.
* Nếu **Chạy tất cả** bị khoá, thanh trên cùng hiện **Vấn đề (n)**: bấm vào để xem cần sửa gì.
* Mỗi node Tạo ảnh / Tạo video có nút **Chạy** riêng để chỉ chạy node đó. Nút bị khoá cho tới khi các node nó phụ thuộc chạy xong (rê chuột để xem lý do).
* **Dừng** huỷ những gì đang chạy.
* Khi đang chạy, các đường nối vào node đang tạo sẽ sáng lên và có dòng chảy, để bạn thấy workflow đang ở bước nào.

> ⚠️ **Chrome tạm dừng Google Flow khi tab không hiển thị** (ví dụ cửa sổ workflow che toàn màn hình). Nhấn **Bật chạy nền** (ngay dưới **Chạy tất cả** trong workflow, hoặc ở side panel), rồi chọn tab Google Flow trong hộp thoại của Chrome. Việc này chia sẻ tab Google Flow (không ghi lại hay gửi đi đâu) để Google Flow tiếp tục tạo khi bị cửa sổ khác che. Nhãn xanh **Đang chạy nền** cho biết đã bật; nhấn ✕ để tắt.

#### Kết quả

Kết quả hiện ngay trong node Tạo ảnh / Tạo video. Rê chuột vào kết quả: 🔍 để xem lớn, ✕ để xoá (nút cục tẩy xoá toàn bộ kết quả của node). Video tự phát khi rê chuột. File vẫn được tải xuống như bình thường.

Node phía sau dùng **kết quả đầu tiên của mỗi prompt**. Muốn chọn kết quả khác, kéo nút ở góc trên trái của một kết quả thả lên kết quả khác để đổi chỗ (ảnh và video).

#### Quản lý workflow

Trong **Workflow của bạn** (bên trái): **Tạo mới**, **Nhập**, và menu **⋯** của từng workflow — **Đổi tên** (hoặc bấm đúp vào tên), **Nhân bản**, **Xuất file**, **Xoá**. Mọi thay đổi được lưu tự động.

* **Xuất file** tải về file `.json`. Đầu file có các dòng chú thích `//` mô tả mọi node, thuộc tính và cách nối, nên bạn có thể đưa file cho trợ lý AI và nhờ AI viết workflow mới. Các dòng `//` được bỏ đi khi nhập.
* **Nhập** file bằng nút Nhập, hoặc đơn giản **kéo file `.json` thả vào bảng vẽ**.

#### Phím tắt khi chỉnh sửa

Nhấn **Phím tắt** trên thanh trên cùng (hoặc phím `?`) để xem tất cả.

| Thao tác | Phím |
| :--- | :--- |
| Hoàn tác / Làm lại | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Sao chép / Cắt / Dán node (dán được sang workflow khác) | `Ctrl/⌘ + C / X / V` |
| Nhân bản phần đang chọn | `Ctrl/⌘ + D` |
| Chọn tất cả / Chọn thêm / Quét chọn | `Ctrl/⌘ + A` / `Ctrl/⌘ + bấm` / `Shift + kéo` |
| Tự sắp xếp | `Shift + A` |
| Xoá phần đang chọn | `Delete` |
| Chạy tất cả / Chạy nền | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

---

## ⚙️ Cấu hình Cài đặt
 
Truy cập tab **Cài đặt** để tùy chỉnh:

### Cài đặt chung
- **Chế độ mặc định**: Đặt chế độ tạo bạn hay dùng nhất khi mở extension.
- **Tỷ lệ khung hình mặc định**: Chọn 16:9, 9:16, 1:1, 3:4 hoặc 4:3.
- **Số đầu ra cần tạo từ 1 prompt**: Đặt số lượng (1-4 ảnh/video) muốn tạo cho mỗi prompt.
- **Prompt đồng thời**: Xử lý 1-6 prompt cùng lúc (lưu ý: chế độ Nối tiếp/Agent sẽ luôn chạy 1 prompt đồng thời để tránh xung đột).
- **Thời gian chờ ngẫu nhiên**: Thêm thời gian chờ giữa các lần gửi prompt để tránh bị giới hạn tần suất.

### Chọn mô hình
- **Mô hình**: Chọn phiên bản mô hình tạo video Veo 3.1 hoặc Veo 2, bao gồm `Veo 3.1 - Lite`, `Veo 3.1 - Lite [Lower Priority]`, `Veo 3.1 - Fast`, `Veo 3.1 - Quality`, và `Omni Flash`.
- **Mô hình hình ảnh**: Chọn mô hình AI tạo ảnh từ văn bản, bao gồm `Nano Banana 2 Lite`, `Nano Banana Pro`, và `Nano Banana 2`.

### Tùy chọn chế độ cụ thể
- **Tùy chọn video mặc định**: Chọn thời lượng 4s, 6s, 8s, 10s hoặc chế độ nối tiếp (`4s/6s/8s/10s nối tiếp`).
  > [!NOTE]
  > Chế độ nối tiếp sẽ kết hợp prompt hiện tại với prompt tiếp theo. Prompt cuối cùng trong chuỗi sẽ luôn sử dụng thời lượng tiêu chuẩn (không nối tiếp).
- **Tùy chọn chế độ ảnh mặc định**: Đặt thành Ảnh mới hoặc Ảnh cuối (tái sử dụng kết quả của prompt trước làm đầu vào).
- **Số hình ảnh/video đầu vào tối đa**: Cài đặt giới hạn số ảnh cho Khung hình thành video, Thành phần thành video, và Hình ảnh thành hình ảnh.
- **Cấu hình Character Control**: Thiết lập **Nhân vật mặc định** (Default characters) và bật/tắt kiểm soát nhân vật.
- **Cấu hình giọng nói diễn giả**: Đặt **Diễn giả mặc định** (Default speaker) khi không có diễn giả nào khớp trong prompt.

### Tải xuống & Cài đặt nâng cao
- **Chất lượng tải xuống tự động (Video)**: Cài đặt độ phân giải tải về cho Video (720p, 1080p, 4K). Các chất lượng 1080p/4K yêu cầu gói Ultra/Pro.
- **Chất lượng tải xuống tự động (Hình ảnh)**: Cài đặt chất lượng tải về cho Hình ảnh (1k, 2k, 4k). Chất lượng 4k yêu cầu gói Ultra.
- **Số lần thử lại tối đa**: Cấu hình tự động thử lại khi lỗi (1-20 lần).
- **Ngôn ngữ**: Chọn ngôn ngữ hiển thị trong số 20 ngôn ngữ được hỗ trợ (tiếng Anh, tiếng Việt, tiếng Trung, tiếng Hàn, tiếng Tây Ban Nha, tiếng Nhật, v.v.).

---

## 💳 Đăng ký & Gói cước

VEO Automation cung cấp **Gói Miễn phí** và **Gói Max** (30.000đ/tháng):
- Bấm **Đăng nhập** ở Banner gói cước để đăng nhập bằng địa chỉ email của bạn (không cần trùng khớp với tài khoản Google Flow).
- Nhập mã xác thực gửi về mail để kiểm tra trạng thái gói cước.
- Nâng cấp lên gói Max giúp mở khóa các tùy chọn nâng cao (tải video 1080p/4K, tùy chọn nối tiếp Ultra và giới hạn lượt tạo hàng ngày cao hơn).

---

## 💡 Mẹo & Thực hành tốt nhất

1. **Tránh giới hạn tần suất (Rate Limit)**
   - Nên để số prompt đồng thời từ 2-3 trong giờ cao điểm.
   - Thiết lập thời gian chờ ngẫu nhiên khoảng 30 giây trở lên.

2. **Đặt tên ảnh hợp lệ**
   - Khi sử dụng tự động khớp ảnh nhân vật, hãy đặt tên ảnh rõ ràng (vd: `hero_pose.png`) và đề cập chính xác tên file đó trong prompt.

3. **Sửa lỗi Hoạt động bất thường (Unusual Activity)**
   - Hãy chắc chắn rằng bạn có thể tự tay gửi tối thiểu 3 prompt liên tiếp trên Google Flow mà không gặp lỗi trước khi bật tự động hóa.

---

## 🔧 Khắc phục sự cố

| Vấn đề | Nguyên nhân & Giải pháp |
| --- | --- |
| **Tiện ích không hoạt động** | Đảm bảo bạn đang ở trang dự án Google Flow (`labs.google/fx/tools/flow/project/...`). |
| **Lỗi Unusual Activity / Xác minh** | 1. Nhấp nút **Sửa lỗi** (Xóa Cache) ở tab Điều khiển.<br>2. Thử tạo một dự án mới.<br>3. Thử sử dụng một Profile trình duyệt mới.<br>4. Kiểm tra tài khoản bằng cách tạo thủ công xem có bị Google đánh dấu spam không. |
| **Không tải xuống được video/ảnh** | Tắt hộp thoại hỏi nơi lưu của Chrome: Cài đặt Chrome -> Tải xuống -> **Tắt** *"Hỏi nơi lưu mỗi file trước khi tải xuống"*. |
| **Lỗi Chính sách (Policy Error)** | Google chặn prompt/hình ảnh do vi phạm chính sách. Công cụ sẽ tự động bỏ qua và chuyển sang prompt tiếp theo. |
| **Màn hình tự động thu nhỏ** | Đây là tính năng tự động của công cụ để bao phủ giao diện và định vị nút chính xác. Vui lòng không thay đổi mức zoom trình duyệt thủ công khi đang chạy. |
| **Workflow: kết quả đứng mãi ở "Đang tạo"** | Chrome đã tạm dừng tab Google Flow bị che. Bật **Bật chạy nền** (hoặc **Chạy nền**), hoặc để tab Google Flow hiển thị. |
| **Workflow: nút Chạy của một node bị mờ** | Rê chuột vào nút: chạy node mà nó phụ thuộc trước, hoặc sửa vấn đề được báo (ví dụ chưa nối prompt). |
| **Workflow: Chạy tất cả bị khoá** | Bấm **Vấn đề (n)** trên thanh trên cùng để xem cần sửa gì; bấm một vấn đề để nhảy tới node đó. |
| **Workflow: "Không tìm thấy tab Google Flow"** | Mở [Google Flow](https://labs.google/fx/tools/flow) trong một tab (chấm xanh trên thanh trên cùng cho biết đã kết nối). |

---

## 🔒 Quyền riêng tư & Dữ liệu

* **Chạy cục bộ:** Tiện ích hoạt động hoàn toàn bên trong sandbox trình duyệt của bạn.
* **Không thu thập dữ liệu:** Prompt, hình ảnh, tài nguyên của bạn được lưu trong `Chrome Local Storage` của máy bạn để đồng bộ cấu hình cài đặt và tuyệt đối không bao giờ gửi về máy chủ bên ngoài.

---

## 📞 Hỗ trợ & Giấy phép

- **Tác giả**: Trường Nguyễn
- **Trang web**: [kylenguyen.me](https://kylenguyen.me)
- **Bản quyền**: Bản quyền © 2025 Trường Nguyễn. Mọi quyền được bảo lưu. (Phần mềm độc quyền; nghiêm cấm sao chép, bán lại hoặc phân phối trái phép).

_Tuyên bố miễn trừ trách nhiệm: Tiện ích mở rộng này là một dự án độc lập và không liên kết, được xác nhận hoặc kết nối với Google hoặc nhóm Google Flow._
