# Known Issues · Buổi 1

Ghi lại lỗi chưa xử lý được hoặc đã xử lý xong.

| STT | Lỗi gặp phải | Lệnh gây lỗi | Cách đã thử | Trạng thái |
|---:|---|---|---|---|
| 1 |docker daemon ready [FAIL]|collect_session01_evidence.ps1 |Cập nhật WSL bằng wsl --update và bật Docker Desktop.|Đã xử lý xong|
| 2 |Lỗi pip is not recognized|Kiểm tra version của tool|Chạy python -m ensurepip hoặc chỉ dùng Python qua Docker.|Chấp nhận rủi ro / Đã xử lý|
| 3 |Thiếu Docker Images|Smoke test|Chạy script .\scripts\pull_all.ps1 để pull toàn bộ ảnh.|Đã xử lý xong|
