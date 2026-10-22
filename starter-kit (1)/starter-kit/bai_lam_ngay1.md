# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** lê quang hào 
- **Lớp:** CNTT1
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
ls -Force
mv "lich_hoc.txt" docs
mv "logo_trung_tam.png" media
mv "anh_lop_hoc.jpg" media
cp "media\logo_trung_tam.png" archive
rm "temp_201.tmp"
rm "temp_202.tmp"
cd logs
ls
cd ..
cd docs
cp "../media/anh_lop_hoc.JPG" "../archive"
cd ..
gci -Recurse -Force
```

### Kết quả B1 (pwd)

```text
Path
----
D:\Github\CNTT1_Nhap-mon-CNTT_OnTap-Ngay1\starter-kit\trung-tam-tieng-anh


```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> Copy-Item ".\media\logo_trung_tam.PNG" ".\archive\"
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> Remove-Item ".\temp_201.tmp"
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> Remove-Item ".\temp_202.tmp"
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> cd .\logs
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\logs> ls


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM           1072 access.log


PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\logs> cd ..
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> cd .\docs
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\docs> Copy-Item "..\media\anh_lop_hoc.JPG" "..\archive\"
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\docs> cd ..
PS C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh> Get-ChildItem -Recurse -Force


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026  10:30 PM                archive
d-----        10/20/2026  10:27 PM                data
d-----        10/20/2026  10:26 PM                docs
d-----        10/20/2026  10:27 PM                logs
d-----        10/20/2026  10:27 PM                media
-a----        10/20/2026  10:19 PM             83 .env


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026  10:19 PM           5184 logo_trung_tam.PNG


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM             67 lich_hoc.txt


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM           1072 access.log


    Directory: C:\Users\lequanghao\Downloads\starter-kit (1)\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:19 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026  10:19 PM           5184 logo_trung_tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
