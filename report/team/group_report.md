# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: BacHo
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): *(đề xuất, chờ nhóm chốt)* Sinh viên phụ trách ghép report nhóm mất khoảng 3 tiếng sát deadline để thu, đọc, hỏi lại và sửa các phần của thành viên thành một report thống nhất
- Quyết định cuối: Go / Not Yet / No-Go

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
- **Dễ kiểm chứng ở CP4:** hầu như sinh viên nào cũng từng làm report nhóm, nên phỏng vấn được bạn học ở nhóm khác về lần ghép report gần nhất.
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

Giả định nhóm kiểm chứng trong buổi này: #1, #2, #3.

**Câu hỏi phỏng vấn (theo The Mom Test, hỏi bạn học ở nhóm khác từng ghép report nhóm):**

1. Lần gần nhất bạn ghép report nhóm, bạn đã làm những bước nào, từ lúc thu bài đến lúc nộp?
2. Bước nào mất nhiều thời gian nhất? Khoảng bao lâu? Cả lần đó mất tổng cộng bao lâu?
3. Nhóm bạn đã thử cách nào để đỡ hơn chưa? Kết quả ra sao?

### 3.2. Kiểm chứng

Cách đã dùng: *(Phỏng vấn / Survey — điền sau khi làm)*

Interview snapshot — người thứ 1 (làm tương tự cho người 2, 3 hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** *(điền sau khi phỏng vấn)*

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

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
