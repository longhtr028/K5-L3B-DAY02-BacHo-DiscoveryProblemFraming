# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: BacHo
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): *(đề xuất, chờ nhóm chốt)* Sinh viên phụ trách ghép report nhóm mất khoảng 3 tiếng sát deadline để thu, đọc, hỏi lại và sửa các phần của thành viên thành một report thống nhất
- Quyết định cuối: *(đề xuất, chờ nhóm chốt)* Go, phạm vi nhỏ: pilot No AI + Rule trước, AI chỉ ở bước đọc chéo phát hiện mâu thuẫn (xem mục 8)

---

## 2. Hội tụ nhóm (CP3)

Nhóm 4 người, 12 candidate (top 3 của mỗi người).

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Hải | Khi bắt đầu lab mới, muốn biết ngay phải nộp file gì, đặt tên ra sao, để không bị trừ điểm cấu trúc | Học viên K5 | Tự dò lại rubric/checklist trước khi nộp, khoảng 15 phút | SUBMISSION.md đã có checklist, pain còn lại nằm ở đọc đề hay tự kiểm? (Tuấn Anh, dự kiến) |
| 2 | Hải | Khi backend đổi API không báo, FE muốn biết sớm để không lỗi lúc QA/demo | FE dev | Hỏi và chờ BE xác nhận, khoảng 20 phút | Team đã có API spec chưa? Nếu có thì pain còn không? |
| 3 | Hải | Khi dựng màn hình từ Figma, muốn đúng ngay lần đầu để không bị designer trả lại | FE dev, designer | Sửa theo review, khoảng 2 vòng, 30 phút | Lỗi do FE dựng sai hay do design thay đổi? |
| 4 | Giang | Khi dùng nhiều API AI, muốn biết nhanh tổng token và chi phí trong ngày để không vượt ngân sách | Sinh viên/dev làm dự án AI | Gom số từ nhiều dashboard, khoảng 10 phút | Lần gần nhất bạn thật sự vượt ngân sách là khi nào? (Hải, dự kiến) |
| 5 | Giang | Khi đi qua cầu giờ cao điểm, muốn biết điểm kẹt để đổi lộ trình | Người đi học/làm ở HN | Tìm tin kẹt xe trong các hội nhóm | Dữ liệu realtime lấy ở đâu, nhóm có tiếp cận được không? |
| 6 | Giang | Khi xe máy khó nổ buổi sáng, muốn biết kiểm tra bộ phận nào trước | Người đi xe số cũ | Tra cứu chung chung, không biết bắt bệnh từ đâu | Đây là thiếu thông tin hay thiếu kỹ năng sửa xe? |
| 7 | Long | Khi làm việc ngoài giờ lên lớp, giáo viên muốn không phải làm lại phần lặp lại | Giáo viên | Soạn giáo án, khoảng 300 phút/tuần | Nhóm không có ai là giáo viên, CP4 phỏng vấn ai? |
| 8 | Long | Khi phải đọc 3–4 bài nghiên cứu trước seminar, muốn nắm luận điểm và phương pháp | Sinh viên | Đọc kỹ, tối đa 60 phút/bài | Đo "đã nắm được bài" bằng cách nào? |
| 9 | Long | Khi đến kỳ kê khai thuế sau khi bỏ thuế khoán, chủ hộ kinh doanh muốn biết phải ghi chép gì, khai mẫu nào, hạn nào, để nộp đúng hạn mà không phải nhờ hướng dẫn nhiều lần | Chủ hộ kinh doanh nhỏ, nhất là người lớn tuổi | Tìm hiểu phải khai mẫu nào, hạn nào, khoảng 45 phút/kỳ (ước tính) | Con số 120 phút/kỳ đo từ ai? Nhóm có phỏng vấn được chủ hộ kinh doanh thật không? |
| 10 | Tuấn Anh | Khi thu dữ liệu ca tối ở Vinmotion, muốn phát hiện sớm lượt lỗi và lỗi hệ thống để thu lại kịp trong ca | Data collector part-time | Hệ thống kiểm tra khoảng 3 phút/lượt, chỉ báo sau khi lượt xong | Dữ liệu nội bộ công ty, nhóm có kiểm chứng với người khác được không? |
| 11 | Tuấn Anh | Khi gần deadline report nhóm 7 người, muốn nhận đủ phần đúng hạn, đúng format và nắm nhanh nội dung để ghép thành report thống nhất | Sinh viên phụ trách ghép report | Đọc từng phần và hỏi lại người viết, khoảng 80 phút | Nếu mọi người nộp đúng hạn, đúng format thì bước đọc có còn là bottleneck không? |
| 12 | Tuấn Anh | Khi nhóm NCKH vướng xử lý dữ liệu, muốn tìm đúng 3 bài báo và rút ra cách xử lý | Thành viên nhóm NCKH | Đọc phần phương pháp, khoảng 30 phút/bài | Khác gì candidate #8 của Long? Chỉ 3–4 tuần/lần có đủ impact không? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Đọc nhanh tài liệu dài | #8, #12 | Phải đọc nhiều bài dài, nhiều thuật ngữ để rút ý chính trước một hạn cụ thể |
| B — Tự tìm và đối chiếu thông tin rời rạc mới làm đúng được | #4, #9 | Thông tin cần nằm rải ở nhiều nơi (nhiều dashboard, nhiều văn bản hướng dẫn), phải tự gom và đối chiếu |
| C — Ghép phần việc của nhiều người | #11, #2, #3 | Đầu ra của người khác đến muộn, sai format hoặc thay đổi mà không báo; người nhận phải đọc, hỏi lại rồi ghép |
| D — Kiểm đầu ra trước khi chốt | #1, #10 | Chỉ biết đầu ra đạt hay không khi đã xong, phải làm lại |
| Ngoài cluster | #5, #6, #7 | Ngoài tầm dữ liệu hoặc domain của nhóm |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian người ghép report nhóm cần để có bản thống nhất trước hạn, mà chất lượng report không giảm
├── Opportunity A: Một số thành viên nộp trễ, việc ghép bị dồn sát deadline
├── Opportunity B: Phần nộp sai format, người ghép phải sửa tay
├── Opportunity C: Phải đọc từng phần và hỏi lại người viết mới hiểu nội dung (bottleneck hiện tại, khoảng 80 phút)
└── Opportunity D: Các phần trùng ý hoặc mâu thuẫn nhau, khó thống nhất văn phong và kết luận
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ "Template Google Docs chung": là solution cho A/B, để dành so sánh ở CP6 (mức No AI).
- ✗ "Bot nhắc deadline": là solution cho A (mức Rule).
- ✗ "AI tóm tắt từng phần": là solution cho C, chưa nói pain là gì.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Ghép report nhóm nhiều người | 5 | 4 | 5 | 4 | 5 | 5 | 5 | **33** |
| Đọc đề và tự kiểm bài lab | 5 | 5 | 3 | 3 | 5 | 4 | 5 | 30 |
| Đọc bài nghiên cứu | 4 | 4 | 4 | 3 | 4 | 5 | 4 | 28 |

**Candidate được chọn:** #11 — Sinh viên phụ trách ghép report nhóm mất khoảng 3 tiếng sát deadline để thu, đọc, hỏi lại và sửa các phần của thành viên thành một report thống nhất.

**Vì sao chọn:**

- **Bằng chứng là hành vi đã xảy ra:** lần gần nhất mất khoảng 3 tiếng; 2/6 người nộp trễ 1 ngày dù đã giục; 1/6 nộp sai format, mất 45 phút sửa (CP1 #4, #10 và Problem Card #2 của Tuấn Anh).
- **Dễ kiểm chứng ở CP4:** hầu như sinh viên nào cũng từng làm report nhóm, nên dễ tìm người ngoài nhóm để hỏi về lần ghép report gần nhất.
- **So sánh được cả 4 mức:** trễ hạn và sai format có thể giải bằng No AI/Rule (template, deadline nội bộ); bước đọc hiểu và phát hiện mâu thuẫn mới là chỗ cần cân nhắc Workflow. Bài có khả năng ra kết luận "phần lớn không cần AI", đúng tinh thần lab.
- **Cả nhóm hiểu domain:** cả 4 người đều đang làm báo cáo nhóm (chính lab này).

**Vì sao loại các candidate còn lại:**

- #1 (đọc đề, tự kiểm bài lab): quy trình rõ nhưng dấu hiệu mới là ước lượng của 1 người (ý tương tự của Tuấn Anh là ý từ AI); phần lớn đã giải được bằng checklist có sẵn, khả năng chỉ dừng ở Rule.
- A (đọc bài nghiên cứu): nhiều người gặp nhưng "đã nắm được bài" khó đo trong thời gian lab; #12 chỉ xảy ra 3–4 tuần/lần. Đưa vào hướng tiếp theo.
- #10 (Vinmotion): số liệu thật và chi tiết nhưng là quy trình nội bộ công ty, chỉ 1 người trong nhóm biết, khó kiểm chứng với người ngoài.
- #4 (token/chi phí API): mới có 1 người gặp; các nhà cung cấp đã có usage dashboard.
- #9 (hộ kinh doanh tự kê khai thuế): impact rộng (3,08 triệu hộ) nhưng thời gian từng bước mới là ước tính; actor là chủ hộ kinh doanh, nằm ngoài lớp nên khó phỏng vấn trong buổi lab; quy định thuế cần chính xác tuyệt đối, chính Long cũng đánh giá checklist (Rule) có thể đủ.
- #5, #6, #7: ngoài tầm dữ liệu (giao thông realtime), ngoài domain (sửa xe), hoặc nhóm không có actor để phỏng vấn (giáo viên).

**Xử lý bất đồng (nếu có):** Bản nháp đầu của Hải đề xuất #1 (đọc đề và tự kiểm bài lab). Khi so lại bằng chứng, #11 có số liệu hành vi thật của nhiều người (trễ hạn, sai format, thời gian sửa) trong khi #1 chủ yếu là ước lượng, nên đề xuất đổi sang #11. *(Nhóm điền kết quả thảo luận thật.)*

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên khác ghép report nhóm cũng mất trên 90 phút mỗi lần | Value | 5 | 2 | ✅ |
| 2 | Bước tốn nhất là đọc và hỏi lại nội dung từng phần, không phải chờ người trễ hay sửa format | Value | 5 | 2 | ✅ |
| 3 | Template chung + deadline nội bộ vẫn chưa đủ để giảm thời gian ghép | Value | 4 | 1 | ✅ |
| 4 | Người ghép chấp nhận đọc bản tóm tắt rồi đối chiếu bản gốc, thay vì tự đọc hết | Usability | 3 | 1 | — |
| 5 | Nội dung các phần lấy ra dễ dàng (đều viết trên Google Docs) | Feasibility | 3 | 4 | — |
| 6 | Giảng viên/môn học cho phép dùng công cụ AI hỗ trợ đọc và tổng hợp khi làm report | Viability | 4 | 2 | Hỏi sau lab |

Giả định nhóm kiểm chứng trong buổi này: #1, #2, #3. Sau phỏng vấn người thứ 1: #1 và #3 có tín hiệu xác nhận, #2 có tín hiệu phản bác (xem 3.2).

**Câu hỏi phỏng vấn (theo The Mom Test, hỏi người ngoài nhóm từng ghép report nhóm):**

1. Lần gần nhất bạn ghép report nhóm, bạn đã làm những bước nào, từ lúc thu bài đến lúc nộp?
2. Bước nào mất nhiều thời gian nhất? Khoảng bao lâu? Cả lần đó mất tổng cộng bao lâu?
3. Nhóm bạn đã thử cách nào để đỡ hơn chưa? Kết quả ra sao?

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn theo The Mom Test (câu hỏi ở mục 3.1). Đã phỏng vấn 1 người, ngày 9/11/2026, người phỏng vấn: Tuấn Anh. Hình thức: nhắn tin.

Interview snapshot — người thứ 1 (câu trả lời nguyên văn: [cp4-interview-snapshot-1.md](../assets/cp4-interview-snapshot-1.md)):

| Trường                                            | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | 1 Data Analyst (DA) đang làm việc tại một công ty cung cấp giải pháp công nghệ; người phụ trách gom và ghép report nhóm môn Phân tích dữ liệu                                                                                                                                                                                                                                                                                                                                                                                     |
| Câu nói đáng nhớ nhất (nguyên văn)                | "Phần nhận xét dữ liệu bị rời rạc, không nối tiếp logic từ EDA sang Model, nên người tổng hợp vẫn phải ngồi viết lại toàn bộ phần insight."                                                                                                                                                                                                                                                                                                                                                                                       |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Thứ Năm tuần trước (5/11/2026), ghép report môn Phân tích dữ liệu. Các bước: (1) nhắc các bạn push code và phần phân tích lên Google Drive/GitHub nhóm; (2) kiểm biểu đồ, KPI/metric và nhận xét của từng bạn có khớp với bộ dữ liệu chung không; (3) ghép vào Google Docs, căn lại biểu đồ cho nét, chuẩn hóa font, bảng biểu, viết lại phần giải thích để EDA, Modeling, Insight nối tiếp logic; (4) kiểm tổng thể lần cuối để tránh chênh lệch số liệu giữa các phần, đảm bảo kết luận trả lời đúng mục tiêu; (5) xuất PDF nộp |
| Hiện đang xử lý bằng cách nào (workaround)?       | Đã thử 2 cách: (a) template chung cho biểu đồ và định dạng (bảng màu chart, font, mẫu bảng): hình thức đỡ hơn một chút nhưng các bạn vẫn quên áp dụng khi export ảnh; (b) mỗi người tự đưa phần phân tích vào Google Docs chung trước deadline 1 ngày: vẫn có người trễ hạn, và nhận xét vẫn rời rạc. Người ghép tự chạy lại code để xuất ảnh nét hơn và tự viết lại insight                                                                                                                                                      |
| Mất bao lâu, bao lần?                             | Tổng 5–6 tiếng từ lúc giục gom bài đến lúc nộp. Riêng bước sửa biểu đồ, hình ảnh và đồng bộ logic dữ liệu giữa các phần: 3–4 tiếng (theo lời kể, chưa bấm giờ)                                                                                                                                                                                                                                                                                                                                                                    |
| Insight / opportunity rút ra                      | Bottleneck không nằm ở việc "đọc và hỏi lại người viết" như nhóm giả định, mà ở **đồng bộ số liệu, biểu đồ và nối logic insight giữa các phần**. Người ghép không hỏi lại mà tự chạy lại code và viết lại. Template và Docs chung chỉ giải được một phần hình thức                                                                                                                                                                                                                                                                |

*(Snapshot người thứ 2, 3: thêm bảng tương tự hoặc đặt file trong* `report/assets/cp4-interview-snapshot-N.md`*.)*

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 1 | Tổng 5–6 tiếng, cao hơn nhiều so với ngưỡng 90 phút (giả định #1). Đã thử template chung và Docs chung + deadline sớm 1 ngày nhưng vẫn phải viết lại insight (giả định #3). Vẫn có người trễ hạn dù đã đặt deadline sớm | Bước tốn nhất **không phải** đọc và hỏi lại người viết (giả định #2 sai một phần): người ghép không hỏi lại mà tự chạy lại code, sửa biểu đồ và viết lại insight. Template chung **có** giúp phần hình thức "đỡ hơn một chút", nên một phần pain giải được không cần AI |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- **Đổi bottleneck:** từ "đọc từng phần và hỏi lại người viết" sang "**đồng bộ số liệu, biểu đồ giữa các phần và viết lại insight để EDA → Model → Insight nối tiếp logic**" (3–4 tiếng/lần theo người được hỏi).
- **Thu hẹp actor:** từ "người ghép report nhóm nói chung" sang "**người ghép report nhóm có phân tích dữ liệu** (code, biểu đồ, metric)", khớp với cả report Big Data của Tuấn Anh và report Phân tích dữ liệu của người được hỏi.
- **Tách phần No AI:** lỗi hình thức (font, màu chart, ảnh mờ) và trễ hạn là vấn đề quy trình nhóm, đưa vào phương án không dùng AI (template + quy định export ảnh, deadline nội bộ). Phần cần cân nhắc AI chỉ còn: phát hiện chênh lệch số liệu giữa các phần và nối logic insight.
- **Giả định #2** chuyển sang "đã có bằng chứng phản bác"; cần thêm 1–2 phỏng vấn để xác nhận bottleneck mới.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Docs — document tabs | https://support.google.com/docs/answer/15499791 | Bước 1 và 3 (thu bài, sửa format): mỗi thành viên viết vào một tab trong cùng một file, dùng chung style | Miễn phí, có sẵn; xem cấu trúc cả report ở panel bên trái | Không giải chuyện nộp trễ; không giúp đọc hiểu hay phát hiện mâu thuẫn giữa các phần | Phần trễ hạn và sai format giải được bằng **No AI** (template + tab + deadline nội bộ) |
| Gemini trong Google Docs | https://support.google.com/docs/answer/14206696 | Bước 2 (đọc nắm nội dung): tóm tắt cả tài liệu hoặc đoạn được chọn ngay trong side panel | Nằm ngay trong Docs, không phải chuyển công cụ | Cần gói Google Workspace/Google AI đủ điều kiện (tài khoản cá nhân chỉ qua chương trình thử nghiệm); tóm tắt có thể sai, không tự so sánh chéo các phần | Đã có công cụ sẵn, **không nên tự xây**; người ghép vẫn phải kiểm lại |
| Gemini Notebook (Google) | https://support.google.com/notebooklm/answer/16164461 | Bước 2 và 4: nạp nhiều nguồn (Docs, PDF), hỏi đáp có trích dẫn inline, tạo briefing | Trích dẫn giúp người ghép mở đúng đoạn gốc để kiểm; hỏi chéo được nhiều phần cùng lúc | Chỉ trả lời dựa trên nguồn đã nạp; phải nạp lại khi thành viên sửa phần của mình; trang không nêu giới hạn số nguồn | Gợi ý hướng **Workflow**: template (No AI) → tóm tắt/hỏi chéo có trích dẫn → người ghép duyệt |

**Kết luận research (nháp, chờ kết quả phỏng vấn):**

```text
Trễ hạn và sai format: giải bằng quy trình nhóm (template, tab, deadline nội bộ), không cần AI.
Đọc hiểu và phát hiện mâu thuẫn giữa các phần: đã có công cụ sẵn (Gemini trong Docs, Gemini Notebook), không có lý do tự xây agent.
Câu hỏi còn mở cho phỏng vấn: sau khi áp dụng template, bước đọc có còn là bottleneck không?
```

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Gộp từ 2 nguồn: Problem Card #2 của Tuấn Anh (report Big Data, 7 người) và phỏng vấn người thứ 1 (report Phân tích dữ liệu). Thời gian của Tuấn Anh là ước lượng từ tổng khoảng 180 phút. Người được phỏng vấn chỉ nêu tổng 5–6 tiếng và riêng bước 3+4 là 3–4 tiếng.

```text
HIỆN TẠI — 5 bước, 5/5 thủ công
Tuấn Anh: khoảng 180 phút (chưa tính 1 ngày chờ người trễ) · Người phỏng vấn: 5–6 tiếng

[1 Nhắc + thu các phần: 10'] → (chờ người nộp trễ, có lần 1 ngày)
→ [2 Đọc từng phần, đối chiếu số liệu/biểu đồ với dữ liệu chung, hỏi lại: 80']
→ [3 Sửa format, chạy lại code xuất lại biểu đồ: 45']           ┐
→ [4 Viết lại insight, đoạn nối EDA → Model → Insight: 35']     ┘ ← BOTTLENECK (PV: 3–4 tiếng)
→ [5 Rà soát số liệu toàn bài, xuất PDF, nộp: 10']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người ghép → các thành viên | Phân công, deadline | Các phần (Docs, code, ảnh biểu đồ) trên Drive/GitHub | 10' + chờ; 2/6 người trễ 1 ngày (TA) | Handoff: thành viên → người ghép. Deadline sớm 1 ngày vẫn có người trễ (PV) |
| 2 | Người ghép | Các phần, bộ dữ liệu chung | Danh sách chỗ chưa rõ, chỗ số liệu lệch | 80' (TA, ước lượng) | Bước này PV gộp vào kiểm số liệu; PV không nói là có hỏi lại người viết |
| 3 | Người ghép | Ảnh biểu đồ mờ, sai màu; code của thành viên | Biểu đồ nét, cùng style; font, bảng thống nhất | 45' (TA) | Template chung có giúp "đỡ hơn một chút" nhưng thành viên quên áp dụng khi export (PV) |
| 4 | Người ghép | Phần nhận xét rời rạc, có chỗ giải thích sai bản chất chỉ số | Insight viết lại, nối logic giữa các phần | 35' (TA) | PV: bước 3+4 mất 3–4 tiếng; phải "viết lại toàn bộ phần insight" |
| 5 | Người ghép | Report đã ghép | File PDF nộp | 10' (TA) | Kiểm lần cuối chênh lệch số liệu, kết luận có trả lời đúng mục tiêu không |

Tần suất: mỗi môn có report nhóm, khoảng 1–2 lần/môn/kỳ (ước lượng, chưa kiểm chứng).

**Bottleneck chính:** Bước 3 + 4: **đồng bộ số liệu, biểu đồ giữa các phần và viết lại insight** cho nối tiếp logic. Theo người được phỏng vấn, bước này mất 3–4 tiếng trên tổng 5–6 tiếng. Ở report của Tuấn Anh, bước 2 (80') cũng tốn nhiều, nhưng phỏng vấn đã phản bác giả định "tốn nhất là đọc và hỏi lại" (xem 3.2).

### 4.2. Quy trình tương lai

```text
TƯƠNG LAI — 6 bước, kỳ vọng khoảng 90 phút, 3/6 bước thủ công

[0 Trước khi làm: template Docs + style biểu đồ chung + bảng "Số liệu chính"]   ← NO AI (quy định nhóm)
→ [1 Thành viên nộp: phần viết + biểu đồ xuất từ hàm vẽ chung + điền số vào bảng chung]
                                                                    ← RULE (hàm vẽ/style file, nhắc deadline tự động)
→ [2 Kiểm số liệu từng phần với bảng "Số liệu chính": 5']           ← RULE (so khớp số; nếu lệch → trả lại thành viên)
→ [3 AI đọc cả report, chỉ liệt kê chỗ kết luận mâu thuẫn giữa các phần,
      mỗi chỗ kèm trích dẫn đoạn gốc: 2']                           ← AI
→ [4 Người ghép kiểm từng cảnh báo với bản gốc, viết lại insight: 60']  ← CON NGƯỜI
→ [5 Rà soát lần cuối, xuất PDF, nộp: 10']                          ← CON NGƯỜI

BOUNDARY: AI không tự sửa file report, không đổi số liệu, không viết hay gợi ý
          câu chữ. AI chỉ liệt kê chỗ mâu thuẫn; viết lại insight là việc của người ghép.
PHƯƠNG ÁN QUAY VỀ: AI báo sai nhiều hoặc không dùng được → bỏ bước 3,
          người ghép đối chiếu thủ công bằng bảng "Số liệu chính" (bước 2 vẫn chạy).
```

Bước 0–2 giải phần "hình thức" (ảnh mờ, màu lộn xộn, số lệch) mà không cần AI. Template giấy trước đây không đủ vì thành viên quên áp dụng khi export ảnh, nên nhóm chuyển sang **hàm vẽ dùng chung** (style file): thành viên gọi hàm là ảnh đúng style, không cần nhớ quy định.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 6 (có bước 0 làm 1 lần đầu môn) | Thêm bước chuẩn bị, bớt việc sửa tay |
| Tổng thời gian | 180' (TA) / 5–6 tiếng (PV) | khoảng 90' | Target chính: không quá 90'. Số "sau" là kỳ vọng, chưa đo |
| Số bước thủ công | 5/5 | 3/6 (bước 0, 4, 5) | Người ghép vẫn viết lại insight và duyệt |
| Bottleneck chính | Đồng bộ số liệu, biểu đồ + viết lại insight (3–4 tiếng) | Người ghép kiểm cảnh báo + viết insight (khoảng 60') | Chấp nhận được vì đây là điểm kiểm soát chất lượng |
| Rủi ro mới phát sinh | — | AI bỏ sót mâu thuẫn; AI bịa mâu thuẫn không có; thành viên ỷ lại, viết nhận xét kém hơn | Xử lý bằng bảng số liệu (Rule) chạy trước AI + tiêu chí đánh giá ở mục 7 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách ghép report nhóm có phần phân tích dữ liệu (code, biểu đồ, metric), nhóm 4–7 người |
| **Quy trình** | 1–2 ngày trước deadline: thu các phần → đọc, đối chiếu số liệu → sửa format và biểu đồ → viết lại insight, đoạn nối → rà soát, xuất PDF, nộp |
| **Bottleneck** | Đồng bộ số liệu, biểu đồ giữa các phần và viết lại insight để EDA → Model → Insight nối tiếp logic: 3–4 tiếng/lần (1 người được phỏng vấn); khoảng 80' (TA, ước lượng) |
| **Impact** | 3–6 tiếng/lần dồn vào một người, sát deadline; 2/6 người nộp trễ 1 ngày làm dời việc ghép; nếu sót chênh lệch số liệu thì report nộp có kết luận mâu thuẫn |
| **Success Metric** (baseline → target, cách đo) | Thời gian ghép: 180' (TA) / 5–6 tiếng (PV), đều theo trí nhớ → không quá 90'. Đo bằng người ghép tự bấm giờ từng bước ở lần report nhóm kế tiếp |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Người ghép chịu trách nhiệm cuối với mọi số liệu và kết luận trong bản nộp. Không thay đổi số liệu hay kết luận của thành viên mà không đối chiếu với dữ liệu/code gốc. Không có gì được nộp khi người ghép chưa rà soát |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

*(Bản nháp phản biện do AI đưa ra theo prompt ở worksheet CP5. Nhóm cần đọc lại, tự quyết đồng ý hay không và sửa cột này.)*

- **Metric chỉ đo tốc độ, không đo chất lượng:** ghép nhanh hơn nhưng còn sót số lệch thì sao? → Đồng ý, thêm metric "số chênh lệch số liệu còn sót khi nộp" ở v1.
- **Baseline của 2 nguồn chênh nhau gấp 2 (180' vs 5–6 tiếng)**, đều là trí nhớ, nhóm khác nhau, môn khác nhau. → Đồng ý, ghi rõ là ước lượng; lần report tới bấm giờ từng bước để có baseline thật.
- **Actor "nhóm 4–7 người" lấy từ đâu?** → Đồng ý một phần: 7 là nhóm Big Data của TA; người được phỏng vấn chưa nói số thành viên. Cần hỏi lại.
- **Nguyên nhân gốc có thể là thành viên viết nhận xét kém**, không phải khâu ghép. → Đồng ý một phần: đưa "mỗi phần kèm 3 dòng: số liệu chính, kết luận, nối với phần trước" vào bước No AI.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ phức tạp thấp–trung bình × độ mơ hồ cao (ở 1 bước)** → Workflow có AI ở một bước.

Vì sao:

- Bài có 2 việc con với độ mơ hồ khác nhau:
  - **Kiểm số liệu lệch:** độ mơ hồ **thấp**, có đúng/sai rõ (số trong phần viết khớp hay không khớp bảng chung). Rule làm được.
  - **Nối logic insight, phát hiện kết luận mâu thuẫn:** độ mơ hồ **cao**, nhiều cách viết đều chấp nhận được. Đây là chỗ Rule không làm được.
- Độ phức tạp **thấp–trung bình**: 4–7 phần, 1 bộ dữ liệu chung, các bước cố định theo thứ tự, không rẽ nhánh. Không cần AI tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Template Docs, deadline nội bộ sớm 2 ngày, mỗi phần kèm 3 dòng tóm tắt (số liệu chính, kết luận, nối với phần trước) | Nhóm chỉ gặp trễ hạn và sai format | Đã thử template + deadline sớm 1 ngày: vẫn trễ, vẫn quên áp dụng, insight vẫn rời rạc (PV) | **Dùng cho bước 0** |
| **Rule** | Hàm vẽ/style file chung cho biểu đồ; bảng "Số liệu chính" + so khớp số; nhắc deadline tự động | Lỗi là ảnh mờ, sai màu, số lệch giữa các phần | Không phát hiện được kết luận mâu thuẫn hay đứt logic khi số vẫn đúng | **Dùng cho bước 1–2** |
| **Workflow** | Rule kiểm số → AI liệt kê chỗ kết luận mâu thuẫn, có trích dẫn → người ghép kiểm, tự viết lại | Các bước cố định; AI chỉ làm phần đọc chéo | AI bỏ sót hoặc bịa mâu thuẫn; người ghép tin AI mà không kiểm | **Chọn** (AI chỉ ở bước 3) |
| **Agent** | AI tự lấy các phần từ Drive/GitHub, tự chạy lại code, tự sửa biểu đồ, tự viết insight, tự nộp | Khi bước tiếp theo không đoán trước được | Quá nhiều quyền (repo, Drive, nộp bài); sai số liệu khó phát hiện; có thể vi phạm quy định môn học | Không chọn |

**Mức chọn:** Workflow, trong đó phần lớn các bước là No AI và Rule. AI chỉ làm 1 việc: đọc chéo cả report và liệt kê chỗ kết luận mâu thuẫn giữa các phần. AI không viết, không gợi ý câu chữ; số liệu lệch đã do Rule kiểm ở bước 2.

**Vì sao không chọn mức đơn giản hơn:** Người được phỏng vấn đã thử No AI (template chung, Docs chung + deadline sớm 1 ngày) và vẫn phải "ngồi viết lại toàn bộ phần insight". Rule (bảng số liệu, hàm vẽ chung) giải được ảnh và số lệch, nhưng không thấy được nhận xét "giải thích chưa đúng bản chất chỉ số" hay EDA và Model không nối nhau. Bằng chứng mới từ 1 người (một DA, bạn của Tuấn Anh) và report của Tuấn Anh, nên nhóm chỉ thêm AI ở 1 bước, và giữ phương án quay về No AI + Rule.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Danh sách chỗ kết luận mâu thuẫn giữa các phần (ví dụ EDA nói một đằng, Insight kết luận ngược lại), mỗi chỗ kèm trích dẫn đoạn gốc. Không tạo nội dung mới |
| **Judgment** — con người cân nhắc, quyết định gì? | Người ghép quyết định cảnh báo nào đúng, chỗ nào cần trả lại thành viên sửa, insight cuối cùng viết thế nào |
| **Action** — hành động cuối cùng là gì, ai làm? | Người ghép sửa report hoặc trả lại phần cho thành viên; người ghép xuất PDF và nộp |
| **Outcome** — đo kết quả bằng gì? | Thời gian ghép; số chênh lệch số liệu còn sót khi nộp; tỉ lệ cảnh báo đúng |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Toàn bộ report (Google Docs) + bảng "Số liệu chính" + mục tiêu bài toán của đề. Có sẵn sau bước 2. Đề bài và dữ liệu môn học có thể có quy định riêng (giả định #6) |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Người ghép đánh dấu cảnh báo đúng/sai mỗi lần; nhận xét của giảng viên về tính nhất quán của report |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **Augment.** Người được phỏng vấn tự chạy lại code, tự viết lại insight và tự kiểm lần cuối "để đảm bảo kết luận trả lời đúng mục tiêu". Người ghép chịu trách nhiệm điểm của cả nhóm, nên cần tự duyệt. Lưu ý: nhóm chưa hỏi thẳng câu này, đây là suy ra từ hành vi; cần hỏi trong phỏng vấn tiếp theo.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **Bỏ sót tệ hơn.** Sót một chênh lệch số liệu thì report nộp đi có kết luận mâu thuẫn, mất điểm cả nhóm. Báo nhầm chỉ tốn vài phút kiểm lại. Thiết kế: (1) bảng "Số liệu chính" (Rule) chạy trước AI, nên số lệch không phụ thuộc hoàn toàn vào AI; (2) prompt yêu cầu AI liệt kê rộng, chấp nhận báo nhầm; (3) mỗi cảnh báo phải có trích dẫn để người ghép kiểm nhanh.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách ghép report nhóm có phần phân tích dữ liệu (code, biểu đồ, metric) |
| **Quy trình** | Thu các phần → đối chiếu số liệu → sửa format, biểu đồ → viết lại insight, đoạn nối → rà soát, xuất PDF, nộp |
| **Bottleneck** | Đồng bộ số liệu, biểu đồ và viết lại insight cho nối tiếp logic: 3–4 tiếng/lần (PV); khoảng 80' (TA, ước lượng) |
| **Impact** | 3–6 tiếng/lần dồn vào một người, sát deadline; rủi ro nộp report có kết luận mâu thuẫn |
| **Success Metric** | (1) Thời gian ghép từ 180' / 5–6 tiếng xuống không quá 90', tự bấm giờ từng bước; (2) số chênh lệch số liệu còn sót khi nộp = 0, đếm bằng một lượt rà soát độc lập của 1 thành viên khác sau khi nộp; (3) số đoạn insight người ghép phải viết lại toàn bộ giảm ít nhất một nửa so với lần trước |
| **Boundary** | AI không tự sửa file report, không đổi số liệu, không viết kết luận không có trong phần của thành viên. Người ghép kiểm mọi cảnh báo và duyệt trước khi nộp |
| **AI intervention point** | Sau khi Rule đã kiểm số với bảng "Số liệu chính" (bước 2), trước khi người ghép viết lại insight (bước 4) |
| **Mức chọn** | Workflow (No AI + Rule ở bước 0–2, AI ở bước 3) |
| **Rủi ro & người kiểm tra** | AI bỏ sót hoặc bịa mâu thuẫn → người ghép kiểm từng cảnh báo với đoạn gốc; thành viên viết phần đó xác nhận nếu insight bị viết lại |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | ... nhóm 4–7 người | Bỏ "4–7 người" | Phản biện: con số chưa có nguồn từ người được phỏng vấn |
| Success Metric | Chỉ đo thời gian | Thêm số chênh lệch còn sót và số đoạn phải viết lại | Phản biện: nhanh hơn nhưng sót số lệch thì không đạt |
| Boundary | Chỉ nói người ghép chịu trách nhiệm | Thêm giới hạn cụ thể cho AI | Sau khi chọn Workflow, cần nói rõ AI không được làm gì |
| AI intervention point, Mức chọn, Rủi ro | — | Thêm | Trường mới của v1 |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Cách thử trước khi dùng thật: lấy 1 report cũ của Tuấn Anh, cố tình cài 5 chỗ kết luận mâu thuẫn giữa các phần (số liệu lệch đã do Rule kiểm, không tính vào đây), rồi chấm danh sách cảnh báo của AI.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bỏ sót | Nêu đủ 5/5 lỗi đã cài | Thiếu từ 1 lỗi đã cài trở lên |
| 2 | Có trích dẫn đúng | Mỗi cảnh báo chỉ đúng phần và đoạn gốc | Cảnh báo không nói ở đâu, hoặc trích sai đoạn |
| 3 | Không bịa | Mọi số và kết luận AI nhắc tới đều có trong input | Có số hoặc kết luận không có trong report |
| 4 | Báo nhầm ở mức chấp nhận được | Không quá 5 cảnh báo sai trên một report | Quá nhiều cảnh báo sai, người ghép mất thời gian hơn tự đọc |
| 5 | Chỉ liệt kê, không viết | Đầu ra chỉ là danh sách cảnh báo kèm trích dẫn | AI viết lại hoặc gợi ý câu chữ cho insight |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Pain có thật ở 2 người (TA và PV, 3–6 tiếng/lần). Nhưng bottleneck mới chỉ có 1 người phỏng vấn (một DA, lại là bạn của Tuấn Anh); chưa biết No AI + Rule đã đủ chưa |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Người ghép chỉ đọc danh sách cảnh báo có trích dẫn; không học công cụ mới. Thành viên phải dùng hàm vẽ chung, có thể ngại thay đổi |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Report nằm sẵn trên Google Docs; Gemini trong Docs và Gemini Notebook đã có (mục 3.3); style file matplotlib/seaborn nhóm tự viết được |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Chưa biết giảng viên có cho dùng AI khi làm report không (giả định #6). Gemini trong Docs cần gói đủ điều kiện. Người vận hành là người ghép, không tốn thêm người |

### 8.2. Kết luận

**Quyết định:** Go, phạm vi nhỏ

**Lý do:** Không có rủi ro mức Cao. Hai rủi ro TB (Value, Viability) kiểm được trước và trong pilot mà không cần xây gì.

**Nếu Go — pilot nhỏ nhất:**

- Lần report nhóm kế tiếp của Tuấn Anh (hoặc của người được phỏng vấn, nếu đồng ý).
- Không xây gì mới. Làm bước 0–2 (template, hàm vẽ chung, bảng "Số liệu chính") trước. Bấm giờ từng bước.
- Ở bước 3, dùng Gemini Notebook hoặc một prompt chuẩn với report + bảng số liệu. Người ghép **vẫn tự rà soát như cũ**, rồi so danh sách mình tìm được với danh sách của AI và chấm theo 5 tiêu chí ở mục 7.
- Trước pilot: hỏi giảng viên về việc dùng AI (giả định #6); phỏng vấn thêm 1–2 người ghép report không quen nhóm để kiểm bottleneck mới.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Nếu chỉ với bước 0–2 (No AI + Rule) mà thời gian ghép đã không quá 90' → không thêm AI, dừng ở mức Rule.
- Nếu AI bỏ sót từ 1 chênh lệch số liệu mà người ghép tự tìm thấy, trong 2 lần chạy liên tiếp → bỏ bước 3, quay về No AI + Rule.
- Nếu giảng viên không cho dùng AI khi làm report → No-Go cho phần AI, giữ No AI + Rule.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- **Mẫu kiểm chứng rất nhỏ:** mới phỏng vấn 1 người, lại là bạn của Tuấn Anh, nên có thể trả lời theo hướng người hỏi mong đợi. Bottleneck mới (đồng bộ số liệu, viết lại insight) chỉ dựa trên 1 người này.
- **Baseline là trí nhớ, chưa bấm giờ:** 180' (Tuấn Anh) và 5–6 tiếng (người được phỏng vấn) chênh nhau gấp 2. Thời gian từng bước của Tuấn Anh là ước lượng chia từ tổng.
- **Hai nguồn khác bối cảnh:** report Big Data 7 người (NEU) và report Phân tích dữ liệu của một DA; chưa biết số thành viên nhóm của người được phỏng vấn.
- **Thời gian "sau" ở mục 4.3 là kỳ vọng**, chưa đo. Tần suất "1–2 lần/môn/kỳ" cũng là ước lượng.
- **Giả định chưa kiểm chứng:** #4 (người ghép chấp nhận đọc danh sách cảnh báo rồi đối chiếu bản gốc) và #6 (giảng viên cho dùng AI khi làm report). Câu hỏi augment hay automate mới suy ra từ hành vi, chưa hỏi thẳng.
- **Tiêu chí đánh giá AI chưa chạy thử:** bộ test cài sẵn lỗi ở mục 7 mới là kế hoạch.

**Hướng tiếp theo:**

1. Phỏng vấn thêm 1–2 người ghép report có phân tích dữ liệu, không quen nhóm; hỏi thẳng: bước nào mất nhiều nhất, có muốn tự duyệt hay giao hẳn không.
2. Hỏi giảng viên về quy định dùng AI khi làm report nhóm (giả định #6).
3. Ở lần report nhóm kế tiếp của Tuấn Anh: bấm giờ từng bước để có baseline thật, rồi chạy pilot theo mục 8.2 (No AI + Rule trước, AI chạy song song để so).
4. Làm bộ eval 10 cặp input/đầu ra mong đợi từ report cũ của Tuấn Anh (bonus B3), lưu ở `report/assets/cp6-eval-set.md`.
5. Candidate để dành cho vòng sau: đọc bài nghiên cứu (#8, #12) và kiểm tra yêu cầu nộp bài lab (#1).

## 10. Tài liệu tham khảo

**Bằng chứng nội bộ của nhóm:**

- Problem Card #2 "Ghép report 7 phần môn Big Data" — báo cáo cá nhân của Trần Tuấn Anh (`report/individual/2A202603909_TranTuanAnh.md`, nhánh `Tanh`).
- Interview snapshot người thứ 1 — [`report/assets/cp4-interview-snapshot-1.md`](../assets/cp4-interview-snapshot-1.md).

**Công cụ đã research (CP4, mục 3.3):**

- Google Docs Help — Use document tabs: https://support.google.com/docs/answer/15499791
- Google Docs Help — Gemini trong Google Docs: https://support.google.com/docs/answer/14206696
- Gemini Notebook Help: https://support.google.com/notebooklm/answer/16164461

**Framework đã dùng** (theo [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md)):

- Design Council — Double Diamond: https://www.designcouncil.org.uk/resources/framework-for-innovation/
- Alan Klement, Intercom — Job Stories: https://www.intercom.com/blog/accidentally-invented-job-stories/
- Teresa Torres — Opportunity Solution Trees: https://www.producttalk.org/opportunity-solution-trees/
- David Bland, Strategyzer — Assumptions Mapping: https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter
- Rob Fitzpatrick — The Mom Test: https://www.momtestbook.com/
- Teresa Torres — The Interview Snapshot: https://www.producttalk.org/interview-snapshot/
- Jeff Gothelf — Business Problem vs Opportunity Statements: https://jeffgothelf.com/blog/business-problem-statement-opportunity-statement/
- Google PAIR — People + AI Guidebook, User Needs: https://pair.withgoogle.com/chapter/user-needs/
- Anthropic — Building effective agents: https://www.anthropic.com/research/building-effective-agents
- Agrawal, Gans, Goldfarb (HBR) — A Simple Tool to Start Making Decisions with the Help of AI: https://hbr.org/2018/04/a-simple-tool-to-start-making-decisions-with-the-help-of-ai
- Hamel Husain, Shreya Shankar — Advanced evals: https://www.lennysnewsletter.com/p/advanced-evals-how-to-find-and-fix
- Marty Cagan, SVPG — The Four Big Risks: https://www.svpg.com/four-big-risks/
- Microsoft Research — Guidelines for Human-AI Interaction: https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/
