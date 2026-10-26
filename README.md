# NConnect Pro – bike test

**English** · [Tiếng Việt](#tiếng-việt)

NConnect Pro is a navigation app for Yamaha bikes with the **LinkBox** connectivity unit, the ones that use
**MyRide-Link / Garmin Motorize**: **TMAX 560**, **Tracer 9 GT / GT+** and similar. It draws its own dash screens
(map, speed, route, music) and sends them to the TFT over the bike's **Wi-Fi** or **USB** using SmartDeviceLink.

It is not finished, and I don't own one of these bikes. This test build records how your bike talks to the phone,
so the connection can be tuned. **Thank you for helping!**

## ⚠️ Safety

Test with the **bike parked**, ignition on (no need to start the engine). Never test while riding.

## What you need

- A **TMAX 560, Tracer 9 GT/GT+** or another bike that works with MyRide-Link / Motorize
- **Android 12+** or **iPhone (iOS 14+)**
- A USB **data** cable that connects your phone to the bike's USB port
- About **15–20 minutes**

## Privacy

The test app is separate from your other apps and only asks for:

- **Bluetooth** ("Nearby devices"): to talk to the bike's connectivity unit
- **Network / local network**: to join the bike's own Wi-Fi (a local network, not the Internet)
- **Background service / keep awake**: keeps the link up during the test

It does **not** ask for location, contacts, messages, calls or photos, and it sends **nothing** by itself.
The log only leaves your phone when you tap **Send log** and choose where to send it. You can uninstall the app
right after the test.

## Install

Download from **[Releases](../../releases)**.

**Android:** `NConnect-Pro-Test-x.y.z.apk`
1. Open the APK and allow "install unknown apps" for your browser or file manager.
2. Google Play Protect may warn about an unknown developer (the test build is not on the Play Store): choose
   **Install anyway**.

**iPhone:** `NConnect-Pro-Test-x.y.z.ipa`
1. Install it with **[AltStore](https://altstore.io)** or **[Sideloadly](https://sideloadly.io)** using your own
   Apple ID (a free Apple ID works; the app then expires after 7 days).
2. Settings › General › VPN & Device Management: trust your Apple ID if iOS asks.

## Test

Open the app: it starts with a **step-by-step test** (English or Vietnamese, switch with the **EN / VI** button).
Each step tells you what to do on the dash, sets the app up for you, ticks off what worked, and asks what the dash
showed:

1. Get ready: force-close MyRide-Link and Motorize, turn off any VPN
2. Bluetooth pairing, **with the phone's Wi-Fi off** (enter the PIN shown on the dash)
3. Join the bike's Wi-Fi (`LB#…`) **only once Bluetooth shows ✓**
4. Press each handlebar key
5. If nothing shows on the dash: a second try (still on Wi-Fi)
6. USB cable
7. Map (Android)
8. **Send log**

iPhone: keep the app **open with the screen on** while testing. iOS doesn't let apps send video in the background.

## Send the log

On the last step tap **Send log** and send the file **privately** to the developer, the person who asked you to
test. If you can, add a **photo or short video of the dash** and your bike's model and year.

Please don't post logs in public issues: they include your phone model and your bike's Bluetooth address.

---

## Tiếng Việt

NConnect Pro là app dẫn đường cho xe Yamaha có bộ kết nối **LinkBox** (dùng app **MyRide-Link / Garmin Motorize**):
**TMAX 560**, **Tracer 9 GT / GT+**… App tự vẽ màn hình (bản đồ, tốc độ, lộ trình, nhạc) và đưa lên đồng hồ qua
**Wi-Fi** hoặc **cáp USB** của xe bằng giao thức SmartDeviceLink.

App chưa hoàn thiện và mình không có xe. Bản thử này ghi lại cách xe nói chuyện với điện thoại để chỉnh kết nối.
**Cảm ơn bạn đã giúp!**

### ⚠️ An toàn

Chỉ thử khi **xe đứng yên**, bật khoá (không cần nổ máy). Không thử khi đang chạy.

### Cần chuẩn bị

- Xe **TMAX 560, Tracer 9 GT/GT+** hoặc xe khác dùng MyRide-Link / Motorize
- Điện thoại **Android 12+** hoặc **iPhone (iOS 14+)**
- Cáp USB **có truyền dữ liệu** nối điện thoại với cổng USB của xe
- Khoảng **15–20 phút**

### Quyền riêng tư

App thử chỉ xin: **Bluetooth** (Thiết bị ở gần), **mạng / mạng cục bộ** (Wi-Fi của xe, không phải Internet),
**chạy nền / giữ máy thức** trong lúc thử. **Không** xin vị trí, danh bạ, tin nhắn, cuộc gọi, ảnh; **không** tự
gửi dữ liệu. Log chỉ rời máy khi bạn bấm **Gửi log** và tự chọn nơi gửi. Thử xong có thể gỡ app ngay.

### Cài đặt

Tải ở mục **[Releases](../../releases)**.

- **Android:** mở file `.apk`, cho phép cài ứng dụng không rõ nguồn gốc. Nếu Play Protect cảnh báo, chọn **Vẫn cài đặt**.
- **iPhone:** cài file `.ipa` bằng **AltStore** hoặc **Sideloadly** với Apple ID của bạn (Apple ID miễn phí thì app
  hết hạn sau 7 ngày). Nếu iOS hỏi, vào Cài đặt › Cài đặt chung › Quản lý VPN & thiết bị để tin cậy.

### Thử

Mở app sẽ vào **màn thử từng bước** (tiếng Việt hoặc tiếng Anh, đổi bằng nút **VI / EN**). Mỗi bước nói việc cần
làm trên đồng hồ, tự cài đặt app, tự đánh dấu bước nào được và hỏi đồng hồ hiện gì. **Ghép Bluetooth khi Wi-Fi của điện thoại đang tắt**, có ✓ rồi mới vào Wi-Fi của xe. Với iPhone, để app **mở và màn
hình sáng** trong lúc thử.

### Gửi log

Ở bước cuối bấm **Gửi log** rồi gửi **riêng** cho người nhờ bạn thử. Gửi kèm **ảnh hoặc video đồng hồ**, đời xe và
năm sản xuất nếu được. Đừng đăng log công khai: trong log có đời máy và địa chỉ Bluetooth của xe.
