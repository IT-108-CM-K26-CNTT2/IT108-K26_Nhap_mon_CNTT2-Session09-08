# Bài 8: Hoàn Thiện file README Dự Án Của Nhóm
## Phần 1. Điền khuyết

| Chỗ trống | Điền | Lý do |
| :--- | :---: | :--- |
| `____ 📅 Ứng dụng...` | `#` | Một `#` kèm dấu cách tạo H1 |
| `____bash` (mở khối code) | ```` ``` ```` | Mở Code Block kèm tên ngôn ngữ |
| `____` (đóng khối code) | ```` ``` ```` | Đóng Code Block |
| `____ [x]` / `____ [ ]` | `-` | Task List: `- [x]` xong, `- [ ]` chưa xong |
| Hàng phân cách (3 cột) | `:---` , `:---` , `:---:` | Căn trái cột chữ, căn giữa cột phiên bản |

## Phần 2. README.md hoàn chỉnh

````markdown
# 📅 Ứng dụng Quản lý Lịch Học Cá nhân

Ứng dụng giúp sinh viên **lên kế hoạch học tập** hiệu quả.

## 🚀 Hướng dẫn Cài đặt

```bash
git clone https://github.com/nhom5/lich-hoc-app
cd lich-hoc-app
```

## ✅ Tính năng đã hoàn thành

- [x] Đăng ký / Đăng nhập tài khoản
- [ ] Nhắc nhở lịch học qua email
- [x] Xuất lịch ra file PDF

## 📊 Bảng So sánh Công nghệ

| Công nghệ | Mục đích | Phiên bản |
| :--- | :--- | :---: |
| Python | Backend xử lý dữ liệu | 3.11 |
| Markdown | Viết tài liệu README | - |
````

## Bẫy dữ liệu

Xóa hàng phân cách `| --- | --- | --- |` thì bảng chỉ còn là văn bản thường có dấu `|`, vì parser dựa vào hàng này để nhận ra bảng.
