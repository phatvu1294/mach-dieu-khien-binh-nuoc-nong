# Mạch điều khiển bình nước nóng
*Mạch điều khiển bình nước nóng được phát triển dựa trên ATMega8/88/168/328*

### Giới thiệu
Mạch điều khiển bình nước nóng thông minh hiển thị LED 7 thanh hỗ trợ cảm ứng chạm và remote điều khiển từ xa, có cảnh báo lỗi.

![Mạch điều khiển bình nước nóng](/images/image-01.png)

### Tính năng
- Cảnh báo lỗi: lỗi cảm biến (E1), lỗi đầu đốt (E2), lỗi đầu đốt (E3).
- Tự động đóng cắt relay tới nhiệt độ đặt.
- Hỗ trợ hẹn giờ tắt bình: tắt hẹn giờ, 1h, 2h, 3h, 4h, 5h, 6h, 7h, 8h, 9h.
- 4 nút cảm ứng chạm:
  + Power: phím bật tắt nguồn.
  + Dec: Giảm nhiệt độ cài đặt bình, chương trình sẽ tự thoát khỏi mode này sau 3 giây để vào chế độ bình thường.
  + Inc: Tăng nhiệt độ cài đặt bình, chương trình sẽ tự thoát khỏi mode này sau 3 giây để vào chế độ bình thường.
  + Enter/Alarm: 2 chế độ: Nhấn 1 chạm để thoát khỏi chế độ cài đặt nhiệt / Nhấn giữ quá 3 giây vào chế độ hẹn giờ tắt thiết bị, tiếp tục ấn 1 chạm để chọn các mức hẹn giờ, chương trình sẽ tự thoát khỏi mode này sau 3 giây để vào chế độ bình thường.
- LED 7 hiển thị nhiệt độ:
  + Chớp tắt toàn bộ LED: báo hiệu đang ở chế độ cài đặt hoặc hẹn giờ.
  + Chớp đắt dấu chấm: báo hiệu đang có hẹn giờ chạy.
- Hỗ trợ remote 5 channel điều khiển từ xa.

### Video demo
[https://www.youtube.com/watch?v=QyWi2RASTpk](https://www.youtube.com/watch?v=QyWi2RASTpk)
