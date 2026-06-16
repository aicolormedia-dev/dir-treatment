---
name: treatment
description: >
  Kiến trúc & dựng HỒ SƠ TREATMENT đạo diễn ColorMedia (v1.3 — generate-first).
  Nhận kịch bản/brief đã chốt → dựng treatment theo Nguyên lý 3 Điểm Chạm (Thị giác
  – Thính giác – Trái tim), bẻ shot + storyboard, rồi CHỦ ĐỘNG TẠO ASSET THẬT: ảnh
  reference/keyvisual/storyboard bằng ChatGPT Image 2 (qua Claude-in-Chrome), reference
  góc máy/chuyển động máy/Color Palette (WebSearch + Chrome), nhạc theo Mood&Tone (Suno),
  rồi RÁP THẲNG vào 1 file Canva (Canva MCP) + 1 file PPTX (pptxgenjs) — người dùng chỉ
  QC & update. DÙNG SKILL NÀY khi người dùng: "làm treatment", "dựng treatment đạo diễn",
  "director treatment", "treatment TVC / phim doanh nghiệp / brand film", "proposal có
  storyboard", "đóng gói kịch bản đã chốt thành hồ sơ hình ảnh gửi khách", "tạo treatment
  cho dự án này", hoặc đưa brief/kịch bản kèm yêu cầu dựng storyboard / mood & tone /
  keyvisual / color palette phim / nhịp dựng / nhạc phim cho treatment. Không dùng để:
  viết kịch bản mới (→ corporate-scriptwriting), tìm insight (→ insight-first), hay QC
  video đã quay (→ videoqc-os).
---

# TREATMENT ARCHITECTURE — Orchestrator (v1.3, generate-first)

Skill này gói trọn quy trình dựng **hồ sơ Treatment đạo diễn** của ColorMedia và **thêm
lớp tự động tạo asset**: từ kịch bản đã chốt → ra 1 file Canva + 1 file PPTX gần hoàn
chỉnh, người dùng chỉ **QC & update**.

> **Câu chốt:** Khách không mua kịch bản — khách mua *niềm tin rằng phim sẽ ra đúng như
> họ hình dung*. Treatment bán niềm tin đó bằng cái khách **THẤY, NGHE và CẢM**.

**Đặc tả đầy đủ ở `references/treatment_architecture_v1_3.md`** — ĐỌC FILE ĐÓ TRƯỚC KHI
LÀM (ma trận section × tầng, chi tiết từng khối craft, công thức prompt, template
pptxgenjs, QC checklist, chunks). SKILL.md này chỉ là bản vận hành rút gọn.

## Ranh giới trung thực (đọc trước, KHÔNG được vi phạm)

- **KHÔNG bịa** insight / big idea / credentials / số liệu / giải thưởng. Thiếu → DỪNG,
  hỏi; hoặc để placeholder field. Insight/Big Idea kéo từ `insight-first` + kịch bản đã
  chốt, không tự sinh.
- Asset tự tạo (ảnh ChatGPT Image 2, nhạc Suno) là **bản định hướng** — dán nhãn
  *"AI-generated — chờ QC"* (ảnh) và *"nhạc demo định hướng"* (Suno). **Không tuyên bố**
  là cảnh quay/sản phẩm thật. Reference đi mượn phải **ghi nguồn** + nhãn "REFERENCE".
- Stillomatic/animatic giữ **disclaimer**: "bản dựng chỉ mang tính hình dung không khí
  & tiết tấu, chưa phải hình quay thực tế".
- Mọi giả định (màu suy ra, ref suy ra) đánh cờ "đề xuất, chờ duyệt".

## Generate-first + Fallback (cốt lõi v1.3)

Agent **chủ động tạo asset thật** khi động cơ sẵn; khi không sẵn/thất bại → **fallback**
về cơ chế placeholder + prompt ẩn + field/QR (v1.2) và **báo rõ** asset nào auto, asset
nào người dùng tự làm. Tiền điều kiện từng động cơ:

| Asset | Công cụ | Cần có | Fallback |
|---|---|---|---|
| Ảnh reference/keyvisual/storyboard | ChatGPT Image 2 qua **Claude-in-Chrome** | Extension kết nối + tab ChatGPT (Plus, Image 2) đăng nhập | prompt ẩn + placeholder |
| Reference góc máy/chuyển động/palette | **WebSearch + WebFetch + Chrome** | Mạng | field link + QR |
| Nhạc | **Suno** qua Claude-in-Chrome | tab Suno đăng nhập | mô tả hướng + field track |
| File Canva | **Canva MCP** | MCP Canva uỷ quyền | outline spec để paste |
| File PPTX | **pptxgenjs** | — | luôn dựng được |

## Khởi tạo (hỏi gọn trước khi làm)

1. Loại job & thời lượng? → suy **TẦNG**: T1 Lite (TVC ngắn) / T2 Full Film (phim DN dài) /
   T3 Strategy Proposal (pitch dẫn bằng chiến lược).
2. Kịch bản đã chốt chưa? Dán KB/voice-off. (T3) Insight & Big Idea từ insight-first? Chưa có → DỪNG.
3. Brand khách: logo + màu brand (thiếu → AI suy ra, ghi "chờ duyệt").
4. Mood & Tone + Color Palette phim (hướng grading)? — **bắt buộc chốt TRƯỚC khi gen ảnh/nhạc.**
5. Âm nhạc: thể loại/tempo/mood? CGI có không? Nhịp dựng theo act? Đạo diễn/DOP ai cầm (showreel)?
6. **Động cơ tự động:** Claude-in-Chrome kết nối chưa? ChatGPT Plus + Suno đăng nhập chưa?
   Canva MCP sẵn chưa? → chốt AUTO/FALLBACK từng asset.
7. **Scope ảnh** (mặc định: Reference + Keyvisual + storyboard *chọn lọc*) — báo số ảnh & số
   bài nhạc dự kiến để duyệt chi phí trước khi gen hàng loạt.
8. Output: mặc định xuất **KÉP (Canva + PPTX)**.

## Quy trình 12 bước (không nhảy bước; text trước, gen sau, ráp cuối)

1. Xác định tầng. 2. Kéo đầu vào (KB chốt + insight T3 + hồ sơ Đạo diễn/DOP). 3. Kiểm tra
động cơ tự động → chốt AUTO/FALLBACK. 4. Chốt palette deck & font. 5. Thiết kế **3 Điểm
Chạm** (lớp ý đồ/text): Thị giác (Keyvisual → Color Palette phim → Mood&Tone →
Cinematography → Character Design/Stylist → Set+Props → CGI → Transitions) · Thính giác
(Music&Sound → Voice/VO) · Trái tim (Emotional Core → Nhịp dựng). 6. Bẻ KB → shot (số,
dur, loại, Nội dung, VO, TEXT, Chuyển cảnh, lens + **góc nhìn Đạo diễn/DOP** per-shot).
7. **★ Động cơ ẢNH** (Reference + Keyvisual + shot chọn lọc, ChatGPT Image 2). 8. **★ Động
cơ REFERENCE** (CAM REF / CAM MOTION REF / COLOR PALETTE REF, WebSearch + Chrome, ghi
nguồn). 9. **★ Động cơ NHẠC** (Suno theo Mood&Tone + cấu trúc act). 10. Dựng storyboard
(4-up/3-up), chèn ảnh thật; ô chưa gen giữ prompt ẩn. 11. Slide nghỉ/hook + Stillomatic +
Lời cuối. 12. **★ Ráp KÉP**: file Canva (Canva MCP) + PPTX (pptxgenjs) → trả 2 link/file
+ **Bảng truy vết asset** → QC theo 3 điểm chạm.

> Chi tiết công thức prompt theo góc nhìn Đạo diễn/DOP, các động cơ, template pptxgenjs,
> QC checklist đầy đủ → đọc `references/treatment_architecture_v1_3.md` (PHẦN 6B, 7, 8).

## Đầu ra

- **Canva (file thật)** qua Canva MCP → LINK để QC/sửa trực tiếp (MCP không sửa lại sau
  khi tạo — chỉnh tiếp trong editor Canva).
- **PPTX** (pptxgenjs) — ô storyboard nhúng **ảnh thật** (`addImage`); ô chưa gen giữ
  placeholder + prompt ẩn trong speaker note.
- **Bảng truy vết asset**: tên file · loại (gen/ref/nhạc) · nguồn · prompt/truy vấn ·
  trạng thái (đã chèn / chờ QC / fallback).

## Cross-ref skill hệ sinh thái

`corporate-scriptwriting-mmcorp` (viết shot/VO) · `insight-first-mmcorp` (insight/big idea
cho T3) · `slide-architecture-mmcorp` (design + slide nghỉ + image prompt block) ·
`videoqc-os` (QC sau khi quay — đồng trục 3 điểm chạm) · `keyvisual` · `mood-tone`.
