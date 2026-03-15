Radar phát hiện vật thể dùng ESP32

Dự án này sử dụng ESP32, cảm biến siêu âm HC-SR04 và servo SG90 để quét khu vực từ 0° đến 180° và đo khoảng cách đến vật thể.

ESP32 kết nối WiFi, gửi dữ liệu đo được lên API Flask và cung cấp WebServer để ứng dụng Android có thể điều khiển bắt đầu hoặc dừng quá trình quét.

Chức năng chính

Quét góc từ 0° đến 180° bằng servo

Đo khoảng cách bằng cảm biến siêu âm HC-SR04

Phát hiện vật thể trong khoảng cách đã đặt trước

Gửi dữ liệu khoảng cách và góc lên API Flask

Cung cấp WebServer trên ESP32 để ứng dụng Android điều khiển

Có thể bắt đầu hoặc dừng quét từ thiết bị bên ngoài

Phần cứng sử dụng

ESP32

Cảm biến siêu âm HC-SR04

Servo SG90

Dây kết nối và nguồn cấp
