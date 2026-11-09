# Báo cáo cá nhân — 2A202603899_NguyenDucHai

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Đức Hải
- MSSV: 2A202603899
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: BacHo
- Link repo nhóm: https://github.com/longhtr028/K5-L3B-DAY02-BacHo-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Hải scan 9 problem, vượt mức tối thiểu 5, trải đủ 4 lăng kính.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu một buổi lab mới, tôi muốn biết ngay đề yêu cầu nộp những file nào, đặt tên ra sao, để không bị trừ điểm vì sai cấu trúc repo | Học viên, coach chấm bài | Mỗi lab mất khoảng 20 phút đọc README/RUBRIC/SUBMISSION, khoảng 3 lab/tuần; quy định trừ 5 điểm nếu sai tên repo/file |
| 2 | Tốn thời gian | Khi nhận một màn hình mới từ Figma, tôi muốn dựng component đúng spacing, màu và responsive ngay từ lần đầu, để không bị designer trả lại sửa | FE dev, designer | Khoảng 3 giờ/màn hình, thường khoảng 2 vòng sửa sau review của designer |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi cần tìm lại một hướng dẫn hay câu trả lời của coach trong Discord lớp, tôi muốn tìm được đúng tin nhắn, để không phải hỏi lại | Học viên, coach | Khoảng 15 phút mỗi lần kéo tìm, khoảng 3 lần/tuần; cùng câu hỏi bị hỏi lại nhiều lần trong group |
| 4 | Pain từ người khác | Khi làm bài nhóm trên một repo chung, các thành viên muốn biết ai đang sửa phần nào, để không ghi đè hoặc conflict khi merge | Thành viên nhóm 3–4 người | Khoảng 2 lần conflict/tuần, mỗi lần khoảng 20 phút xử lý |
| 5 | Lặp lại | Khi tới cuối tuần, tôi muốn biết các deadline của tuần sau ở các môn/lab, để không nộp trễ | Học viên | Deadline nằm rải ở LMS, group chat, email; 15 phút/tuần tổng hợp lại; đã từng suýt trễ 1 bài |
| 6 | Tốn thời gian | Khi đọc một tài liệu/paper dài cho bài học, tôi muốn nắm được các ý chính và thuật ngữ, để kịp làm bài trong buổi lab | Học viên | Khoảng 50 phút/tài liệu, 2 tài liệu/tuần |
| 7 | Pain từ người khác | Khi backend đổi API (tên field, format response) mà không báo trước, team FE muốn biết sớm thay đổi, để không phát hiện lỗi lúc QA hoặc demo | FE dev, BE dev, QA | Khoảng 2 lần/sprint, mỗi lần khoảng 45 phút debug mới ra nguyên nhân |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi UI chỉ lỗi trên một số trình duyệt/thiết bị, tôi muốn tìm ra nguyên nhân từ console, network log và bug report của QA, để sửa đúng chỗ | FE dev, QA, người dùng | Khoảng 40 phút/bug, khoảng 4 bug/tuần |
| 9 | Lặp lại | Khi review pull request của đồng đội FE, tôi muốn biết nhanh thay đổi ảnh hưởng tới màn hình nào, để duyệt đúng hạn mà không lọt lỗi UI | FE team, reviewer | Khoảng 30 phút/PR, khoảng 4 PR/tuần |

**AI gợi ý thêm:** 

Bỏ ý "lộ trình tự học machine learning" vì là mục tiêu cá nhân, khó vẽ quy trình và đo dấu hiệu cụ thể. 

Bỏ ý "trợ lý quản lý toàn bộ việc học" vì quá rộng, không có quy trình thật và là solution trá hình.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra yêu cầu nộp bài lab (#1) | Lặp lại khoảng 3 lần/tuần, cả lớp cùng gặp nên dễ kiểm chứng với bạn học; quy trình rõ; sai bị trừ 5 điểm | Repo đã có checklist trong SUBMISSION.md, có thể chỉ cần Rule hoặc No AI |
| 2 | Backend đổi API không báo (#7) | Bottleneck rõ (chờ hỏi BE), đo được thời gian debug, có hậu quả lỗi lọt tới QA/demo | Phụ thuộc quy trình của team BE, ngoài tầm kiểm soát của FE |
| 3 | Dựng màn hình từ Figma bị trả lại sửa (#2) | Việc chính hằng ngày của FE, đo được số vòng sửa | "Đúng design" khó đo khách quan; một phần do design thay đổi chứ không do FE |

Không chọn: #3 (tìm tin nhắn Discord) vì phụ thuộc công cụ chat, khó vẽ quy trình cố định; #6 (đọc tài liệu dài) vì kết quả "nắm được ý chính" khó đo.

### Problem Card #1 — Kiểm tra yêu cầu nộp bài lab

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một buổi lab mới, tôi muốn biết ngay đề yêu cầu nộp những file nào, đặt tên ra sao, để không bị trừ điểm vì sai cấu trúc repo |
| Actor | Học viên K5 làm lab vừa cá nhân vừa nhóm, nộp qua GitHub, deadline 23h59 hoặc 11h59 hôm sau |
| Thời điểm / bối cảnh | Đầu buổi lab (đọc đề) và ngay trước deadline (tự kiểm trước khi nộp) |
| Quy trình hiện tại (3–7 bước) | 1. Mở repo, đọc README · 2. Đọc CHECKPOINTS + RUBRIC để biết phải nộp gì · 3. Đọc SUBMISSION, ghi lại tên file, cấu trúc thư mục · 4. Làm bài · 5. Trước khi nộp, dò lại từng mục rubric/checklist với file của mình · 6. Push và nộp link LMS |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, tự dò lại rubric/checklist: khoảng 15 phút, phải mở qua lại 3–4 file, dễ sót mục khi đang vội trước deadline |
| Impact (nếu không giải thì sao) | Khoảng 35 phút/lab × khoảng 3 lab/tuần = khoảng 105 phút/tuần; sai tên repo/file bị trừ 5 điểm, thiếu file nhóm thì phần nhóm bị 0 |
| Success metric (baseline → target) | Thời gian tự kiểm bước 5: khoảng 15 phút → dưới 5 phút; số lỗi cấu trúc bị trừ điểm: giữ ở 0. Đo bằng tự bấm giờ 3 lab tới |
| Phương án không dùng AI | Checklist cố định copy vào đầu báo cáo + script/GitHub Action kiểm tên file, file bắt buộc, chữ "MSSV_HoTen" còn sót |
| Giả thuyết về AI (nếu có) | Có thể so nội dung báo cáo với rubric để chỉ ra mục còn trống/hời hợt; nhưng phần kiểm cấu trúc thì Rule là đủ |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 35 phút/lab (không tính bước làm bài)

[1 Đọc README: 5'] → [2 Đọc CHECKPOINTS + RUBRIC: 8'] → [3 Đọc SUBMISSION: 7']
→ [4 Làm bài] → [5 Dò lại rubric/checklist: 15'] ← BOTTLENECK
→ [6 Push + nộp LMS: 5'] (không tính vào tổng đọc/kiểm)
```

### Problem Card #2 — Backend đổi API không báo

| Trường | Nội dung |
|---|---|
| Job Story | Khi backend đổi API (tên field, format response) mà không báo trước, team FE muốn biết sớm thay đổi, để không phát hiện lỗi lúc QA hoặc demo |
| Actor | FE dev trong team có FE và BE tách riêng, làm theo sprint |
| Thời điểm / bối cảnh | Trong sprint, khi BE merge thay đổi API lên môi trường dev/staging |
| Quy trình hiện tại (3–7 bước) | 1. UI lỗi khi dev hoặc QA test · 2. Mở DevTools > Network, so response với code FE · 3. Hỏi BE trên Slack, chờ xác nhận thay đổi · 4. Sửa type/mapping ở FE · 5. Test lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, hỏi và chờ BE xác nhận: khoảng 20 phút, có khi lâu hơn nếu BE đang họp |
| Impact (nếu không giải thì sao) | Khoảng 70 phút/lần × khoảng 2 lần/sprint = khoảng 140 phút/sprint cho 1 FE; lỗi có thể lọt tới QA hoặc demo |
| Success metric (baseline → target) | Thời gian từ lúc thấy lỗi đến biết nguyên nhân: khoảng 45 phút → dưới 10 phút; số lần phát hiện thay đổi API lúc QA/demo: khoảng 2/sprint → 0. Đo bằng ghi lại mỗi lần gặp trong 2 sprint |
| Phương án không dùng AI | API spec (OpenAPI) dùng chung + generate type cho FE; contract test trong CI; quy định PR đổi API phải tag FE |
| Giả thuyết về AI (nếu có) | Có thể tóm tắt thay đổi trong PR backend thành changelog cho FE; nhưng spec + CI giải được phần lớn |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 70 phút/lần

[1 Thấy UI lỗi: 10'] → [2 Soi Network, so response: 15']
→ [3 Hỏi BE, chờ xác nhận: 20'] ← BOTTLENECK
→ [4 Sửa type/mapping: 15'] → [5 Test lại: 10']
```

### Problem Card #3 — Dựng màn hình từ Figma bị trả lại sửa

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một màn hình mới từ Figma, tôi muốn dựng component đúng spacing, màu và responsive ngay từ lần đầu, để không bị designer trả lại sửa |
| Actor | FE dev nhận design từ designer qua Figma |
| Thời điểm / bối cảnh | Mỗi khi có màn hình/feature mới trong sprint |
| Quy trình hiện tại (3–7 bước) | 1. Mở Figma, xem tổng thể màn hình · 2. Inspect spacing, màu, font từng phần tử · 3. Code component + layout · 4. Kiểm responsive ở các breakpoint · 5. Gửi designer review, sửa theo comment |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, sửa theo review: khoảng 30 phút cho khoảng 2 vòng, mỗi vòng còn phải chờ designer phản hồi |
| Impact (nếu không giải thì sao) | Khoảng 3 giờ/màn hình; mỗi vòng sửa đẩy lùi ngày merge, designer cũng mất thời gian review lại |
| Success metric (baseline → target) | Số vòng sửa/màn hình: khoảng 2 → tối đa 1; tổng thời gian: khoảng 180 phút → khoảng 150 phút. Đo bằng đếm comment review trên Figma/PR |
| Phương án không dùng AI | Design token dùng chung (màu, spacing, font) giữa Figma và code; checklist tự kiểm trước khi gửi review; plugin overlay so pixel |
| Giả thuyết về AI (nếu có) | Có thể so ảnh chụp UI với frame Figma để chỉ ra chỗ lệch; chưa chắc đáng công so với design token |
| Cảm nhận nhanh | No AI / Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 180 phút/màn hình

[1 Xem tổng thể Figma: 10'] → [2 Inspect spacing/màu/font: 30']
→ [3 Code component + layout: 90'] → [4 Kiểm responsive: 20']
→ [5 Designer review + sửa (2 vòng): 30'] ← BOTTLENECK
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: cả lớp đều gặp nên nhóm dễ phỏng vấn bạn học ở CP4 bằng hành vi thật (lab gần nhất mất bao lâu để tự kiểm, có từng sửa tên file sát giờ không); quy trình ngắn, vừa sức một buổi lab.
- Câu hỏi muốn nhóm phản biện: SUBMISSION.md đã có sẵn checklist, vậy pain còn lại thật sự nằm ở việc **đọc đề** hay ở việc **tự kiểm trước khi nộp**? Nếu chỉ là kiểm cấu trúc thì có cần gì hơn một script Rule không?

### AI đã phản biện card thế nào

Đưa card #1 cho AI (Claude) đóng vai PM hoài nghi theo prompt trong worksheet.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor "học viên" quá chung, không rõ bối cảnh | Đồng ý | Sửa actor thành học viên K5 làm lab cá nhân + nhóm, nộp qua GitHub, có deadline cụ thể |
| Bottleneck ban đầu ghi "đọc đề mất thời gian" là cả cụm bước 1–3, không phải 1 bước | Đồng ý | Chốt bottleneck là bước 5 (tự dò lại checklist trước khi nộp, khoảng 15 phút) |
| Repo đã có checklist, một script kiểm tên file có thể đủ; đang nhảy sang AI quá sớm | Đồng ý một phần | Ghi script/GitHub Action vào phương án không dùng AI, đổi cảm nhận nhanh từ Workflow sang Rule; giữ ý kiểm nội dung báo cáo làm giả thuyết cần kiểm chứng |
| Baseline 15 phút dựa trên trí nhớ | Đồng ý | Ghi cách đo: tự bấm giờ 3 lab tới; đưa vào giả định cần kiểm ở CP4 |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý problem theo 4 lăng kính, viết lại dạng Job Story | Nhắc được lăng kính còn thiếu (debug UI, review PR) | Số liệu chỉ là ước lượng, không phải dấu hiệu thật; vài ý chung chung | *(Hải điền: đã sửa số / bỏ dòng nào)* |
| CP2 Problem Card | Đóng vai PM hoài nghi phản biện card #1 | Chỉ ra actor quá chung, bottleneck là cả cụm bước, Rule có thể đủ | Ban đầu gợi ý kiểm nội dung báo cáo bằng AI mà chưa hỏi checklist có sẵn chưa | Đổi cảm nhận nhanh sang Rule, chốt bottleneck là bước 5, thêm cách đo baseline |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
