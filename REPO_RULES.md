# Quy tắc Repo

## Quy tắc phân tách

- `official/` trả lời: **Franchise/nguồn thực sự nói gì?**
- `fanfic/` trả lời: **Trong truyện này điều gì là sự thật?**
- `drafts/` trả lời: **Chúng ta đang cân nhắc điều gì?**

Không đưa phần vá/giải thích của fanfic vào `official/`, và không trình bày một chi tiết từ nguồn chính thức như canon fanfic đã được áp dụng nếu chưa có quyết định `ADOPTED` rõ ràng.

## Quy tắc bằng chứng

Mọi thông tin chính thức quan trọng phải xác định continuity nguồn và URL/tập/chương/file nguồn. Nếu nguồn im lặng, ghi `UNSPECIFIED`; không suy ra từ ngựa thật.

## Quy tắc override

Mỗi chỉnh sửa hoặc phần mở rộng fanfic có chủ đích nên ghi:

- trạng thái của nguồn/chính thức;
- trạng thái trong fanfic;
- status (`OVERRIDDEN` hoặc `ORIGINAL`);
- lý do.

## Quy tắc profile Haise/Takiyama — HARD

`fanfic/characters/haise-kimegaya.md` và `fanfic/characters/takiyama-shizurawa.md` phải đọc giống profile nhân vật Uma Musume tiêu chuẩn. Chúng **không được** biến thành dossier crossover.

Nguồn gốc OU, lịch sử chiến đấu cũ, cách tư duy chiến đấu chuyển sang đua, bất đối xứng meta-knowledge, hiệu chuẩn mức độ tâm lý, giới hạn sức mạnh và guardrail chống OOC chỉ được đặt trong `fanfic/internal-character-notes/` và/hoặc repo OU liên kết.

## Thông tin chưa biết

Một giá trị `DRAFT`, `TBD` hoặc `UNSPECIFIED` tuyệt đối không được nâng lên `APPROVED`/`LOCKED` chỉ vì thuận tiện cho prose. Dữ liệu đã audit nhưng nguồn im lặng phải dừng ở `UNSPECIFIED`; không tạo fact để lấp chỗ trống.

## Quy tắc timeline

- Các mốc ngày tháng cụ thể 2025–2035 là chronology của fanfic.
- Nếu adaptation chính thức không cung cấp ngày dương lịch, ngày trong repo là mốc `ORIGINAL`, không phải tuyên bố về canon chính thức.
- `Season` là giai đoạn kể chuyện nhiều mùa đua, không đồng nghĩa một năm lịch.
- Mỗi race hằng năm chỉ có một kỳ chính thức và một kết quả cuối. Hai source arc chỉ được ghép cùng kỳ khi bảng override fanfic nói rõ.
- Classic Triple Crown chỉ được dự trong Classic Year duy nhất; không được dùng University Division để đăng ký Classic lần hai.
- Official result bị ghi đè vẫn giữ trong `official/`; chỉ fanfic calendar ghi kết quả hợp nhất.

## Quy tắc lịch quốc tế

`fanfic/calendar/SENIOR_INTERNATIONAL_RACE_REFERENCE.md` là tài liệu planning dựa trên hệ đua thật. Nó không tự biến mọi giải ngoài đời thành official Uma canon. Tháng tổ chức là cửa sổ thường niên; ngày chính xác từng năm phải nằm trong writing schedule hoặc master calendar trước khi dùng trong prose.

Không gọi bất kỳ race nào là “World Cup duy nhất của Uma” nếu canon chưa xác nhận. Fanfic dùng nhãn planning `GLOBAL_CHAMPIONSHIP_MAJOR` cho các đỉnh quốc tế và ghi rõ giải nào mang tên/branding World Cup thật.

## Quy tắc độ phủ nhân vật

Mục tiêu: mọi nhân vật có tên/được credit xuất hiện trong corpus animation thuộc phạm vi (TV S1–S3, animation kỷ niệm 1 năm, RTTT, Beginning of a New Era, Umayon, Umayuru, Cinderella Gray). Vai nền không tên bị loại trừ trừ khi tìm được tên canon ổn định. Bất kỳ nhân vật mới nào được gọi tên trên màn ảnh phải được thêm vào `official/characters/INDEX.md` và có profile.
