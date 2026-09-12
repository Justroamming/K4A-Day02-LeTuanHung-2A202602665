# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên:
- Mã học viên:
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại |Tìm kiếm và tổng hợp các quyết định kỹ thuật hoặc tài liệu kiến trúc hệ thống đã trôi nổi trong các thread thảo luận dài trên Slack/Discord/Teams của dự án |Developer, Tech Lead | 1 tuần phải lục tìm lại lịch sử chat khoảng 10–12 lần; mỗi lần mất trung bình 10–15 phút do tin nhắn bị trôi; ảnh hưởng trực tiếp đến 4–5 thành viên trong team.|
| 2 | Tốn thời gian|Đọc hiểu, lọc thông tin và cập nhật các phiên bản API/thư viện mới (thay đổi thường xuyên hằng tuần) trước khi tích hợp vào mã nguồn |Developer, Intern |Gặp 3–4 lần/tuần khi nhận task mới; mỗi lần nghiên cứu tài liệu mất khoảng 60–90 phút, trong đó 50% thời gian là đọc lại các phần thay đổi breaking-change nhỏ. |
| 3 |AI có thể tốt hơn |Viết mô tả Pull Request (PR description) và tóm tắt các thay đổi trong code sao cho người review dễ nắm bắt ngữ cảnh mà không phải đọc toàn bộ git diff |Developer, Code Reviewer |Tạo 5–7 PR/tuần; mỗi lần tốn khoảng 10–15 phút để cấu trúc lại nội dung thay đổi bằng tiếng Anh; PR thường xuyên bị nhắc nhở bổ sung context. |
| 4 |Pain từ người khác |Các thành viên trong nhóm liên tục hỏi lại về deadline, phân công task hiện tại hoặc link tài liệu chung thay vì tự tra cứu trên bảng quản lý công việc (Jira/Trello/Notion) |Project Manager, Trưởng nhóm |Nhận trung bình 10–15 câu hỏi lặp lại mỗi tuần qua tin nhắn cá nhân; tổng thời gian trả lời và gửi lại link mất khoảng 40–50 phút/tuần. |
| 5 |Lặp lại |Định dạng lại cấu trúc, dọn dẹp bố cục và viết báo cáo tiến độ tuần (Weekly Report) theo đúng chuẩn template của công ty/trường học |Người làm báo cáo, Quản lý trực tiếp |Thực hiện đều đặn 1 lần/tuần; mất khoảng 30 phút chỉ để chỉnh sửa định dạng, căn lề, lọc đầu việc và viết lại câu chữ cho mượt mà |
| 6 |Tốn thời gian |Nghe lại bản ghi âm hoặc transcript từ các cuộc họp trực tuyến kéo dài để chắt lọc và tổng hợp các đầu việc cần làm (action items) |Toàn bộ thành viên nhóm dự án |Họp 3–4 buổi/tuần, mỗi buổi kéo dài 45–60 phút; việc tự nghe lại và phân loại action items tốn khoảng 30–45 phút cho mỗi buổi. |
| 7 |AI có thể tốt hơn |Kiểm tra, tinh chỉnh văn phong và sửa lỗi diễn đạt, lỗi thuật ngữ chuyên ngành trong các tài liệu thuyết trình (slides) trước khi đem đi báo cáo |Người trực tiếp báo cáo/thuyết trình |Thực hiện 2 lần/tuần; mỗi lần mất khoảng 20 phút tự đọc lại nhưng vẫn thường bị sót 2–3 lỗi diễn đạt hoặc thuật ngữ chưa chuẩn xác. |
| 8 |Pain từ người khác |Đối soát, đồng bộ và kiểm tra tính hợp lệ của các dữ liệu giao dịch, chứng từ hoặc biểu mẫu phi cấu trúc định kỳ chéo hệ thống (thường xuyên lệch số liệu hoặc thiếu thông tin định danh giữa các phòng ban) |Nhân sự xử lý dữ liệu, Bộ phận kiểm toán/tài chính |Xử lý khoảng 15–20 bộ hồ sơ/tuần; gần 30% số lượng gặp lỗi lệch dữ liệu phải gửi email phản hồi qua lại hoặc liên hệ xác minh, tốn trung bình 20 phút cho mỗi trường hợp lỗi. |
| 9 |Tốn thời gian |Tự động hóa việc phân rã một yêu cầu tính năng phần mềm bằng ngôn ngữ tự nhiên từ khách hàng thành các user story chuẩn, tự động sinh mã kiểm thử (test case) sơ bộ và dự báo các điểm xung đột kiến trúc tiềm ẩn trước khi đưa vào backlog sprint |Product Owner, Kỹ sư phần mềm, Đội ngũ kiểm thử |Xảy ra 10–12 lần/sprint; quá trình phân rã thủ công và viết tài liệu mô tả yêu cầu tốn trung bình 3–4 giờ cho mỗi tính năng lớn, thường xuyên phát sinh tranh cãi do thiếu hụt case thực tế. |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Tự động hóa việc phân rã một yêu cầu tính năng phần mềm bằng ngôn ngữ tự nhiên từ khách hàng thành các user story chuẩn, tự động sinh mã kiểm thử (test case) sơ bộ và dự báo các điểm xung đột kiến trúc tiềm ẩn trước khi đưa vào backlog sprint | Quy trình phức tạp, tốn nhiều thời gian phân tích thủ công, thể hiện rõ sự kết hợp của Workflow, LLM và Agent để xử lý logic đa bước, impact lớn, đo lường rõ ràng qua thời gian lên kế hoạch sprint. |Mức độ chính xác của AI khi dự báo xung đột kiến trúc với các hệ thống legacy phức tạp |
| 2 |Nghe lại bản ghi âm hoặc transcript từ các cuộc họp trực tuyến kéo dài để chắt lọc và tổng hợp các đầu việc cần làm (action items) |Xảy ra liên tục hằng tuần với tần suất cao, workflow hiện tại tốn kém thời gian nghe và lọc thô, bài toán có thể tối ưu hiệu quả bằng LLM kết hợp workflow |Bài toán có thể tối ưu hiệu quả bằng LLM kết hợp workflow |Tỉ lệ bỏ sót các action items ngầm (không được chốt bằng từ khóa rõ ràng) trong transcript.
| 3 |Viết mô tả Pull Request (PR description) và tóm tắt các thay đổi trong code sao cho người review dễ nắm bắt ngữ cảnh mà không phải đọc toàn bộ git diff |Vấn đề hằng ngày của dev |Liệu dev có chịu dùn nếu AI viết ra câu chữ không hợp với cá nhân |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Phân rã tính năng tự động từ ngôn ngữ tự nhiên

```text
Problem 1 câu Product Owner và kỹ sư phần mềm mất nhiều thời gian phân rã thủ công yêu cầu khách hàng thành user story, test case và kiểm tra xung đột kiến trúc.

Actor: Product Owner, Kỹ sư phần mềm, Đội ngũ kiểm thử.

Thời điểm / bối cảnh: Giai đoạn trước khi lập kế hoạch sprint khi có yêu cầu tính năng từ khách hàng.

Current workflow 3-7 bước:

Current workflow 3-7 bước:
1. Tiếp nhận yêu cầu thô bằng ngôn ngữ tự nhiên từ khách hàng
2. Product Owner đọc hiểu, họp bàn để phân rã thành các Epic/User Story
3. Viết thủ công tiêu chí chấp nhận và test case sơ bộ
4. Kỹ sư phần mềm rà soát lại để tìm điểm xung đột kiến trúc/hệ thống cũ
5. Hoàn thiện tài liệu và đưa vào backlog chuẩn bị cho sprint

Bottleneck: Bước 2 và Bước 4 (Phân rã thủ công và rà soát xung đột kiến trúc tốn thời gian, dễ thiếu sót các case)

Impact: Tốn 3–4 giờ/tính năng lớn; thường xuyên tranh cãi và thiếu hụt kịch bản để kiểm thử khi code.

Success metric: Giảm thời gian chuẩn bị backlog từ 3–4 giờ xuống dưới 45 phút; giảm 70% số lượng thiếu hụt các case khi vào sprint

Non-AI alternative: Xây dựng checklist thủ công cực kỳ chi tiết và bắt buộc PO tuân thủ mẫu template cố định.

AI hypothesis: Sử dụng Workflow điều phối kết hợp LLM để bóc tách ý nghĩa, và Agent tự động đối chiếu ma trận tài liệu kiến trúc để sinh ra User Story, Test Case cùng cảnh báo xung đột.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[X] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 210 phút

[1. Nhận yêu cầu thô: 15'] → [2. Phân rã User Story thủ công: 60'] → [3. Viết test case: 60'] → [4. Rà soát xung đột kiến trúc: 45']  <-- bottleneck → [5. Đưa vào backlog: 30']

FUTURE STATE — 40 phút

[1. Input yêu cầu thô vào hệ thống: 5'] → [2. AI Workflow/LLM phân rã User Story & Test Case tự động: 5'] → [3. Agent tự động tra cứu kiến trúc và dự báo xung đột: 5'] → [4. PO & Dev review, chỉnh sửa và chốt: 25'] 

Fallback: Nếu AI sinh thiếu edge-case hoặc hiểu sai ý nghiệp vụ phức tạp, PO trực tiếp sửa đổi thủ công trên giao diện review.
```


---

#### Problem Card #2 — Tổng hợp Action Items từ cuộc họp

```text
Problem 1 câu: Thành viên nhóm mất quá nhiều thời gian nghe lại bản ghi âm hoặc đọc transcript thô để chắt lọc và tổng hợp đầu việc sau mỗi cuộc họp.

Actor:

Thời điểm / bối cảnh: Ngay sau khi các cuộc họp trực tuyến kết thúc (3–4 buổi/tuần).

Current workflow 3-7 bước:

Current workflow 3-7 bước:
1. Mở file ghi âm hoặc đọc lại toàn bộ file transcript thô (20')
2. Tự lọc thủ công các đoạn hội thoại có nhắc đến phân công công việc (10')
3. Viết lại diễn giải thành danh sách action items (10')
4. Gửi email hoặc nhắn tin thông báo kết quả họp cho các bên liên quan (5')

Bottleneck: Bước 1 và Bước 2 (Nghe/đọc lại khối lượng thông tin lớn, dễ bỏ sót nhiệm vụ được giao phó mập mờ).

Impact: Tốn 30–45 phút mỗi buổi họp; thường xuyên xảy ra tình trạng "quên việc" hoặc hiểu sai người chịu trách nhiệm.

Success metric: Rút ngắn thời gian xử lý biên bản họp xuống dưới 5 phút; tỉ lệ bỏ sót action items giảm về 0%.

Non-AI alternative: Chỉ định cố định một thư ký chuyên trách ghi chép tỉ mỉ từng buổi họp.

AI hypothesis: Dùng LLM chuyên biệt để đọc transcript, nhận diện câu lệnh phân công (ai, làm gì, deadline khi nào) và tự động tạo danh sách chuẩn hóa.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 45 phút

[1. Mở file ghi âm/transcript thô: 20'] → [2. Lọc thủ công nội dung: 10'] → [3. Viết action items: 10']  <-- bottleneck → [4. Gửi thông báo: 5']

FUTURE STATE — 10 phút

[1. Tải transcript vào hệ thống: 2'] → [2. AI tự động bóc tách và phân loại đầu việc: 3'] → [3. Người quản lý review và phê duyệt danh sách: 5']  <-- human boundary

Fallback: Nếu AI phân loại nhầm người phụ trách, người quản lý bấm chỉnh sửa trực tiếp trước khi hệ thống tự động đồng bộ.
```


---

#### Problem Card #3 — Viết mô tả Pull Request tự động

```text
Problem 1 câu: Lập trình viên tốn thời gian cấu trúc và viết mô tả Pull Request (PR description) bằng tiếng Anh sao cho người review dễ nắm bắt ngữ cảnh code thay đổi.

Actor: Developer, Code Reviewer.

Thời điểm / bối cảnh: Ngay sau khi hoàn thành một task lập trình và chuẩn bị đẩy code lên hệ thống quản lý mã nguồn.

Current workflow 3-7 bước:
1. Chạy lệnh xem lại toàn bộ các file thay đổi (git diff) (3')
2. Nhớ lại toàn bộ quá trình tư duy và các điểm kỹ thuật đã sửa (5')
3. Mở khung soạn thảo PR description và tự viết thủ công bằng tiếng Anh (7')
4. Đẩy code lên và chờ reviewer nhắc nhở bổ sung thiếu context (nếu có) (2')

Bottleneck: Bước 3 (Viết diễn giải thủ công bằng ngoại ngữ, dễ bị sơ hở thiếu thông tin kỹ thuật quan trọng).

Impact: Mất 10–15 phút mỗi PR; reviewer mất thêm thời gian hỏi lại do thiếu ngữ cảnh tổng quan.

Success metric: Giảm thời gian chuẩn bị PR xuống dưới 2 phút; tăng độ hoàn chỉnh của mô tả code lên 95%.

Non-AI alternative: Dùng một template mẫu định sẵn buộc dev phải điền các trường bắt buộc bằng tay.

AI hypothesis: Tự động phân tích git diff thông qua LLM để tóm tắt ngắn gọn các thay đổi chính theo cấu trúc chuẩn.

Quick gut:
[ ] No AI / process fix
[X] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 15 phút

[1. Xem git diff: 3'] → [2. Nhớ lại logic code: 5'] → [3. Viết mô tả thủ công: 7']  <-- bottleneck

FUTURE STATE — 3 phút

[1. Lệnh gọi trợช่วย AI đọc git diff: 1'] → [2. AI sinh bản draft mô tả PR: 1'] → [3. Dev review nhanh và bấm tạo PR: 1']  <-- human boundary

Fallback: Nếu AI tóm tắt chưa sát ý trọng tâm, dev tự chỉnh sửa lại câu chữ trực tiếp trên khung PR.
```


---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Phân rã tính năng tự động từ ngôn ngữ tự nhiên (Problem #9)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán này giải quyết trực tiếp quy trình tiền lập kế hoạch sprint từ lúc nhận yêu cầu thô đến khi ra User Story và Test Case. Nó giúp cắt giảm thời gian chuẩn bị thủ công từ 3–4 giờ xuống dưới 45 phút mỗi tính năng lớn. Đồng thời, giải pháp kết hợp giữa Workflow, LLM và Agent này giúp hạn chế tối đa tình trạng thiếu hụt kịch bản kiểm thử (edge-case) khi đưa vào thực tế.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Liệu AI Agent khi tra cứu tài liệu kiến trúc hệ thống cũ có gặp tình trạng "ảo giác" (hallucination) và tự sinh ra các kịch bản xung đột ảo không?

Nếu yêu cầu từ phía khách hàng quá mơ hồ và thay đổi liên tục, bước workflow tự động hóa này có bị nghẽn ở khâu Product Owner duyệt lại hay không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI nhận định rằng việc tự động sinh ra mã kiểm thử (test case) sơ bộ phụ thuộc rất lớn vào độ chuẩn hóa của dữ liệu đầu vào; nếu input từ khách hàng không có cấu trúc rõ ràng, Agent sẽ dễ đưa ra các tiêu chí chấp nhận (Acceptance Criteria) sai lệch về mặt nghiệp vụ.
- Tôi sửa gì: Tôi bổ sung thêm một lớp kiểm soát (human boundary) ngay tại bước PO review và chỉnh sửa trước khi hệ thống chính thức đẩy các User Story này vào backlog của sprint.

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge
