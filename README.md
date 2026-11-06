# CPX Encoder

Trang tải CPX Encoder: **https://hoanglanprovip.github.io/cpx/**

CPX Encoder là app Windows để đóng gói mã C++ thành file mã nộp `.cpp`, hỗ trợ đầu ra Linux và Windows, xử lý một file hoặc nhiều file.

## Tải app

[CPX Encoder.exe](docs/downloads/CPX%20Encoder.exe) — Windows 64-bit, 31.215.506 byte.

SHA-256:

```text
10798a8cf24fc9c3f54cf2e87c2dec1b645f25af48e2900ccbafcd4b49bb4328
```

App cần Zig trong `PATH` và MinGW-w64. Với MSYS2, app tìm `g++.exe` tại `C:\msys64\mingw64\bin`, `C:\msys64\ucrt64\bin`, hoặc trong `PATH`.

## GitHub Pages

Site tĩnh nằm trong `docs/`, không có bước build hoặc dependency JavaScript. GitHub Pages dùng nhánh `main`, thư mục `/docs`.

Xem thử tại máy:

```powershell
python -m http.server 8080 --directory docs --bind 127.0.0.1
```

Mở `http://127.0.0.1:8080`.

## Phạm vi bản đăng

Trang web dùng để tải app Windows. Chức năng mã hóa chạy trong app, cần compiler native; GitHub Pages không chạy phần Python/Zig/MinGW này.

Thư mục source được cung cấp hiện chỉ còn các file thực thi. File `.exe` đăng trong repo giữ nguyên từng byte của bản được cung cấp, chưa có bản source GUI hoàn chỉnh hoặc bản encoder chạy trong trình duyệt.
