# TX Workspace - Bộ công cụ tổng hợp

Ứng dụng web tổng hợp nhiều công cụ tiện ích cho công việc hàng ngày.

## 🚀 Tính năng

### 1. Tra cứu kích thước thêu
- Tìm kiếm nhanh theo tên sản phẩm
- Xem dữ liệu kích thước thêu cho 50+ loại sản phẩm
- Hiển thị dạng bảng, ma trận hoặc biểu đồ
- Xuất dữ liệu ra CSV hoặc PDF
- **Admin Panel**: Đăng nhập để thêm/sửa/xóa sản phẩm và kích thước trực tiếp trên web
- Quản lý sản phẩm trực tiếp trong tool với giao diện thân thiện

### 2. Xử lý văn bản
- Chuyển đổi chữ hoa/chữ thường
- Đếm ký tự, từ, dòng
- Sao chép nhanh

### 3. Xử lý file
- Quản lý và xem thông tin file
- Drag & Drop hỗ trợ

### 4. Xử lý ảnh
- **Resize**: Điều chỉnh kích thước, giữ tỷ lệ
- **Compress**: Nén ảnh với nhiều format (JPEG/PNG/WebP)
- **Crop**: Cắt ảnh theo tọa độ
- **Rotate**: Xoay 90°, 180°
- **Flip**: Lật ngang/dọc

### 5. Công cụ tiện ích
- **QR Code Generator**: Tạo và tải QR Code
- **Password Generator**: Tạo mật khẩu mạnh với nhiều tùy chọn
- **Base64 Encode/Decode**: Mã hóa/giải mã Base64
- **JSON Formatter**: Format, minify, validate JSON
- **URL Encode/Decode**: Mã hóa/giải mã URL
- **Timestamp Converter**: Chuyển đổi Unix timestamp
- **Color Converter**: HEX ↔ RGB ↔ HSL với preview màu
- **UUID Generator**: Tạo UUID đơn hoặc hàng loạt

### 6. Tải ảnh từ CSV
- Đọc file CSV tự động
- Tự động tìm cột PO, Item ID, Artwork, Size
- Tải ảnh hàng loạt với tên PO_ItemID_Size.png
- Progress bar và báo cáo chi tiết

### 7. Chat System (Mới!)
- Chat widget nhỏ gọn ở góc màn hình
- Tự động reset sau 24 giờ để tránh đầy dung lượng
- Tên ngẫu nhiên hài hước cho mỗi người dùng (24 con vật dễ thương)
- Lưu trữ tin nhắn trong localStorage
- Responsive trên mọi thiết bị

## 📁 Cấu trúc thư mục

```
web/
├── index.html              # File chính - Trang web chính (GitHub Pages)
├── workspace.html          # File backup - Giao diện mới hoàn chỉnh
├── .nojekyll              # Tắt Jekyll cho GitHub Pages
├── .gitignore             # Git ignore file
├── lib/                    # Thư viện và assets
│   ├── css/               # Stylesheets
│   ├── js/                # JavaScript libraries
│   └── qr-donate.png      # QR Code donate
└── README.md              # File này
```

## 🎨 Giao diện

- **Dark/Light mode**: Chuyển đổi theme dễ dàng
- **Responsive design**: Tương thích mọi thiết bị
- **Modern UI**: Giao diện hiện đại với animations mượt mà và màu sắc mới
- **Modal system**: Mở các công cụ trong modal overlay
- **Chat Widget**: Widget chat nhỏ gọn, không làm phiền
- **Admin Interface**: Giao diện quản lý trực quan và dễ sử dụng

## 🛠️ Công nghệ sử dụng

- **HTML5, CSS3, JavaScript** (Vanilla JS)
- **Chart.js**: Biểu đồ
- **jsPDF**: Xuất PDF
- **PapaParse**: Xử lý CSV
- **QRCode.js**: Tạo QR Code
- **Font Awesome**: Icons

## 📖 Cách sử dụng

### Sử dụng trực tiếp trên GitHub Pages

🌐 **Truy cập website**: https://truongxoantit.github.io/checksizeEmbroiderGOD/

1. Mở website trên trình duyệt
2. Chọn công cụ cần dùng từ sidebar hoặc dashboard
3. Công cụ sẽ mở trong modal overlay
4. Sử dụng các tính năng và đóng modal khi xong

### Sử dụng local

1. Clone repository về máy
2. Mở file `index.html` trong trình duyệt
3. Hoặc sử dụng local server (ví dụ: `python -m http.server`)

## 🌐 GitHub Pages Setup

Website đã được cấu hình sẵn cho GitHub Pages:

1. Repository đã có file `index.html` và `.nojekyll`
2. Vào **Settings** → **Pages** trong repository
3. Chọn branch **master** và folder **/ (root)**
4. Save và đợi vài phút để GitHub Pages deploy
5. Website sẽ có tại: `https://[username].github.io/checksizeEmbroiderGOD/`

## 📝 Lưu ý

- File `index.html` là file chính cho GitHub Pages
- File `workspace.html` là file backup
- Tất cả dữ liệu được lưu trữ local trong browser (localStorage)
- Website hoạt động hoàn toàn offline sau lần tải đầu tiên

## 📄 License

Free to use for personal and commercial projects.

## 🙏 Support

Nếu thấy hữu ích, bạn có thể ủng hộ tác giả qua QR Code trong phần Donate.

