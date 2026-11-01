# Càn Khôn Bát Quái 3D

Một screensaver/la bàn phong thủy 3D chạy hoàn toàn trong trình duyệt. Dự án mô phỏng các vòng Luopan phát sáng, hạt vũ trụ, đồng hồ thời gian thực và bảng điều khiển tương tác.

## Chạy dự án

Mở `index.html` bằng trình duyệt, hoặc dùng một static server tại thư mục gốc:

```powershell
python -m http.server 4173
```

Sau đó truy cập `http://127.0.0.1:4173`.

## Tính năng

- Hai hệ đồ hình: Hỗn Độn Ngũ Hành và Càn Khôn Bát Quái.
- Chuyển cảnh mở đầu, xoay 3D, thu phóng và hiệu ứng hạt.
- Sáu bảng màu, ảnh nền tùy chọn và chế độ toàn màn hình.
- Điều khiển bằng chuột, HUD và phím tắt (`R`, `T`, `M`, `C`, `F`, `Space`, `H`).

## Công nghệ

- HTML/CSS/JavaScript thuần
- Three.js (được đóng gói cục bộ)
- Canvas 2D cho ký tự, hoa văn và hiệu ứng nền

## Cấu trúc

- `index.html` — giao diện và điều khiển.
- `app.js` — cảnh Three.js và tương tác.
- `bagua-data.js`, `bagua-textures.js` — dữ liệu và texture La Kinh.
- `particles.js`, `code-background.js` — hiệu ứng nền.
