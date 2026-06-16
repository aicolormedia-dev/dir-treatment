# Changelog

Mọi thay đổi đáng chú ý của marketplace `director-treatment-skills`.

## [1.3.0] — 2026-06-16

### Skill `treatment` v1.3 — GENERATE-FIRST
- **Mới:** Động cơ tự động (Automation Engine) — agent chủ động tạo asset thật thay vì chỉ để placeholder:
  - Tạo ảnh **reference + keyvisual + storyboard chọn lọc** bằng **ChatGPT Image 2** qua Claude-in-Chrome, prompt soạn theo **góc nhìn Đạo diễn & DOP**.
  - Chủ động tìm & chèn **reference góc máy / chuyển động máy / Color Palette** (WebSearch + Chrome), có ghi nguồn.
  - Tạo **nhạc** theo Mood & Tone + cấu trúc act bằng **Suno** qua Claude-in-Chrome.
  - Ráp **file Canva thật** (Canva MCP) + **PPTX** (pptxgenjs) nhúng asset thật.
  - **Bảng truy vết asset** cuối phiên.
- **Giữ nguyên:** Nguyên lý 3 Điểm Chạm và toàn bộ luật chống-bịa. Thiếu công cụ → fallback minh bạch về placeholder + prompt ẩn (cơ chế v1.2).

### Hạ tầng phân phối
- Đóng gói skill thành plugin `director-treatment` trong marketplace `director-treatment-skills`.
- Thêm bộ docs: README, USAGE, PROMPT-LIBRARY, EXAMPLE-walkthrough, sơ đồ pipeline.

---

## Lịch sử skill `treatment` (trước khi lên marketplace)
- **v1.2** — Prompt ẩn per-shot trong speaker note, slide Stillomatic/Animatic mockup, trang Lời cuối (Director's Final Note).
- **v1.1** — Cấu trúc lại craft theo 3 Điểm Chạm; bổ sung 9 thành phần nghề; trang Đạo diễn/DOP; lớp slide nghỉ/hook.
- **v1.0** — Bản đầu: 3 tầng Treatment, hệ khung Storyboard 3 làn, template pptxgenjs.
