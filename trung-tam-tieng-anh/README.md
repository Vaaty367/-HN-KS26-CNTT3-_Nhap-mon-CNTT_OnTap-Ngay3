# Dự án Website Trung tâm Tiếng Anh

## Giới thiệu
Hệ thống quản lý nội bộ trung tâm, ghi log truy cập và xử lý học phí. **Lưu ý:** Dữ liệu bảo mật được lưu trữ *biệt lập* để đảm bảo an toàn.

## Cấu trúc thư mục

| Thư mục | Nội dung |
| :--- | :--- |
| `data/` | File Excel quản lý học viên và học phí |
| `docs/` | Tài liệu hướng dẫn và lịch học |
| `logs/` | Nhật ký truy cập và giao dịch |
| `archive/`| Lưu trữ dữ liệu, sao lưu định kỳ và hồ sơ các khóa đào tạo |
## Quy trình đăng ký
1. Học viên chọn mã khóa học.
2. Hệ thống kiểm tra học phí và số tháng.
3. Kế toán duyệt và xếp lớp.

## Lệnh kiểm tra dự án
```powershell
Get-ChildItem -Force
```

## Việc cần làm
- [x] Tổ chức cây thư mục
- [ ] Thiết lập bộ lọc lỗi

> Không upload file `.env` lên GitHub/GitLab.