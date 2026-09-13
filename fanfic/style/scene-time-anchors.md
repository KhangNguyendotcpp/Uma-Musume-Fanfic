# Mốc thời gian đầu cảnh — QUY TẮC CỨNG

**Trạng thái:** `AUTHOR-DIRECTED / HARD / BLOCKING`. Áp dụng cho mọi prose mới và mọi đoạn prose được sửa từ quyết định tác giả ngày 2026-09-13.

## Bắt buộc khi chuyển thời gian

Nếu giữa hai cảnh có một khoảng chuyển thời gian đủ dài để nhảy sang hoạt động hoặc buổi khác, **phải ghi giờ, phút, thứ, ngày, tháng, năm thành một dòng ngay trước đoạn đầu tiên của cảnh mới**. Không chờ tới giữa/cuối cảnh mới giải thích thời gian.

Bắt buộc với nhảy qua giấc ngủ, sang sáng/trưa/chiều/tối khác, sang ngày khác, bỏ qua một buổi tập/bữa ăn/quãng di chuyển, hoặc các cụm “vài giờ sau”, “sáng hôm sau”, “sau bốn tiếng”. Không cần lặp timestamp cho từng lượt thoại, động tác hay vài phút nối liên tục trong cùng cảnh. Không dùng sự mơ hồ của “đủ dài” để bỏ mốc khi người đọc có thể nhầm ngày/buổi.

## Định dạng

`**HH:MM JST — Thứ [tên thứ], ngày DD tháng MM năm YYYY.**`

Ví dụ định dạng với mốc đã có nguồn:

**06:00 JST — Thứ Sáu, ngày 03 tháng 04 năm 2026.**

Mọi trường đều bắt buộc: không dùng riêng “sáng hôm sau”, “chiều thứ Sáu”, `03/04` hoặc chỉ `06:00` để thay dòng đầy đủ. Cảnh ngoài Nhật dùng timezone địa phương, kiểm tra đổi ngày theo timezone; không lấy ngày giờ chạy công cụ/ngày commit làm giờ trong truyện.

## Cổng kiểm tra trước khi viết

1. Đọc timeline tổng, lịch vận hành, event và current state; giai đoạn 01–03/04 phải đọc thêm `fanfic/timeline/2026-04-01-to-03-chronology.md`.
2. Xác định cảnh trước kết thúc ở ngày nào, thời gian đã trôi qua, cảnh mới bắt đầu lúc nào. Kiểm tra thứ bằng lịch Gregory, cộng cả thời lượng di chuyển/ăn/tập/ngủ.
3. Giờ/phút chưa được nguồn khóa phải được xác lập nhất quán trong timeline trước khi xuất prose; không lấy một giờ suy đoán và tuyên bố đó là canon cũ. Khi chỉ sửa hồ sơ lịch sử, giữ `TBD` cho giờ chưa biết; đây không phải quyền xuất prose mới với timestamp thiếu.
4. Phân biệt ngày hoạt động, ngày viết/gửi báo cáo, ngày kể lại cho nhân vật khác và ngày cập nhật repo.
5. Khi chuyển ngày, cập nhật mọi “hôm nay”, “hôm qua”, “đêm trước”, “sáng mai”, lịch hẹn phục hồi và knowledge registry liên quan. Không thay toàn bộ `02/04` thành `03/04` vì chúng có thể thuộc các sự kiện khác nhau.

## Hậu kiểm blocking

- Thiếu dòng đầy đủ trước một cảnh có bước nhảy thời gian: **chưa đạt, phải sửa trước khi giao**.
- Thứ không khớp ngày hoặc clock lùi mà không có hồi tưởng/chuyển múi giờ rõ: phải sửa.
- Hồi tưởng có bước nhảy thời gian cũng phải ghi mốc đầy đủ trước đoạn hồi tưởng; khi trở về hiện tại phải tái lập mốc.
- Không khóa giờ giả cho prose cũ chỉ để vượt kiểm tra. Việc rà timeline không tự tạo chapter nguyên văn mới.
