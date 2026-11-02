<div align="center">

# ShuraDB

### Làm việc với MySQL gọn gàng hơn.

[![Latest release](https://img.shields.io/github/v/release/hienl-019/shuradb-releases?display_name=tag&label=latest)](https://github.com/hienl-019/shuradb-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/hienl-019/shuradb-releases/total?label=downloads)](https://github.com/hienl-019/shuradb-releases/releases)

Ứng dụng desktop cho MySQL và MariaDB — kết nối trực tiếp hoặc qua SSH, duyệt dữ liệu, viết SQL và quản lý cấu trúc bảng trong một nơi.

[⬇️ Tải ShuraDB mới nhất](https://github.com/hienl-019/shuradb-releases/releases/latest) · [Xem tất cả phiên bản](https://github.com/hienl-019/shuradb-releases/releases) · [Báo lỗi](https://github.com/hienl-019/shuradb-releases/issues)

**Windows 10/11 · x64**

</div>

---

## Dành cho công việc database hằng ngày

| 🗂️ Duyệt dữ liệu | ⌨️ Viết SQL | 🧱 Thiết kế bảng | 🔐 Kết nối từ xa |
| --- | --- | --- | --- |
| Xem, lọc và chỉnh sửa bản ghi với bảng dữ liệu trực quan. | Trình soạn thảo có tô màu cú pháp và gợi ý theo schema. | Xem trước câu lệnh DDL trước khi áp dụng thay đổi. | Kết nối MySQL/MariaDB trực tiếp hoặc qua SSH tunnel. |

## Tải và cài đặt

1. Chọn **Tải ShuraDB mới nhất** ở đầu trang.
2. Trong mục **Assets**, tải file `ShuraDB-Setup-<phiên-bản>.exe`.
3. Mở file cài đặt. Nếu Windows hiện cảnh báo nhà phát hành chưa xác định, chọn **More info → Run anyway** để tiếp tục.

Không cần cài Node.js hay MySQL trên máy chạy ShuraDB. Bạn cần có quyền truy cập tới một máy chủ MySQL hoặc MariaDB để kết nối dữ liệu.

> Các bản chưa ký số có thể gặp cảnh báo Microsoft Defender SmartScreen. Tải bộ cài từ trang Releases này và kiểm tra SHA-256 trong `SHA256SUMS.txt` nếu cần. Không tắt antivirus để cài đặt.

## Cập nhật ứng dụng

Mở **Cài đặt → Cập nhật ứng dụng** để kiểm tra phiên bản mới. Bản `0.1.2` cần cài thủ công một lần để có chức năng cập nhật; các bản sau có thể tải cập nhật ngay trong ứng dụng.

Trước khi cài cập nhật, hãy lưu thay đổi đang làm và kết thúc transaction đang mở. ShuraDB sẽ không bắt đầu cài khi còn tác vụ database đang chạy.

## Kiểm tra bộ cài

Mỗi release có `SHA256SUMS.txt`. Trong PowerShell, tính mã băm của file đã tải:

```powershell
Get-FileHash .\ShuraDB-Setup-<version>.exe -Algorithm SHA256
```

Đối chiếu giá trị `Hash` với dòng tương ứng trong `SHA256SUMS.txt` của cùng release.

---

<div align="center">

Repo này chỉ phân phối bộ cài và thông tin phát hành. Mã nguồn được quản lý riêng.

</div>
