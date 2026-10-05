# Track1_Day19_2A202602649_NguyenLongKhanh

## 1. Thông tin cá nhân và nhóm
- **MHV:** 2A202602649
- **Họ tên:** Nguyễn Long Khánh
- **Tên nhóm:** 3aecaykhe
- **Thành viên:** Nguyễn Văn An, Lưu Xuân Dũng, Nguyễn Long Khánh
- **Case:** Case B — AI Notes: Personal Learning Notes

## 2. Hypothesis Problem
Khi cần ôn tập hoặc dùng lại kiến thức đã học trong khóa online (VLearn) sau một thời gian, người học tự ghi chú gặp khó khăn trong việc tiếp cận đúng ý cần dùng và quay về nội dung gốc, vì ghi chú nằm phân tán (theo từng slide trên nền tảng, hoặc ở công cụ riêng tách khỏi slide) và AI bên ngoài không biết ngữ cảnh bài học, dẫn đến phải dò lại slide, chuyển qua lại giữa nhiều công cụ và mất thêm công để tìm lại.

- **Dấu vết Day 17:** An-P01 chuyển từ note theo slide trên VLearn sang Notion vì note phân tán (03:53); SV1 phải lục slide rồi mới tìm được note, và phải prompt kỹ vì AI trả lời chung chung.
- **Chưa chứng minh:** độ phổ biến (An-P01 02:09 và SV2 không thấy khó khi tìm trong công cụ riêng); barrier có thể là hiểu kiến thức (Dũng-P01); người học cần AI hay chỉ cần truy cập nhanh.

Chi tiết ở [three-option-design-sheet.md](three-option-design-sheet.md).

## 3. Three Solution Options
Cả ba cùng giải một task: học viên đang làm Lab, cần tìm lại ý "làm rất tốt một thứ không ai cần", biết nó đến từ đâu, rồi viết một câu có dẫn nguồn vào bài Lab. Ba option khác nhau ở **ai làm phần việc nào** (user tự làm → user + AI → AI khởi động, user duyệt).

| | A — Gom ghi chú, gắn nguồn, tự tìm | B — Bôi đen để ghi chú tại nguồn | C — Trợ lý chủ động gom |
|---|---|---|---|
| Cơ chế | Ghi chú của cả khóa gom về tab Ghi chú, mỗi cái gắn video/mốc thời gian/slide; tìm từ khóa trên ghi chú và slide | Bôi đen (hoặc bấm) một câu trong Transcript → Thêm vào ghi chú · Chưa hiểu · Chèn vào bài Lab; ghi chú tự gắn nguồn | Khi học viên bấm vào ô bài Lab, trợ lý gom ghi chú liên quan kèm "Vì sao gợi ý" và mức chắc chắn |
| Vai trò AI | Không có | Chỉ gợi ý thẻ, học viên bấm mới gắn | Chọn ghi chú và giải thích; không tự chèn |
| Kiểm soát / khôi phục | Đổi từ khóa, mở nguồn, Hoàn tác, bỏ nguồn "×" | Bỏ chọn, Hoàn tác, Xóa, bỏ thẻ | Bỏ, Hoàn tác, Tắt gợi ý (bật lại được) |

- **Prototype A/B/C (link chung của nhóm):** https://claude.ai/artifact/Uksm7P8XQ8hNXCuP8mv25H · cách dùng ở [prototype-link.md](prototype-link.md)
- **Màn thiết kế tĩnh (Claude Design):** https://claude.ai/artifact/Snx6wtgwPtrTs9PkPA7YvR

## 4. Đóng góp của tôi trong nhóm
- **Phỏng vấn 1 và 2 (SV1, SV2):** tôi thực hiện hai cuộc phỏng vấn học viên ở Day 17. Đây là nguồn evidence của Practice Note 3, dùng để cập nhật Hypothesis Problem sang hướng "khó tìm lại và quay về nguồn" (Interview Record ở Chặng 3 Day 17).
- **Chốt Option B:** tôi quyết định hướng cuối của Option B là "bôi đen để ghi chú tại nguồn", thay cho hai hướng trước đó ("hỏi trợ lý" và "tả ý, AI tìm ghi chú gần nghĩa").
- **Cải thiện prototype:** tôi đề xuất và kiểm tra các vòng cải thiện prototype A/B/C, gồm chuyển sang giao diện học video giống VLearn, làm flow end-to-end và tăng độ dễ dùng.

## 5. Prototype Feedback
> **Trạng thái:** Chưa test — phiên test của tôi chưa thực hiện được trong giờ lab do hết thời gian; sẽ bổ sung trước deadline. Prototype đã sẵn sàng để test (Gate 4), chưa có dữ liệu cho Gate 5.

- **Feedback Note phiên tôi facilitate:** [prototype-feedback-note.md](prototype-feedback-note.md)
- **Tổng hợp ba feedback của nhóm:** [group-feedback-synthesis.md](group-feedback-synthesis.md)
- **Observation nổi bật từ phiên của tôi:** [điền sau khi test]
- **Next Change nhóm chốt:** [điền sau khi tổng hợp]
- **Still Unproven:** [điền sau khi tổng hợp]

## 6. AI Support Log
Chi tiết ở [ai-support-log.md](ai-support-log.md). Tóm tắt: AI hỗ trợ chép ghi âm phỏng vấn, soạn bản nháp design sheet và bảng Human–AI, viết code prototype và dữ liệu mẫu, chuẩn bị kịch bản test. AI không tạo quote, observation hay feedback của tester và không viết phần đóng góp/reflection cá nhân.

## Checklist trước khi nộp
- [x] Repo đúng tên `Track1_Day19_2A202602649_NguyenLongKhanh` (xác nhận với giảng viên/TA nếu đề ghi Day18)
- [x] Design sheet đủ Chặng 1–5; ba prototype cùng user, situation, task, content và desired outcome
- [x] Link prototype mở được ("Anyone with the link")
- [ ] (Bổ sung trước deadline) Đã test cả A/B/C với 1 tester ngoài nhóm và điền [prototype-feedback-note.md](prototype-feedback-note.md)
- [ ] Nhóm đủ 3 Feedback Notes, đã điền [group-feedback-synthesis.md](group-feedback-synthesis.md) (pattern, Next Change, Still Unproven)
- [ ] Tự viết mục 4 "Đóng góp của tôi" và mục 3–4 trong AI Support Log
- [ ] Repo để private và đã mời giảng viên/TA; các link mở được với giảng viên/TA
