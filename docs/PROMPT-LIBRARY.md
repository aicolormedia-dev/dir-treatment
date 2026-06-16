# Thư viện Prompt — copy & dùng

Tổng hợp các mẫu prompt mà skill `treatment` dùng nội bộ. Bạn có thể **copy thủ công**
để tạo ảnh/nhạc khi không chạy chế độ tự động, hoặc để hiểu agent đang làm gì.

---

## 1. Prompt ẢNH theo góc nhìn Đạo diễn & DOP (ChatGPT Image 2 / Midjourney…)

**Công thức (4 lớp):**
```
[loại asset] <chủ thể + hành động/nội dung>, <bối cảnh>,
— DOP layer: shot size <ECU/CU/MS/WS/EWS>, góc máy <eye-level/low/high/top/dutch>,
  lens <wide 24mm / normal 35-50mm / tele 85mm+>, độ sâu trường ảnh <shallow/deep DOF>,
  chuyển động gợi ý <static/dolly/pan/crane/handheld/FPV>,
— Director layer: mood <chip Mood&Tone>, cảm xúc cảnh, ánh sáng/thời điểm
  <golden hour / hard key / soft / neon / silhouette>,
— Color: bảng màu <hex từ Color Palette phim>, hướng grading <teal-orange/desaturate…>,
— Format: tỷ lệ 16:9, <chừa negative space cho chữ nếu shot có TEXT>,
  phong cách <camera→cinematic photoreal; VFX/graphic→motion/UI; CGI→3D render;
  tư liệu→documentary>, high detail, no watermark, no on-image text.
```

**Bảng tra nhanh thuật ngữ DOP**

| Shot size | Dùng cho | | Góc máy | Cảm giác |
|---|---|---|---|---|
| ECU/CU | Cảm xúc, chi tiết sản phẩm | | Eye-level | Trung tính, đời thường |
| MS | Giao tiếp, hành động | | Low angle | Quyền lực, hùng vĩ |
| WS/EWS | Bối cảnh, quy mô | | High angle | Nhỏ bé, bao quát |
| | | | Dutch | Bất ổn, kịch tính |

**Ví dụ đã điền — Keyvisual (TVC bia, mood "sảng khoái, kết nối"):**
```
Keyvisual: nhóm bạn trẻ nâng ly bia cụng nhau trên sân thượng nhìn ra phố cổ Hà Nội
lúc hoàng hôn, — DOP: medium shot, góc eye-level hơi thấp, lens 35mm, shallow DOF
hậu cảnh bokeh đèn phố, — Director: mood sảng khoái & ấm áp kết nối, ánh sáng golden
hour ngược nắng viền tóc, bọt bia lấp lánh, — Color: #C8102E đỏ thương hiệu / #F2A900
vàng bia / #1A1A1A nền tương phản, grading ấm contrast vừa, — Format: 16:9, chừa
negative space góc trên cho logo, high detail, photoreal cinematic, no watermark, no text.
```

**Ví dụ — Shot storyboard (cảnh rót bia cận đặc tả):**
```
[SHOT 04] dòng bia vàng rót đầy ly thủy tinh, bọt trào chậm, — DOP: extreme close-up,
góc eye-level ngang mặt ly, lens macro 100mm, shallow DOF, gợi ý slow-motion static,
— Director: mood thèm khát/đã, ánh sáng hard key cạnh trái tạo highlight giọt nước,
— Color: #F2A900 vàng bia / #FFFFFF bọt / #1A1A1A nền tối, grading ấm high-contrast,
— Format: 16:9, high detail, photoreal cinematic, no watermark, no text.
```

> 💡 Giữ **nhất quán nhân vật** giữa nhiều shot: lặp lại mô tả wardrobe/look (từ phần
> Character Design) trong mỗi prompt. Lệch thì gen lại đúng shot đó.

---

## 2. Style prompt NHẠC (Suno)

**Công thức:**
```
<genre>, <mood chips>, <BPM> BPM, <nhạc cụ chủ đạo>, cinematic,
structure: <intro build / mid groove / breakdown / climax>, instrumental
(trừ khi cần lyric). Title: <tên bài>
```

**Ví dụ — TVC bia, mood "sảng khoái, trẻ trung":**
```
Upbeat indie pop-rock, energetic & feel-good, 120 BPM, electric guitar + claps +
punchy drums, cinematic, structure: light intro → groove build → big anthemic
climax with gang vocals shout, instrumental with occasional "hey!" chants.
Title: Cụng Ly Hà Nội
```

**Ví dụ — Brand film doanh nghiệp, mood "tự hào, truyền cảm hứng":**
```
Cinematic orchestral, inspiring & emotional, 90 BPM, strings + piano + subtle
percussion building to brass, structure: intimate piano intro → strings swell →
full orchestra climax at brand reveal → soft outro, instrumental.
Title: Hành Trình
```

> 🎵 Tạo **1–2 phương án mood** khác nhau (vd "hùng tráng" vs "ấm áp") để khách chọn.
> Đồng bộ cấu trúc nhạc với **tempo map** của phần Nhịp dựng.

---

## 3. Truy vấn tìm REFERENCE (WebSearch)

Skill chủ động tìm 3 nhóm reference. Mẫu truy vấn:

**Góc máy (CAM REF):**
```
low angle hero shot cinematography
extreme close up product macro shot film still
over the shoulder dialogue framing reference
```

**Chuyển động máy (CAM MOTION REF):**
```
crane shot reveal corporate film
dolly in emotional close up
FPV drone one take commercial
speed ramp transition action
```

**Color Palette / grading (COLOR PALETTE REF):**
```
teal orange grading reference still
golden hour warm grading commercial
<mood> color palette film still
desaturated moody grading cinematography
```

> ⚖️ Reference chỉ để **định hướng nội bộ** — luôn **ghi nguồn (URL)**, gắn nhãn
> "REFERENCE", không tuyên bố là sản phẩm của mình.

---

## 4. Prompt ẩn per-shot (đặt trong speaker note PPTX)

Với mỗi ô storyboard, skill nhét sẵn 1 prompt vào speaker note theo định dạng:
```
### SHOT 1
[SHOT 1] <prompt 4 lớp ở mục 1>

### SHOT 2
[SHOT 2] <prompt 4 lớp>
```
→ Bạn mở pane Notes, copy, dán vào công cụ tạo ảnh, rồi chèn đè placeholder.
