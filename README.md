📡 Bronc3 VoLTE Tool V1.0.0
Bronc3 VoLTE Tool là công cụ dành cho Windows hỗ trợ kiểm tra, chẩn đoán và xử lý các vấn đề liên quan đến VoLTE, IMS và VoWiFi trên thiết bị Android thông qua ADB.
Tool được thiết kế với giao diện trực quan, có hướng dẫn tiếng Việt và Live Console, phù hợp cả với người mới sử dụng ADB.
✨ Chức năng chính
- 📱 Tự động nhận diện thiết bị Android
  - Hãng và Model
  - Phiên bản Android / SDK
  - Device Codename
  - Nhà mạng / Operator
  - MCC/MNC
- 📡 Kiểm tra IMS
  - Kiểm tra trạng thái IMS
  - Phát hiện thông tin IMS Registration
  - Kiểm tra dữ liệu liên quan đến VoLTE
  - Kiểm tra VoWiFi / IWLAN
- ⚡ Auto Diagnose / VoLTE Safe Mode
  - Tự động phân tích thiết bị trước khi xử lý
  - Kiểm tra cấu hình mạng hiện tại
  - Phân tích IMS và Telephony
  - Hiển thị kết quả trực tiếp trong Live Console
  - Hạn chế thực hiện thay đổi không phù hợp với thiết bị
- 📶 VoWiFi
  - Kiểm tra khả năng Wi-Fi Calling
  - Phân tích trạng thái IWLAN/IMS khi firmware hỗ trợ
- 🔌 ADB / Shizuku
  - Kiểm tra kết nối ADB
  - Hiển thị trạng thái thiết bị
  - Chuẩn bị cho các chức năng cần quyền nâng cao
- 🟧 Xiaomi / Redmi / POCO
  - Nhận diện MIUI / HyperOS
  - Đọc Region / ROM
  - Device Codename
  - Platform/Chipset Hint
  - Operator MCC/MNC
  - Xiaomi IMS Analyzer
- 💾 Sao lưu & Khôi phục
  - Xuất báo cáo chẩn đoán
  - Lưu thông tin Live Console
  - Hỗ trợ kiểm tra lại cấu hình trước và sau khi xử lý
- ⚠️ Modem Lab
  - Khu vực riêng dành cho các chức năng modem nâng cao
  - Có cảnh báo trước khi truy cập
  - Tách biệt hoàn toàn khỏi Auto Fix thông thường
Lưu ý: Các thao tác ghi EFS/NV/modem có rủi ro cao. Phiên bản hiện tại không tự động áp một modem profile chung cho nhiều model.

🖥️ Yêu cầu
Máy tính
- Windows 10 / Windows 11
- Cổng USB hoạt động bình thường
- Driver USB/ADB phù hợp với điện thoại
Điện thoại Android
- Bật Tùy chọn nhà phát triển
- Bật USB Debugging
- Cho phép máy tính thực hiện gỡ lỗi USB
🚀 Cách sử dụng
1. Mở Bronc3 VoLTE Tool.
2. Bật USB Debugging trên điện thoại.
3. Kết nối điện thoại với máy tính bằng cáp USB.
4. Chọn Cho phép gỡ lỗi USB trên điện thoại.
5. Chờ tool nhận diện thiết bị.
6. Chạy Kiểm Tra IMS trước.
7. Sử dụng chức năng VoLTE/VoWiFi phù hợp.
8. Kiểm tra lại trạng thái IMS sau khi thực hiện.
⚠️ Lưu ý quan trọng
VoLTE không chỉ phụ thuộc vào điện thoại. Khả năng hoạt động còn có thể phụ thuộc vào firmware, modem/carrier configuration, SIM và việc nhà mạng provision IMS cho thuê bao/thiết bị.
Vì vậy, tool không thể đảm bảo mọi thiết bị Android đều có thể kích hoạt VoLTE chỉ bằng một thao tác.
Không nên sử dụng file EFS, NV hoặc modem profile của một model khác cho thiết bị của bạn.
🔐 An toàn
Bronc3 VoLTE Tool được thiết kế theo hướng kiểm tra → chẩn đoán → xác định phương pháp phù hợp, thay vì tự động thực hiện các thay đổi modem nguy hiểm trên mọi thiết bị.
Người dùng tự chịu trách nhiệm đối với các thao tác nâng cao được thực hiện trên thiết bị.
👨‍💻 Developer
Dev by Bronc3
Zalo: +84387223628
❤️ Nếu phần mềm hữu ích, bạn có thể ủng hộ quá trình phát triển thông qua QR Donate được tích hợp trong tab Thông Tin của phần mềm.
Version: V1.0.0
