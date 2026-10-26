# HỆ THỐNG WEBSITE GAMEZONE

## Hệ thống dùng để quản lý **web game GameZone**, các chức năng bao gồm: *lưu lỗi hệ thống*, *ghi lại lịch sử giao dịch* của người chơi, *quản lý* thư mục website.

## Hệ thống thư mục của web
| Thư mục | Nội dung |
| :---: | :---: |
| backup | Lưu lại dữ liệu backup của website |
| data | Lưu lại lịch sử giao dịch vật phẩm của người chơi |
| logs | Ghi lại nhật ký hệ thống |

## Lệnh liệt kê nội dung dự án
```powershell
Get-ChildItem -Recurse -Force
```

## Tasklist công việc

- [ ] Sắp xếp và chuẩn hóa thư mục dự án
- [X] Hoàn thiện báo cáo tổng hợp đơn hàng tháng 10

> Lưu ý: Tuyệt đối không upload file .env để tránh lộ thông tin nội bộ