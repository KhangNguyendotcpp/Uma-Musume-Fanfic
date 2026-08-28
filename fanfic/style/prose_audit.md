# Prose Audit — từ mở đầu đến điểm hiện tại

**Phạm vi:** các sự kiện prose đã được khóa trong repo từ Equinox xuất hiện ngày 2026-03-09 tới vòng bầu lớp phó tổ chức sự kiện Senior 3-A sáng 2026-03-12. Repo hiện giữ phần lớn các cảnh dưới dạng continuity summary thay vì chapter nguyên văn; vì vậy audit này chỉ kết luận chắc chắn ở nơi còn đủ văn bản/dữ kiện, không dựng lỗi cho đoạn không còn nguyên văn.

**Trạng thái:** tài liệu chẩn đoán, không tự retcon sự kiện. Guardrail bắt buộc nằm tại `fanfic/style/prohibited_tendencies.md`.

| Mức | Khu vực | Vấn đề đã thấy | Xử lý bắt buộc cho prose sau |
|---|---|---|---|
| CRITICAL | Quầy thanh toán | Air Groove nhớ lương 460.000 yên và lựa chọn tài khoản dù không dự cảnh hợp đồng | Xóa nguồn nhớ này; chỉ dùng hành vi mua sắm mà cô trực tiếp thấy |
| HIGH | Cảnh may đo | Equinox tự xưng “cô” với nhân viên trưởng thành | Dùng “tôi/vợ tôi”; giữ “cô–em” riêng cho Air Groove/học sinh |
| HIGH | Cảnh may đo | Thước đo được 210 cm nhưng phải đổi thước dài hơn cho 200 cm | Sửa đạo cụ hoặc lý do đổi thước; không giữ mâu thuẫn số học |
| HIGH | Cảnh may đo | Vòng dưới ngực được đo rồi lại liệt kê như một phép đo mới | Ghi rõ đo xác nhận/cấu trúc khác hoặc bỏ lần lặp |
| HIGH | Nhiều file repo trước cập nhật này | Mốc prose và trạng thái tuyển dụng/orientation bị lệch giữa `current_state`, timeline, legal framework và guide | Đã đồng bộ trong commit cập nhật; các lần sau phải tìm toàn repo trước khi đổi mốc |
| MEDIUM | Cảnh cửa hàng | Head-hopping sang nội tâm/mục tiêu doanh số của nhân viên | Chỉ mô tả tín hiệu nhìn thấy hoặc xác lập người kể toàn tri nhất quán |
| MEDIUM | Cảnh cửa hàng | Cùng một beat “Air Groove ngăn mua quá nhiều” lặp qua giày, dép, dây tóc, quần áo và đồ may đo | Giữ các lượt làm quan hệ tiến triển; rút gọn lượt chỉ lặp kết luận |
| MEDIUM | Cảnh cửa hàng | Inventory và phí được liệt kê quá chi tiết, làm nhịp truyện đứng yên | Gom theo nhóm; chỉ giữ món/giá tạo setup, payoff hoặc continuity |
| MEDIUM | Cảnh may đo | Phản ứng đứng hình/đỏ mặt/che ngực/đồng thanh bị dồn dập và đồng bộ | Cá thể hóa phản ứng; giữ nhân viên chuyên nghiệp; không dùng học sinh làm thước so sánh cơ thể |
| MEDIUM | Tuyển dụng/orientation | Nhiều nguyên tắc nghề nghiệp có nguy cơ biến cảnh thành biên bản policy | Để hành động chứng minh nguyên tắc; cắt câu hỏi–đáp không thay đổi quyết định |
| MEDIUM | Equinox–Air Groove | Air Groove nhiều lần quyết định hoặc chốt thay một Uma trưởng thành | Giữ vai trò tư vấn/phản biện, sau đó để Equinox tự xác nhận quyết định |
| OPEN LOGIC | Đồ lót ban đầu | Zenith biết incarnation nhưng để lại sản phẩm sai rõ rệt | Chờ tác giả chốt lý do; không tự hợp thức hóa |
| LOW | Nhịp câu | Chuỗi câu cực ngắn, lặp “Có/Không”, “hai đôi”, “lần thứ…” tạo dấu vết sinh văn bản máy móc | Pha câu ngắn với câu có chuyển động; mỗi nhịp lặp phải tăng stakes hoặc tạo payoff |
| LOW | Câu “Do giống loài thôi” | Câu nói có thể bị hiểu rằng số đo này bình thường với mọi Uma, trái với chính phản ứng của nhân viên Uma | Nếu giữ như deadpan, cần để ngữ cảnh cho thấy Equinox nói về dạng draft-horse của mình hoặc đang cố giản lược quá mức |

## Kiểm tra cảnh bầu lớp trưởng 2026-03-12

- Phép tính đã khớp: mỗi ứng viên có 27 phiếu từ học sinh không ứng cử + 4 phiếu từ đối thủ = 31; năm ứng viên tạo tổng 155 phiếu.
- Cả năm hàng kết quả đều cộng đúng 31 và giữ đúng thứ tự author chốt: Sirius, Gentildonna, Opera O, Rudolf, Orfevre.
- `Phiếu trắng` là ô lựa chọn hợp lệ, không mâu thuẫn với việc không có tờ nào bỏ trống cả ba ô.
- Chưa phát hiện lỗi `CRITICAL/HIGH` mới trong phần quy trình và kết quả đã khóa. Các timestamp dạng số giảm dần trong bản prose phải được hiểu/ghi rõ là **thời gian còn lại trên đồng hồ**, không phải giờ đồng hồ đảo ngược.

## Kiểm tra cảnh bầu lớp phó tổ chức sự kiện 2026-03-12

- Phép tính tổng đã khớp: 32 cử tri đánh giá 7 ứng viên, trừ 7 lượt tự đánh giá bị loại = **217 lựa chọn hợp lệ**.
- Ledger từng cử tri cộng đúng bảng cuối: Opera O `30–0–1`, Fuji `29–0–2`, Maruzensky `26–2–3`, Taiki `24–3–4`, Winning Ticket `22–4–5`, Hishi Akebono `20–3–8`, Gold Ship `2–24–5` theo thứ tự Thuận–Chống–Trắng.
- Hai phiếu Thuận và năm phiếu Trắng của Gold Ship khớp đúng các cử tri tác giả nêu; 24 phiếu còn lại đều là Chống. Phiếu Tamamo tô đậm vẫn hợp lệ vì chỉ nằm trong một ô.
- Có một lỗi số học trong câu prose ở checkpoint sau lượt Narita Taishin: trước hai người cuối, sáu ứng viên đã tự bỏ qua hàng của mình có **29** đánh giá, còn Winning Ticket chưa nộp phiếu và đã nhận đủ **30** đánh giá từ 30 người đầu. Cụm “hai mươi chín lần hoặc hai mươi tám lần” phải sửa thành **“hai mươi chín hoặc ba mươi lần”** nếu chapter nguyên văn được lưu/chỉnh lại. Lỗi này không làm sai ledger hoặc kết quả cuối.
- Việc Equinox nhắm cả hai mắt trong lúc đọc phiếu phù hợp canon cô vẫn nhìn thấy bình thường. Lần mở mắt trái để công bố Opera O là một nhịp mới; không tự gán nó kéo dài năm phút chỉ vì khoảng chuyển tiếp sau vòng lớp trưởng từng kéo dài đúng năm phút.

## Những phần hiện không thấy lỗi canon chắc chắn

- Equinox dùng “cô–em” với Air Groove là đúng vì Air Groove vẫn là học sinh.
- Equinox đọc kỹ hợp đồng/hóa đơn phù hợp với năng lực và tính literal đã thiết lập.
- Việc cửa hàng Uma có mũi giày rộng, độ rộng khác nhau và dịch vụ dựng rập riêng phù hợp với worldbuilding nếu đây là cửa hàng chuyên biệt.
- Air Groove biết số đo 210–118–200, địa chỉ giao hàng và hành vi chi tiêu vì cô bé hiện diện trong cảnh tương ứng.
- Equinox nhắm mắt nhưng vẫn thấy là canon đã khóa; câu đùa về việc nhắm mắt không phải continuity error.

## Điểm cần kiểm tra khi có chapter nguyên văn

- mức lặp của “cô ấy”, câu đơn chủ–vị và cấu trúc phủ định ba nhịp;
- tính nhất quán focalization từ cảnh xuất hiện, phỏng vấn, orientation tới mua sắm;
- thời lượng thực tế của toàn bộ ngày 2026-03-10 so với số hợp đồng, orientation, di chuyển và mua sắm;
- kênh truyền thông tin giữa HR, staff, Student Council và Air Groove;
- sự chuyển biến quan hệ Equinox–Air Groove có đủ bước đệm hay chưa.
