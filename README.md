# Ebs Media Scan

<img src="AppIcon.png" width="128" alt="icon">

Ứng dụng theo dõi tin tức y tế – sự kiện (Event-Based Surveillance): quét tin từ các nguồn feed theo bộ từ
khoá, lọc tin nóng, biểu đồ xu hướng, đám mây từ khoá, báo cáo ngắn bằng AI và đồng bộ dữ liệu giữa các máy.

Phát triển: **EOC KVMB**

Mỗi phiên bản là **một** bản phát hành chung cho máy tính, Android và iPhone (cùng số phiên bản).
Bản mới nhất luôn ở [Releases › Latest](https://github.com/NHL08/ebs-media-scan-releases/releases/latest).

## Máy tính (Windows)

Tải **`CaiDat_EbsMediaScan_<phiên bản>.exe`** ở bản phát hành mới nhất — chạy, bấm Tiếp → Cài đặt.
Không cần quyền quản trị.

Lần đầu chạy, Windows có thể báo "Windows protected your PC" (bộ cài chưa ký số) → **More info → Run anyway**.
Mỗi máy phải được quản trị viên duyệt và nhập khoá OpenAI riêng trước khi dùng.

**Cập nhật:** ứng dụng tự kiểm tra bản mới khi mở và mỗi 6 giờ; vào **Hệ thống → Cập nhật** rồi bấm
**Cập nhật ngay**. Dữ liệu, khoá API và cấu hình của máy được giữ nguyên.

## Điện thoại

App điện thoại xem dữ liệu đã đồng bộ từ các máy tính: tin mới, tìm kiếm, bộ lọc từ khoá nóng, xu hướng, báo cáo
ngắn. Lần đầu mở, app hiện **mã máy** — gửi mã này cho quản trị viên để duyệt
(trên máy tính: **Ctrl + Shift + Alt + Q › Duyệt máy**).

### Android

Tải APK mới nhất:

```
https://github.com/NHL08/ebs-media-scan-releases/releases/latest/download/EbsMediaScan.apk
```

Mở tệp để cài (cho phép "cài ứng dụng không rõ nguồn" nếu được hỏi).
App tự báo khi có bản mới: **Cài đặt › Cập nhật** tự tải APK, kiểm tra SHA-256 rồi mở trình cài đặt.

### iPhone (SideStore)

Thêm nguồn vào **SideStore › Sources › +**:

```
https://github.com/NHL08/ebs-media-scan-releases/releases/latest/download/sidestore.json
```

rồi cài **Ebs Media Scan** từ nguồn đó. Cập nhật: **SideStore › My Apps › Update**.
(Link nguồn cũ `raw.githubusercontent.com/.../main/sidestore.json` vẫn dùng được.)

---
Kho này chỉ chứa bộ cài phát hành; mã nguồn được lưu riêng.
