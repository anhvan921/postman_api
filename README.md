
# 📌 API Testing Report – Reqres API

## 📝 Giới thiệu

- **Tên dự án:** Kiểm thử API bằng Postman  
- **Ngày thực hiện:** 19/06/2025  
- **Người thực hiện:** Nguyễn Thị Cẩm Tú  
- **Mã sinh viên:** 22010230  
- **Môi trường kiểm thử:** Postman  
- **Phương pháp kiểm thử:**  
  - Kiểm thử thủ công  
  - Kiểm thử tự động  

## 🎯 Mục tiêu

- Gửi các request đến API `https://reqres.in/`
- Viết script kiểm thử trong Postman (Test Script)
- Tự động hóa kiểm thử bằng dòng lệnh sử dụng `newman`
- Tạo báo cáo minh họa kết quả kiểm thử (báo cáo HTML/CLI)

---

## 🛠️ Công cụ sử dụng

- [Postman](https://www.postman.com/)
- [Newman – Postman CLI](https://www.npmjs.com/package/newman)
- HTML Extra Reporter (tùy chọn)

---

##  chạy kiểm thử tự động

1. Cài đặt newman:
   ```bash
   npm install -g newman
