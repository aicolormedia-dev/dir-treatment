---
title: "Skill — Treatment Architecture (Kiến Trúc Hồ Sơ Treatment Đạo Diễn)"
doc_type: skill
business_unit: ColorMedia
owner: Hoang Dung
status: production_ready
version: 1.3
last_updated: 2026-06-16
tags: [treatment, director_treatment, treatment_architecture, three_touchpoints, thi_giac_thinh_giac_trai_tim, storyboard_frame, shooting_storyboard, voice_over, reference_board, reference_video, keyvisual, color_palette, character_design, stylist, props, set_art, music, sound_design, transitions, vfx, cgi, editing_rhythm, nhip_dung, director_dop, break_slide, hook_slide, image_prompt, prompt_block, stillomatic, animatic, director_final_note, loi_cuoi, pre_production, post_production, tvc, brand_film, proposal, mood_tone, cinematography, pptxgenjs, slide_architecture, colormedia, insight_first, automation_engine, chatgpt_image_2, gpt_image, suno, claude_in_chrome, canva_mcp, auto_reference, generate_first, asset_generation, browser_automation]
access_level: public_internal
authority_level: high
source_type: interview
quality_score: 9
readiness_level: production_ready
source_summary: >
  Skill kiến trúc hồ sơ Treatment đạo diễn ColorMedia. v1.1 cấu trúc lại phần craft
  theo Nguyên lý 3 Điểm Chạm (Thị giác – Thính giác – Trái tim) để treatment & QC
  dùng chung một trục, và bổ sung 9 thành phần chuyên môn: Âm nhạc/Sound, Chuyển cảnh,
  Character Design/Stylist, Reference Video, Keyvisual, Color Palette phim, Props,
  Kỹ xảo/CGI, Nhịp dựng. Thêm trang Đạo diễn/DOP và lớp slide nghỉ/hook. Build theo
  yêu cầu trực tiếp của Hoàng Dũng (12/06/2026).
agent_trigger: >
  Kích hoạt khi người dùng yêu cầu: làm treatment, dựng treatment đạo diễn,
  director treatment, treatment TVC / phim doanh nghiệp / brand film, proposal
  có storyboard, đóng gói kịch bản đã chốt thành hồ sơ hình ảnh gửi khách,
  khung storyboard, shooting board, reference board, mood & tone, keyvisual,
  color palette phim, nhịp dựng, character design, nhạc phim cho treatment.
initialization_required: true
cross_ref:
  - skill_slide_architecture_v2_6.md
  - skill_storyboard_visual_direction_v1.md
  - skill_qc_3_touchpoints_v2.md
  - skill_keyvisual_colormedia_v1.md
  - skill_insight_first_v3.md
  - skill_mood_tone_v1.md
  - skill_set-design-art-direction.md
  - skill_corporate_film_2_v1_4.md
  - colormedia_contact_info.md
  - hoang_dung_trainer_profile_v1.md
changelog: >
  v1.3 — CHUYỂN SKILL TỪ THỦ CÔNG SANG CHỦ ĐỘNG TẠO ASSET (GENERATE-FIRST). Bổ sung
  PHẦN 6B — ĐỘNG CƠ TỰ ĐỘNG (Automation Engine): (A) tạo ảnh REFERENCE + KEYVISUAL +
  shot storyboard chọn lọc bằng ChatGPT Image 2 qua Claude-in-Chrome, prompt soạn theo
  GÓC NHÌN ĐẠO DIỄN & DOP (shot size, góc máy, lens, chuyển động máy, ánh sáng, grading
  từ Color Palette phim); (B) chủ động tìm & insert Reference góc máy / chuyển động máy /
  Color Palette bằng WebSearch + Chrome; (C) chủ động tạo NHẠC bằng Suno qua Claude-in-Chrome
  theo Mood & Tone + cấu trúc act; (D) ráp FILE CANVA THẬT qua Canva MCP (upload asset →
  generate-design → export); (E) ráp PPTX nhúng ảnh/nhạc thật (không còn placeholder rỗng).
  Cập nhật triết lý minh bạch (Generate-first + fallback v1.2), Workflow, Output, QC,
  Agent Init, thêm chunk_08 & chunk_09. Giữ nguyên 3 Điểm Chạm và luật chống-bịa.
  ---PREVIOUS---
  v1.2 — Bổ sung: (a) PROMPT ẨN per-shot trong speaker note mỗi trang storyboard —
  người dùng copy để tạo ảnh storyboard theo ý (công thức 6 thành phần, tự soạn từ
  Nội dung + Mood + Color Palette phim + loại shot). (b) Slide STILLOMATIC / ANIMATIC
  MOCKUP (khung player + disclaimer + link/QR). (c) Trang LỜI CUỐI (Director's Final
  Note) — tổng hợp mong muốn quan trọng của đạo diễn cho team tiền kỳ & hậu kỳ.
  Cập nhật ma trận, workflow, QC, Agent Init, chunk_07.
  v1.1 — CẤU TRÚC LẠI PHẦN CRAFT THEO 3 ĐIỂM CHẠM (Thị giác – Thính giác – Trái tim),
  đồng trục với skill_qc_3_touchpoints (treatment thiết kế cái gì → QC kiểm đúng cái đó).
  Bổ sung 9 thành phần: (1) Âm nhạc & Sound Design + (2) Voice/VO direction trong Thính giác;
  (3) Chuyển cảnh/Transitions, (4) Character Design & Stylist, (5) Keyvisual, (6) Color Palette
  của phim, (7) Props trong Set/Location, (8) Kỹ xảo/CGI trong Thị giác; (9) Nhịp dựng (Editing
  Rhythm) trong Trái tim. Thêm: hệ Reference Video per-section (placeholder + link), trang
  Đạo diễn/DOP (tăng thuyết phục), lớp Slide Nghỉ/Hook (Quote / Keyvisual full-bleed / Divider).
  Cập nhật ma trận section, workflow, QC, Agent Init, chunks.
  v1.0 — Bản đầu. 3 tầng Treatment, hệ khung Storyboard 3 làn (2 layout), placeholder đánh số,
  template pptxgenjs, luật áp design Slide Arch.
---

# SKILL: TREATMENT ARCHITECTURE — KIẾN TRÚC HỒ SƠ TREATMENT ĐẠO DIỄN (v1.3)

> **Phạm vi:** Director, DOP, Creative Lead, Account, AI Director Agent.
> **Câu chốt:** Khách không mua kịch bản — khách mua *niềm tin rằng phim sẽ ra đúng như họ hình dung*. Treatment bán niềm tin đó bằng cái khách THẤY, NGHE và CẢM.
> **★ v1.3 — GENERATE-FIRST:** Skill không còn dừng ở placeholder + prompt ẩn. Agent **chủ động tạo asset thật** — ảnh reference & keyvisual & storyboard (ChatGPT Image 2), reference góc máy/chuyển động máy/Color Palette (WebSearch + Chrome), nhạc theo Mood&Tone (Suno) — rồi **ráp thẳng vào 1 file Canva + 1 file PPTX**. Người dùng chỉ **QC & update**. Khi automation không sẵn/thất bại → fallback về cơ chế placeholder + prompt ẩn của v1.2 (không bao giờ bịa asset).

---

## PHẦN 0 — VẤN ĐỀ CẦN GIẢI QUYẾT

**Treatment làm sai thường mắc:**
- Đổ chữ kín slide, không nhịp nghỉ — khách đọc mệt, không "thấy" được phim.
- Craft rời rạc: liệt kê Mood, Cinematography… như danh sách, không gom theo cái khách cảm nhận.
- **Thiếu hẳn các tầng nghề:** không có Âm nhạc, Color Palette phim, Kỹ xảo/CGI, Nhịp dựng, Chuyển cảnh, Character Design/Stylist, Props, Reference Video — những thứ quyết định phim hay/dở.
- Storyboard mỗi người một kiểu, không khung chuẩn.
- Áp đại 1 bộ màu cho mọi dự án; bịa insight/big idea.
- Không có trang Đạo diễn/DOP → khách thiếu cơ sở tin ekip làm được.

**Mục tiêu skill (v1.1):** dựng hồ sơ Treatment đạt 6 tiêu chí:
1. **Đúng tầng** (TVC / phim dài / proposal chiến lược).
2. **Có nhịp** — xen slide nghỉ/hook, không đổ chữ.
3. **Đủ tầng nghề** — Thị giác + Thính giác + Trái tim đều được thiết kế.
4. **Đồng trục với QC** — treatment thiết kế gì, nghiệm thu kiểm đúng cái đó.
5. **Bám brand khách** — palette deck từ thương hiệu + mood phim.
6. **Đáng tin** — Reference, Storyboard, trang Đạo diễn/DOP khiến khách tin ekip làm được.

> **Ranh giới:** Skill này lo KIẾN TRÚC TÀI LIỆU + KHUNG STORYBOARD. Ngôn ngữ viết shot → `skill_storyboard_visual_direction_v1`. Insight/Big Idea → `skill_insight_first_v3` + kịch bản đã chốt (KHÔNG tự sinh). Phương pháp design/màu/font/slide nghỉ → `skill_slide_architecture_v2_6`. Keyvisual → `skill_keyvisual_colormedia_v1`. Trục QC → `skill_qc_3_touchpoints_v2`.

---

## PHẦN 1 — 3 TẦNG TREATMENT (chọn đúng trước)

| Tầng | Khi dùng | Bản chất | Mẫu |
|---|---|---|---|
| **T1 — Lite** | TVC ngắn, KB chốt, dựng nhanh | Thực thi hình thuần | Niku-Ichi |
| **T2 — Full Film** | Phim DN/brand film dài, craft sâu | Craft đầy đủ theo 3 điểm chạm | MB Life |
| **T3 — Strategy Proposal** | Pitch dẫn dắt bằng chiến lược | Chiến lược → craft → storyboard đa version | Cebraton |

Luật: KB chốt + job nhỏ→T1; phim dài→T2; cần thuyết phục bằng insight→T3. T3 kéo Insight/Big Idea từ `skill_insight_first_v3` + kịch bản sáng tạo — không bịa.

---

## PHẦN 2 — KIẾN TRÚC THEO 3 ĐIỂM CHẠM (CỐT LÕI v1.1)

### 2.1 — Vì sao gom craft theo 3 điểm chạm
ColorMedia QC phim theo **Nguyên lý 3 Điểm Chạm: Thị giác (Visual) – Thính giác (Aural) – Trái tim (Heart)** (`skill_qc_3_touchpoints_v2`). Khi Treatment cũng gom phần craft theo đúng 3 trục này thì:
- Khách cảm nhận tài liệu theo cách họ sẽ cảm nhận phim (Thấy → Nghe → Cảm).
- **Đồng trục Treatment ↔ QC:** thứ đạo diễn thiết kế ở đây chính là thứ nghiệm thu kiểm sau. Không lệch pha.
- Không bỏ sót tầng nghề: mỗi điểm chạm là một checklist các thành phần bắt buộc.

### 2.2 — Bộ xương Treatment v1.1

```
── FRONT MATTER ──
[A] COVER
[B] OVERVIEW            (+ Strategy block cho T3)
[C] DIRECTOR'S STATEMENT
[D] CREATIVE FOUNDATION (1 core theme)
[E] ĐẠO DIỄN / DOP      ★ MỚI — credentials + showreel (tăng thuyết phục)
   » slide nghỉ/hook (Quote core message)

── 3 ĐIỂM CHẠM (CRAFT DESIGN) ──
[TC1] THỊ GIÁC (VISUAL)
      • Keyvisual ★ • Color Palette phim ★ • Mood & Tone
      • Cinematography • Character Design & Stylist ★
      • Set / Location + Props ★ • Kỹ xảo & CGI ★ • Chuyển cảnh ★
   » slide nghỉ/hook (Keyvisual full-bleed)
[TC2] THÍNH GIÁC (AURAL)
      • Âm nhạc & Sound Design ★ • Voice / VO Direction ★
[TC3] TRÁI TIM (HEART)
      • Emotional Core (mạch cảm xúc) • Nhịp dựng / Editing Rhythm ★
   » slide nghỉ/hook (Quote manifesto)

── EXECUTION ──
[F] BREAKDOWN + STORYBOARD   (3 Act / tuyến tính — PHẦN 4)
      › prompt ẩn per-shot trong speaker note (copy để tạo ảnh) ★v1.2
[G] STILLOMATIC (nếu có)      ★v1.2 — mockup player animatic + disclaimer
[H] LỜI CUỐI                  ★v1.2 — Director's Final Note: mong muốn cho tiền kỳ & hậu kỳ

── CLOSING ──
[Z] THANK YOU + credit ColorMedia + contact
```
★ = thành phần bổ sung v1.1. » = vị trí khuyến nghị chèn slide nghỉ/hook.

> **Lưu ý thiết kế (cần duyệt/override):** 3 điểm chạm tổ chức **lớp craft (ý đồ)**. **Storyboard giữ tuyến tính theo Act** vì đó là lớp thực thi tuần tự — không bẻ storyboard theo điểm chạm. Reference Video gắn vào từng khối craft tương ứng (PHẦN 3E).

### 2.3 — Ma trận section × tầng

| Khối | Section | T1 | T2 | T3 |
|---|---|:--:|:--:|:--:|
| Front | Cover · Overview | ✅ | ✅ | ✅ |
| Front | Strategy block (từ Insight First) | — | tuỳ | ✅ |
| Front | Director's Statement | tuỳ | ✅ | tuỳ |
| Front | Creative Foundation | — | ✅ | tuỳ |
| Front | **Đạo diễn / DOP** | tuỳ | ✅ | ✅ |
| TC1 Thị giác | **Keyvisual** | tuỳ | ✅ | ✅ |
| TC1 | **Color Palette phim** | tuỳ | ✅ | tuỳ |
| TC1 | Mood & Tone | ✅ | ✅ | ✅ |
| TC1 | Cinematography | ✅ | ✅ | tuỳ |
| TC1 | **Character Design & Stylist** | tuỳ | ✅ | tuỳ |
| TC1 | Set/Location + **Props** | ✅ | ✅ | tuỳ |
| TC1 | **Kỹ xảo & CGI** | tuỳ | ✅ | tuỳ |
| TC1 | **Chuyển cảnh** | tuỳ | ✅ | tuỳ |
| TC2 Thính giác | **Âm nhạc & Sound Design** | ✅ | ✅ | ✅ |
| TC2 | **Voice / VO Direction** | ✅ | ✅ | ✅ |
| TC3 Trái tim | Emotional Core | tuỳ | ✅ | tuỳ |
| TC3 | **Nhịp dựng (Editing Rhythm)** | tuỳ | ✅ | tuỳ |
| Exec | Storyboard | ✅ | ✅ | ✅ |
| Exec | **Prompt ẩn per-shot** (speaker note) | ✅ | ✅ | ✅ |
| Exec | **Stillomatic mockup** (nếu có) | tuỳ | tuỳ | tuỳ |
| Exec | **Lời cuối (Director's Final Note)** | tuỳ | ✅ | ✅ |
| — | **Reference Video** (gắn từng khối) | tuỳ | ✅ | tuỳ |
| — | **Slide nghỉ/Hook** | ≥1 | ≥3 | ≥3 |
| Closing | Thank You | ✅ | ✅ | ✅ |

> **Luật cứng (mọi tầng):** Cover · Overview · Mood&Tone · **Âm nhạc** · **Voice/VO** · Storyboard · Closing. (Âm nhạc + Voice lên luật cứng vì Thính giác là 1/3 trải nghiệm — thiếu là treatment khuyết.)

---

## PHẦN 3 — CHI TIẾT SECTION

### 3A — FRONT MATTER

**[A] Cover** — logo SP + client + "Presented by ColorMedia" + loại tài liệu + tháng + tên đạo diễn (Dir.). Nền bám brand SP.

**[B] Overview** — project · thời lượng (ver chính + cut-down) · tagline · mục tiêu. T3: + Client Brief table và Strategy block (Background, TA, Insight, Big Idea, USP — kéo từ Insight First, không bịa).

**[C] Director's Statement** — 1 đoạn ngôi thứ nhất: phim về điều gì sâu xa, tiếp cận bằng ngôn ngữ điện ảnh nào.

**[D] Creative Foundation** — 1 core theme + 3 góc đỡ.

**[E] ĐẠO DIỄN / DOP ★ (MỚI)** — tăng thuyết phục.
- Nội dung: chân dung · tên + vai trò (Director / DOP) · 2–3 dòng credentials (số năm, thể loại sở trường) · **showreel link/QR** · 3–6 logo dự án/thương hiệu tiêu biểu đã làm.
- Đặt ngay sau Statement (hoặc cuối deck trước Closing).
- ⚠️ KHÔNG bịa credentials/giải thưởng — lấy từ hồ sơ đạo diễn/DOP thật (`hoang_dung_trainer_profile_v1` cho Hoàng Dũng; nếu DOP khác → người dùng cung cấp). Thiếu → để placeholder field.

### 3B — ĐIỂM CHẠM 1 · THỊ GIÁC (VISUAL)

**Keyvisual ★** — 1 frame "đinh" đại diện mood + thông điệp (dùng được cho poster/thumbnail). Slide full-bleed. Áp `skill_keyvisual_colormedia_v1`. Tạo placeholder + IMAGE PROMPT BLOCK để đạo diễn tạo/chèn.

**Color Palette PHIM ★** — bảng màu **không khí & grading của phim** (khác palette thiết kế deck).
- 4–6 swatch: Hex + tên cảm xúc + vai trò (key tone / shadow / accent / skin). Ví dụ AI-tech: blue khoa học · cyan dữ liệu · vàng điểm nhấn · đen tương phản.
- Ghi rõ hướng grading (high-contrast / teal-orange / desaturate…).

**Mood & Tone** — 3–5 chip cảm xúc + 1 đoạn tone + lưới ảnh ref (placeholder). `skill_mood_tone_v1`.

**Cinematography** — lighting, camera effect, editing nhịp. T2 tách sub-concept mỗi slide. Ngôn ngữ shot → `skill_storyboard_visual_direction_v1`.

**Character Design & Stylist ★** — nâng từ casting lên thiết kế nhân vật.
- Bảng mỗi nhân vật: **Wardrobe** (trang phục, màu, chất liệu) · **Hair & Make-up** · **Grooming/đạo cụ cá nhân** · **Look note** (khí chất tổng thể) + ảnh look ref.
- Bám Color Palette phim + brand SP để wardrobe không phá tông.

**Set / Location + Props ★** — mỗi bối cảnh: paragraph + (T2) Vai trò/Ứng dụng + **danh sách Props** (set dressing · đạo cụ tay · đạo cụ đặc tả) + ảnh ref. `skill_set-design-art-direction`.

**Kỹ xảo & CGI ★** — tách khỏi Motion Graphic 2D.
- Liệt kê shot cần **3D / CGI / compositing / simulation / set-extension**, độ phức tạp (Low/Med/High), ghi chú kỹ thuật (logo 3D build, particle, sim khói, tracking).
- Cờ **"cần Previs"** cho shot phức tạp. Note: CGI nặng = rủi ro timeline/chi phí — phải nêu rõ để khách duyệt.

**Chuyển cảnh ★ (Transitions)** — hệ chuyển cảnh chủ đạo của phim.
- Loại: match cut · light swipe · morph · speed ramp · whip pan · graphic wipe · seamless dolly. Mỗi loại: vai trò + đặt ở đâu.
- Trong Storyboard, transition cụ thể ghi tại ô shot (`Chuyển cảnh: match cut → shot sau`).

### 3C — ĐIỂM CHẠM 2 · THÍNH GIÁC (AURAL)

**Âm nhạc & Sound Design ★**
- **Music:** thể loại · hướng tempo/BPM · cấu trúc theo act (build / drop / lắng / cao trào) · mood. **Reference track** (tên + link — đặt ở 3E).
- **Sound design:** SFX chủ đạo (UI sound, data whoosh, impact, riser), foley, ambience.
- **Mix:** triết lý (VO chủ đạo / nhạc nâng / sound dẫn nhịp).
- ⚠️ AI **không nghe được** link nhạc — chỉ mô tả hướng + tạo field link.

**Voice / VO Direction ★** — giọng (nam/nữ, độ tuổi, chất giọng) · tông đọc (dứt khoát / ấm / điềm tĩnh) · tiết tấu · ngôn ngữ. Casting VO ref.

### 3D — ĐIỂM CHẠM 3 · TRÁI TIM (HEART)

**Emotional Core** — 1 câu chốt cảm xúc phim muốn để lại + "khoảnh khắc nhớ mãi" (the one moment). Đồng bộ tầng Heart của QC.

**Nhịp dựng / Editing Rhythm ★** — bản đồ nhịp theo act.
- Mỗi act: nhanh/chậm · độ dài cut trung bình · điểm lặng (beat) · cao trào.
- Khuyến nghị 1 **tempo map** đơn giản (thanh nhịp theo timeline). Ví dụ: Act1 dồn (cut 0.5–2s) → Act2 vừa (interview + b-roll) → Act3 lắng → bùng (brand reveal).
- Đồng bộ với cấu trúc nhạc (3C) — nhịp hình và nhịp nhạc phải khớp.

### 3E — REFERENCE VIDEO (gắn từng khối) ★

- Mỗi khối craft (Mood, Cinematography, VFX/CGI, Music, và mỗi Act) có ô **Reference Video**: tên + **link** + 1 dòng *"lấy gì từ ref này"*.
- ⚠️ AI **không xem/nghe được** link → tạo placeholder + field link + **QR** để khách quét. Đặt trong slide hoặc speaker note.
- Quy ước: `refvid_<khối>_<##>` ghi trong note.

### 3F — SLIDE NGHỈ / HOOK

Từ `skill_slide_architecture_v2_6` PHẦN 2B. Chèn để tạo nhịp nghỉ + hook:
- **Quote slide** — 1 câu manifesto/core message full-bleed (vd "ADAPT OR LEAD?").
- **Keyvisual slide** — 1 frame mood full-bleed, ít chữ.
- **Section divider** — typo lớn mở mỗi khối (Front / Thị giác / Thính giác / Trái tim / Storyboard).
- Luật nhịp: sau mỗi **3–4 slide nặng chữ → chèn 1 slide nghỉ**.

### 3G — STILLOMATIC / ANIMATIC MOCKUP ★ (nếu có)

- 1 slide dựng **mockup khung player YouTube**: thumbnail + nút play + dòng "Watch on YouTube" + tên bản dựng + tên đạo diễn — nhúng link bản stillomatic/animatic.
- **Disclaimer bắt buộc (in rõ trên slide):** *"Bản dựng chỉ mang tính chất hình dung không khí và tiết tấu phim, chưa phải là hình quay thực tế."*
- Tạo **placeholder thumbnail + field link + QR** để khách quét xem nhịp phim.
- ⚠️ AI **không xem được** nội dung link — chỉ dựng khung + disclaimer, người dùng dán link thật.
- Vị trí: ngay sau Storyboard (cho khách "xem thử" nhịp trước khi qua Lời cuối / Closing).

### 3H — LỜI CUỐI (DIRECTOR'S FINAL NOTE) ★

> Khác Director's Statement (hướng **khách**). Lời cuối hướng **TEAM tiền kỳ & hậu kỳ** — tổng hợp những mong muốn quan trọng nhất của đạo diễn để cả ekip cùng tạo ra sản phẩm tốt nhất.

- Cấu trúc 2 cột:
  - **TIỀN KỲ (Pre-production):** casting & wardrobe phải đạt gì · set / props / đạo cụ không được thiếu · ánh sáng & máy quay ưu tiên · điều kiện bối cảnh / thời điểm quay.
  - **HẬU KỲ (Post-production):** grading bám đúng **Color Palette phim** · nhịp dựng theo **tempo map** · nhạc & sound khớp cảm xúc từng act · **VFX/CGI** ưu tiên & mức hoàn thiện · **transition signature**.
- + 1 dòng **NON-NEGOTIABLE**: điều tuyệt đối không được sai — linh hồn của phim.
- Giọng ngắn, declarative (tham chiếu `skill_hoang_dung_writing_style`). Đặt trước Closing.
- Có thể trình khách (thể hiện sự kỹ lưỡng) nhưng bản chất là **brief cho crew** — viết để team thực thi nắm đúng ý, không phải để bán.

---

## PHẦN 4 — HỆ KHUNG STORYBOARD (giữ v1.0 + bổ sung)

### 4.1 — 3 LÀN (chuẩn cứng): Shooting Storyboard / Voice Over / Reference Board.
- Làn 1 bắt buộc; Làn 2 luôn hiển thị (ô có thể trống); Làn 3 (ảnh ref) tuỳ chọn.

### 4.2 — 2 LAYOUT: **4-up** (TVC, T1/T3) · **3-up** (phim dài, T2).

### 4.3 — Giải phẫu ô shot (cập nhật): số · thời lượng · **loại** (camera/VFX/CGI/enframe/graphic/tư liệu) · ô hình (placeholder) · Nội dung · `TEXT:` · ghi chú kỹ thuật gồm **`Chuyển cảnh:`** + lens/camera move. Khi shot cần CGI → loại = `CGI` và đối chiếu mục Kỹ xảo (3B).

### 4.4 — Nhãn Reference Board: CAM REF · CAM MOTION REF · TRANSITION REF · MATCH CUT EFFECT · BACKGROUND REF · CAMERA EFFECT · FPV DRONE.

### 4.5 — Placeholder đánh số: ô hình viền nhạt, nhãn mờ `[SHOT n — hình]`; header/Nội dung/VO điền sẵn; đạo diễn kéo-thả ảnh đè. Đặt tên `sb_<##>.jpg`, `ref_<##>_<loại>.jpg` (note slide).

### 4.6 — PROMPT ẨN PER-SHOT ★ (copy để tạo ảnh storyboard)
Mỗi ô shot đính kèm **1 prompt tạo ảnh** đặt trong **speaker note** của trang storyboard (ẩn khỏi mặt slide, copy được). Người dùng copy → dán vào công cụ tạo ảnh (Higgsfield / Midjourney / Magic Media…) → tạo đúng ảnh mong muốn → chèn đè placeholder.

Công thức 6 thành phần (chuẩn `skill_slide_architecture_v2_6` chunk_12), **tự soạn từ dữ liệu shot**:
```
[SHOT n] <chủ thể + hành động (từ Nội dung)>, <bối cảnh>,
mood <chip Mood & Tone>, phong cách <style theo loại shot>,
bảng màu <hex từ Color Palette phim>, tỷ lệ 16:9,
<bố cục: chừa negative space cho chữ nếu shot có TEXT>, high detail, no watermark
```
- **Style theo loại shot:** camera → `cinematic, shallow DOF`; VFX/graphic → `motion graphic / UI`; CGI → `3D render`; tư liệu → `documentary`.
- Shot có `TEXT:` → thêm "chừa khoảng trống bố cục cho chữ on-screen".
- Ghi trong note theo `### SHOT n` để dễ tìm khi chèn.
- ⚠️ Prompt là **gợi ý** — đạo diễn chỉnh trước khi tạo. AI không tự tạo/chèn ảnh.

---

## PHẦN 5 — ÁP DESIGN (Slide Arch v2.6)

- **Palette deck = brand SP + mood phim** (KHÔNG ép Style 01 teal-vàng trừ phim chính chủ ColorMedia). ColorMedia chỉ ở credit Cover + Closing.
- Mượn: Section Divider typo lớn, typography hierarchy, font đủ dấu TV, 2 chế độ output, **lớp slide nghỉ/hook (2B)**.
- Lưu ý: **Color Palette PHIM (3B) ≠ palette thiết kế deck.** Một cái là grading phim, một cái là màu của tài liệu — đừng lẫn.

---

## PHẦN 6 — WORKFLOW 12 BƯỚC (v1.3 — generate-first)

```
1. XÁC ĐỊNH TẦNG (T1/T2/T3).
2. KÉO ĐẦU VÀO: KB chốt + (T3) Insight/Big Idea từ Insight First + hồ sơ Đạo diễn/DOP.
   Thiếu → dừng, yêu cầu. KHÔNG bịa.
3. KIỂM TRA ĐỘNG CƠ TỰ ĐỘNG (PHẦN 6B.0): Claude-in-Chrome đã kết nối? ChatGPT Plus +
   Suno đã đăng nhập? Canva MCP sẵn? → chốt chế độ AUTO hay FALLBACK cho từng loại asset.
4. CHỐT PALETTE DECK & FONT (brand SP + mood) — ghi rõ màu suy ra.
5. THIẾT KẾ 3 ĐIỂM CHẠM (lớp ý đồ — text trước, asset sau):
   · THỊ GIÁC: Keyvisual → Color Palette phim → Mood&Tone → Cinematography
     → Character Design/Stylist → Set+Props → CGI → Transitions
   · THÍNH GIÁC: Music & Sound → Voice/VO
   · TRÁI TIM: Emotional Core → Nhịp dựng
6. BẺ KỊCH BẢN → SHOT: số, thời lượng, loại, Nội dung, VO, TEXT, Chuyển cảnh, lens,
   + GÓC NHÌN ĐẠO DIỄN/DOP per-shot (shot size, góc máy, chuyển động, ánh sáng).
7. ★ CHẠY ĐỘNG CƠ ẢNH (PHẦN 6B.A): tạo Reference + Keyvisual + shot storyboard chọn lọc
   bằng ChatGPT Image 2 qua Claude-in-Chrome. Tải về, đặt tên, log nguồn.
8. ★ CHẠY ĐỘNG CƠ REFERENCE (PHẦN 6B.B): WebSearch + Chrome tìm & lưu reference
   GÓC MÁY / CHUYỂN ĐỘNG MÁY / COLOR PALETTE cho từng khối craft + từng Act.
9. ★ CHẠY ĐỘNG CƠ NHẠC (PHẦN 6B.C): tạo nhạc Suno theo Mood&Tone + cấu trúc act,
   tải mp3, gắn vào khối Âm nhạc + Stillomatic.
10. DỰNG STORYBOARD: layout 4-up/3-up, CHÈN ẢNH THẬT vào ô; ô chưa gen giữ placeholder
    + prompt ẩn per-shot (4.6) để người dùng tự bấm tạo. Chèn nhãn ref + ảnh ref.
11. CHÈN SLIDE NGHỈ/HOOK (3F) + STILLOMATIC mockup (3G) + LỜI CUỐI (3H).
12. ★ RÁP OUTPUT KÉP (PHẦN 6B.D + 6B.E): (1) FILE CANVA THẬT qua Canva MCP, (2) FILE PPTX
    qua pptxgenjs nhúng ảnh/nhạc thật. → Trả 2 link/file → QC theo 3 điểm chạm (PHẦN 8).
```

> **Nguyên tắc thứ tự:** luôn dựng **lớp ý đồ (text)** trước, rồi mới chạy động cơ tạo asset (bước 7–9), rồi mới ráp file (bước 12). Không gen ảnh/nhạc khi chưa chốt Mood&Tone + Color Palette phim — gen sẽ lệch tông.

---

## PHẦN 6B — ĐỘNG CƠ TỰ ĐỘNG (AUTOMATION ENGINE) ★ v1.3

> **Triết lý GENERATE-FIRST:** Agent **chủ động tạo asset thật** thay vì chỉ để placeholder. Mục tiêu: người dùng nhận hồ sơ gần hoàn chỉnh, **chỉ QC & update**. Nhưng **luật chống-bịa của v1.2 vẫn tối thượng**: không bịa insight/credentials/số liệu; nếu một động cơ không sẵn hoặc thất bại → **fallback** về placeholder + prompt ẩn của v1.2 và **báo rõ** asset nào auto / asset nào người dùng cần tự làm.

### 6B.0 — TIỀN ĐIỀU KIỆN & CHỌN CHẾ ĐỘ

Trước khi gen, kiểm tra & chốt với người dùng:

| Asset | Công cụ | Tiền điều kiện | Fallback nếu thiếu |
|---|---|---|---|
| Ảnh reference/keyvisual/storyboard | **ChatGPT Image 2** qua **Claude-in-Chrome** | Extension Claude in Chrome đã kết nối; tab ChatGPT đã đăng nhập (Plus, có Image 2) | Prompt ẩn + placeholder (v1.2 §4.6) |
| Reference góc máy/chuyển động/palette | **WebSearch + WebFetch + Claude-in-Chrome** | Mạng | Field link + QR (v1.2 §3E) |
| Nhạc | **Suno** qua **Claude-in-Chrome** | Tab Suno đã đăng nhập | Mô tả hướng nhạc + field reference track (v1.2 §3C) |
| File Canva | **Canva MCP** (`5cb69fff…`) | MCP Canva đã kết nối/uỷ quyền | Outline spec để người dùng paste (v1.2) |
| File PPTX | **pptxgenjs** (PHẦN 7) | — | luôn dựng được |

- Nếu Claude-in-Chrome **chưa kết nối** → hướng dẫn người dùng cài/kết nối extension; KHÔNG tự rơi xuống computer-use trừ khi người dùng yêu cầu.
- Mỗi phiên, **xác nhận scope ảnh** (mặc định: *Reference + Keyvisual + storyboard chọn lọc* — không gen mọi shot để tiết kiệm lượt).
- **Minh bạch chi phí:** trước khi gen hàng loạt, báo số ảnh/số bài nhạc dự kiến để người dùng duyệt.

### 6B.A — ĐỘNG CƠ ẢNH: CHATGPT IMAGE 2 QUA CLAUDE-IN-CHROME

**Phạm vi (mặc định, đã chốt):** Reference + Keyvisual + **shot storyboard chọn lọc** (các shot chủ chốt: mở phim, cao trào, brand reveal, các shot khách dễ hiểu lầm). Các shot còn lại giữ prompt ẩn để người dùng tự bấm tạo.

**Quy trình:**
```
1. Mở/định vị tab ChatGPT (mcp__Claude_in_Chrome__navigate tới chatgpt.com).
2. Với mỗi asset cần gen, soạn PROMPT theo GÓC NHÌN ĐẠO DIỄN & DOP (công thức 6B.A.1).
3. Gửi prompt vào ô chat (form_input/find), chờ Image 2 render (đợi ảnh xuất hiện).
4. Tải ảnh: lấy URL ảnh từ DOM (read_page/javascript_tool) → download.
5. Đặt tên & log: keyvisual_<dự_án>.png · ref_<khối>_<##>.png · sb_<shot##>.png.
   Ghi mapping {asset → prompt → file} để QC truy vết.
6. Lặp tới hết danh sách. Lỗi/timeout 1 ảnh → log fallback, đi tiếp, KHÔNG dừng cả lô.
```

**6B.A.1 — Công thức PROMPT theo GÓC NHÌN ĐẠO DIỄN & DOP** (mở rộng từ §4.6):
```
[loại asset] <chủ thể + hành động/nội dung>, <bối cảnh>,
— DOP layer: shot size <ECU/CU/MS/WS/EWS>, góc máy <eye-level/low/high/top/dutch>,
  lens <wide 24mm / normal 35-50mm / tele 85mm+>, độ sâu trường ảnh <shallow/deep DOF>,
  chuyển động gợi ý <static/dolly/pan/crane/handheld/FPV> (mô tả tĩnh frame đại diện),
— Director layer: mood <chip Mood & Tone>, cảm xúc cảnh, thời điểm/ánh sáng
  <golden hour / hard key / soft / neon / silhouette>,
— Color: bảng màu <hex từ Color Palette phim>, hướng grading <teal-orange/desaturate…>,
— Format: tỷ lệ 16:9, <chừa negative space cho chữ nếu shot có TEXT>,
  phong cách <camera→cinematic photoreal; VFX/graphic→motion/UI; CGI→3D render;
  tư liệu→documentary>, high detail, no watermark, no on-image text.
```
- **Keyvisual:** ưu tiên 1 frame "đinh" dùng được cho poster/thumbnail; áp `skill_keyvisual_colormedia_v1`.
- **Nhất quán nhân vật/bối cảnh:** với loạt shot cùng nhân vật, mô tả lặp lại wardrobe/look (từ Character Design 3B) trong mỗi prompt để giữ đồng nhất; nếu lệch → gen lại shot đó.
- ⚠️ **Người duyệt cuối là người dùng.** Agent gen theo ý đồ đã chốt; mọi ảnh đánh dấu *"AI-generated — chờ QC"*. Không tuyên bố ảnh là cảnh quay thật.

### 6B.B — ĐỘNG CƠ REFERENCE: GÓC MÁY / CHUYỂN ĐỘNG MÁY / COLOR PALETTE

Chủ động **tìm và insert** reference thật (khác với ảnh tự gen — đây là ảnh/clip tham chiếu có nguồn):
```
1. Với mỗi khối craft (Cinematography, VFX, từng Act) + 3 nhãn cố định:
   · CAM REF (góc máy)  · CAM MOTION REF (chuyển động máy)  · COLOR PALETTE REF.
2. WebSearch truy vấn theo từ khoá điện ảnh (vd "low angle hero shot cinematography",
   "crane shot reveal corporate film", "teal orange grading reference still",
   "<mood> color palette film still").
3. WebFetch / Claude-in-Chrome mở kết quả, chọn ảnh/clip phù hợp tông phim.
4. Lưu ảnh thumbnail + GHI NGUỒN (URL + tên) + 1 dòng "lấy gì từ ref này".
   Clip chuyển động → chèn thumbnail + link + QR (AI không nhúng video chạy được trong deck).
5. Color Palette ref: trích 4–6 hex từ ảnh tham chiếu để đối chiếu Color Palette phim (3B).
```
- ⚠️ **Tôn trọng bản quyền:** reference dùng để *định hướng nội bộ*, luôn **ghi nguồn**; không tuyên bố là sản phẩm ColorMedia. Đánh nhãn "REFERENCE — nguồn: …".
- Quy ước tên: `ref_cam_<##>.jpg` · `ref_motion_<##>.jpg` · `ref_palette_<##>.jpg`.

### 6B.C — ĐỘNG CƠ NHẠC: SUNO QUA CLAUDE-IN-CHROME

```
1. Từ khối Âm nhạc (3C): chốt thể loại · tempo/BPM · mood · cấu trúc theo act
   (build → drop → lắng → cao trào).
2. Soạn STYLE PROMPT cho Suno: "<genre>, <mood chips>, <BPM> BPM, <nhạc cụ chủ đạo>,
   cinematic, structure: <intro build / mid groove / breakdown / climax>, instrumental
   (trừ khi cần lyric)". + tiêu đề bài.
3. Mở tab Suno (navigate), dán style prompt, tạo (thường Suno trả 2 biến thể).
4. Nghe/đối chiếu mô tả → tải mp3 bản phù hợp nhất (download). Tên: music_<dự_án>_v<#>.mp3.
5. Gắn: link/file nhạc vào khối Âm nhạc (3C) + nhúng vào Stillomatic nếu có (3G).
   Đồng bộ cấu trúc nhạc với tempo map Nhịp dựng (3D).
```
- Tạo **1–2 phương án** mood khác nhau để người dùng chọn (vd "hùng tráng" vs "ấm áp").
- ⚠️ Nhạc Suno là **demo định hướng tông**, không phải nhạc final có bản quyền thương mại trừ khi mua gói phù hợp — ghi rõ trên slide Âm nhạc: *"nhạc demo định hướng — bản phát hành sẽ produce/đối chiếu license sau"*.

### 6B.D — RÁP FILE CANVA THẬT (CANVA MCP)

```
1. upload-asset-from-url / từ file: đẩy toàn bộ ảnh đã gen + reference + (thumbnail nhạc).
2. generate-design / generate-design-structured: dựng deck theo bộ xương Treatment (2.2)
   + palette deck (PHẦN 5) + nội dung 3 điểm chạm + storyboard.
3. perform-editing-operations: chèn ảnh đúng ô, swatch Color Palette phim, tempo map,
   slide nghỉ/hook, trang Đạo diễn/DOP, Lời cuối.
4. export-design: xuất link Canva (để người dùng QC/sửa trực tiếp) + (tuỳ) PDF.
5. Trả người dùng: LINK CANVA + ghi chú "mở Canva chỉnh trực tiếp; MCP không sửa lại được
   sau khi tạo — sửa trong editor Canva".
```
- File nhạc/clip không nhúng phát trong Canva → để **nút/QR link** tới file nhạc + stillomatic.

### 6B.E — RÁP FILE PPTX (pptxgenjs) — NHÚNG ASSET THẬT

Như PHẦN 7 nhưng **ô storyboard/keyvisual/reference chèn ẢNH THẬT** (`slide.addImage`) thay cho placeholder rỗng; ô nào chưa gen mới giữ placeholder + prompt ẩn trong speaker note. Nhạc & stillomatic: nút + QR link (PPTX không nhúng audio stream từ web).

### 6B.F — BẢNG TRUY VẾT ASSET (bắt buộc khi auto)

Cuối phiên, agent xuất 1 bảng (in trong chat + slide phụ lục) liệt kê mọi asset:
`tên file · loại (gen/ref/nhạc) · nguồn (ChatGPT Image2 / URL / Suno) · prompt/truy vấn · trạng thái (đã chèn / chờ QC / fallback)`.
→ Người dùng QC nhanh, biết cái gì auto, cái gì cần tự làm.

---

## PHẦN 7 — OUTPUT SPEC

> **★ v1.3 — ĐẦU RA KÉP MẶC ĐỊNH:** mỗi dự án xuất **đồng thời 1 file Canva + 1 file PPTX** (không còn "chọn 1 trong 2"). Cả hai **nhúng asset thật** đã gen ở PHẦN 6B; ô nào chưa gen mới giữ placeholder + prompt ẩn. Cuối cùng đính kèm **Bảng truy vết asset (6B.F)**.

- **Canva (file thật):** dựng qua **Canva MCP** (6B.D) → trả LINK Canva để QC/sửa trực tiếp. (Chế độ outline-spec cũ chỉ dùng khi Canva MCP không sẵn — fallback.)
- **PPTX (pptxgenjs):** file .pptx, ô storyboard **chèn ảnh thật** (`addImage`); ô chưa gen giữ placeholder đã điền header/Nội dung/VO + prompt ẩn trong speaker note.
- Template `buildStoryboardRow` (WIDE 13.33×7.5, bounds x≤12.7 y≤7.1, shape "rect", viền-bỏ line width 0): header (số/dur/loại) → ô hình placeholder → Nội dung+TEXT+Chuyển cảnh → làn VO → làn Ref. 3-up đổi chia 4→3.
- **Prompt ẩn:** mỗi trang storyboard gọi `slide.addNotes("### SHOT n\n<prompt 6 thành phần>\n\n### SHOT n+1\n…")` — soạn tự động từ shot data (4.6). Speaker note ẩn khỏi mặt slide, người dùng mở pane Notes để copy.
- Color Palette phim & swatch: dùng các ô `rect` fill hex + nhãn. Tempo map: thanh `rect` theo timeline.

---

## PHẦN 8 — QC CHECKLIST (đồng trục 3 ĐIỂM CHẠM)

**Cấu trúc & nhịp**
- [ ] Đúng tầng; đủ luật cứng (Cover, Overview, Mood&Tone, Âm nhạc, Voice/VO, Storyboard, Closing).
- [ ] Có trang Đạo diễn/DOP (T2/T3). Có ≥3 slide nghỉ/hook (T2/T3).
- [ ] Section divider mở mỗi khối; không đổ chữ liên tục >4 slide.

**THỊ GIÁC**
- [ ] Có Keyvisual; Color Palette phim rõ hex + vai trò.
- [ ] Character Design có wardrobe/hair-makeup/look; Set có Props.
- [ ] CGI gắn cờ độ phức tạp + Previs khi cần; Transitions có hệ thống.

**THÍNH GIÁC**
- [ ] Music có hướng tempo + cấu trúc theo act + reference track (link).
- [ ] Voice/VO có giọng + tông + tiết tấu.

**TRÁI TIM**
- [ ] Có Emotional Core + "khoảnh khắc nhớ mãi".
- [ ] Nhịp dựng có tempo map khớp cấu trúc nhạc.

**Storyboard & trung thực**
- [ ] 3 làn; mỗi ô đủ số·dur·loại·hình·Nội dung; VO khớp shot; Chuyển cảnh ghi ở shot cần.
- [ ] Ô đã gen có **ảnh thật** chèn đúng; ô chưa gen còn **prompt ẩn** trong speaker note.
- [ ] Stillomatic (nếu có) đúng **disclaimer** + link/QR.
- [ ] Lời cuối đủ **Tiền kỳ + Hậu kỳ + 1 dòng non-negotiable**.
- [ ] Không bịa insight/credentials/số liệu; disclaimer animatic; cờ "màu/ref suy ra chờ duyệt".

**★ Asset tự tạo (v1.3 — generate-first)**
- [ ] Keyvisual + reference + shot chọn lọc đã gen bằng ChatGPT Image 2; mọi ảnh đánh nhãn *"AI-generated — chờ QC"*, không bị tuyên bố là cảnh quay thật.
- [ ] Ảnh gen bám **góc nhìn Đạo diễn/DOP** (shot size, góc máy, lens, chuyển động) + **Color Palette phim** (grading/hex); nhân vật giữ nhất quán wardrobe/look.
- [ ] Reference góc máy / chuyển động máy / Color Palette có **ghi nguồn** (URL) + nhãn "REFERENCE".
- [ ] Nhạc Suno khớp Mood&Tone + cấu trúc act + tempo map; ghi rõ *"nhạc demo định hướng"*.
- [ ] Xuất **cả Canva (link) + PPTX (file)**; có **Bảng truy vết asset (6B.F)** phân biệt auto / fallback / chờ người dùng tự làm.

---

## PHẦN 9 — AGENT CONFIGURATION

**Initialization:**
```
1. Loại job & thời lượng? → suy TẦNG (T1/T2/T3).
2. Kịch bản chốt chưa? Dán KB/voice-off.
3. (T3) Insight & Big Idea từ Insight First? Dán. Chưa có → DỪNG.
4. Brand khách: logo + màu brand (hoặc AI suy ra, duyệt sau).
5. Mood & Tone + Color Palette phim định hướng (grading)?
6. ÂM NHẠC: thể loại/tempo + mood mong muốn? (→ động cơ Suno tạo 1–2 phương án)
7. CGI/Kỹ xảo: phim có shot 3D/compositing/sim không? (quyết định mục CGI)
8. NHỊP DỰNG: nhanh/chậm theo act? có cao trào ở đâu?
9. ĐẠO DIỄN/DOP: ai cầm? có showreel/credentials để đưa vào không?
10. Phim chia Phần/Act không? (Breakdown — T2)
11. Storyboard 4-up hay 3-up?
12. Có bản dựng STILLOMATIC/animatic để nhúng không?
13. LỜI CUỐI: 3 điều quan trọng nhất muốn team tiền kỳ & hậu kỳ nắm? (1 điều non-negotiable?)
14. ★ ĐỘNG CƠ TỰ ĐỘNG: Claude-in-Chrome đã kết nối? ChatGPT Plus (Image 2) + Suno đã
    đăng nhập? Canva MCP sẵn? → chốt AUTO / FALLBACK cho từng loại asset (6B.0).
15. ★ SCOPE ẢNH: mặc định Reference + Keyvisual + storyboard chọn lọc — xác nhận/đổi
    (báo số ảnh & số bài nhạc dự kiến để duyệt chi phí trước khi gen hàng loạt).
16. Output: mặc định xuất KÉP (Canva + PPTX). Đổi không?
```
> Câu 1 → suy tầng → ma trận section. Câu 4: thiếu màu → AI suy ra, ghi "đề xuất, chờ duyệt".
> Câu 14–15 → quyết định chế độ động cơ (PHẦN 6B). Không gen trước khi chốt Mood&Tone + Color Palette phim (câu 5).

**Hành vi bắt buộc (minh bạch — v1.3 generate-first):**
- Agent **chủ động tạo asset thật** (ảnh ChatGPT Image 2, reference, nhạc Suno) khi động cơ sẵn; khi không sẵn/thất bại → **fallback** placeholder + prompt ẩn + field/QR (v1.2) và **báo rõ** asset nào auto, asset nào người dùng tự làm.
- Mọi ảnh tự tạo dán nhãn *"AI-generated — chờ QC"*; reference luôn **ghi nguồn**; nhạc ghi *"demo định hướng"*; stillomatic giữ disclaimer. **Không tuyên bố** asset tạo máy là cảnh quay/sản phẩm thật.
- **Không bịa** insight/credentials/số liệu. Đánh dấu mọi giả định để duyệt. Xuất **Bảng truy vết asset (6B.F)** cuối phiên.

---

## PHẦN 10 — RETRIEVAL-READY CHUNKS

### chunk_01
**title:** 3 tầng Treatment & luật chọn tầng
**content:** T1 Lite (Niku-Ichi): TVC ngắn, thực thi hình thuần. T2 Full Film (MB Life): phim dài, craft sâu theo 3 điểm chạm. T3 Strategy Proposal (Cebraton): chiến lược → craft → storyboard đa version. Luật: KB chốt+nhỏ→T1; phim dài→T2; cần thuyết phục bằng insight→T3. T3 kéo Insight/Big Idea từ skill_insight_first + KB sáng tạo, không bịa.
**tags:** [treatment_tier, t1, t2, t3]
**retrieval_keywords:** [tầng treatment, loại treatment, chọn độ sâu, lite, full film, proposal]

### chunk_02
**title:** Kiến trúc Treatment theo 3 Điểm Chạm (đồng trục QC)
**content:** v1.1 gom phần craft theo Nguyên lý 3 Điểm Chạm: THỊ GIÁC (Visual) – THÍNH GIÁC (Aural) – TRÁI TIM (Heart), trùng trục skill_qc_3_touchpoints → treatment thiết kế gì thì QC kiểm đúng cái đó. Bộ xương: Front (Cover, Overview, Statement, Foundation, trang Đạo diễn/DOP) → 3 ĐIỂM CHẠM (TC1 Thị giác: Keyvisual, Color Palette phim, Mood&Tone, Cinematography, Character Design/Stylist, Set+Props, CGI, Transitions; TC2 Thính giác: Music&Sound, Voice/VO; TC3 Trái tim: Emotional Core, Nhịp dựng) → Storyboard (tuyến tính theo Act) → Closing. Slide nghỉ/hook chèn xen. Storyboard KHÔNG bẻ theo điểm chạm — giữ tuần tự. Luật cứng mọi tầng: Cover, Overview, Mood&Tone, Âm nhạc, Voice/VO, Storyboard, Closing.
**tags:** [three_touchpoints, thi_giac, thinh_giac, trai_tim, architecture, qc_alignment]
**retrieval_keywords:** [3 điểm chạm, thị giác thính giác trái tim, cấu trúc treatment, đồng trục QC, visual aural heart]

### chunk_03
**title:** 9 thành phần craft bổ sung v1.1 (theo điểm chạm)
**content:** THỊ GIÁC: (5) Keyvisual — 1 frame đinh full-bleed, áp skill_keyvisual_colormedia; (6) Color Palette PHIM — bảng màu grading/không khí (khác palette deck), 4–6 swatch hex+vai trò; (3) Character Design & Stylist — wardrobe, hair&make-up, grooming, look note mỗi nhân vật; (7) Props — danh sách đạo cụ mỗi Set/Location; (8) Kỹ xảo & CGI — shot 3D/compositing/sim, độ phức tạp Low/Med/High, cờ Previs; (2) Chuyển cảnh — hệ transition (match cut, light swipe, morph, speed ramp), ghi tại shot. THÍNH GIÁC: (1) Âm nhạc & Sound Design — thể loại/tempo/cấu trúc theo act + reference track + SFX + mix; Voice/VO Direction — giọng, tông, tiết tấu. TRÁI TIM: (9) Nhịp dựng/Editing Rhythm — tempo map theo act, khớp cấu trúc nhạc; Emotional Core. (4) Reference Video — gắn từng khối, placeholder+link+QR. AI không xem/nghe được link → chỉ tạo field.
**tags:** [keyvisual, color_palette, character_design, stylist, props, cgi, transitions, music, sound_design, voice, editing_rhythm, reference_video]
**retrieval_keywords:** [âm nhạc treatment, color palette phim, character design stylist, props set art, kỹ xảo cgi, chuyển cảnh transition, nhịp dựng, reference video, keyvisual]

### chunk_04
**title:** Trang Đạo diễn/DOP & lớp slide nghỉ/hook
**content:** Trang ĐẠO DIỄN/DOP (mới, T2/T3): chân dung, tên+vai trò, 2–3 dòng credentials, showreel link/QR, 3–6 logo dự án tiêu biểu — tăng thuyết phục. KHÔNG bịa credentials/giải thưởng; lấy từ hồ sơ thật (hoang_dung_trainer_profile cho Hoàng Dũng), thiếu→placeholder. Slide nghỉ/hook (từ Slide Arch 2B): Quote slide (manifesto full-bleed), Keyvisual slide (mood full-bleed), Section divider (typo lớn mở mỗi khối). Luật nhịp: sau 3–4 slide nặng chữ chèn 1 slide nghỉ. T2/T3 ≥3 slide nghỉ.
**tags:** [director_dop, credentials, showreel, break_slide, hook_slide, breathing]
**retrieval_keywords:** [trang đạo diễn, DOP, showreel, credentials, slide nghỉ, hook, quote slide, section divider]

### chunk_05
**title:** Hệ khung Storyboard 3 làn, 2 layout, placeholder
**content:** 3 làn: Shooting Storyboard (bắt buộc) / Voice Over (luôn hiển thị) / Reference Board (tuỳ chọn). 2 layout: 4-up (TVC) / 3-up (phim dài). Ô shot: số · thời lượng · loại (camera/VFX/CGI/enframe/graphic/tư liệu) · ô hình placeholder · Nội dung · TEXT · ghi chú KT gồm Chuyển cảnh + lens/camera move. Nhãn ref: CAM REF, CAM MOTION REF, TRANSITION REF, MATCH CUT, BACKGROUND REF, CAMERA EFFECT, FPV DRONE. Placeholder đánh số [SHOT n — hình], đạo diễn chèn ảnh đè; tên sb_##.jpg / ref_##_loại.jpg.
**tags:** [storyboard_frame, three_lanes, layout, placeholder, shot_anatomy, transition_note]
**retrieval_keywords:** [khung storyboard, 3 làn, 4-up 3-up, placeholder ảnh, ghi chú chuyển cảnh, nhãn ref]

### chunk_06
**title:** Áp design, output pptxgenjs & luật trung thực
**content:** Palette deck = brand SP + mood phim, không ép Style 01 trừ phim chính chủ ColorMedia; ColorMedia ở credit Cover+Closing. Color Palette PHIM (grading) khác palette thiết kế deck. Mượn Slide Arch: divider, typography hierarchy, font đủ dấu TV, slide nghỉ/hook 2B. Output Canva hoặc PPTX (pptxgenjs WIDE 13.33×7.5, shape rect, viền-bỏ line 0, buildStoryboardRow). Swatch màu & tempo map dựng bằng rect fill hex. LUẬT TRUNG THỰC: AI không xem/nghe link video&nhạc → placeholder+field+QR; không bịa insight/credentials/số liệu; disclaimer animatic; cờ giả định chờ duyệt.
**tags:** [design_method, palette_rule, pptxgenjs, output, honesty, qr_link]
**retrieval_keywords:** [áp design, palette deck vs palette phim, xuất pptx, swatch màu, tempo map, không bịa, QR reference]

### chunk_07
**title:** Prompt ẩn per-shot, Stillomatic mockup & Lời cuối (Director's Final Note)
**content:** v1.2 bổ sung 3 thứ. (a) PROMPT ẨN PER-SHOT: mỗi ô storyboard có 1 prompt tạo ảnh đặt trong speaker note (slide.addNotes), ẩn khỏi mặt slide, người dùng copy để tạo ảnh storyboard rồi chèn đè placeholder. Công thức 6 thành phần tự soạn từ shot: [SHOT n] chủ thể+hành động (Nội dung), bối cảnh, mood (chip Mood&Tone), phong cách theo loại shot (camera→cinematic, VFX/graphic→motion/UI, CGI→3D render, tư liệu→documentary), bảng màu hex từ Color Palette phim, 16:9, bố cục chừa negative space nếu có TEXT, high detail. Prompt là gợi ý — đạo diễn chỉnh trước khi tạo; AI không tự tạo/chèn ảnh. (b) STILLOMATIC/ANIMATIC MOCKUP: slide khung player YouTube + thumbnail + link/QR + DISCLAIMER bắt buộc "bản dựng… chưa phải hình quay thực tế"; AI không xem được link. (c) LỜI CUỐI (Director's Final Note): khác Director's Statement (hướng khách) — hướng TEAM tiền kỳ & hậu kỳ; 2 cột TIỀN KỲ (casting/wardrobe/set/props/đạo cụ/ánh sáng) + HẬU KỲ (grading bám Color Palette phim, nhịp dựng theo tempo map, nhạc&sound, VFX/CGI ưu tiên, transition signature) + 1 dòng NON-NEGOTIABLE; giọng ngắn declarative; brief cho crew, đặt trước Closing.
**tags:** [image_prompt, prompt_block, hidden_prompt, stillomatic, animatic, director_final_note, loi_cuoi, pre_production, post_production]
**retrieval_keywords:** [prompt ẩn storyboard, copy tạo ảnh, speaker note prompt, stillomatic mockup, animatic, disclaimer, lời cuối, director final note, tiền kỳ hậu kỳ, non-negotiable]

### chunk_08
**title:** Động cơ tự động v1.3 — generate-first (ảnh, reference, nhạc)
**content:** v1.3 lật skill từ thủ công sang CHỦ ĐỘNG TẠO ASSET. (A) ẢNH: tạo Reference + Keyvisual + shot storyboard chọn lọc bằng ChatGPT Image 2 qua Claude-in-Chrome; prompt soạn theo GÓC NHÌN ĐẠO DIỄN & DOP — DOP layer (shot size ECU/CU/MS/WS, góc máy eye-level/low/high/dutch, lens, DOF, chuyển động) + Director layer (mood, cảm xúc, ánh sáng/thời điểm) + Color (hex từ Color Palette phim, hướng grading) + format 16:9. Giữ nhất quán nhân vật bằng lặp wardrobe/look. Mọi ảnh nhãn "AI-generated — chờ QC". (B) REFERENCE: WebSearch + WebFetch + Chrome tìm & insert ref CAM REF (góc máy) / CAM MOTION REF (chuyển động) / COLOR PALETTE REF cho từng khối + Act, GHI NGUỒN URL, nhãn REFERENCE, tôn trọng bản quyền. (C) NHẠC: Suno qua Claude-in-Chrome theo Mood&Tone + tempo/BPM + cấu trúc act; tạo 1–2 phương án; ghi "nhạc demo định hướng". Tiền điều kiện: Claude-in-Chrome kết nối + ChatGPT Plus/Suno đăng nhập; thiếu → fallback placeholder/prompt ẩn/field+QR của v1.2. Dựng lớp text (Mood&Tone + Color Palette) TRƯỚC khi gen.
**tags:** [automation_engine, generate_first, chatgpt_image_2, gpt_image, suno, claude_in_chrome, auto_reference, director_dop_prompt, asset_generation]
**retrieval_keywords:** [tự động tạo ảnh, chatgpt image 2, gpt image, suno tạo nhạc, claude in chrome, reference góc máy chuyển động máy color palette, prompt đạo diễn dop, generate first treatment]

### chunk_09
**title:** Ráp đầu ra kép Canva MCP + PPTX & bảng truy vết asset
**content:** v1.3 xuất ĐỒNG THỜI 1 file Canva + 1 file PPTX, cả hai NHÚNG ASSET THẬT. CANVA: dựng file thật qua Canva MCP — upload-asset-from-url (đẩy ảnh đã gen + reference), generate-design / generate-design-structured (bộ xương Treatment + palette deck + 3 điểm chạm + storyboard), perform-editing-operations (chèn ảnh, swatch Color Palette phim, tempo map, slide nghỉ, trang Đạo diễn/DOP, Lời cuối), export-design → trả LINK Canva (sửa tiếp trong editor Canva, MCP không sửa lại sau tạo). PPTX (pptxgenjs): ô storyboard/keyvisual/reference chèn ảnh thật bằng addImage; ô chưa gen giữ placeholder + prompt ẩn speaker note. Nhạc & stillomatic: nút/QR link (Canva/PPTX không nhúng audio stream web). Cuối phiên xuất BẢNG TRUY VẾT ASSET (6B.F): tên file · loại (gen/ref/nhạc) · nguồn · prompt/truy vấn · trạng thái (đã chèn/chờ QC/fallback) để người dùng QC nhanh & biết cái gì cần tự làm.
**tags:** [canva_mcp, pptxgenjs, dual_output, asset_traceability, export_design, generate_first]
**retrieval_keywords:** [dựng canva mcp, file canva thật, xuất pptx nhúng ảnh, đầu ra kép, bảng truy vết asset, export design, upload asset url]

---

*Hết skill v1.3. Cross-ref: storyboard_visual_direction (viết shot) · slide_architecture_v2_6 (design + slide nghỉ + image prompt block) · qc_3_touchpoints_v2 (trục Thị giác–Thính giác–Trái tim) · keyvisual_colormedia · insight_first_v3 (chiến lược) · mood_tone · set-design-art-direction · hoang_dung_writing_style (giọng Lời cuối). Động cơ tự động (6B): Claude-in-Chrome (ChatGPT Image 2 + Suno) · WebSearch/WebFetch (reference) · Canva MCP (file Canva) · pptxgenjs (PPTX).*
