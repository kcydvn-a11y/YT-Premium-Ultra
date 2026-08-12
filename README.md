# 🛡️ **YT PREMIUM ULTRA**
**YouTube Ad Blocker chuyên sâu cho Android**

> Trải nghiệm YouTube **sạch quảng cáo – phát nền mượt – không bị hỏi “Tiếp tục xem?” – fullscreen cực nét**.

**Phiên bản:** `3.7.3-Ultimate-Engine`  
**Nền tảng:** Android (Mobile + TV Box + Android TV)  
**Framework:** Flutter 3.x  
**Giấy phép:** Free for Personal Use  

---

### 🎥 Demo trên YouTube
[![Watch Demo](https://img.shields.io/badge/Xem_Demo_trên_YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=Qnc-bOVZrQM)

---

## ✨ TÍNH NĂNG NỔI BẬT

- **Chặn quảng cáo triệt để**  
  Loại bỏ hoàn toàn pre-roll, mid-roll, overlay, banner, sponsored cards và mọi dạng quảng cáo ẩn.

- **Phát nhạc nền thật sự**  
  Video/âm thanh vẫn tiếp tục chạy khi tắt màn hình, khóa máy hoặc chuyển sang ứng dụng khác.

- **Nonstop Playback (Không hỏi “Tiếp tục xem?”)**  
  Tự động bỏ qua mọi dialog “Continue watching”, “Ad blocker detected”, enforcement message. Video không bao giờ bị dừng đột ngột.

- **Fullscreen cực nét & thông minh**  
  Hỗ trợ 4 chế độ tỷ lệ: **Gốc – Fit – Auto (Smart) – Full**. Chế độ Smart tự căn chỉnh khung hình đẹp mắt, không bị cắt đầu/chân.

- **Voice Search (Tìm kiếm bằng giọng nói)**  
  Hỗ trợ đầy đủ micro trong WebView, tìm video nhanh chóng như trên YouTube chính thức.

- **Điều khiển màn hình khóa chuẩn HD**  
  Hiển thị tiêu đề, nghệ sĩ, ảnh bìa và nút Play / Pause / Next / Previous ngay trên lockscreen.

- **Khôi phục thông minh**  
  Tự phục hồi tốc độ phát và âm thanh ngay sau khi hết quảng cáo hoặc khi bị hệ thống tạm dừng.

- **Tiết kiệm pin & RAM**  
  WebView nhẹ, chỉ cập nhật media info khi thực sự cần, tối ưu chống Doze.

- **Giao diện hiện đại**  
  Dark Mode, splash screen đẹp, logo kim cương 3D “ULTRA”, thanh tiến trình màu cam đồng bộ.

---

## 🧠 CÔNG NGHỆ LÕI BÊN TRONG

| Lớp | Công nghệ | Mô tả |
|-----|-----------|-------|
| 1 | **Stealth JS Injection** | Tiêm engine trực tiếp vào Main World của YouTube |
| 2 | **JSON Proxy Manipulation** | Can thiệp sâu vào `playerResponse` & `ytInitialPlayerResponse` để xóa quảng cáo + enforcement |
| 3 | **Network Interceptor** | Chặn toàn bộ request tracking / ad reporting (doubleclick, pagead, ptracking…) |
| 4 | **AudioService + Foreground Service** | Duy trì phát nền ổn định, chống bị Android Doze giết |
| 5 | **Smart Playback Engine** | Thuật toán phát thông minh chống spam play, tự resume sau interruption |
| 6 | **Hardware Interaction Tracker** | Phân biệt thao tác thật của người dùng để không can thiệp sai |
| 7 | **Aspect Ratio Engine** | 4 chế độ tỷ lệ màn hình với MutationObserver giữ style ổn định |
| 8 | **Anti-Detection Shield** | Giả lập `document.visibilityState = visible`, fingerprint shield |
| 9 | **Pull-to-Refresh & Smart Back** | Vuốt làm mới + điều hướng Back thông minh (Shorts / Watch / Search) |

---

## 🎯 CHI TIẾT CÁC CƠ CHẾ QUAN TRỌNG

### 1. Chặn quảng cáo đa tầng
- CSS ẩn toàn bộ element quảng cáo
- Xóa `adPlacements`, `playerAds`, `adSlots` trong JSON
- Chặn network request chứa chữ ký quảng cáo
- Tự động tua & skip khi phát hiện ad-showing

### 2. Phát nền & Nonstop
- Sử dụng `audio_service` + `audio_session`
- Keep-alive timer + smart kick khi vào background
- Tự động bỏ dialog “Continue watching” / “Ad block detected”
- Phục hồi âm thanh & tốc độ ngay sau khi hết quảng cáo

### 3. Fullscreen & Aspect Ratio
- Nút xoay màn hình + menu chọn tỷ lệ
- 4 chế độ: **Gốc / Fit / Auto / Full**
- Tự giữ style khi YouTube reset DOM

### 4. Voice Search
- Cấp quyền micro đầy đủ cho WebView
- Hỗ trợ `getUserMedia` để tìm kiếm bằng giọng nói hoạt động mượt

---

## 📥 HƯỚNG DẪN CÀI ĐẶT

1. Tải file `app-YT-Premium-Ultra.apk` phiên bản mới nhất
2. Cài đặt trên Android (bật **Unknown Sources** nếu cần)
3. Mở ứng dụng → tận hưởng YouTube sạch sẽ

**Link tải nhanh (Google Drive):**  
[https://drive.google.com/drive/folders/15mSp3mwzZsaiLAV2r3pZ2m8aVxnQjV_C?usp=sharing](https://drive.google.com/drive/folders/15mSp3mwzZsaiLAV2r3pZ2m8aVxnQjV_C?usp=sharing)

---

## 📋 LƯU Ý

- Hoạt động tốt nhất trên **Chrome WebView** mới
- Sau khi YouTube cập nhật lớn, có thể cần cập nhật engine
- Ứng dụng chỉ dùng cho mục đích cá nhân

---

## 📬 LIÊN HỆ & HỖ TRỢ

- **Tác giả:** Thái Thông  
- **Email:** [ThaiThongSj@gmail.com](mailto:ThaiThongSj@gmail.com)

### 💰 Ủng hộ dự án

**Vietcombank**  
Số tài khoản: `9898661918`  
Chủ tài khoản: **NGUYỄN NGỌC THÁI THÔNG**

---

**Cảm ơn bạn đã sử dụng YT Premium Ultra!**  
Trải nghiệm YouTube sạch – mượt – không quảng cáo – phát nền thật sự. ❤️
