# Prototype A/B/C

- **Link chung của nhóm:** https://claude.ai/artifact/Uksm7P8XQ8hNXCuP8mv25H
  - Link đang ở chế độ riêng tư; cần bật chia sẻ (Share) trước khi gửi cho tester, giảng viên và TA.
- **Mã nguồn:** `prototype/index.html`. Có thể mở trực tiếp bằng trình duyệt nếu không dùng link.

## Cách dùng (flow end-to-end)
1. **Màn đầu:** đọc tình huống và nhiệm vụ, chọn **Phương án A / B / C**.
2. **Màn học video** (giống giao diện VLearn): menu bài học, video "Video 01. Mở đầu" (bấm ▶ để chạy, bấm thanh tua để nhảy đoạn), ô **Nháp Lab · Chặng 1 · phần Change**, panel phải có tab **Transcript · Ghi chú · Tài liệu**.
   - **A:** tab Ghi chú → chọn phạm vi (Video này / Tất cả ghi chú của khóa) → gõ từ khóa → bấm nguồn để mở lại đúng đoạn video, hoặc "Chèn nguồn vào nháp".
   - **B:** tab Transcript → bôi đen hoặc bấm vào một câu → thanh thao tác: Thêm vào ghi chú · Chưa hiểu · Chèn vào nháp → ở tab Ghi chú: viết ý riêng, nhận/bỏ thẻ AI gợi ý, chèn vào nháp; có Hoàn tác, Xóa.
   - **C:** khi người học bấm vào ô nháp Lab, trợ lý tự mở tab Ghi chú với 3 gợi ý (kèm "Vì sao gợi ý" và mức chắc chắn) → Chèn vào nháp / Bỏ / Hoàn tác / Tắt gợi ý (bật lại được).
   - Ở mọi phương án: nguồn đã chèn hiện dưới ô nháp, bỏ được bằng "×".
3. **Màn kết quả:** bấm "Xong phương án này" để xem nháp và nguồn đã gắn → **Thử phương án khác**, **Làm lại**, hoặc **Về màn đầu** (màn đầu đánh dấu phương án đã thử).
4. **Bắt đầu lại** ở thanh trên cùng luôn đưa về màn đầu, xóa nháp.

## Hướng dẫn trong app
- Mỗi phương án có **hướng dẫn nhanh 3 bước**, hiện khi mở phương án. Mỗi bước có viền vàng chỉ vào đúng chỗ trên màn hình, kèm nút Tiếp / Quay lại / Bỏ qua (Esc để đóng).
- Nút **Hướng dẫn** trên thanh trên cùng để xem lại bất cứ lúc nào.
- Ở màn đầu có ô **"Hiện hướng dẫn nhanh khi mở mỗi phương án"** (mặc định bật).
- **Khi test:** nhóm nên thống nhất bật hay tắt cho cả 3 tester và ghi lại trong Feedback Note. Tắt hướng dẫn thì quan sát được người dùng có tự khám phá ra cách dùng không. Bật thì kiểm tra hướng dẫn có đủ rõ không.

## Ghi chú kỹ thuật
- HTML/CSS/JS thuần, không gọi model hay API thật. Transcript Video 01 ở B là dữ liệu mẫu (trừ câu 0:42 lấy từ phụ đề video thật); thẻ AI gợi ý ở B và gợi ý ở C đều viết sẵn.
- Dữ liệu slide và ghi chú là dữ liệu mẫu, viết theo phong cách ghi chú của SV1.
- Mỗi thao tác được ghi vào console trình duyệt với tiền tố `[proto]`. Facilitator có thể xem lại thứ tự thao tác; tester không thấy.
