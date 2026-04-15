# QuanLyCuaHangVanPhongPham - GD10
# Dự án Quản lý Cửa hàng Văn phòng phẩm

Dự án phần mềm quản lý hoạt động kinh doanh cho cửa hàng văn phòng phẩm, được phát triển bằng ngôn ngữ C# và công nghệ Entity Framework.

## 📌 Tổng quan dự án
Dự án cung cấp một giải pháp toàn diện để quản lý kho, nhân sự và quy trình bán hàng một cách hiệu quả và chính xác. Toàn bộ mã nguồn được quản lý phiên bản nghiêm ngặt qua từng giai đoạn trên GitHub.

## ✨ Tính năng chính
- **Dashboard thông minh:** Theo dõi hoạt động kinh doanh với cơ chế nạp dữ liệu không đồng bộ (Asynchronous Loading).
- **Quản lý Bán hàng:** Giao diện bán hàng trực quan, hỗ trợ giỏ hàng và thanh toán nhanh.
- **Quản lý Kho:** Theo dõi nhập kho, danh mục sản phẩm, loại hàng và thương hiệu.
- **Quản lý Đối tác & Nhân sự:** Quản lý chi tiết thông tin Khách hàng, Nhà cung cấp và Nhân viên.
- **Tiện ích mở rộng:** 
    - Xuất/Nhập dữ liệu báo cáo thông qua công cụ **ExcelHelper**.
    - Phân quyền tài khoản bảo mật.
    - Tìm kiếm và lọc dữ liệu thông minh.

## 🛠 Công nghệ sử dụng
- **Ngôn ngữ:** C# (.NET Framework/Core)
- **Công nghệ truy cập dữ liệu:** Entity Framework (Code First & Migrations)
- **Cơ sở dữ liệu:** SQL Server
- **Giao diện:** Windows Forms (UserControl-based UI)
- **Quản lý phiên bản:** Git/GitHub

## 🚀 Hướng dẫn cài đặt
1. Clone dự án về máy: `git clone [URL-Repository]`
2. Mở file `.sln` bằng Visual Studio.
3. Cập nhật chuỗi kết nối (Connection String) trong `App.config` hoặc `DbContext`.
4. Chạy lệnh `Update-Database` trong Package Manager Console để khởi tạo cơ sở dữ liệu.
5. Build và Run dự án.

## 👤 Tác giả
- **Sinh viên thực hiện:** Huỳnh Minh Nhật
- **Mã số sinh viên:** DTH235713
