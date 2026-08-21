# Nghiên cứu Chính thức — Hệ thống Racing

**Trạng thái:** `FOUND / NORMALIZED`  
**Continuity chính của các định nghĩa:** `TV_S1`; game và các animation khác được ghi riêng.

## 1. Twinkle Series
Portal Cygames định nghĩa Twinkle Series là **sports entertainment cấp quốc gia**, nơi Umamusume có năng lực chạy siêu phàm thi đấu. Nhiều Umamusume mơ hoạt động ở series này; thành tích cao tạo địa vị star/idol.

## 2. Hạng race và lớp tham gia
- Grade races chia theo thứ tự cao xuống **G1, G2, G3**; thắng G1 được glossary TV S1 xem là vinh dự tối cao của Twinkle Series.
- Series chia Junior và Senior class; race được phép dự khác nhau.
- Junior A/B/C tồn tại trong `TV_S1`; Junior C có thể vào Classic Triple Crown.
- Make Debut chỉ dành cho người chưa từng xuất phát, là debut race.
- Race/qualification cụ thể ngoài các định nghĩa này phải dẫn episode, scenario hoặc rule tương ứng.

## 3. Team/trainer requirement trong TV S1
- Racer Twinkle Series phải thuộc một team.
- Team được công nhận cần tối thiểu năm Umamusume.
- Mỗi team có ít nhất một licensed trainer.
- Trainer chọn race và chỉ đạo training. Chi tiết ở `official/world/trainers.md`.

Không tự áp rule “5 người” cho mọi game/CG scene nếu production source biểu hiện khác.

## 4. Course, surface và venue
Glossary nêu turf và dirt. Twinkle Series có 10 venue lớn: Tokyo, Nakayama, Kyoto, Hanshin, Chukyo, Sapporo, Hakodate, Fukushima, Niigata, Kokura. Local organizers còn tổ chức local racing, ví dụ Kochi.

JRA đời thật chỉ dùng làm `REAL_HORSE_REFERENCE` cho topology/course/distance/mùa; không quyết định tuổi hay chronology franchise.

## 5. Chiến thuật và thuật ngữ chạy
- **Nige/front:** giành vị trí đầu sớm rồi giữ lead.
- **Senko/pace:** ở khoảng hạng hai hoặc trước pack rồi bứt trên straight.
- **Sashi/late:** ở giữa hoặc hơi sau pack, thoát ra trên straight.
- **Oikomi/closer:** giữ sức ở cuối pack và vượt nhóm trước ở straight.
- `Shikake`: thời điểm tung last spurt.
- `Sueashi`: độ tăng tốc/đà cuối race.
- Stride và pitch là hai running mechanics; slipstream giảm drag cho runner bám sau.

Rank aptitude trong game không phải physics tuyệt đối và không tự đổi character prose thành con số.

## 6. Race-day flow có nguồn
1. Paddock: runner đi vòng/khởi động và lần lượt được giới thiệu trên runway.
2. Underground passage nối paddock với course.
3. Main-course entry.
4. Fanfare và starting gate.
5. Race.
6. Nếu có obstruction/foul, officials có thể mở inquiry.
7. Kết quả được confirmed; có thể demotion hoặc disqualification.
8. Sau toàn bộ race trong ngày là Winning Live buổi chiều/tối.

Call-room, exact paperwork, giờ cố định và medical sign-off không được glossary chốt.

## 7. Kết quả và discipline
- Tie là hai Umamusume chạm đích hoàn toàn cùng lúc.
- Inquiry có đèn xanh; result confirmation có đèn đỏ trong venue.
- Demotion hạ thứ hạng finish vì violation; disqualification xóa finish.
- Margin dùng đơn vị body length, glossary xấp xỉ 2.5 m.
- Fan vote được mô tả là bình chọn cổ vũ **không có tính gambling**.

## 8. Racewear và equipment
Racewear là ceremonial/special outfit mặc ở sân khấu lớn như G1; glossary gán cho nó nguồn lực “bí ẩn” đối với Umamusume. Horseshoe-shaped fitting gắn dưới race shoes được xác nhận. Không tự chuyển câu mô tả magical thành hệ số power.

## 9. Game systems tách riêng
Official URA scenario xác nhận:
- menu training cá nhân theo trainee;
- cần theo dõi stamina/condition và race schedule;
- training khi thể lực thấp có thể thất bại, gây injury, giảm motivation/ability;
- aptitude, mục tiêu và skill khác nhau;
- summer camp tháng 7–8.
URA Finals tournament là `GAME`, không mặc định tồn tại trong TV.

## 10. Nguồn
- https://umamusume.jp/about/
- https://anime-umamusume.jp/archive/1st/keywords/
- https://umamusume.jp/contents/game/scenario/ura/
- https://umamusume.jp/contents/anime/roadtothetop/words
- Corpus animation Drive
