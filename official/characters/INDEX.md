# Chỉ mục hồ sơ nhân vật Animation

## Mục tiêu
Mỗi nhân vật có **tên ổn định** xuất hiện, được gọi tên, được ghi trên race card/roster/caption hoặc được credit trong animation thuộc phạm vi repo phải có **một file Markdown riêng**.

**Baseline đã chuẩn hóa hiện tại: 186 profile, gồm 117 profile `HIGH-DETAIL`.** Đây là độ phủ đã xác minh tới pass 2026-08-21; **không phải tuyên bố đã audit 100% từng frame của toàn bộ video Google Drive**.

`Gentildonna` là benchmark profile giàu dữ liệu: [season3-profiles/gentildonna.md](season3-profiles/gentildonna.md).

Audit ledger: [ANIMATION_NAME_AUDIT.md](ANIMATION_NAME_AUDIT.md).

## Cấu trúc thư mục

| Nhóm | Số profile hiện tại | Thư mục |
|---|---:|---|
| Core | 20 | [core-profiles/](core-profiles/) |
| TV supporting / anime-exclusive | 33 | [tv-supporting-profiles/](tv-supporting-profiles/) |
| Season 3 / later anime | 24 | [season3-profiles/](season3-profiles/) |
| RTTT / Beginning of a New Era | 19 | [rttt-boane-profiles/](rttt-boane-profiles/) |
| Umayuru / Umayon / Umayuru: Pretty Gray / shorts | 22 | [shorts-profiles/](shorts-profiles/) |
| Cinderella Gray | 38 | [cinderella-gray-profiles/](cinderella-gray-profiles/) |
| Trainer / staff / officials / media / named humans | 30 | [staff-human-profiles/](staff-human-profiles/) |
| **Tổng** | **186** | |

Mỗi file trong các thư mục trên là **một nhân vật**, không quay lại mô hình một Markdown nhồi nhiều character.

## Các bổ sung gần nhất từ animation audit

### Cinderella Gray media/profile pass
- [Bamboo Memory](cinderella-gray-profiles/bamboo-memory.md) — profile nguồn xác nhận `Anime -> Cinderella Gray`; hồ sơ được chuẩn hóa `HIGH-DETAIL`.
- [Katsuragi Ace](cinderella-gray-profiles/katsuragi-ace.md) — profile nguồn xác nhận `Anime -> Cinderella Gray (Cameo)`; hồ sơ được chuẩn hóa `HIGH-DETAIL`.

**Không tự động kéo nhân vật chỉ có tag `Cinderella Gray (Cameo)` mơ hồ từ manga/epilogue vào animation baseline.** Nếu source không tách medium rõ hoặc anime chưa tới phần truyện đó, giữ ở trạng thái pending cho tới khi có cast/on-screen/production evidence.

### Season 3 episode/background pass
- [Nishino Flower](season3-profiles/nishino-flower.md) — S3 cameo.
- [Wonder Acute](season3-profiles/wonder-acute.md) — background có tên ở tập 6 `Diamond`.
- [Hokko Tarumae](season3-profiles/hokko-tarumae.md) — opening + background có tên ở tập 6.
- [Sakura Laurel](season3-profiles/sakura-laurel.md) — cameo montage Tenno Sho Spring ở tập 9.
- [It's Calling](season3-profiles/its-calling.md) — runner về nhì + Winning Live ở final Arima, tập 13.

### Umayuru: Pretty Gray pass
Official portal xác nhận đây là spin-off anime 4 tập năm 2025, vì vậy được đưa vào animation scope. Năm profile mới:
- [Chrono Genesis](shorts-profiles/chrono-genesis.md)
- [Mejiro Bright](shorts-profiles/mejiro-bright.md)
- [No Reason](shorts-profiles/no-reason.md)
- [Gran Alegria](shorts-profiles/gran-alegria.md)
- [Loves Only You](shorts-profiles/loves-only-you.md)

Các cast còn lại của 4 tập đã có profile từ các pass trước.

### BOANE / cross-animation cameo pass trước đó
Neo Universe, Sweep Tosho, Daiichi Ruby, K.S.Miracle, Yamanin Zephyr, Air Messiah, Zenno Rob Roy và Hishi Miracle đã được bổ sung vào `rttt-boane-profiles/`.

## Quy tắc độ phủ
- Không cần có thoại mới được tính: proper name trên race card/roster hoặc production asset vẫn có thể đủ evidence.
- Generic role như `Reporter`, `Doctor`, `Teacher`, `Audience Member`, `Head Chef`... không tạo profile nếu không có stable canonical name.
- `UNSPECIFIED` = đã kiểm tra nguồn nhưng nguồn không nói.
- `TBD` = fanfic chưa quyết định.
- `SOURCE-LIMITED` = đã bóc hết dữ kiện tìm được nhưng nguồn công bố quá mỏng để đạt high-detail.
- Manga-only character không tự động được kéo vào anime baseline. Phải có evidence animation.
