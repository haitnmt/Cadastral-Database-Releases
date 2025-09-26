# Hướng Dẫn Cài Đặt Ứng Dụng Cadastral Database

## Truy Cập Phiên Bản Cuối

https://github.com/haitnmt/Cadastral-Database-Releases/releases/latest

## Cài Đặt Lần Đầu Tiên

### Bước 1: Tải về file nén
Từ trang releases, tải về file nén:
- `CadastralDatabase-Setup.zip` (chứa đầy đủ file cài đặt)

### Bước 2: Giải nén và chuẩn bị
1. Giải nén file `CadastralDatabase-Setup.zip` vào một thư mục tùy chọn
2. Trong thư mục giải nén sẽ có 3 file:
   - `CaiDat-CadastralApp.bat` (file cài đặt tự động)
   - `Haihv.CadastralDatabase.Maui.AppBlazor_*.msix` (ứng dụng)
   - `Haihv.CadastralDatabase.Maui.AppBlazor_*.cer` (chứng chỉ)

### Bước 3: Chạy file cài đặt
1. Nhấp chuột phải vào file `CaiDat-CadastralApp.bat`
2. Chọn "Chạy với quyền quản trị" hoặc "Run as administrator"
3. Chờ cài đặt hoàn tất
4. Tìm ứng dụng trong menu Start

## Cập Nhật Tự Động (Các Lần Sau)

Sau khi cài đặt lần đầu:
- Ứng dụng sẽ tự động kiểm tra phiên bản mới mỗi 4 giờ
- Khi có phiên bản mới, sẽ có thông báo
- Nhấp "Cập nhật" để tự động cài đặt phiên bản mới
- Không cần quyền quản trị cho các lần cập nhật sau

### Gỡ Lỗi

### Lỗi: "Không tìm thấy file chứng chỉ"
**Nguyên nhân:** File chưa được giải nén đúng cách hoặc thiếu file
**Cách sửa:** 
- Kiểm tra lại file ZIP có tải đúng không
- Giải nén lại và đảm bảo 3 file cùng thư mục

### Lỗi: "File ZIP bị hỏng"
**Cách sửa:** Tải lại file ZIP từ releases và thử giải nén bằng công cụ khác (WinRAR, 7-Zip)

### Lỗi: "Không có quyền quản trị"
**Cách sửa:** Nhấp chuột phải file bat → "Chạy với quyền quản trị"

### Lỗi: "Chứng chỉ không tin cậy"
**Cách sửa:** Tắt phần mềm diệt virus tạm thời khi cài đặt

## Liên Hệ Hỗ Trợ

Nếu gặp vấn đề, vui lòng liên hệ qua [GitHub Issues](https://github.com/haitnmt/Cadastral-Database-Releases/issues) với thông tin lỗi chi tiết.

---

**Lưu ý quan trọng:** 
- Chỉ cần cài đặt thủ công lần đầu tiên. Các phiên bản sau sẽ tự động cập nhật!
- Đảm bảo tải file ZIP từ trang releases chính thức để tránh file bị hỏng
- Sau khi cài đặt xong có thể xóa thư mục giải nén