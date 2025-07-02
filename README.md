## 🛠 Công cụ & Môi trường phát triển

| Công cụ              | Phiên bản đề xuất                          |
|----------------------|--------------------------------------------|
| STM32CubeIDE         | `1.15.0` trở lên                           |
| TouchGFX Designer    | `4.23.0` trở lên                           |
| STM32CubeMX          | Tích hợp trong STM32CubeIDE hoặc riêng     |
| GCC ARM Toolchain    | `10.3-2021.10` hoặc do STM32CubeIDE cung cấp |
| Driver ST-Link       | Phiên bản mới nhất (từ ST hoặc IDE yêu cầu)|
| Hệ điều hành         | Windows 10/11 hoặc Ubuntu 20.04 trở lên     |

---

## 🔌 Yêu cầu phần cứng

- Kit **STM32F429I-DISC1**
- Cảm biến lực (Loadcell 5kg hoặc 10kg)
- Mạch HX711 để đọc tín hiệu loadcell
- Dây kết nối

## 🧩 Cài đặt & Biên dịch

1. **Clone project** về máy:
   ```bash
   git clone https://github.com/Tel1307/HeNhung.git
2. Mở project bằng STM32CubeIDE:
File .ioc sẽ tự động cấu hình chân và đồng bộ mã nguồn.
Nếu dùng TouchGFX, mở thư mục TouchGFX với TouchGFX Designer, sau đó Generate Code.
3. Build & Flash:
Kết nối kit qua cáp USB.
Nhấn Build Project (Ctrl+B) trong STM32CubeIDE.
Chọn Run > Debug để nạp chương trình.
