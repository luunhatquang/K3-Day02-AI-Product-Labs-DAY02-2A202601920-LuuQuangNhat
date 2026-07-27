# 01 — Individual Problem Scan

## Scan rộng


| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi học kỳ lại phải tự lên kế hoạch học. | Sinh viên | Mất khoảng 2-3 giờ để tìm roadmap, video, sách, khóa học phù hợp với trình độ và mục tiêu cá nhân |
| 2 | Lặp lại | Mỗi tuần phải tự điều chỉnh lịch học khi lịch cá nhân thay đổi. | Sinh viên | Mất khoảng 30 phút/tuần để điều chỉnh lịch học |
| 3 | Tốn thời gian | Mất nhiều thời gian so sánh khóa học. | Sinh viên | 60 phút/lần |
| 4 | Tốn thời gian | Mất thời gian xem YouTube nhưng học lan man. | Sinh viên | 2-3 giờ/lần |
| 5 | Tốn thời gian | Không biết ưu tiên học cái gì trước nên mất thời gian thử sai. | Sinh viên | 2-3 giờ/lần |
| 6 | AI có thể tốt hơn | Khó khăn trong tổng hợp tài liệu | Sinh viên | Nhiều tài liệu nên tổng hợp còn mơ hồ chưa đi sâu vào trọng tâm |
| 7 | AI có thể tốt hơn | Khó cá nhân hóa roadmap theo mục tiêu, thời gian, trình độ. | Sinh viên | Mất nhiều thời gian để tìm hiểu và cá nhân hóa roadmap. |
| 8 | Điểm đau của người dùng | Không biết bắt đầu học từ đâu | Sinh viên | Thiếu mục tiêu cụ thể, thiếu lộ trình học tập rõ ràng |
| 9 | Điểm đau của người dùng | Không biết mình còn thiếu kỹ năng nào | Sinh viên | Thiếu công cụ để đánh giá năng lực bản thân rõ ràng |
| 10 | Lặp lại | Mỗi lần thấy khóa học mới đều phải tự đánh giá có nên học không. | Sinh viên | 15-30 phút/lần |


## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Lên roadmap học tập cho cá nhân | AI có thể dựa vào năng lực, mục tiêu, thời gian, trình độ để cá nhân hóa roadmap. | Khó đo được độ phù hợp cho từng cá nhân.|
| 2 | Không biết bắt đầu học từ đâu.| Có pain thật, AI có thể giúp tổng hợp tài liệu và đưa ra roadmap học tập. | Vẫn khó để đánh giá được độ phù hợp của nội dung học tập. |
| 3 | Không biết mình còn thiếu kỹ năng nào | Nhiều người đau, impact rộng | Việc xác định kỹ năng còn thiếu còn mơ hồ. |

## Problem Card #1 — Lên roadmap học tập cho cá nhân

**Problem 1 câu:**  
Sinh viên mất 2-3 giờ để lên roadmap học tập cho cá nhân, bao gồm việc tìm kiếm, so sánh, đánh giá và lựa chọn tài liệu học tập phù hợp.

**Actor:**  
Sinh viên.

**Thời điểm / bối cảnh:**  
Mỗi kỳ nhập học, trước khi bắt đầu học.

**Current workflow:**

```text
1. Xác định mục tiêu
2. Tìm kiếm roadmap trên Google/YouTube/GitHub
3. So sánh nhiều roadmap khác nhau
4. Xác định trình tự các kỹ năng cần học
5. Tìm kiếm khóa học, sách, video cho từng kỹ năng
6. Đọc review, so sánh chất lượng và độ phù hợp
7. Lựa chọn tài liệu học tập
8. Tự xây dựng roadmap trên Notion/Excel/Giấy
9. Bắt đầu học
```

**Bottleneck:**  
Bước 5 — tìm kiếm khóa học, sách, video cho từng kỹ năng tốn nhiều thời gian và khó tìm được tài liệu phù hợp.

**Impact:**  
2-3 giờ cho 1 sinh viên.

**Success metric:**  
Giảm tổng thời gian từ 2-3 giờ xuống dưới 1 giờ.

**Non-AI alternative:**  
Xây dựng website tổng hợp roadmap và review tài liệu học tập. Tuy nhiên, việc duy trì và cập nhật website sẽ tốn nhiều công sức và khó đảm bảo tính chính xác của thông tin.

**AI hypothesis:**  
AI hỗ trợ cá nhân hóa roadmap học tập, giúp sinh viên tìm kiếm, so sánh, đánh giá và lựa chọn tài liệu học tập phù hợp với mục tiêu, trình độ và thời gian của bản thân.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 2-3 giờ

[1 Xác định mục tiêu: 15']
→ [2 Tìm roadmap trên Google/YouTube/GitHub: 30']
→ [3 So sánh nhiều roadmap: 20']
→ [4 Xác định trình tự kỹ năng: 15']
→ [5 Tìm khóa học/sách/video cho từng kỹ năng: 40']  <-- bottleneck
→ [6 Đọc review, so sánh chất lượng: 20']
→ [7 Lựa chọn tài liệu: 10']
→ [8 Tự xây dựng roadmap trên Notion/Excel: 15']
→ [9 Bắt đầu học: 5']
```

### Draft future workflow

```text
FUTURE STATE — 45-60 phút

[1 Sinh viên nhập mục tiêu + trình độ + thời gian: 10']
→ [2 AI phân tích và gợi ý lộ trình kỹ năng: 2']
→ [3 AI tìm và đề xuất tài liệu phù hợp: 3']  -- AI step
→ [4 Sinh viên review roadmap + chỉnh sửa: 25']  <-- human boundary
→ [5 Xuất roadmap ra Notion/Excel: 5']

Fallback: AI gợi ý không phù hợp → Sinh viên tự điều chỉnh hoặc quay lại tìm thủ công.
```

---

## Problem Card #2 — Không biết bắt đầu học từ đâu

**Problem 1 câu:**  
Sinh viên khi bắt đầu học một lĩnh vực mới (ví dụ: lập trình, data science, AI) không biết nên bắt đầu từ đâu, dẫn đến mất 1-2 giờ tìm hiểu mà vẫn không có hướng đi rõ ràng.

**Actor:**  
Sinh viên muốn tự học thêm kỹ năng mới ngoài chương trình chính khóa.

**Thời điểm / bối cảnh:**  
Khi bắt đầu học một lĩnh vực/công nghệ mới, hoặc khi muốn chuyển hướng học tập.

**Current workflow:**

```text
1. Nghe bạn bè/mentor giới thiệu một lĩnh vực mới
2. Google tìm "learn X from scratch" hoặc "X roadmap for beginners"
3. Đọc nhiều bài blog, xem video "how to start learning X"
4. Bị overwhelm vì quá nhiều nguồn, mỗi nguồn nói khác nhau
5. Chọn thử một khóa học / tutorial
6. Học được vài buổi, phát hiện không phù hợp trình độ
7. Quay lại bước 2-3, lặp lại
```

**Bottleneck:**  
Bước 3-4 — đọc quá nhiều nguồn khác nhau, mỗi nguồn đưa ra lời khuyên khác, dẫn đến bị overwhelm và không đưa ra được quyết định bắt đầu từ đâu.

**Impact:**  
1-2 giờ mỗi lần muốn bắt đầu học cái mới; nhiều sinh viên bỏ cuộc trước khi thực sự bắt đầu. Vòng lặp thử-sai có thể kéo dài vài ngày đến vài tuần.

**Success metric:**  
Giảm thời gian từ "muốn học" đến "bắt đầu học bài đầu tiên" từ 1-2 giờ xuống dưới 20 phút; giảm tỷ lệ bỏ ngang khóa học trong tuần đầu.

**Non-AI alternative:**  
Hỏi mentor/anh chị khóa trên trực tiếp; tham gia cộng đồng học tập có hướng dẫn sẵn. Tuy nhiên, không phải ai cũng có mentor và lời khuyên vẫn chung chung, chưa cá nhân hóa.

**AI hypothesis:**  
AI đóng vai trò "cố vấn học tập": hỏi sinh viên về trình độ hiện tại, mục tiêu, thời gian rảnh, rồi tổng hợp từ nhiều nguồn để gợi ý điểm bắt đầu phù hợp nhất và 3-5 bước đầu tiên cụ thể.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 1-2 giờ (lặp lại nhiều lần)

[1 Nghe giới thiệu lĩnh vực mới: 5']
→ [2 Google "learn X from scratch": 15']
→ [3 Đọc nhiều bài blog/video: 30']  <-- bottleneck
→ [4 Bị overwhelm, không chọn được: 15']
→ [5 Chọn thử 1 khóa: 10']
→ [6 Học vài buổi, phát hiện không phù hợp: vài ngày]
→ [7 Quay lại bước 2: vòng lặp]
```

### Draft future workflow

```text
FUTURE STATE — 15-20 phút

[1 Sinh viên mô tả lĩnh vực muốn học + trình độ hiện tại: 5']
→ [2 AI phân tích và đề xuất điểm bắt đầu + 3-5 bước đầu: 2']  -- AI step
→ [3 AI gợi ý 2-3 tài liệu/khóa học phù hợp trình độ: 1']  -- AI step
→ [4 Sinh viên review, chọn hướng đi: 10']  <-- human boundary
→ [5 Bắt đầu học: 2']

Fallback: AI gợi ý sai trình độ → Sinh viên feedback lại để AI điều chỉnh, hoặc hỏi mentor.
```

---

## Problem Card #3 — Không biết mình còn thiếu kỹ năng nào

**Problem 1 câu:**  
Sinh viên không có cách đánh giá hệ thống xem mình đang thiếu kỹ năng nào so với yêu cầu của ngành/vị trí mục tiêu, dẫn đến học lan man hoặc bỏ sót kỹ năng quan trọng.

**Actor:**  
Sinh viên chuẩn bị đi thực tập hoặc xin việc, cần biết mình còn thiếu gì.

**Thời điểm / bối cảnh:**  
Trước khi apply thực tập/việc làm; cuối mỗi học kỳ khi review lại năng lực; khi thấy bạn bè có kỹ năng mình chưa biết.

**Current workflow:**

```text
1. Đọc job description (JD) của vị trí mục tiêu
2. Liệt kê yêu cầu kỹ năng từ JD
3. Tự đánh giá mình biết/chưa biết từng kỹ năng
4. Hỏi bạn bè/mentor xem mình còn thiếu gì
5. So sánh với CV của những người đã được nhận
6. Tự lập danh sách kỹ năng cần bổ sung
7. Ưu tiên học cái nào trước (thường dựa vào cảm tính)
```

**Bottleneck:**  
Bước 3 — tự đánh giá năng lực rất chủ quan, sinh viên thường đánh giá quá cao hoặc quá thấp, không có tiêu chí rõ ràng để đo.

**Impact:**  
Mỗi lần tự đánh giá mất 1-2 giờ nhưng kết quả không chính xác; nhiều sinh viên đến khi phỏng vấn mới phát hiện thiếu kỹ năng quan trọng. Ảnh hưởng đến cả nhóm sinh viên cùng ngành.

**Success metric:**  
Giảm thời gian đánh giá skill gap từ 1-2 giờ xuống dưới 30 phút; tăng độ chính xác bằng cách so sánh với benchmark ngành (ít nhất 5 JD cùng vị trí).

**Non-AI alternative:**  
Làm checklist kỹ năng theo từng vị trí; hỏi mentor đánh giá; làm mock interview. Tuy nhiên, checklist tĩnh nhanh lỗi thời và mentor không phải lúc nào cũng sẵn sàng.

**AI hypothesis:**  
AI phân tích nhiều JD cùng vị trí mục tiêu, tổng hợp danh sách kỹ năng yêu cầu, sau đó hỏi sinh viên một số câu hỏi đánh giá nhanh để xác định skill gap và đề xuất thứ tự ưu tiên học.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 1-2 giờ

[1 Đọc JD vị trí mục tiêu: 15']
→ [2 Liệt kê yêu cầu kỹ năng: 10']
→ [3 Tự đánh giá biết/chưa biết: 20']  <-- bottleneck (chủ quan)
→ [4 Hỏi bạn bè/mentor: 15-30']
→ [5 So sánh CV người đã được nhận: 15']
→ [6 Lập danh sách kỹ năng cần bổ sung: 10']
→ [7 Ưu tiên theo cảm tính: 5']
```

### Draft future workflow

```text
FUTURE STATE — 20-30 phút

[1 Sinh viên nhập vị trí mục tiêu + CV/profile hiện tại: 5']
→ [2 AI crawl và phân tích 5-10 JD cùng vị trí: 2']  -- AI step
→ [3 AI tổng hợp skill map + hỏi câu hỏi đánh giá nhanh: 3']  -- AI step
→ [4 AI xác định skill gap và đề xuất thứ tự ưu tiên: 1']  -- AI step
→ [5 Sinh viên review kết quả + điều chỉnh: 15']  <-- human boundary
→ [6 Xuất danh sách học tập có ưu tiên: 2']

Fallback: AI đánh giá sai trình độ → Sinh viên tự điều chỉnh hoặc hỏi mentor để verify.
---
