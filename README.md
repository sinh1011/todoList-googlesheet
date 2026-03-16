# TodoList with Google Sheet Database

React Core Daily Checklist - phiên bản sử dụng Google Sheet làm database thay vì LocalStorage.

## 🚀 Demo

**Live Demo:** [https://sinh1011.github.io/todoList-googlesheet/](https://sinh1011.github.io/todoList-googlesheet/)

## 📝 Mô tả

Đây là bản cải tiến của [todoList](https://github.com/sinh1011/todoList) với các tính năng:

- ✅ Lưu trữ dữ liệu trên Google Sheet thay vì LocalStorage
- ✅ Đồng bộ dữ liệu giữa nhiều thiết bị
- ✅ Dữ liệu được lưu trữ trên cloud, không mất khi xóa cache
- ✅ Có thể xem và quản lý dữ liệu trực tiếp trên Google Sheet

## 🔧 Công nghệ sử dụng

- HTML/CSS/JavaScript (Vanilla)
- Google Sheets API (via Google Apps Script)
- GitHub Pages (hosting)

## 📦 Cấu trúc

- `index.html` - File chính chứa toàn bộ app
- Google Apps Script - API endpoint để CRUD dữ liệu
- Google Sheet - Database lưu trữ tiến độ học tập

## 🎯 Cách sử dụng

1. Truy cập [Demo](https://sinh1011.github.io/todoList-googlesheet/)
2. Tick các mục đã hoàn thành
3. Dữ liệu tự động lưu vào Google Sheet
4. Truy cập từ bất kỳ thiết bị nào để xem tiến độ

## 📚 So sánh với phiên bản cũ

| Tính năng | LocalStorage | Google Sheet |
|-----------|--------------|-------------|
| Lưu trữ | Trình duyệt | Cloud |
| Đồng bộ | ❌ | ✅ |
| Mất data khi xóa cache | ✅ | ❌ |
| Truy cập từ nhiều thiết bị | ❌ | ✅ |

## 👨‍💻 Tác giả

**Võ Trương Sinh** - [sinh1011](https://github.com/sinh1011)

---

⭐ Nếu thấy hữu ích, hãy cho repo này một ngôi sao nhé!
