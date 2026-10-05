# AI Support Log

**Công cụ:** Claude (Claude Code trên claude.ai) · **Người dùng:** Nguyễn Long Khánh
**Nguyên tắc đã giữ:** AI không tạo quote, observation hay feedback của tester; không viết phần đóng góp cá nhân và reflection. Dữ liệu trong prototype là dữ liệu mẫu, có ghi rõ trên màn hình.

## 1. AI đã giúp gì (theo thứ tự thực hiện)

| # | Việc | Đầu vào tôi đưa | Đầu ra của AI | Tôi quyết định / kiểm tra |
|---|---|---|---|---|
| 1 | Chuyển ghi âm phỏng vấn Day 17 (SV1, SV2) sang văn bản | 2 file ghi âm | Bản chép thô có mốc thời gian và bản biên tập, đánh dấu `[?]` chỗ nghe không rõ; thay tên thật bằng mã SV1/SV2 | [ghi lại bạn đã nghe lại những đoạn nào] |
| 2 | Hoàn thiện Chặng 1–3 Day 17 | File Chặng 1–3 của nhóm + bản chép | Bảng đối chiếu evidence, Hypothesis cập nhật (chuyển trọng tâm sang Pain B), 2 Interview Record, tự đánh giá Checkpoint 3 | Quote lấy nguyên văn từ bản chép |
| 3 | Đọc đề và gộp Practice Notes | Nội dung đề (dán từ VLearn), README Day 17 của An và Dũng | Evidence huddle 3 note, Hypothesis Problem, Parking Lot gộp 10 hướng | Chỉ dùng mã P01/SV1/SV2, không dùng tên thật |
| 4 | Gợi ý ba Solution Options, distance check, Human–AI Decision Table | Hypothesis, Parking Lot | Bản nháp A/B/C và bảng quyết định | Tôi đổi Option B hai lần: (1) từ "hỏi trợ lý" sang "tả ý, AI tìm ghi chú gần nghĩa"; (2) sang "bôi đen để ghi chú tại nguồn" |
| 5 | Viết code micro-prototype | Design sheet, ảnh màn VLearn gốc | `prototype/index.html` (HTML/CSS/JS, không gọi model thật); sau đó dựng lại trên giao diện học video giống VLearn với flow màn đầu → màn học → màn kết quả | Tôi yêu cầu chuyển sang giao diện học video gốc để tester thấy quen |
| 6 | Cải tiến dễ dùng | Yêu cầu "dễ dùng nhất có thể" | Hoàn tác sau khi chèn, tô từ khóa, xếp hạng kết quả, dòng hướng dẫn, dòng nhắc gợi ý ở C, hướng dẫn 3 bước trong app (bật/tắt được), đổi "Nháp" thành "Bài Lab của bạn" | Giữ nguyên nguyên tắc không mớm từ khóa cho A |
| 7 | Màn tĩnh A/B/C trên Claude Design và file xuất cho Figma | Ảnh màn VLearn gốc | 3 màn 1440×900, file PNG/HTML | Figma không nhận trực tiếp; phải nhập bằng plugin |
| 8 | Dữ liệu mẫu | Slide và phụ đề quan sát được (câu 0:42 lấy từ video thật) | 4 câu transcript, 5 ghi chú mẫu, 2 slide mẫu, thẻ gợi ý và gợi ý của trợ lý viết sẵn | Dữ liệu mẫu, không phải ghi chú của ai |
| 9 | Chuẩn bị test | Đề Chặng 5–6 | Câu hỏi relevant context, outcome task, observation focus, kịch bản 20 phút, mẫu Feedback Note và Group Synthesis | Phần quan sát để trống, tôi tự điền sau phiên test |
| 10 | Repo nộp bài | Cấu trúc đề yêu cầu | Tạo và đẩy các file lên GitHub | Tôi kiểm tra quyền truy cập repo và link prototype |

## 2. Dữ kiện về chỗ AI sai hoặc phải sửa (để tôi tự đánh giá ở mục 3)
Những điều sau đã xảy ra trong quá trình làm, ghi lại để đối chiếu:
- Nhận dạng giọng nói tiếng Việt sai nhiều từ (tên khóa học, thuật ngữ) và tách người nói sai ở file ngắn; phải đánh dấu `[?]`.
- Phiên bản prototype đầu tiên không theo giao diện VLearn, khung tình huống khác thực tế.
- Option B ban đầu ("hỏi trợ lý, AI đề xuất câu viết") làm AI viết hộ người học; đã đổi.
- Tìm kiếm ở Option A ban đầu khớp từng chữ riêng lẻ nên ra kết quả lạc (ví dụ "Day 15 · slide 7" chỉ vì chữ "không"); đã sửa để khớp ít nhất 2 từ.
- Nút trên thanh thao tác ở màn B bị xuống dòng; đã sửa.
- Ảnh xuất PNG dùng font dự phòng nên chữ khác bản trên canvas.
- AI không truy cập được trang VLearn (cần đăng nhập) và không ghi được vào Figma.

## 3. AI sai hoặc hời hợt ở đâu (tự viết)
> Gợi ý: chọn 2–3 điểm ở mục 2 hoặc điểm bạn tự thấy; nói vì sao đó là vấn đề với bài lab (ví dụ ảnh hưởng tới tester, tới tính trung thực của evidence).

[Tự viết]

## 4. Tôi đã tự sửa hoặc quyết định gì (tự viết)
> Gợi ý: những quyết định bạn đưa ra khác với đề xuất của AI (ví dụ đổi Option B, chọn giao diện VLearn), và những gì bạn tự kiểm tra lại (nghe lại ghi âm, thử prototype).

[Tự viết]
