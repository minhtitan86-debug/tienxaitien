# 💵 Tiền Xài Tiền (TienXaiTien) - Đổi Ngoại Tệ & USD sang VND (Vietcombank Live)

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Deploy to GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue.svg)](https://pages.github.com/)
[![Vietcombank Live](https://img.shields.io/badge/Vietcombank-100%25%20Auto%20Live-green.svg)]()
[![No Ads](https://img.shields.io/badge/Ads-100%25%20Free%20%26%20No%20Ads-amber.svg)]()

> **Tiền Xài Tiền** là ứng dụng web mã nguồn mở (Single-Page App) giúp quy đổi ngoại tệ: **Đô la Mỹ ($ USD)**, **Euro (€ EUR)**, **Yên Nhật (¥ JPY)**, **Bảng Anh (£ GBP)**, **Won Hàn (₩ KRW)**... sang **Việt Nam Đồng (₫ VND)** và ngược lại theo thời gian thực **tự động 100% từ Ngân hàng Vietcombank**.

---

## ✨ Tính Năng Nổi Bật

### 1. 🏦 Dữ Liệu Tỷ Giá Vietcombank Trực Tiếp (100% Tự Động)
- Kết nối trực tiếp vào cổng tỷ giá XML chính thức của **Vietcombank**: `https://portal.vietcombank.com.vn/Usercontrols/TVWeb.TyGia/pXML.aspx`.
- **Cơ chế Multi-Proxy Fallback:** Tự động xoay vòng qua các proxy tốc độ cao giúp vượt rào cản CORS và hoạt động hoàn toàn ở máy khách (Client-Side).
- **Tự động cập nhật:** Cứ mỗi 5 phút một lần hoặc bấm nút 🔄 để làm mới tức thì.
- Hiển thị chính xác ngày giờ cập nhật tỷ giá của Vietcombank.

### 2. 🔄 Quy Đổi Hai Chiều Linh Hoạt ($ ⇄ ₫)
- **3 Loại Tỷ Giá Thực Tế:**
  - 🏦 **Bán ra (Sell):** Áp dụng khi bạn mua ngoại tệ từ ngân hàng.
  - 💳 **Mua chuyển khoản (Transfer):** Áp dụng khi nhận lương, kiều hối bằng USD/EUR bán cho ngân hàng.
  - 💵 **Mua tiền mặt (Buy Cash):** Áp dụng khi bạn có tiền giấy ngoại tệ bán cho ngân hàng.
- **Nút đảo chiều (Swap button) 1 chạm** mượt mà.
- **Đọc số tiền thành chữ Tiếng Việt chuẩn xác:** Ví dụ: `25,410,000` ➔ *"Hai mươi lăm triệu bốn trăm mười nghìn đồng"*.

### 3. 📊 Bảng Tra Cứu Tỷ Giá Toàn Diện
- Bảng hiển thị đầy đủ ~20 loại tiền tệ của Vietcombank (USD, EUR, GBP, JPY, AUD, SGD, CNY, KRW, THB, CAD, CHF, HKD, INR, MYR, RUB...).
- Thanh tìm kiếm nhanh tên ngoại tệ hoặc mã tiền.
- Chạm vào bất kỳ dòng nào trong bảng để nạp ngay vào bộ quy đổi.

### 4. 🎨 Giao Diện Fintech Đẳng Cấp
- Phong cách **Fintech Dark Mode & Light Mode** với hiệu ứng Glassmorphism.
- Phím bấm chọn nhanh mệnh giá phổ biến ($10, $50, $100, $500, $1000, 1tr, 5tr, 10tr, 50tr, 100tr VND).
- Tối ưu 100% cho màn hình điện thoại di động và máy tính.

---

## 🚀 Hướng Dẫn Tải Lên GitHub & Bật GitHub Pages

### 1. Tải lên GitHub:
Truy cập vào trang tải file của repo:
👉 **[https://github.com/minhtitan86-debug/tienxaitien/upload/main](https://github.com/minhtitan86-debug/tienxaitien/upload/main)**

Kéo & thả file `index.html`, `README.md` vào và bấm **Commit changes**.

### 2. Kích hoạt Web chạy Online (GitHub Pages):
1. Vào **Settings** > **Pages** trên repository `tienxaitien`.
2. Tại mục **Branch**, chọn nhánh `main` và thư mục `/ (root)` > Nhấn **Save**.
3. Sau 1 phút, trang web của bạn sẽ chạy online tại:
   👉 **`https://minhtitan86-debug.github.io/tienxaitien/`**

---

## 📜 Giấy phép (License)
Dự án được phát hành theo giấy phép [MIT License](LICENSE).
