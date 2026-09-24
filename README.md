# Bé Học Đọc Tiếng Anh

Ứng dụng học chữ cái, từ vựng (theo chương trình lớp 1-2) và đọc tiếng Anh cho bé.
Đây là một Web App (PWA) — có thể cài icon ra màn hình điện thoại như app thật.

## 1. Đưa lên GitHub Pages

1. Tạo một repository mới trên GitHub (ví dụ: `hoc-doc-tieng-anh`).
2. Tải lên **toàn bộ nội dung của thư mục này** (index.html, manifest.json,
   service-worker.js, thư mục icons/) vào repo — giữ nguyên cấu trúc thư mục,
   không để trong thư mục con.
3. Vào **Settings → Pages** của repo.
4. Ở mục "Build and deployment", chọn **Source: Deploy from a branch**,
   **Branch: main**, thư mục **/ (root)** → bấm **Save**.
5. Đợi khoảng 1-2 phút, GitHub sẽ cung cấp một đường link dạng:
   `https://<tên-tài-khoản>.github.io/<tên-repo>/`
6. Mở link đó bằng trình duyệt trên điện thoại.

## 2. Cài icon ra màn hình điện thoại

**Trên iPhone (Safari):**
1. Mở link ở trên bằng Safari.
2. Bấm nút Chia sẻ (hình vuông có mũi tên) ở thanh dưới.
3. Chọn **"Thêm vào MH chính" (Add to Home Screen)**.
4. Bấm **Thêm** — icon chú gà con sẽ xuất hiện ngoài màn hình chính.

**Trên Android (Chrome):**
1. Mở link ở trên bằng Chrome.
2. Bấm menu 3 chấm ở góc trên phải.
3. Chọn **"Cài đặt ứng dụng" / "Thêm vào Màn hình chính"**.
4. Xác nhận — icon sẽ xuất hiện như một ứng dụng bình thường.

Sau khi cài, mở app từ icon sẽ không còn thanh địa chỉ trình duyệt, dùng gần
như một ứng dụng thật. App cũng lưu tạm nội dung để dùng được cả khi không có mạng.

## Cấu trúc file
```
index.html          → toàn bộ ứng dụng
manifest.json        → cấu hình tên, icon, màu sắc của app
service-worker.js    → giúp app chạy được khi mất mạng
icons/icon-192.png   → icon nhỏ
icons/icon-512.png   → icon lớn
icons/apple-touch-icon.png → icon riêng cho iPhone
```
