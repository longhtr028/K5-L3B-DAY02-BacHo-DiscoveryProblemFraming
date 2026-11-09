# CP4 – Interview snapshot #1

| Trường | Nội dung |
|---|---|
| Người được hỏi | Bạn của Tuấn Anh (ẩn tên), Data Analyst (DA) đang làm việc tại một công ty cung cấp giải pháp công nghệ; người phụ trách gom và ghép report nhóm môn Phân tích dữ liệu |
| Hình thức | *(điền: gặp trực tiếp / nhắn tin / gọi điện)* |
| Ngày phỏng vấn | 9/11/2026 |
| Sự việc được kể | Lần ghép report gần nhất: thứ Năm tuần trước (5/11/2026) |
| Người hỏi | Trần Tuấn Anh (2A202603909) |
| Giả định kiểm chứng | #1, #2, #3 trong Assumption Map (mục 3.1, `report/team/group_report.md`) |

## Câu hỏi và câu trả lời gốc

**Câu 1:** Lần gần nhất bạn ghép report nhóm, bạn đã làm những bước nào, từ lúc thu bài đến lúc nộp?

> Lần gần nhất tôi gom report về môn phân tích dữ liệu là thứ 5 tuần trước. Đầu tiên mình sẽ gom bài Nhắc các bạn push code và phần viết phân tích lên Google Drive/GitHub nhóm. Tiếp là check xem kết quả trực quan hóa (biểu đồ), các chỉ số (KPIs, metric) và phần nhận xét của từng bạn có khớp với bộ dữ liệu chung không, sau đó là bước ghép bài vào Google Docs, lúc này mình phải căn chỉnh lại định dạng biểu đồ cho nét, chuẩn hóa font chữ, bảng biểu và viết lại phần giải thích để các đoạn EDA, Modeling và Insight nối tiếp logic với nhau. Cuối cùng, mình kiểm tra tổng thể lần cuối để tránh chênh lệch số liệu giữa các phần, đảm bảo kết luận trả lời đúng mục tiêu bài toán rồi xuất file PDF nộp.

**Câu 2:** Bước nào mất nhiều thời gian nhất? Khoảng bao lâu? Cả lần đó mất tổng cộng bao lâu?

> Bước tiêu tốn nhiều thời gian nhất là chỉnh sửa biểu đồ, hình ảnh và đồng bộ lại logic dữ liệu giữa các phần. Lý do là nhiều bạn chụp màn hình biểu đồ bị mờ, chọn màu sắc lung tung hoặc giải thích chưa đúng bản chất chỉ số, buộc mình phải chạy lại một số đoạn code để xuất lại ảnh nét hơn và rewrite phần insight cho chính xác. Riêng khâu này đã ngốn của mình khoảng 3 đến 4 tiếng. Tổng cộng từ lúc giục gom bài, đọc rà soát, chỉnh sửa cho đến khi bấm nộp bài mất khoảng 5 đến 6 tiếng.

**Câu 3:** Nhóm bạn đã thử cách nào để đỡ hơn chưa? Kết quả ra sao?

> Nhóm mình đã thử áp dụng 2 giải pháp nhưng chưa hiệu quả như mong đợi. Cách đầu tiên là quy định template chung cho biểu đồ và định dạng (gửi sẵn bảng màu chart, font chữ, mẫu trình bày bảng). Kết quả là hình thức có đỡ hơn một chút, nhưng các bạn vẫn quên áp dụng quy chuẩn khi export ảnh khiến báo cáo vẫn thiếu tính đồng bộ. Cách thứ hai là yêu cầu mỗi bạn tự đưa thẳng phần phân tích vào file Google Docs chung trước deadline 1 ngày. Tuy nhiên, các bạn vẫn bị trễ hạn, và quan trọng hơn là phần nhận xét dữ liệu bị rời rạc, không nối tiếp logic từ EDA sang Model, nên người tổng hợp vẫn phải ngồi viết lại toàn bộ phần insight.

## Ghi chú của người phỏng vấn

| Giả định | Kết quả | Bằng chứng |
|---|---|---|
| #1 Ghép report mất trên 90 phút mỗi lần | Xác nhận | Tổng 5–6 tiếng; riêng sửa biểu đồ và đồng bộ logic mất 3–4 tiếng (theo lời kể, chưa bấm giờ) |
| #2 Bước tốn nhất là đọc và hỏi lại người viết | Phản bác | Người ghép không hỏi lại. Họ tự chạy lại code để xuất ảnh và tự viết lại insight |
| #3 Template chung và deadline nội bộ chưa đủ | Xác nhận | Đã thử cả hai cách. Hình thức "đỡ hơn một chút" nhưng vẫn có người trễ hạn và phần nhận xét vẫn rời rạc |

**Insight:** Bottleneck nằm ở việc đồng bộ số liệu và biểu đồ, rồi nối logic insight giữa các phần (EDA → Model → Insight). Bottleneck không nằm ở việc đọc nội dung.
