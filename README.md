# bai6.6
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.6: HỆ THỐNG QUẢN LÝ MƯỢN TRẢ SÁCH THƯ VIỆN (LIBRARY MANAGEMENT SYSTEM)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:
<img width="1136" height="773" alt="GD" src="https://github.com/user-attachments/assets/7954089e-1c03-4266-a450-2187785ce97a" />


2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="1137" height="772" alt="CN1" src="https://github.com/user-attachments/assets/5cbbe79e-dbcb-4900-bc21-528980d4e81f" />

3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="1137" height="773" alt="CN2" src="https://github.com/user-attachments/assets/ff54a9ae-9027-44e9-8f91-da180fb21296" />
<img width="1138" height="768" alt="CN4" src="https://github.com/user-attachments/assets/bd684138-d14f-40cb-915f-0d7a76f4c964" />
<img width="1133" height="776" alt="CN3" src="https://github.com/user-attachments/assets/a2ce7092-4c51-4129-9d81-8b93f1fc38cd" />

4. Màn hình Báo cáo - Thống kê:
<img width="1137" height="774" alt="KQ" src="https://github.com/user-attachments/assets/5d94b89e-0f00-423d-afa9-0d6b21c8b51d" />

5. Minh họa An toàn Dữ liệu (Phòng chống SQL Injection / Báo lỗi Transaction Rollback):
<img width="1132" height="776" alt="LOI" src="https://github.com/user-attachments/assets/62b39427-6eec-4de9-852c-0d0e03675c10" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
