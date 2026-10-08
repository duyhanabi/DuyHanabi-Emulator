# DuyHanabi Emulator 1.0.0

[English version](README.en.md)

**DuyHanabi Emulator** đưa game Java ME (J2ME/MIDP) lên máy tính Windows. Chọn tệp JAR hoặc JAD để chạy trong môi trường giả lập Java ME tích hợp.

## Tính năng

- Bản Windows x64 dạng một tệp EXE độc lập, đã kèm ứng dụng và Java runtime; không cần cài Java riêng.
- Giao diện mặc định tiếng Việt; có thể chuyển sang tiếng Anh.
- Mặc định dùng **Resizable device**; có thể chọn hồ sơ thiết bị khác và thay đổi kích thước màn hình.
- Phóng to màn hình bằng nội suy điểm ảnh gần nhất để giữ nét pixel; có thể ghi màn hình thành GIF.
- Hiện FPS, CPU và RAM; bảng log, thông tin luồng và quản lý dữ liệu RecordStore.
- Auto click theo tọa độ, ghi/phát macro bàn phím và chuột, tự ngủ khi ẩn cửa sổ.
- Mở tối đa 50 phiên giả lập, sắp xếp phiên theo hàng ngang/dọc/tự động, chọn tab chủ và đồng bộ thao tác.
- Quản lý JAR đã nhập, xóa dữ liệu của game hoặc xóa toàn bộ dữ liệu do trình giả lập quản lý.

## Tải và chạy

Tải **DuyHanabi Emulator.exe** trong mục **Releases**, sau đó chạy trực tiếp trên Windows 64-bit. Lần mở đầu tiên có thể lâu hơn vì EXE cần bung ứng dụng và runtime vào bộ nhớ đệm; những lần sau dùng lại bản đã bung.

Thiết lập và dữ liệu game được lưu trong `%USERPROFILE%\.duyhanabiemulator`. Nếu máy có dữ liệu cũ tại `%USERPROFILE%\.microemulator`, ứng dụng sẽ chép dữ liệu đó sang thư mục mới ở lần chạy đầu.

## Lưu ý

- Mức tương thích phụ thuộc API mà từng game sử dụng.
- Tốc độ khung hình do game quyết định; trình giả lập không ép mọi game chạy ở FPS cố định.
- Tối ưu RAM là yêu cầu Java thu gom rác, không thể giải phóng đối tượng mà game còn đang sử dụng.
- Bộ cài có chứa thành phần của MicroEmulator và Java runtime; xem thông tin giấy phép/ghi công đi kèm bản phát hành.

Trang GitHub này dành cho giới thiệu và tải bản phát hành; không đính kèm mã nguồn dự án.
