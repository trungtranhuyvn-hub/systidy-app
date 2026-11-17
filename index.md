---
title: SysTidy – System Data Cleaner for Mac
---

# SysTidy – System Data Cleaner for Mac

SysTidy shows what is inside the grey "System Data" bar in macOS Storage settings: caches, logs, temporary files, installers, developer tools, backups and app data. Each item comes with its size, a risk level and a recommended action, so you decide what to remove.

![SysTidy](screenshots/02-systemdata.png)

## Support

Questions, bug reports or feature ideas: **tongduoctuvien@gmail.com**

Please include your macOS version and, for bugs, what you were doing when it happened.

## Frequently asked questions

**Why does SysTidy ask me to choose my Home folder?**
Apps from the Mac App Store run in a sandbox. Choosing your Home folder once lets SysTidy measure caches, logs and app data inside `~/Library`. The permission is remembered; you can revoke it by deleting the app.

**Why can't SysTidy see Mail, Messages or the Trash?**
macOS protects those folders. You can grant SysTidy Full Disk Access in System Settings › Privacy & Security › Full Disk Access. It is optional, and SysTidy explains the risks before you do it.

**Why do some items show a command instead of a Delete button?**
Some parts of System Data, such as local Time Machine snapshots or the Spotlight index, can only be changed by macOS tools. SysTidy copies the right command so you can review it and run it in Terminal yourself.

**Does SysTidy delete anything on its own?**
No. Nothing is removed until you select items and confirm. By default, files are moved to the Trash.

**Does SysTidy collect my data?**
No. See the [Privacy Policy](privacy.html).

---

# Hỗ trợ (Tiếng Việt)

SysTidy cho bạn thấy phần "System Data" màu xám trong Cài đặt › Dung lượng gồm những gì: cache, log, tệp tạm, bộ cài, công cụ lập trình, sao lưu và dữ liệu ứng dụng, kèm dung lượng, mức rủi ro và gợi ý xử lý.

Góp ý, báo lỗi hoặc đề xuất tính năng: **tongduoctuvien@gmail.com**

- **Chọn thư mục Home:** app App Store chạy trong sandbox, cần bạn chọn thư mục Home một lần để đo cache và log.
- **Mail, Tin nhắn, Thùng rác:** cần cấp quyền Truy cập toàn bộ ổ đĩa (không bắt buộc).
- **Không tự xóa:** SysTidy chỉ xóa khi bạn chọn và xác nhận; mặc định chuyển vào Thùng rác.

[Chính sách quyền riêng tư](privacy.html)
