# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: BacHo
- Candidate problem nhóm chọn (1 câu): Sinh viên phụ trách ghép report nhóm có phần phân tích dữ liệu mất khoảng 3–4 tiếng sát deadline để đồng bộ số liệu, biểu đồ và viết lại insight của các thành viên thành một report thống nhất
- Quyết định cuối (Go / Not Yet / No-Go): Go, phạm vi nhỏ: pilot No AI + Rule trước, AI chỉ ở bước đọc chéo phát hiện mâu thuẫn (mục 8 `group_report.md`)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Trần Hải Long | 202603891 | Nhóm trưởng: fork repo, commit báo cáo nhóm, review CP3–CP6 | longhtr028 |
| 2 | Lê Danh Giang | 202603912 | Phản biện, research | giangj |
| 3 | Nguyễn Đức Hải | 2A202603899 | Soạn bản nháp báo cáo nhóm (CP3–CP6), research, tổng hợp kết quả phỏng vấn | hainguyen312 |
| 4 | Trần Tuấn Anh | 2A202603909 | Phụ trách kiểm chứng (phỏng vấn), cung cấp candidate được chọn | Tanh0406 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Đức Hải | Trần Hải Long, Lê Danh Giang | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Trần Tuấn Anh | Nguyễn Đức Hải (tổng hợp), Trần Hải Long (rút gọn câu hỏi) | Assumption map, snapshot hoặc survey |
| CP4 — Research | Nguyễn Đức Hải, Lê Danh Giang | | Bảng research có link |
| CP5 — Quy trình trước/sau | Nguyễn Đức Hải | Lê Danh Giang, Trần Tuấn Anh (số liệu quy trình) | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Nguyễn Đức Hải | Trần Hải Long (review) | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Đức Hải, Lê Danh Giang | Trần Hải Long (review) | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Nguyễn Đức Hải | Trần Hải Long (review) | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên một mục, tiêu đề là `HoVaTen-MSSV`.

### TranHaiLong-202603891

**Phần việc phụ trách:**

- Nhóm trưởng: fork repo chung, điền thông tin nhóm, gom bài lên `main`
- CP3: pitch 3 Problem Card (#7 công việc ngoài giờ lên lớp của giáo viên, #8 đọc bài nghiên cứu trước seminar, #9 hộ kinh doanh tự kê khai thuế)
- CP4: rút gọn câu hỏi phỏng vấn
- CP3–CP6: review cluster, cây OST, bảng chấm điểm, quy trình, Problem Statement v0/v1, mức can thiệp AI và quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp 3/12 candidate; card #8 (đọc bài nghiên cứu) vào shortlist. Sau phản biện, nhóm loại card giáo viên và hộ kinh doanh vì khó phỏng vấn đúng người
- Commit bản nháp báo cáo nhóm do Hải soạn (`1426d8e`)
- Rút gọn câu hỏi phỏng vấn còn 3 câu, được dùng ở mục 3.1 báo cáo nhóm
- Gom 4 báo cáo cá nhân và phần cá nhân trong `TEAM.md` lên `main`

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng pitch #7–#9), mục 2.4 (lý do loại #9), mục 3.1 (câu hỏi phỏng vấn)
- Báo cáo cá nhân: `report/individual/202603891_TranHaiLong.md`
- Commit trên `main`: `1426d8e` (draft group report), `1d8ba68` (update basic info), `22dd774` (gom báo cáo cá nhân)
- Commit trên nhánh `TranHaiLong-03891`: `8ae63cc` (thêm báo cáo cá nhân), `8f8f534` (CP1, CP2), `947e43b` (hoàn thiện báo cáo cá nhân)

**Điều mình học được từ phần nhóm:**

- Problem phải kiểm chứng được với đúng người trong thời gian làm bài: card giáo viên và hộ kinh doanh có impact lớn nhưng bị loại vì nhóm không phỏng vấn được actor thật
- Gợi ý của AI cần được đọc lại kỹ: dòng "tìm thông tin khi làm việc" do AI viết quá chung nên phải bỏ

### LeDanhGiang-202603912

**Phần việc phụ trách:**

- Pitch 3 Problem Cards ban đầu (#4, #5, #6).
- Phản biện bài toán, tìm hiểu công cụ có sẵn (CP4).
- Hỗ trợ viết Problem Statement v1 (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp 3/12 candidate ban đầu để nhóm lựa chọn.
- So sánh các công cụ (Google Docs, Gemini Notebook) để chốt mức độ dùng AI là Workflow.
- Xác định Boundary: AI chỉ tìm mâu thuẫn, không tự sửa file.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 2.1 (Pitch), 3.3 (Research giải pháp) và 7 (Problem Statement v1) trong `group_report.md`.
- Báo cáo cá nhân: `report/individual/202603912_LeDanhGiang.md`
- Commit trên nhánh `LeDanhGiang-03912`: `62f489d` (tạo báo cáo cá nhân), `aa1eb24` (bổ sung đóng góp và reflection), `fa2214d`, `a2d02e0` (cập nhật `TEAM.md`)

**Điều mình học được từ phần nhóm:**

- Học được cách dùng số liệu thực tế để đo lường nút thắt thay vì nói chung chung.
- Hiểu được rào cản lớn nhất khi dùng AI là rủi ro bịa thông tin (hallucination), nên luôn cần con người duyệt lại (Human-in-the-loop).

### NguyenDucHai-2A202603899

**Phần việc phụ trách:**

- CP3: pitch 3 Problem Card (#1 kiểm tra yêu cầu nộp bài lab, #2 backend đổi API, #3 dựng màn hình từ Figma) và phản biện card của bạn khác; soạn bản nháp cluster, cây OST, bảng chấm điểm
- CP4: research công cụ đã có; tổng hợp kết quả phỏng vấn vào báo cáo nhóm
- CP5–CP6: soạn bản nháp quy trình trước/sau, Problem Statement v0 và v1, mức can thiệp AI và quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch card #1 "kiểm tra yêu cầu nộp bài lab": vào shortlist (30 điểm, xếp thứ 2). Sau câu phản biện của Tuấn Anh, tự rút #1 và ủng hộ chuyển sang #11 vì có số liệu hành vi thật
- Phản biện card #4 của Giang ("Lần gần nhất bạn thật sự vượt ngân sách là khi nào?"), góp phần loại #4
- Soạn bản nháp báo cáo nhóm phần CP3–CP4 (Long commit ở `1426d8e`): 4 cluster, cây OST gạch 3 ý là solution đội lốt opportunity, bảng chấm điểm, assumption map
- Research 3 công cụ (Google Docs tabs, Gemini trong Docs, Gemini Notebook), tự mở từng link; kết luận phần trễ hạn và sai format giải được bằng No AI, không có lý do tự xây agent
- Tổng hợp câu trả lời phỏng vấn vào mục 3.2: bảng tín hiệu xác nhận/phản bác và phần "Nhóm đã sửa problem thế nào"
- Soạn quy trình trước/sau, Problem Statement v0 → v1, bảng 4 mức, AI Canvas, 5 tiêu chí đánh giá, 4 rủi ro, quyết định "Go, phạm vi nhỏ" với 3 ngưỡng dừng; mục 9–10

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng pitch #1–#3), mục 2.2–2.4 (cluster, OST, chấm điểm, xử lý bất đồng), mục 3.1, 3.2 (tổng hợp và "Nhóm đã sửa problem"), 3.3 (research), mục 4–10
- Báo cáo cá nhân: `report/individual/2A202603899_NguyenDucHai.md`
- Commit trên `main`: `f4b3d30` (update group-report), `f0e5a3e` (update assets, group-report)
- Commit trên nhánh `NguyenDucHai-03899`: `19452bd` (CP1, CP2), `0f4ca35` (thêm problem CP1)

**Điều mình học được từ phần nhóm:**

- Trước khi chọn một vấn đề, cần kiểm tra xem vấn đề đó đã có cách giải chưa.
- Lựa chọn theo tiêu chí nhất định chứ không lựa chọn theo cảm tính.

### TranTuanAnh-2A202603909

**Phần việc phụ trách:**

- CP3: pitch 3 Problem Card (#10 Vinmotion, #11 ghép report nhóm, #12 đọc bài báo NCKH) và phản biện card của bạn khác
- CP4: kiểm chứng bằng phỏng vấn (người chính theo bảng phân công)
- Cung cấp số liệu cho quy trình hiện tại và Problem Statement; người chạy pilot ở mục 8.2

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đưa ra candidate #11 "ghép report nhóm" kèm bằng chứng hành vi đã xảy ra: lần gần nhất mất ~3 tiếng, 2/6 người nộp trễ 1 ngày, 1/6 sai format mất 45' sửa. Nhóm chọn candidate này (33/35 điểm)
- Phản biện card #1 của Hải ("SUBMISSION.md đã có checklist, vậy pain còn lại nằm ở đọc đề hay tự kiểm?"), góp phần loại #1
- Soạn 3 câu hỏi phỏng vấn theo The Mom Test; phỏng vấn 1 Data Analyst từng ghép report nhóm (nhắn tin, 9/11/2026); ghi nguyên văn câu trả lời thành interview snapshot
- Kết quả phỏng vấn phản bác giả định #2, làm nhóm đổi bottleneck từ "đọc và hỏi lại người viết" sang "đồng bộ số liệu, biểu đồ và viết lại insight", và thu hẹp actor thành người ghép report có phân tích dữ liệu
- Cung cấp quy trình 5 bước và baseline 180' của report Big Data (nguồn "TA" trong quy trình hiện tại và Success Metric)
- Tự rút card #10 (Vinmotion) vì là quy trình nội bộ, chỉ mình tôi biết, khó kiểm chứng

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng pitch #10–#12 và câu hỏi phản biện #1), mục 2.4 (lý do chọn #11), mục 3.1 (câu hỏi phỏng vấn), mục 3.2 (interview snapshot người thứ 1 và "Nhóm đã sửa problem thế nào"), mục 4.1 (số liệu "TA"), mục 8.2 (pilot)
- `report/assets/cp4-interview-snapshot-1.md`, `report/assets/cp4-interview-chat-1.png`
- Báo cáo cá nhân: `report/individual/2A202603909_TranTuanAnh.md` (Problem Card #2 là nguồn của candidate nhóm)
- Commit trên nhánh `Tanh`: `46a5677` (CP1–CP2), `7120ca1` (3 Problem Card + quy trình nháp), `9697ef3` (hoàn thiện báo cáo cá nhân, cập nhật report nhóm, điền hình thức snapshot)

**Điều mình học được từ phần nhóm:**

- Một problem tốt không nằm ở impact nghe lớn mà ở bằng chứng hành vi và khả năng kiểm chứng. Vì vậy card #9 (thuế hộ kinh doanh) và card Vinmotion của tôi đều bị loại
- Phỏng vấn người thật có thể làm đổi bottleneck: giả định "đọc và hỏi lại" của tôi bị phản bác ngay ở người đầu tiên
- Phỏng vấn một người quen là chưa đủ. Cần hỏi thêm người không quen nhóm và hỏi thẳng họ muốn AI hỗ trợ hay giao hẳn việc
