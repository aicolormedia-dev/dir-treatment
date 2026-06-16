# Hướng dẫn dùng skill `treatment`

> Đọc README trước để cài. File này hướng dẫn **cách dùng** sau khi đã cài.

## 1. Chuẩn bị trước khi gọi skill

Để skill chạy mượt (và tự động tối đa), chuẩn bị sẵn:

- **Kịch bản / brief đã chốt** — dán trực tiếp hoặc đính kèm file (PDF/DOCX/txt). Skill **không tự viết kịch bản** và **không bịa insight** — thiếu thì nó sẽ dừng và hỏi.
- **Brand khách** — logo + màu thương hiệu (nếu có). Thiếu, agent sẽ đề xuất màu và đánh dấu *"chờ duyệt"*.
- **Mood & Tone + Color Palette phim** — định hướng cảm xúc & grading. Đây là thứ **bắt buộc chốt trước khi gen ảnh/nhạc**, nếu không asset sẽ lệch tông.
- **(Tùy chọn) Hồ sơ Đạo diễn / DOP** — showreel, credentials để tăng thuyết phục.
- **Công cụ tự động** (xem bảng Prerequisites ở README): Claude-in-Chrome + ChatGPT Plus + Suno + Canva MCP. Thiếu cái nào, phần đó tự lùi về thủ công.

## 2. Gọi skill

Một trong hai cách:
- Gõ lệnh: `/director-treatment:treatment`
- Hoặc nói tự nhiên: *"Tạo treatment cho dự án này"* + đính kèm kịch bản → Claude tự nhận diện và gọi.

## 3. Agent sẽ hỏi (Initialization)

Trả lời gọn các câu sau là đủ để agent chạy:

1. **Loại job & thời lượng?** → quyết định **tầng treatment**:
   - **T1 Lite** — TVC ngắn, kịch bản chốt, dựng nhanh.
   - **T2 Full Film** — phim doanh nghiệp / brand film dài, craft sâu.
   - **T3 Strategy Proposal** — pitch dẫn dắt bằng chiến lược (cần insight/big idea).
2. **Kịch bản đã chốt chưa?** (dán vào)
3. **Brand khách:** logo + màu?
4. **Mood & Tone + Color Palette phim** (hướng grading)?
5. **Âm nhạc:** thể loại / tempo / mood mong muốn?
6. **CGI/Kỹ xảo, Nhịp dựng, Đạo diễn/DOP** — có gì đặc biệt?
7. **Động cơ tự động:** Chrome/ChatGPT/Suno/Canva đã sẵn chưa? → chốt AUTO hay FALLBACK.
8. **Scope ảnh** (mặc định: Reference + Keyvisual + storyboard *chọn lọc*).
9. **Output:** mặc định xuất **kép (Canva + PPTX)**.

> Mẹo: trả lời câu 1 + dán kịch bản là agent có thể chạy với mặc định hợp lý cho phần còn lại; nó sẽ báo các giả định để bạn duyệt.

## 4. Quy trình 12 bước agent thực hiện

```
1  Xác định tầng (T1/T2/T3)
2  Kéo đầu vào: kịch bản + (T3) insight + hồ sơ Đạo diễn/DOP
3  Kiểm tra động cơ tự động → chốt AUTO/FALLBACK từng asset
4  Chốt palette deck & font
5  Thiết kế 3 Điểm Chạm (lớp ý đồ = text trước)
6  Bẻ kịch bản → shot (+ góc nhìn Đạo diễn/DOP per-shot)
7  ★ Tạo ẢNH: reference + keyvisual + shot chọn lọc (ChatGPT Image 2)
8  ★ Tìm REFERENCE: góc máy / chuyển động máy / Color Palette (WebSearch)
9  ★ Tạo NHẠC: Suno theo Mood&Tone + cấu trúc act
10 Dựng storyboard, chèn ảnh thật (ô chưa gen giữ prompt ẩn)
11 Slide nghỉ/hook + Stillomatic + Lời cuối
12 ★ Ráp KÉP: file Canva + PPTX → trả link/file + Bảng truy vết asset
```

**Nguyên tắc:** text trước → gen asset → ráp file. Agent không gen ảnh/nhạc khi chưa chốt Mood & Tone + Color Palette phim.

## 5. Bạn nhận được gì

- **1 link Canva** (sửa trực tiếp trong editor Canva).
- **1 file PPTX** (ô storyboard nhúng ảnh thật; ô chưa gen có prompt ẩn trong speaker note).
- **Bảng truy vết asset**: mỗi asset ghi rõ `tên · loại (gen/ref/nhạc) · nguồn · prompt/truy vấn · trạng thái (đã chèn / chờ QC / fallback)` → bạn biết ngay cái gì auto, cái gì cần tự hoàn thiện.

## 6. QC & update (việc của bạn)

- Duyệt ảnh AI-generated (đánh nhãn *"chờ QC"*) — giữ/chỉnh/gen lại.
- Nghe nhạc Suno (*"demo định hướng"*) — chọn phương án.
- Kiểm reference đã ghi nguồn.
- Với ô storyboard chưa gen: mở speaker note, copy prompt ẩn, tự tạo ảnh và chèn đè.

## 7. Ranh giới trung thực (skill cam kết)

- ❌ Không bịa insight / big idea / credentials / số liệu / giải thưởng.
- 🏷️ Ảnh AI luôn gắn nhãn *"AI-generated — chờ QC"*; nhạc *"demo định hướng"*; reference **ghi nguồn**; stillomatic giữ disclaimer.
- 🔁 Thiếu công cụ → fallback minh bạch, không giả vờ đã làm.
