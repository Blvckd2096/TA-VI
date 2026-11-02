# TrollAgent — bản tiếng Việt (TA-VI)

Fork từ zrrt/TrollAgent, thêm ngôn ngữ `vi` (Tiếng Việt) vào hệ L10n.

- Màn Ngữ cảnh (Context usage) và Model API (mục model dự phòng, chế độ cố định, tự sửa giao thức, chuỗi hạ cấp, streaming) trước đây là chữ cứng tiếng Trung, nay dùng `L10n.t(...)`.
- Chọn "Tiếng Việt" trong Settings → Language.
- v2 (02/11): các dòng chưa dịch trong bản tiếng Việt hiện tiếng Anh thay vì tiếng Trung; các dòng hay gặp (Cài đặt/An toàn, màn chat trống, ô nhập, chip, ngày tháng) đã dịch thật sang tiếng Việt.
- Chỗ nào chưa có bản dịch tiếng Việt sẽ hiện tiếng Anh, không hiện tiếng Trung, không hiện mã key.

Ghi chú build: run v2 đầu tiên (commit 8e2b050) bị hủy giữa chừng khi các job native đang chạy, job build chính chưa chạy — commit này chỉ để chạy lại build v2 từ đầu, không đổi code.
