# Website cá nhân: Trần Quốc Trung (Trungdapchai)

Bộ mã nguồn sẵn sàng **đưa lên GitHub Pages** (miễn phí).

## Hướng dẫn nhanh (GitHub Pages)
1. Đăng nhập GitHub → bấm **New repository**.
2. **Tên repo phải giống hệt username của bạn** theo cú pháp:  
   `trungdapchai.github.io` (thay `trungdapchai` bằng username thật).
3. Chọn **Public** → **Create repository**.
4. Bấm **Upload files** → kéo cả **toàn bộ file này** (index.html, assets/, .nojekyll, README.md) vào.
5. Bấm **Commit changes** để lưu.
6. Vào **Settings → Pages**:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
   → Save.
7. Đợi 1–3 phút rồi mở: `https://trungdapchai.github.io`

> Nếu username của bạn khác, ví dụ `trungdeptrai`, thì link sẽ là `https://trungdeptrai.github.io`.

## Tùy chỉnh
- Đổi email nhận liên hệ trong file `index.html`:
  Tìm biến `mailTarget = 'you@example.com'` và thay bằng email thật.
- Thay ảnh đại diện: đặt ảnh của bạn vào `assets/` và sửa CSS `.avatar` nếu muốn.
- Màu sắc: chỉnh `--primary` và `--accent` ở phần `:root`.

## Ghi chú
- File `.nojekyll` giúp tránh lỗi build khi dùng thư mục và file có dấu `_`.
- Nếu không thấy site hiển thị, đảm bảo **tên repo** đúng và đã bật Pages như hướng dẫn.

© 2025 Trần Quốc Trung (Trungdapchai)
