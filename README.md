# HỆ THỐNG ĐẶT HÀNG HABECO – NPP OANH SƠN

Bộ mã nguồn đã được chuẩn bị để triển khai bằng **GitHub Pages**.

## Cấu trúc

- `index.html`: Trang chính của phần mềm. Biểu tượng đã được nhúng trực tiếp trong tệp, không cần tải ảnh riêng.
- `.nojekyll`: Giúp GitHub Pages phục vụ trực tiếp các tệp tĩnh.

## Cách tải lên GitHub

1. Mở repository GitHub cần dùng.
2. Chọn **Add file → Upload files**.
3. Giải nén bộ ZIP này trên máy tính.
4. Kéo `index.html`, `.nojekyll` và `README.md` vào vùng tải lên ở thư mục gốc repository.
5. Chọn **Commit changes** để lưu.

> Nếu repository đang chứa một phần mềm khác, hãy kiểm tra và sao lưu trước khi thay thế `index.html`.

## Bật GitHub Pages

1. Vào **Settings → Pages**.
2. Trong **Build and deployment**, chọn **Deploy from a branch**.
3. Chọn branch `main` và thư mục `/(root)`.
4. Nhấn **Save**.
5. Chờ GitHub hoàn tất triển khai. Đường dẫn website sẽ hiện tại mục **Settings → Pages**.

Nếu repository có tên `gia-pha-nguyen-dinh` thì URL Pages sẽ theo tên repository đó; muốn xuất bản hệ thống đặt hàng độc lập, nên tạo repository riêng, ví dụ `oanh-son-dat-hang`.

## Lưu ý dữ liệu

Phần mềm lưu dữ liệu trên trình duyệt bằng `localStorage`. Dữ liệu được lưu trên từng trình duyệt/thiết bị, không tự đồng bộ giữa máy tính và iPhone. Hãy thường xuyên dùng chức năng sao lưu/khôi phục của phần mềm và giữ file sao lưu JSON ở nơi an toàn. Xóa dữ liệu trình duyệt hoặc đổi trình duyệt có thể làm mất dữ liệu chưa sao lưu.
