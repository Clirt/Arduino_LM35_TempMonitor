# Arduino LM35 Temperature Monitor
Dự án thực hành môn Mạng Cảm Biến - Tuần 03.

## 1. Giới thiệu
Hệ thống đọc dữ liệu nhiệt độ từ cảm biến LM35 và gửi lên máy tính thông qua giao tiếp Serial theo định dạng CSV/JSON.

## 2. Tính năng
* Đọc nhiệt độ từ nhiều kênh Analog (A0, A1).
* Chuyển đổi giá trị ADC sang độ C chính xác.
* Xuất dữ liệu định dạng chuẩn để phần mềm máy tính dễ dàng xử lý.

## 3. Phần cứng yêu cầu
| Linh kiện | Số lượng | Ghi chú |
|-----------|----------|---------|
| Arduino Uno R3 | 01 | Board mạch chính |
| Cảm biến LM35 | 02 | Cảm biến nhiệt độ Analog |
| Dây cắm | 10 | Dây kết nối |

## 4. Cấu trúc thư mục
```text
Arduino_LM35_TempMonitor/
├── firmware/              # Mã nguồn Arduino (3 kênh + JSON)
│   └── LM35_TempReader/
│       └── LM35_TempReader.ino
├── docs/                  # Tài liệu sơ đồ mạch và hướng dẫn
├── simulation/            # File mô phỏng (Proteus/Tinkercad)
├── .gitignore             # Quy tắc loại bỏ tệp biên dịch rác
└── README.md              # Giới thiệu và hướng dẫn dự án

## 5. Thành viên nhóm
* Nguyễn Phan Tấn Đạt - MSSV: N23DCCI012
* Nguyễn Bình An - MSSV: N23DCCI001