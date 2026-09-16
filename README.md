# Nhom Nhom With Cá Mèo 🐱

Website random món ăn Sài Gòn, dùng dữ liệu từ sheet `HCM` trong file Food tour SG.xlsx.

## Có sẵn
- Bộ lọc: Lẩu, Nướng, Ăn Vặt, Cơm Tấm, Món Nước.
- Tìm kiếm theo tên quán / món / địa chỉ.
- Lọc theo quận.
- Vòng quay random theo bộ lọc hoặc toàn bộ danh sách, quay thật 4-6 vòng rồi giảm dần.
- Hiệu ứng confetti + bubble mèo biết nói khi có kết quả.
- Nút "Quay lại nè" ngay trong khung kết quả.
- Báo lỗi bằng toast (không dùng alert).
- Kết quả hiển thị: quán, món, địa chỉ, giờ mở cửa, khoảng giá, note.
- Nút mở Google Maps.
- Giao diện chibi dễ thương, responsive cho điện thoại (tối ưu cảm ứng, không tràn ngang).
- Font Baloo 2 + Be Vietnam Pro hỗ trợ tiếng Việt (lần đầu mở cần internet để tải font).
- Không cần backend, chạy trực tiếp bằng HTML/CSS/JS.

## Chạy bằng VS Code

Cách nhanh nhất:
1. Mở thư mục này bằng VS Code.
2. Cài extension **Live Server**.
3. Chuột phải `index.html` → **Open with Live Server**.

Hoặc có thể mở `index.html` trực tiếp trên trình duyệt.

## Đưa lên GitHub Pages

1. Tạo một repository mới trên GitHub.
2. Upload `index.html` và `style.css`.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**.
5. Chọn branch `main` và folder `/root`.
6. Save, sau đó GitHub sẽ cấp link website.

## Cập nhật khi sửa web

1. Vào repo trên GitHub → nút **Add file** → **Upload files**.
2. Kéo thả `index.html` + `style.css` (trùng tên file cũ) → GitHub tự thay thế.
3. Ghi chú commit (vd: "cập nhật giao diện mới") → **Commit changes**.
4. Chờ 1-2 phút, GitHub Pages tự cập nhật lại trang.

## Dữ liệu
Đã lọc từ sheet `HCM`: 284 dòng có ít nhất một trong 5 tag yêu cầu.
