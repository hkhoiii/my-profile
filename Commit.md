# Nhật ký học Frontend

Lộ trình: React + TypeScript, mục tiêu Fresher/Junior.
Trang tuần 1: https://hkhoiii.github.io/my-profile/

---

## 16/11/2026 – Tuần 1, ngày 1 (làm xong nội dung ngày 2)
- **Đã học:** cài VS Code, Prettier, Live Server; tạo repo `my-profile`, viết `.gitignore`, commit đầu tiên, push lên GitHub, bật GitHub Pages, dựng khung trang bằng thẻ ngữ nghĩa `header`, `nav`, `main`, `section`, `footer`; menu là một `ul` chứa các link `#id`.
- **Hiểu ra:** `.gitignore` chỉ có tác dụng với file chưa được tracked; Git là công cụ trong máy, còn GitHub là nơi lưu repo trên mạng.; mỗi trang chỉ có 1 `h1` và 1 `main`; mỗi `section` nên có `h2`; `id` phải là duy nhất.
- **Còn vướng (đã giải quyết):** không biết đưa code mới lên Git thế nào. Hoá ra chỉ cần sửa tiếp `index.html`, rồi chạy `git add .`, `git commit`, `git push`; không cần `git init` hay `remote add` lại.

## 17/11/2026 – Tuần 1, ngày 2 (hoàn thành toàn bộ sản phẩm tuần 1)
- **Đã làm:** xong cả 4 phần: Giới thiệu (`img`, `p`, `strong`), Kỹ năng (`ul`, `ol`, `h3`), Dự án (`article`, link `target="_blank"`), Liên hệ (`form`, `label`, `input`, `select`, `textarea`, checkbox, `button`).
- **Hiểu ra:** tên file ảnh trong `src` phải khớp chính xác với file thật (đã sửa ở commit `fix: correct image file names`). `label for` phải trùng `id` của input. `type="email"` và `required` tự kiểm tra dữ liệu mà không cần code.
- **Hiểu ra:** bấm Gửi thì dữ liệu hiện lên thanh địa chỉ (`?email=...&topic=...`). Mỗi `name` trở thành một khoá trong URL. Form không gửi đi đâu vì GitHub Pages là trang tĩnh, không có server nhận.
- **Còn vướng:** (tự điền)
- **Tiếp theo:** dùng các ngày còn lại của tuần 1 để rà soát, sửa lỗi và đọc MDN thay vì học sang phần mới.