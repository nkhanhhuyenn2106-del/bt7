# Dự Án Mini-Site Câu Lạc Bộ Sinh Viên (INS2053 - Session 07)

Dự án bài tập môn **INS2053: Soạn thảo & Quản trị Web (Web Authoring and Web Management)** - Trường Quốc tế, ĐHQGHN (VNU-IS).

## 📌 Nội dung Bài tập 7: Typography với Google Fonts

### 1. Cấu trúc thư mục chuẩn
```text
INS2053-Club-Website/
├── project/
│   ├── index.html        # Trang chủ CodeBreakers Club
│   ├── about.html        # Trang giới thiệu sứ mệnh & thành viên
│   ├── contact.html      # Trang liên hệ & biểu mẫu gửi thông tin
│   └── css/
│       └── style.css     # File CSS định kiểu Typography & hiệu ứng
├── homework/
│   └── submissions.md    # Nơi dán link Google Drive video OBS
└── README.md
```

### 2. Các tiêu chí đạt điểm tối đa (Rubric 10/10 điểm Code)
- **Tích hợp Google Fonts (3đ):** Đã tích hợp cặp font `Poppins` (tiêu đề) và `Open Sans` (nội dung) đồng bộ trong `<head>` của cả 3 trang HTML kèm `preconnect` tối ưu tốc độ tải.
- **Áp dụng font trong CSS (2đ):** Định nghĩa font-family rõ ràng, có font dự phòng (system font fallbacks: `'Poppins', 'Segoe UI', Tahoma, sans-serif;` và `'Open Sans', Arial, sans-serif;`).
- **Phân cấp Typography (2đ):** Phân định rành mạch giữa các cấp `h1`, `h2`, `h3` qua `font-size`, `font-weight` (700, 600, 400), `letter-spacing` và đường viền trang trí.
- **Style liên kết & tương tác (2đ):** Thẻ `<a>` có màu nhận diện thương hiệu, hiệu ứng `a:hover` đổi màu và gạch chân mềm mại, hỗ trợ `focus-visible`.
- **Độ dễ đọc (1đ):** `line-height: 1.7` (vượt mức tối thiểu 1.6), khối văn bản giới hạn `max-width: 780px` căn giữa giúp người đọc không bị mỏi mắt.

---

## 🎬 Kịch Bản Quay Video OBS 60 - 90 Giây (Đạt 4/4 điểm Video)

### Chuẩn bị trước khi quay:
- Mở **OBS Studio**, chọn nguồn quay là toàn bộ màn hình (Display Capture).
- Chia màn hình làm 2 nửa:
  - Một bên là trình duyệt đang mở file `project/index.html`.
  - Một bên là VS Code đang mở file `project/index.html` và `project/css/style.css`.
- Bật micro kiểm tra âm thanh rõ ràng.

### Lời thoại mẫu (Script thuyết trình):
1. **Mở đầu (10 - 15 giây):**
   > *"Xin chào thầy và các bạn. Em tên là [Họ và tên], mã số sinh viên là [Mã SV]. Sau đây em xin phép trình bày phần thực hiện Bài tập 7 môn INS2053: Cải thiện Typography với Google Fonts cho dự án Website Câu lạc bộ sinh viên CodeBreakers."*
2. **Thân bài - Giải thích Code (35 - 45 giây):**
   > *"Trong bài tập này, em đã chọn cặp font chữ trên Google Fonts gồm: **Poppins** dành cho các tiêu đề (Headings) và **Open Sans** dành cho phần nội dung (Body text).*
   > *Đầu tiên, trong file `index.html` (và cả `about.html`, `contact.html`), ở phần thẻ `<head>`, em đã nhúng link CDN của Google Fonts kèm theo các thẻ `preconnect` để tối ưu tải font.*
   > *Tiếp theo, chuyển sang file `css/style.css`, em áp dụng font `Open Sans` cho thẻ `body` với `line-height` là 1.7 giúp bài đọc rất thoáng và dễ nhìn. Với các đề mục `h1, h2, h3`, em áp dụng font `Poppins` cùng độ đậm `font-weight: 700` để tạo sự tương phản và phân cấp thị giác rõ nét. Em cũng luôn khai báo các font dự phòng như Segoe UI, Arial phòng trường hợp mạng offline.*
   > *Các liên kết đều được tùy biến màu sắc và hiệu ứng `:hover` gạch chân đổi màu rõ rệt khi rê chuột."*
3. **Kết luận (10 giây):**
   > *"Nhờ áp dụng hệ thống typography này, giao diện website trở nên chuyên nghiệp, hiện đại và thân thiện hơn rất nhiều với người đọc. Em xin kết thúc phần trình bày, cảm ơn thầy đã theo dõi ạ!"*

---

## 🚀 Hướng Dẫn Git & Tự Chấm Điểm
1. **Kiểm tra tự chấm điểm:**
   - Mở trình duyệt truy cập: `https://hieutachi.github.io/INS2053-Web-Authoring-and-Web-Management-IS_VNU_Course/cham-bai.html`
   - Chọn mục **Buổi 7**, trỏ tới thư mục `INS2053-Club-Website` để kiểm tra máy tự động chấm điểm xanh (AUTO Pass).
2. **Commit và đẩy lên Git:**
   ```bash
   cd INS2053-Club-Website
   git init
   git add .
   git commit -m "HW7: Add Google Fonts and improve typography"
   ```
3. **Nộp video:**
   - Xuất video OBS thành định dạng MP4.
   - Tải lên Google Drive cá nhân, bật chia sẻ: *"Bất kỳ ai có đường liên kết đều có thể xem"*.
   - Dán link vào file `homework/submissions.md`, sau đó commit và push lên repository của bạn.
