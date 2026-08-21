# Audit tên nhân vật xuất hiện trong Animation

## Mục tiêu
Repo phải có **một Markdown riêng cho mọi nhân vật có tên ổn định xuất hiện/được gọi tên/được credit trong animation thuộc phạm vi**: TV S1–S3, 1st Anniversary, ROAD TO THE TOP, Beginning of a New Era, Umayon, Umayuru, **Umayuru: Pretty Gray** và Cinderella Gray.

Nếu source đã được kiểm tra mà không nói một field, ghi `UNSPECIFIED`; không được để `NOT_YET_NORMALIZED` như một cách né research.

## Các loại evidence
1. `ANIME_CREDIT_CONFIRMED` — tên nằm trong cast/credit hoặc source phát sóng đáng tin.
2. `ANIME_NAMED_ON_SCREEN` — tên hiện trên bảng race, caption, roster hoặc được nhân vật khác gọi dù không có voice credit riêng.
3. `ANIME_VISUAL_CONFIRMED` — character design/model xuất hiện rõ và được production/source định danh, nhưng có thể không thoại.
4. `MANGA_ONLY_OR_NOT_CONFIRMED` — có ở manga/wiki nhưng chưa đủ evidence animation.
5. `PENDING_FRAME_AUDIT` — cần xem frame/video Drive để chốt episode/exact on-screen naming.

## Cinderella Gray — media/profile pass mở rộng
Ngoài cast/credit/race-name pass trước, profile `Media Appearances` của roster chính thức được đối chiếu để bắt các cameo không nhất thiết có voice credit.

### Bổ sung mới
- **Bamboo Memory** — `ANIME_VISUAL_CONFIRMED`; profile nguồn tách rõ `Media Appearances -> Anime -> Cinderella Gray`.
- **Katsuragi Ace** — `ANIME_VISUAL_CONFIRMED`; profile nguồn tách rõ `Media Appearances -> Anime -> Cinderella Gray (Cameo)`.

Cả hai đã có profile `HIGH-DETAIL` riêng trong `cinderella-gray-profiles/`.

### False-positive guard
Một số character page/community index có thể ghi `Cinderella Gray (Cameo)` mà **không tách rõ anime/manga**, đặc biệt các nhân vật chỉ xuất hiện ở phần manga muộn/epilogue. Repo không được tự suy rằng đó là animation presence. Ví dụ các tag mơ hồ kiểu Buena Vista/Believe phải giữ pending cho tới khi có ít nhất một trong các bằng chứng: anime cast/credit, on-screen name, production asset, episode source, hoặc frame xác nhận từ video.

## TV Season 3 — episode/background pass
Cast table riêng của S3 không đủ để cover toàn bộ background/cameo, nên đã đối chiếu episode lists và Media Appearances.

### Bổ sung đã xác nhận
- **Nishino Flower** — `ANIME_VISUAL_CONFIRMED`; profile source ghi rõ `Season 3 (Cameo)`.
- **Wonder Acute** — `ANIME_VISUAL_CONFIRMED`; episode 6 `Diamond` liệt kê trong Background Characters.
- **Hokko Tarumae** — `ANIME_VISUAL_CONFIRMED`; Season 3 opening và episode 6 `Diamond` background.
- **Sakura Laurel** — `ANIME_VISUAL_CONFIRMED`; cameo trong montage các Tenno Sho Spring winner ở episode 9.
- **It's Calling** — `ANIME_NAMED_ON_SCREEN / race participant`; episode 13 final Arima, về nhì sau Kitasan Black và đứng center-side trong Winning Live top 3. Voice không được credit riêng; game cũng có NPC cùng tên.

### Spelling/alias đã kiểm tra
- **Genjitsu Steal** là spelling English mà master Umamusume Wiki hiện dùng; một số Fandom/secondary page viết `Genjitsu Steel`. Repo giữ `Genjitsu Steal` và ghi alias, không tạo duplicate.
- **To-Car** là tên English của nhân vật; **Tsuukaa** là romaji của `ツウカア`. Đây là cùng một nhân vật, không phải hai profile.

## Beginning of a New Era — cameo pass
Cast chính/credit đã được cover từ trước. Cross-animation cameo pass bổ sung:
- Neo Universe
- Sweep Tosho
- Daiichi Ruby
- K.S.Miracle
- Yamanin Zephyr
- Air Messiah
- Zenno Rob Roy
- Hishi Miracle

Các nhân vật trên có profile riêng ở `rttt-boane-profiles/`. BOANE vẫn cần frame audit trực tiếp để bắt race-card/campus extras không thoại.

## Umayon — 24 tập
Episode character-list pass đã chạy; missing profile đáng chú ý phát hiện được là **Biko Pegasus** ở tập 8. Do Umayon có rất nhiều visual cameo, frame-level audit vẫn còn mở.

## Umayuru — 24 tập
Episode/character-list pass đã chạy; **Nakayama Festa** ở tập 20 là missing profile được phát hiện. Zenno Rob Roy có cameo dạng chip mahjong và đã có profile.

## Umayuru: Pretty Gray — 4 tập, 2025
Official Cygames portal xác nhận đây là spin-off anime chính thức, phát hành 30/04–06/05/2025. Vì yêu cầu repo bao phủ named animation characters, series này được đưa vào scope dù không nằm trong corpus Drive gốc.

Cast đã đối chiếu đủ 4 tập. Các tên chưa có profile trước pass này:
- **Chrono Genesis** — main/Gray Week cast; trọng tâm tập 4.
- **Mejiro Bright** — tập 2.
- **No Reason** — tập 3.
- **Gran Alegria** — tập 4.
- **Loves Only You** — tập 4.

Các cast còn lại như Oguri Cap, Gold Ship, Mejiro McQueen, Seiun Sky, Tamamo Cross, Biwa Hayahide, Curren Chan, Hishi Miracle, Winning Ticket, Narita Taishin, King Halo, Tsurumaru Tsuyoshi, Tanino Gimlet... đã có profile từ các nhóm trước.

## Cinderella Gray — cast/credit pass trước đó
Credit/name-confirmed bổ sung ở các pass gần nhất:
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
- Cast/episode-character-list/cameo-source audit hiện đạt **186 profile**.
- **Race-card/on-screen text/cameo frame audit vẫn phải tiếp tục trực tiếp trên video Google Drive**, đặc biệt BOANE, S1–S3 race scenes và Cinderella Gray race fields có runner không thoại.
- Không được tuyên bố “100% mọi named frame đã cover” cho tới khi từng episode/movie được đánh dấu frame-audited.
