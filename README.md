# Hệ thống giám sát môi trường sử dụng STM32F446RE

## 1. Giới thiệu

Dự án xây dựng hệ thống giám sát môi trường sử dụng vi điều khiển STM32F446RE, được phát triển trên STM32CubeIDE.

Dự án tập trung vào lập trình C nhúng, cấu hình ngoại vi và xây dựng chương trình điều khiển vi điều khiển STM32. Hệ thống được phát triển theo hướng thu thập và hiển thị thông tin môi trường thông qua các cảm biến và thiết bị ngoại vi.

## 2. Phần cứng và công cụ phát triển

- **Vi điều khiển:** STM32F446RE
- **Môi trường phát triển:** STM32CubeIDE
- **Ngôn ngữ lập trình:** C
- **Thư viện điều khiển:** STM32 HAL
- **Cấu hình ngoại vi:** STM32CubeMX tích hợp trong STM32CubeIDE
- **Quản lý mã nguồn:** Git và GitHub

## 3. Cấu trúc dự án

```text
Project_GiamSatMoiTruong/
├── Core/
│   ├── Inc/       # Các tệp tiêu đề
│   └── Src/       # Các tệp mã nguồn
├── Drivers/       # Thư viện HAL và CMSIS
├── .settings/     # Cấu hình dự án
├── Project_GiamSatMoiTruong.ioc
├── STM32F446RETX_FLASH.ld
├── STM32F446RETX_RAM.ld
└── README.md
```

## 4. Nội dung thực hiện

- Lập trình C cho vi điều khiển STM32.
- Cấu hình và sử dụng các ngoại vi thông qua STM32 HAL.
- Tổ chức mã nguồn thành các tệp `.c` và `.h`.
- Sử dụng STM32CubeIDE để xây dựng và biên dịch chương trình.
- Quản lý mã nguồn bằng Git và GitHub.

## 5. Hướng dẫn sử dụng

1. Cài đặt STM32CubeIDE.
2. Tải hoặc sao chép repository về máy tính.
3. Mở STM32CubeIDE.
4. Chọn **File → Open Projects from File System**.
5. Chọn thư mục dự án.
6. Biên dịch chương trình và kiểm tra cấu hình phần cứng trước khi nạp lên vi điều khiển.

## 6. Trạng thái dự án

Dự án đang trong quá trình phát triển. Các chức năng thực tế sẽ được cập nhật sau khi hoàn thành kiểm tra và xác nhận hoạt động trên phần cứng.

## 7. Tác giả

**Huỳnh Văn Khoa**

Sinh viên ngành Điện tử – Viễn thông.
