# Thiết kế Vi mạch Tương tự (Analog IC Design - EE3207) 📚🔬

Repository này chứa các báo cáo thí nghiệm môn **Thiết kế Vi mạch Tương tự (EE3207)**, học kỳ 252 tại Trường Đại học Bách Khoa - ĐHQG TP.HCM (HCMUT).

## 👥 Thông tin nhóm thực hiện
- **Lớp:** L01
- **Nhóm:** 16

| STT | Họ và tên | MSSV | Vai trò / Đóng góp |
| :---: | :--- | :---: | :---: |
| 1 | **Nguyễn Thanh Phong** | 2312626 | 100% |
| 2 | Cao Thị Thanh Huyền | 2311272 | 100% |
| 3 | Nguyễn Hoàng Tuấn | 2313746 | 100% |
| 4 | Trương Đại Phong | 2312635 | 100% |
| 5 | Trương Đào Đan Huy | 2311258 | 100% |

**Giảng viên & Trợ giảng hướng dẫn:**
- ThS. Phan Võ Kim Anh
- ThS. Nguyễn Thanh Trung
- ThS. Đỗ Huy Khang

## 📂 Nội dung Repository

Repository bao gồm 2 báo cáo tổng hợp cho 5 bài thí nghiệm thực hành thiết kế và mô phỏng trên nền tảng Cadence:

### 1. [Báo cáo Lab 1, 2 & 3](./EE3207_L01_N16_report_lab_1_3.pdf)
* **Lab 1: CMOS Inverter Analysis** - Phân tích đặc tuyến tĩnh và động của bộ đảo CMOS, khảo sát ảnh hưởng của kích thước transistor (W/L) đến độ trễ (delay) và công suất tiêu thụ.
* **Lab 2: MOS Device Characterization** - Đặc tả linh kiện MOSFET, trích xuất các thông số mô hình cơ bản và khảo sát hoạt động trong các vùng khác nhau.
* **Lab 3: High-Speed Latch and Flip-Flop Design** - Thiết kế và mô phỏng các cấu trúc Latch và D-Flip Flop tốc độ cao, phân tích timing margin, setup/hold time, và tối ưu logic tổ hợp cùng tải fanout.

### 2. [Báo cáo Lab 4 & 5](./EE3207_L01_N16_report_lab_4_5.pdf)
* **Lab 4: Common Source Single Stage Amplifier** - Thiết kế mạch khuếch đại nguồn chung (CS), phân tích DC bias, độ lợi tín hiệu nhỏ (AC gain) và băng thông.
* **Lab 5: Two-Stage Op-amp Design** - Thiết kế bộ khuếch đại thuật toán (Op-amp) hai tầng. Thực hiện STB analysis để đánh giá độ ổn định, sử dụng tụ bù Miller nhằm đạt được DC gain, tần số cắt ($f_{UGB}$) và phase margin thỏa mãn yêu cầu. Qua đó làm rõ sự đánh đổi (trade-off) cơ bản giữa băng thông và độ ổn định trong thiết kế mạch khuếch đại tương tự.

## 🛠 Công cụ & Kỹ thuật sử dụng
- **Cadence Virtuoso**: Thiết kế schematic mức transistor.
- **ADE Explorer / Assembler**: Thiết lập môi trường và kịch bản mô phỏng (DC, AC, Transient, STB).
- **Phân tích nâng cao**: Đánh giá timing margin, khảo sát và kiểm chứng độ tin cậy của thiết kế dưới các góc PVT (Process, Voltage, Temperature).

## 📌 Khuyến cáo
Các tài liệu trong repository này phục vụ mục đích lưu trữ tiến độ dự án học thuật và tham khảo.
