# 🌐 Mạng Thế Hệ Mới (NGN)

## Bài giảng Chương 1: Tổng quan về mạng thế hệ mới

> **Tài liệu học tập môn Mạng Viễn thông - Dành cho sinh viên ngành Điện tử - Viễn thông, Công nghệ Thông tin**

[![PowerPoint](https://img.shields.io/badge/Tài%20liệu-PowerPoint-red.svg)](./Bài%20giảng%20chương%201.pptx)
[![Language](https://img.shields.io/badge/Ngôn%20ngữ-Tiếng%20Việt-green.svg)]()
[![Topic](https://img.shields.io/badge/Chủ%20đề-NGN-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

---

## 📡 Giới thiệu

Chào mừng bạn đến với bài giảng **Chương 1: Tổng quan về mạng thế hệ mới (NGN - Next Generation Network)**!

Trong bối cảnh công nghệ viễn thông đang phát triển với tốc độ chóng mặt, mạng NGN được xem là **cuộc cách mạng** trong lĩnh vực viễn thông, đánh dấu sự chuyển đổi từ mạng chuyển mạch kênh truyền thống sang **mạng chuyển mạch gói hội tụ**.

Bài giảng này cung cấp cái nhìn tổng quan về:
- 📞 **Các thành phần của mạng viễn thông**
- 🏗️ **Phân cấp mạng viễn thông**
- 🔍 **Đặc điểm và hạn chế của mạng viễn thông hiện nay**
- 🚀 **Khái niệm, đặc điểm và lý do xuất hiện của NGN**

---

## 📚 Nội dung bài giảng

### 1. Mạng Viễn Thông

| Nội dung | Mô tả |
|----------|-------|
| **Định nghĩa** | Phương tiện truyền thông tin từ đầu phát đến đầu thu, cung cấp dịch vụ cho khách hàng |
| **Cấu trúc** | Hệ thống các nút chuyển mạch (tổng đài) được nối với nhau bằng đường truyền dẫn |
| **Phân cấp** | Nút được phân thành nhiều cấp, kết hợp với đường truyền tạo thành các cấp mạng khác nhau |

### 2. Các Thành Phần Chính

| Thành phần | Ví dụ |
|------------|-------|
| **Thiết bị chuyển mạch** | Tổng đài nội hạt, Tổng đài quá giang |
| **Thiết bị truyền dẫn** | Cáp kim loại, Cáp quang, Vô tuyến, Không dây |
| **Môi trường truyền** | Hữu tuyến (cáp), Vô tuyến (vi ba, vệ tinh) |

> 💡 **Ưu điểm của mạng viễn thông:** Dùng chung đường truyền, tiết kiệm kinh tế

### 3. Phân Cấp Mạng Viễn Thông

```
📊 Cấp 1: Mạng đường trục quốc tế
    ├── Cấp 2: Mạng đường trục quốc gia
    │   ├── Cấp 3: Mạng quá giang
    │   │   ├── Cấp 4: Mạng nội hạt
    │   │   │   └── Cấp 5: Thuê bao
```

### 4. Đặc Điểm Mạng Viễn Thông Hiện Nay

| Loại mạng | Đặc điểm |
|-----------|----------|
| **Telex** | Gửi bức điện dạng ký tự mã hóa 5 bit (mã Baudot) |
| **POTS/PSTN** | Thoại số hóa, chuyển mạch kênh, tập trung, phần cứng/phần mềm độc quyền |
| **Mạng số liệu** | X.25 (chuyển mạch gói), X.21 (chuyển mạch kênh) |
| **Truyền hình** | Analog, số, vệ tinh |
| **LAN** | Mạng cục bộ |
| **ISDN** | Mạng số tích hợp dịch vụ, cung cấp nhiều ứng dụng thoại và phi thoại |
| **PSDN** | Mạng chuyển mạch số liệu công cộng, chủ yếu cung cấp dịch vụ số liệu |
| **GSM** | Mạng thoại qua kênh truyền vô tuyến (BSC, BTS, HLR, VLR, MS) |

### 5. So Sánh Các Loại Mạng

| Đặc tính | PSTN | ISDN | PSDN |
|----------|------|------|------|
| **Công nghệ** | Chuyển mạch kênh | Kỹ thuật số | Chuyển mạch gói |
| **Băng thông** | Gán trước | Đa dạng | Thu nhận/giải phóng khi cần |
| **Đường dẫn** | Dành riêng | Linh hoạt | Không tồn tại đường dẫn riêng |
| **Chi phí** | Khoảng cách + thời lượng | Đa dạng | Dựa trên sử dụng dữ liệu |
| **Dịch vụ** | Thoại | Thoại + Dữ liệu + Video | Dữ liệu |

### 6. Hạn Chế Của Mạng Viễn Thông Hiện Nay

- 🔒 **Độc quyền**: Phụ thuộc nhà cung cấp, giảm sức cạnh tranh
- 📉 **Lạc hậu**: Tổng đài chuyển mạch kênh đã sử dụng hết năng suất
- 🧩 **Phân mảnh**: Chỉ truyền các dịch vụ độc lập ứng với từng mạng riêng lẻ
- ❌ **Thiếu mềm dẻo**: Không đáp ứng nhu cầu đa dạng
- 💰 **Kém hiệu quả**: Trong bảo dưỡng, vận hành và sử dụng tài nguyên

---

## 🚀 Mạng Thế Hệ Mới (NGN)

### Định nghĩa

> *"Mạng thế hệ mới (NGN) là mạng có cơ sở hạ tầng thông tin duy nhất dựa trên công nghệ **chuyển mạch gói**, triển khai các dịch vụ một cách **đa dạng và nhanh chóng**, đáp ứng sự hội tụ giữa thoại và số liệu, giữa di động và cố định."*

### Đặc Điểm Nổi Bật

| Đặc điểm | Ý nghĩa |
|----------|---------|
| 🏗️ **Nền tảng mở** | Hệ thống mạng linh hoạt, không bị ràng buộc |
| 📦 **Chuyển mạch gói** | Dựa trên giao thức thống nhất (IP) |
| 🔀 **Tách biệt dịch vụ - mạng lưới** | Dịch vụ thực hiện độc lập với hạ tầng |
| 📈 **Dung lượng tăng** | Thích ứng và đủ dung lượng đáp ứng nhu cầu |
| ⚡ **Triển khai nhanh** | Dịch vụ mới được đưa ra nhanh chóng |

### Lý Do Xuất Hiện NGN

1. 💰 **Cải thiện chi phí đầu tư**: Dữ liệu xuất hiện ngày càng nhiều trên mạng PSTN trong khi chuyển mạch kênh đáp ứng không tốt
2. 🌍 **Xu thế đổi mới viễn thông**: Cuộc cách mạng công nghệ đang diễn ra
3. 💵 **Các nguồn doanh thu mới**: Tạo ra các dịch vụ giá trị gia tăng

---

## 🎯 Lợi ích của NGN

| Lợi ích | Mô tả |
|---------|-------|
| **Hội tụ** | Một mạng duy nhất cho tất cả dịch vụ (thoại, video, dữ liệu) |
| **Tiết kiệm** | Giảm chi phí vận hành và bảo trì |
| **Linh hoạt** | Dễ dàng triển khai dịch vụ mới |
| **Mở** | Tạo môi trường cạnh tranh lành mạnh |
| **Đa dạng** | Phục vụ nhiều loại hình dịch vụ khác nhau |

---

## 📊 So Sánh Mạng Truyền Thống và NGN

| Tiêu chí | Mạng truyền thống | NGN |
|----------|-------------------|-----|
| **Công nghệ chuyển mạch** | Kênh | Gói (IP) |
| **Cấu trúc** | Đóng, độc quyền | Mở, chuẩn hóa |
| **Dịch vụ** | Mỗi mạng một dịch vụ | Hội tụ, đa dịch vụ |
| **Triển khai dịch vụ mới** | Chậm, phức tạp | Nhanh, dễ dàng |
| **Chi phí** | Cao | Thấp hơn |
| **Khả năng mở rộng** | Hạn chế | Cao |

---

## 🧠 Tóm Tắt Chương

**Nội dung chính:**
1. ✅ Mạng viễn thông là nền tảng cho mọi dịch vụ truyền thông
2. ✅ Mạng hiện tại tồn tại nhiều hạn chế: phân mảnh, độc quyền, thiếu mềm dẻo
3. ✅ NGN là xu hướng tất yếu, giải quyết các hạn chế của mạng hiện tại
4. ✅ NGN dựa trên nền tảng chuyển mạch gói, hội tụ dịch vụ, mở và linh hoạt

---

## 📖 Tài liệu tham khảo

| Tài liệu | Mô tả |
|----------|-------|
| **Sách giáo trình** | Mạng viễn thông và NGN |
| **ITU-T** | Khuyến nghị về NGN |
| **Tài liệu bổ sung** | Mạng PSTN, ISDN, PSDN, GSM |

---

## 🔄 Ứng dụng thực tế

NGN đang được ứng dụng trong:

| Lĩnh vực | Ứng dụng |
|----------|----------|
| **Viễn thông** | VoIP, Video Call, Hội nghị truyền hình |
| **Mạng di động** | 4G/5G, VoLTE, RCS |
| **Internet** | Mạng lõi IP, CDN, Cloud |
| **Doanh nghiệp** | IP PBX, UCaaS, Contact Center |
| **Truyền thông** | IPTV, OTT, Streaming |

---

## 🎓 Đối tượng phù hợp

| Đối tượng | Lợi ích |
|-----------|---------|
| **Sinh viên ngành Viễn thông** | Nắm vững nền tảng về NGN |
| **Sinh viên ngành CNTT** | Hiểu về hạ tầng mạng viễn thông |
| **Kỹ sư mạng** | Cập nhật xu hướng công nghệ |
| **Chuyên viên quy hoạch** | Hiểu về kiến trúc mạng thế hệ mới |

---

## 🌟 Đừng quên ⭐ Star và Share để ủng hộ nhé!

---

**Made with ❤️ for students of Telecommunications Networks**
