# Demo — một phiên chạy hoàn chỉnh

> ⚠️ **Ví dụ minh hoạ** để bạn hình dung skill hoạt động ra sao. Dữ liệu là hư cấu
> (thương hiệu "Bia X"), không phải dự án thật. Ảnh/nhạc trong demo này được mô tả
> bằng chữ — khi chạy thật, agent tạo asset thực tế qua ChatGPT Image 2 / Suno.

---

## Bối cảnh

Bạn vừa chốt kịch bản một **TVC 30 giây** cho thương hiệu **Bia X**, dịp hè, thông
điệp *"Cụng ly — kết nối bạn bè"*. Bạn muốn đóng gói thành treatment gửi khách.

## Bước 1 — Gọi skill

```
Bạn: /director-treatment:treatment
     (hoặc) Tạo treatment cho TVC này [đính kèm kịch bản đã chốt]
```

## Bước 2 — Agent hỏi khởi tạo, bạn trả lời

| Agent hỏi | Bạn trả lời |
|---|---|
| Loại job & thời lượng? | TVC 30s, kịch bản đã chốt → **T1 Lite** |
| Brand khách | Đỏ `#C8102E`, vàng `#F2A900`, logo đính kèm |
| Mood & Tone + Color Palette phim | Sảng khoái, trẻ trung, ấm; grading ấm high-contrast |
| Âm nhạc | Indie pop-rock, vui, ~120 BPM |
| Động cơ tự động | Có Claude-in-Chrome + ChatGPT Plus + Suno + Canva MCP → **AUTO** |
| Scope ảnh | Mặc định: reference + keyvisual + 4 shot chọn lọc |
| Output | Kép (Canva + PPTX) |

## Bước 3 — Agent thiết kế 3 Điểm Chạm (trích)

**THỊ GIÁC**
- *Keyvisual:* nhóm bạn nâng ly trên sân thượng phố cổ, hoàng hôn.
- *Color Palette phim:* `#C8102E` đỏ (key) · `#F2A900` vàng bia (accent) · `#1A1A1A` nền tương phản · `#FFE9C7` ánh nắng (skin tone warm).
- *Cinematography:* hand-held năng động xen slow-mo đặc tả bia.

**THÍNH GIÁC**
- *Music:* indie pop-rock 120 BPM, build → climax có gang vocals.
- *VO:* nam trẻ, ấm, dứt khoát, 1 câu chốt cuối.

**TRÁI TIM**
- *Emotional core:* "khoảnh khắc cụng ly là khoảnh khắc thuộc về nhau".
- *Nhịp dựng:* nhanh dồn ở mở → lắng ở rót bia → bùng ở cụng ly + logo.

## Bước 4 — Agent tạo asset (chế độ AUTO)

```
🖼️  ChatGPT Image 2 (qua Claude-in-Chrome):
    ✓ keyvisual_biax.png            (mô tả: nhóm bạn cụng ly sân thượng golden hour)
    ✓ sb_01.png  (WS sân thượng mở cảnh)
    ✓ sb_04.png  (ECU rót bia macro)
    ✓ sb_07.png  (MS cụng ly slow-mo)
    ✓ sb_09.png  (CU nụ cười + logo reveal)
🎥  WebSearch reference:
    ✓ ref_cam_01   low angle hero        — nguồn: <url>
    ✓ ref_motion_01 dolly-in close up    — nguồn: <url>
    ✓ ref_palette_01 warm golden grading — nguồn: <url>
🎵  Suno:
    ✓ music_biax_v1.mp3  (indie pop-rock vui, 120 BPM)
    ✓ music_biax_v2.mp3  (acoustic ấm hơn — phương án 2)
```

## Bước 5 — Agent ráp output kép

```
📐 Canva: https://canva.com/design/xxxx  (đã upload ảnh + dựng slide)
📊 PPTX:  treatment_biax_TVC.pptx        (storyboard nhúng ảnh thật)
```

## Bước 6 — Bảng truy vết asset (agent trả về)

| Tên file | Loại | Nguồn | Trạng thái |
|---|---|---|---|
| keyvisual_biax.png | gen | ChatGPT Image 2 | ✅ đã chèn — chờ QC |
| sb_01/04/07/09.png | gen | ChatGPT Image 2 | ✅ đã chèn — chờ QC |
| sb_02/03/05/06/08.png | — | (prompt ẩn) | ⏳ bạn tự gen khi cần |
| ref_cam/motion/palette_01 | ref | WebSearch | ✅ ghi nguồn |
| music_biax_v1/v2.mp3 | nhạc | Suno | ✅ demo — chọn 1 |

## Bước 7 — Việc của bạn (QC)

1. Duyệt 5 ảnh AI — giữ/gen lại.
2. Nghe v1 vs v2, chọn nhạc.
3. Với 5 ô storyboard còn lại: mở speaker note PPTX → copy prompt ẩn → tự tạo ảnh.
4. Mở Canva chỉnh chữ/bố cục → gửi khách.

---

➡️ Xem [PROMPT-LIBRARY.md](PROMPT-LIBRARY.md) để biết prompt cụ thể agent dùng cho từng ảnh/nhạc ở trên.
