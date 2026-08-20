# Audit tên nhân vật xuất hiện trong Animation

## Mục tiêu
Repo phải có **một Markdown riêng cho mọi nhân vật có tên ổn định xuất hiện/được gọi tên/được credit trong animation thuộc phạm vi**: TV S1–S3, 1st Anniversary, ROAD TO THE TOP, Beginning of a New Era, Umayon, Umayuru và Cinderella Gray.

`Có profile` không đồng nghĩa mọi field đều có dữ liệu. Nếu source đã được kiểm tra mà không nói, ghi `UNSPECIFIED`; không được để `NOT_YET_NORMALIZED` như một cách né research.

## Các loại evidence
1. `ANIME_CREDIT_CONFIRMED` — tên nằm trong cast/credit hoặc source phát sóng đáng tin.
2. `ANIME_NAMED_ON_SCREEN` — tên hiện trên bảng race, caption, roster hoặc được nhân vật khác gọi dù không có voice credit riêng.
3. `ANIME_VISUAL_CONFIRMED` — character design/model xuất hiện rõ và được production/source định danh, nhưng có thể không thoại.
4. `MANGA_ONLY_OR_NOT_CONFIRMED` — có ở manga/wiki nhưng chưa đủ evidence để nói đã xuất hiện trong anime.
5. `PENDING_FRAME_AUDIT` — cần xem frame/video Drive để chốt episode/exact on-screen naming.

## Cross-check cast-list các adaptation

### TV Season 1
Cast list chính thức/wiki adaptation đã được đối chiếu với repo. Toàn bộ **proper-named cast** trong cast list hiện đã có profile. Các vai generic không có tên riêng không được tạo file chỉ vì có seiyuu.

### TV Season 2
Cast list đã được đối chiếu. Proper-named cast đã có profile; `Butler`, `Doctor` là role generic nên không tạo character file cho tới khi có stable canonical personal name.

### TV Season 3
Cast list đã được đối chiếu. Proper-named cast hiện đã có profile.

### 1st Anniversary Special Animation
Danh sách nhân vật đã được đối chiếu; Kitasan Black, Satono Diamond, Cheval Grand, Satono Crown, Spica/Canopus cast, Aston Machan, Sakura Bakushin O, Trainer, Tazuna và Yayoi đều đã có profile.

### ROAD TO THE TOP
Cast list đã được đối chiếu; Narita Top Road, Admire Vega, T.M. Opera O, Meisho Doto, Rice Shower, Haru Urara, Curren Chan, Special Week, King Halo, Seiun Sky, Oguri Cap và Trainer Okita đều đã có profile.

### Beginning of a New Era
Main credited cast Jungle Pocket, Agnes Tachyon, Manhattan Cafe, Dantsu Flame, T.M. Opera O, Fuji Kiseki, Narita Top Road, Meisho Doto, Trainer Tanabe, Ru, Shima, Mai và Nana Izumoto đã có profile. Cameo/on-screen-name audit vẫn phải tiếp tục bằng frame/video vì movie có nhiều background/cameo hơn credited cast.

### Umayon
Cast list 24 tập đã được đối chiếu; proper-named cast trong list đã có profile. Đây chưa thay thế visual audit từng tập vì một số nhân vật có thể xuất hiện mà không nằm ở main cast table.

### Umayuru
Cast list đã được đối chiếu. `Innkeeper Hostess`, `Innkeeper Host`, `Narrator` là role generic; các Uma/human có proper name trong credited cast đã có profile.

## Kết quả pass 2026-08-21 — Cinderella Gray

### Anime credit/name confirmed mới bổ sung
- Nanto Ichiban — tập 1
- Sekai Touha — tập 2
- Walk Dancer — tập 2
- Yamano Thousand — tập 14
- Spring Thing — tập 14
- Face No More — tập 23
- Romance Bubbly — tập 23
- Fuyuno Nakasumi — tập 23
- **Ai-chan — tập 10; named civilian đi cùng Sensuke Fujii**
- Yuichi Iwao — trainer, tập 1–3
- Igawa — race analyst, tập 7/12/17
- Shihandai — trainer của Yaeno Muteki, nhiều tập
- Tadashi Kouchi — trainer của Dicta Striker, tập 20–21
- Ryuko Yusuhara — trainer Oi của Inari One, tập 23
- Taro Yusuhara — trainer Central của Inari One, tập 23
- Frank McMonahan / Obey Your Master's Trainer — anime credit xác nhận trainer; tên riêng đến từ manga/source ecosystem

### Anime visual/race-name confirmed nhưng không có voice credit riêng
- Massive Viking
- Top Shunbetsu
- Long Live Free

### Không được tự kéo toàn bộ manga cast vào anime baseline
Các tên trong master Cinderella Gray wiki category như Bethe Sugar, Bright Rock, Carrie's Room, Clarizza, Dynamu Painter, Eve Binti, Folkqueen, Joy Maker, Miss Armagnac, Okan Maker, Royal Cherry... **không tự động là anime character**. Chỉ thêm khi có cast, on-screen name, production asset hoặc frame evidence.

## Generic roles bị loại khỏi character profile coverage
`Teacher`, `Reporter`, `Doctor`, `Audience Member`, `Head Chef`, `Chairman`, `Vice-Chairman`, `Maintenance Staff`, `Innkeeper Host/Hostess`, `Narrator`... chỉ là role generic nếu không có stable canonical personal name. Nếu source về sau đặt proper name, phải tạo profile.

## Vấn đề wiki stale
Một số wiki page cũ vẫn viết “manga only” dù anime đã credit nhân vật. Khi có xung đột như Walk Dancer, Sekai Touha, Face No More, Romance Bubbly, Fuyuno Nakasumi, **anime cast source mới hơn thắng cho câu hỏi animation presence**.

## Audit chưa hoàn thành tuyệt đối
- Cast-credit audit của các adaptation chính ở trên đã được đối chiếu.
- **Race-card/on-screen text/cameo audit vẫn phải tiếp tục trên video Google Drive** để bắt runner hoặc nhân vật có tên nhưng không có voice credit.
- Không được tuyên bố “100% mọi named frame đã cover” cho tới khi từng tập/movie đã được đánh dấu frame-audited.
