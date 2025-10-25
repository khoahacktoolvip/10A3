# Website nhập liệu điểm (Admin + Người xem)

Hướng dẫn nhanh:
- Mở `index.html` để xem bảng điểm (chỉ xem).
- Mở `admin.html` để quản lý (mật khẩu: `admin123`).
- Dữ liệu gốc có sẵn trong `data.js` (45 học sinh). Khi admin lưu, dữ liệu được lưu vào `localStorage` của trình duyệt — trang `index.html` sẽ ưu tiên đọc từ `localStorage` (nên khi chạy cục bộ, cả 2 trang cùng trình duyệt sẽ thấy thay đổi).

Các file:
- index.html
- admin.html
- style.css
- data.js

Gợi ý: Mở bằng Live Server (VSCode) để trải nghiệm tốt nhất. Nếu muốn triển khai trên server, thay thế data.js bằng file xuất từ admin (data-export.js).
