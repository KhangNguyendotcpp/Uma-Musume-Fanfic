# Audit tên nhân vật xuất hiện trong Animation

## Mục tiêu
Repo phải có **một Markdown riêng cho mọi nhân vật có tên ổn định xuất hiện/được gọi tên/được credit trong animation thuộc phạm vi**: TV S1–S3, 1st Anniversary, ROAD TO THE TOP, Beginning of a New Era, Umayon, Umayuru và Cinderella Gray.

Nếu source đã được kiểm tra mà không nói một field, ghi `UNSPECIFIED`; không được để `NOT_YET_NORMALIZED` như một cách né research.

## Các loại evidence
1. `ANIME_CREDIT_CONFIRMED` — tên nằm trong cast/credit hoặc source phát sóng đáng tin.
2. `ANIME_NAMED_ON_SCREEN` — tên hiện trên bảng race, caption, roster hoặc được nhân vật khác gọi dù không có voice credit riêng.
3. `ANIME_VISUAL_CONFIRMED` — character design/model xuất hiện rõ và được production/source định danh, nhưng có thể không thoại.
4. `MANGA_ONLY_OR_NOT_CONFIRMED` — có ở manga/wiki nhưng chưa đủ evidence animation.
5. `PENDING_FRAME_AUDIT` — cần xem frame/video Drive để chốt episode/exact on-screen naming.

## Audit adaptation

### TV Season 1 / Season 2 / Season 3 / 1st Anniversary / RTTT
Proper-named cast trong các cast table đã được đối chiếu với profile tree. Role generic không tên riêng bị loại. Cameo pass vẫn tiếp tục vì credited cast không bao phủ toàn bộ visual presence.

### Beginning of a New Era — cameo pass
Cast chính/credit đã được cover từ trước. Pass mới đối chiếu `Media Appearances` và background/campus cameo, phát hiện 8 nhân vật có animation presence nhưng baseline 166 chưa có profile riêng:

- **Neo Universe** — `ANIME_VISUAL_CONFIRMED`; background cameo ở RTTT, Season 3 và BOANE.
- **Sweep Tosho** — `ANIME_VISUAL_CONFIRMED`; background cameo BOANE.
- **Daiichi Ruby** — `ANIME_VISUAL_CONFIRMED`; Season 3 background + BOANE opening/campus.
- **K.S.Miracle** — `ANIME_VISUAL_CONFIRMED`; background ở cảnh Jungle Pocket vào Tracen.
- **Yamanin Zephyr** — `ANIME_VISUAL_CONFIRMED`; background ở cảnh Jungle Pocket vào Tracen.
- **Air Messiah** — `ANIME_VISUAL_CONFIRMED`; cameo BOANE.
- **Zenno Rob Roy** — `ANIME_VISUAL_CONFIRMED`; cameo Season 2 + BOANE, đồng thời có Umayuru appearance.
- **Hishi Miracle** — `ANIME_VISUAL_CONFIRMED`; xuất hiện trong BOANE và `Umayuru: Pretty Gray`.

Cả 8 đã được tạo profile riêng ở `rttt-boane-profiles/`. Pass này nâng baseline từ **166 lên 174 profile**.

**Quan trọng:** đây vẫn chưa phải frame audit hoàn chỉnh của movie. BOANE có nhiều racer/background shot hơn cast table và vẫn cần quét trực tiếp race card, bảng tên, caption và crowd/campus frames trong file Drive.

### Umayon — episode character-list audit
Đã đối chiếu character section của toàn bộ 24 tập ở mức episode wiki/list. Phát hiện một thiếu sót của baseline cast-table:
- **Biko Pegasus — tập 8 `Hero Theater: Uma Soldier V!!`**.

Biko đã được bổ sung profile. Trivia của trang Umayon cũng cho biết gần như toàn bộ base-release roster xuất hiện, vì vậy **frame-level visual audit vẫn cần thiết** để bắt cameo không nằm trong character section.

### Umayuru — episode/character-list audit
Đã đối chiếu cast table, episode character lists và character index xuyên 24 tập. Phát hiện:
- **Nakayama Festa — tập 20 `Dealing with Danger`**; trước đó baseline repo thiếu profile dù cô nằm trong Umayuru character ecosystem.

Các nhân vật proper-named khác trong character list đã có profile. Hishi Akebono có recurring background sighting nhưng đã được cover từ trước. Zenno Rob Roy cũng có cameo ở tập 20 dưới dạng chip trong mahjong và hiện đã có profile riêng.

### Cinderella Gray
Credit/name-confirmed mới bổ sung ở các pass gần nhất:
- Nanto Ichiban — tập 1
- Sekai Touha — tập 2
- Walk Dancer — tập 2
- Yamano Thousand — tập 14
- Spring Thing — tập 14
- Face No More — tập 23
- Romance Bubbly — tập 23
- Fuyuno Nakasumi — tập 23
- Ai-chan — tập 10
- Yuichi Iwao — trainer, tập 1–3
- Igawa — race analyst, tập 7/12/17
- Shihandai — trainer Yaeno Muteki
- Tadashi Kouchi — trainer Dicta Striker, tập 20–21
- Ryuko Yusuhara — trainer Oi của Inari One, tập 23
- Taro Yusuhara — trainer Central của Inari One, tập 23
- Frank McMonahan / Obey Your Master's Trainer — anime credit + manga/source-name mapping

Anime visual/race-name confirmed nhưng không có voice credit riêng: Massive Viking, Top Shunbetsu, Long Live Free.

## Generic roles bị loại
`Teacher`, `Reporter`, `Doctor`, `Audience Member`, `Head Chef`, `Chairman`, `Vice-Chairman`, `Maintenance Staff`, `Innkeeper Host/Hostess`, `Narrator`... không tạo profile nếu không có stable canonical personal name.

## Audit chưa hoàn thành tuyệt đối
- Cast/episode-character-list/cameo-source audit hiện đạt **174 profile**.
- **Race-card/on-screen text/cameo frame audit vẫn phải tiếp tục trực tiếp trên video Google Drive**, đặc biệt BOANE và các race scene có runner không thoại.
- Không được tuyên bố “100% mọi named frame đã cover” cho tới khi từng episode/movie được đánh dấu frame-audited.
