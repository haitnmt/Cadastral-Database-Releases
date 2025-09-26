# 📱 Cadastral Database MAUI App - Version 1.0.4

## 🚀 Cài Đặt Nhanh (Khuyến Nghị)

### ⚡ Cài đặt tự động với Auto-Update:
```
Nhấp vào link này để cài đặt trực tiếp:
```
**🔗 [CÀI ĐẶT NGAY](https://github.com/haitnmt/Cadastral-Database/releases/latest/download/CadastralDatabaseApp.appinstaller)**

---

## 📋 Hướng Dẫn Cài Đặt Chi Tiết

### 🎯 **Phương Pháp 1: Cài Đặt Tự Động (Khuyến nghị)**
1. **Click vào link**: [CadastralDatabaseApp.appinstaller](https://github.com/haitnmt/Cadastral-Database/releases/latest/download/CadastralDatabaseApp.appinstaller)
2. **Browser sẽ hỏi**: "Mở với App Installer?" → Chọn **"Có"**
3. **Popup cài đặt hiện ra** → Click **"Cài Đặt"**
4. **Chờ cài đặt hoàn tất** → Tìm app trong Start Menu

### 🎯 **Phương Pháp 2: Tải File MSIX**
1. **Download**: [Haihv.CadastralDatabase.Maui.AppBlazor_1.0.4.0_x64.msix](https://github.com/haitnmt/Cadastral-Database/releases/latest/download/Haihv.CadastralDatabase.Maui.AppBlazor_1.0.4.0_x64.msix)
2. **Double-click** file đã tải
3. **Click "Install"** trong popup
4. **Nếu lỗi certificate**: Tải [Certificate](https://github.com/haitnmt/Cadastral-Database/releases/latest/download/Haihv.CadastralDatabase.Maui.AppBlazor_1.0.4.0_x64.cer) và cài đặt trước

---

## ✨ Tính Năng Mới trong Version 1.0.4

- ✅ **Tự động cập nhật**: App sẽ tự kiểm tra và cập nhật phiên bản mới
- ✅ **Giao diện Blazor**: Hiện đại và responsive
- ✅ **Kết nối cơ sở dữ liệu**: Tích hợp với hệ thống cadastral
- ✅ **Tối ưu hiệu suất**: Chạy mượt mà trên Windows 10/11

---

## 🔧 Yêu Cầu Hệ Thống

- **OS**: Windows 10 version 2004 (build 19041) trở lên
- **Architecture**: x64 (64-bit)
- **RAM**: Tối thiểu 4GB
- **Disk**: 200MB trống

---

## 🆘 Hỗ Trợ & Troubleshooting

### ❌ **Lỗi Certificate không tin cậy**
```powershell
# Chạy PowerShell as Administrator
Import-Certificate -FilePath "Haihv.CadastralDatabase.Maui.AppBlazor_1.0.4.0_x64.cer" -CertStoreLocation "Cert:\LocalMachine\TrustedPeople"
```

### ❌ **Lỗi Sideloading không được bật**
1. **Settings** → **Update & Security** → **For developers**
2. Chọn **"Sideload apps"**

### ❌ **App không khởi động**
- Kiểm tra Windows version ≥ build 19041
- Restart máy sau khi cài đặt
- Chạy Windows Update

---

## 🔄 Auto-Update

- **Kiểm tra**: Mỗi 4 giờ hoặc khi khởi động
- **Thông báo**: Popup khi có version mới  
- **Cập nhật**: Tự động download và install
- **Nguồn**: GitHub Releases

---

## 📞 Liên Hệ

- **GitHub**: [haitnmt/Cadastral-Database](https://github.com/haitnmt/Cadastral-Database)
- **Website**: vpdkbacninh.vn
- **Email**: haihv.vn

---

**🎉 Cảm ơn bạn đã sử dụng Cadastral Database MAUI App!**
