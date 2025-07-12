# Banking SQL Sample Project

## 📘 Mô tả
Dự án thiết lập một database mẫu từ dữ liệu marketing ngân hàng trên Kaggle. Bao gồm:
- Tạo database `bank_marketing`
- Tạo bảng `bank_data`
- Chèn 4521 dòng dữ liệu thực tế

## 🗃️ Cấu trúc thư mục
- `data/bank.csv`: Dữ liệu nguồn gốc (Kaggle)
- `scripts/import_full_data.sql`: Script tạo database, table, insert dữ liệu
- `README.md`: Tài liệu hướng dẫn

## ▶️ Hướng dẫn chạy lại
1. Mở SQL Server Management Studio (SSMS)
2. Mở file `scripts/import_full_data.sql`
3. Nhấn **F5** để thực thi
4. Kiểm tra dữ liệu:
   ```sql
   SELECT COUNT(*) FROM bank_data;
   SELECT TOP 10 * FROM bank_data;
