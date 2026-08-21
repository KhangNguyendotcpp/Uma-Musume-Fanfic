# Chỉ mục hồ sơ nhân vật Animation

## Mục tiêu
Mỗi nhân vật có **tên ổn định** xuất hiện, được gọi tên, được ghi trên race card/roster/caption hoặc được credit trong animation thuộc phạm vi repo phải có **một file Markdown riêng**.

**Baseline đã chuẩn hóa hiện tại: 173 profile.** Đây là độ phủ đã xác minh tới pass 2026-08-21; **không phải tuyên bố đã audit 100% từng frame của toàn bộ video Google Drive**.

`Gentildonna` là benchmark profile giàu dữ liệu: [season3-profiles/gentildonna.md](season3-profiles/gentildonna.md).

Audit ledger: [ANIMATION_NAME_AUDIT.md](ANIMATION_NAME_AUDIT.md).

## Cấu trúc thư mục

| Nhóm | Số profile hiện tại | Thư mục |
|---|---:|---|
| Core | 20 | [core-profiles/](core-profiles/) |
| TV supporting / anime-exclusive | 33 | [tv-supporting-profiles/](tv-supporting-profiles/) |
| Season 3 / later anime | 19 | [season3-profiles/](season3-profiles/) |
| RTTT / Beginning of a New Era | 18 | [rttt-boane-profiles/](rttt-boane-profiles/) |
| Umayuru / Umayon / shorts | 17 | [shorts-profiles/](shorts-profiles/) |
| Cinderella Gray | 36 | [cinderella-gray-profiles/](cinderella-gray-profiles/) |
| Trainer / staff / officials / media / named humans | 30 | [staff-human-profiles/](staff-human-profiles/) |
| **Tổng** | **173** | |

Mỗi file trong các thư mục trên là **một nhân vật**, không quay lại mô hình một Markdown nhồi nhiều character.

## Các bổ sung gần nhất từ animation/cameo audit

### Beginning of a New Era / cross-animation cameo pass
- [Neo Universe](rttt-boane-profiles/neo-universe.md) — cameo ở RTTT, Season 3 và BOANE.
- [Sweep Tosho](rttt-boane-profiles/sweep-tosho.md) — background cameo BOANE.
- [Daiichi Ruby](rttt-boane-profiles/daiichi-ruby.md) — background Season 3 và BOANE opening/campus.
- [K.S.Miracle](rttt-boane-profiles/k-s-miracle.md) — background campus BOANE.
- [Yamanin Zephyr](rttt-boane-profiles/yamanin-zephyr.md) — background campus BOANE.
- [Air Messiah](rttt-boane-profiles/air-messiah.md) — cameo BOANE.
- [Zenno Rob Roy](rttt-boane-profiles/zenno-rob-roy.md) — cameo Season 2, BOANE và Umayuru.

### Episode-level pass trước đó
- **Biko Pegasus** — bị cast-table baseline bỏ sót nhưng xuất hiện trong Umayon tập 8.
- **Nakayama Festa** — xuất hiện trong Umayuru tập 20 và cameo Season 3.
- **Ai-chan** — named civilian ở Cinderella Gray tập 10.
- Cùng các racer/trainer CG được ghi trong `ANIMATION_NAME_AUDIT.md`.

## Quy tắc độ phủ

- Không cần có thoại mới được tính: proper name trên race card/roster hoặc production asset vẫn có thể đủ evidence.
- Generic role như `Reporter`, `Doctor`, `Teacher`, `Audience Member`, `Head Chef`... không tạo profile nếu không có stable canonical name.
- `UNSPECIFIED` = đã kiểm tra nguồn nhưng nguồn không nói.
- `TBD` = fanfic chưa quyết định.
- `NOT_YET_NORMALIZED` không phải trạng thái đích cho character database; nếu còn gặp trong một profile nhân vật thì phải tiếp tục research hoặc đổi thành `UNSPECIFIED` khi đã xác nhận source im lặng.
- Manga-only character không tự động được kéo vào anime baseline. Phải có evidence animation.
