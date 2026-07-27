# 03 — Individual Reflection

> Lưu Quang Nhật — 2A202601920

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems về học tập cá nhân, bao gồm lên roadmap, so sánh khóa học, học lan man, thiếu kỹ năng | Nhóm có thêm 3 candidates về lộ trình học tập (#4, #5, #6 trong bảng tổng hợp) |
| Pitch Problem Card | Pitch top 3: Lên roadmap học tập, Không biết bắt đầu học từ đâu, Không biết mình còn thiếu kỹ năng nào | Cả 3 được gom vào Cluster C — Lộ trình học tập cá nhân; vào shortlist nhưng không được chọn làm candidate cuối |
| Challenge bài của bạn khác | Challenge việc nhóm chọn candidate chỉ vì ý tưởng nghe có vẻ "AI"; yêu cầu dùng cùng tiêu chí cho mọi candidate | Nhóm thống nhất chấm scorecard theo 7 tiêu chí, không vote theo cảm tính |
| Gom trùng / cluster | Tổng hợp 11 candidates thành 4 clusters (A–D), gom các pain trùng workflow tra cứu văn bản | Giúp nhóm thấy rõ Cluster A+B+D có thể hợp nhất thành PolicyMate |
| Chọn candidate problem | Điều phối shortlist, tính scorecard và ghi chú lý do cho từng điểm | PolicyMate được chọn với tổng 33/35, cao nhất nhóm; lập luận hội tụ minh bạch |
| Validation / research | Hỗ trợ kiểm tra chéo biên bản pitch/challenge cho Nguyễn Thị Xuân Mai | Đảm bảo log hội tụ có tên người phát biểu và quyết định |
| Workflow nhóm | Góp ý cấu trúc current workflow 8 bước và xác nhận bottleneck nằm ở bước 5 (kiểm tra hiệu lực) | Workflow nhất quán với scorecard và Problem Statement |
| Problem Statement | Góp ý vào PS v0 về việc metric phải tách riêng citation accuracy và version accuracy | PS v1 tách rõ 4 metric: answer correctness ≥85%, citation accuracy ≥95%, version accuracy 100%, access violation = 0 |
| Rule / Workflow / Agent | Lập luận Workflow phù hợp hơn Agent vì các bước cố định và có human review rõ ràng | Nhóm chọn Workflow, không nhảy sang Agent |
| Decision | Đồng thuận Not Yet vì chưa có baseline và audit dữ liệu | Quyết định có lý do rõ, không chọn Go khi thiếu bằng chứng |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problems theo góc nhìn sinh viên tự học | Giúp mở rộng từ 5 lên 10 problems; gợi ý thêm lăng kính "AI có thể tốt hơn" và "Pain từ người khác" | Một số gợi ý quá rộng kiểu "xây trợ lý AI toàn năng cho học tập" | Bỏ các ý không có trải nghiệm thật; chỉ giữ problems mình từng gặp |
| Problem Card | Nhờ AI phản biện Problem Card #1 (roadmap học tập) | Chỉ ra metric "giảm 2-3 giờ xuống 1 giờ" chưa rõ cách đo; gợi ý thêm non-AI alternative | AI gợi ý xây Agent tự tìm và gợi ý khóa học ngay lập tức — quá sớm | Giữ ở mức Workflow; thêm non-AI alternative rõ hơn |
| Workflow | Nhờ AI cấu trúc draft workflow từ mô tả thành dạng bước có thời gian | Nhanh hơn khi viết workflow 9 bước current state | AI gộp bước "tìm khóa học" và "đọc review" thành 1 bước | Tách lại vì bottleneck nằm ở bước tìm khóa học riêng |
| Research | Hỗ trợ tìm pattern/tool tương tự cho PolicyMate | Gợi ý Google NotebookLM, Azure AI Search, PowerDMS — đều có link chính thức | Có claim "AI giảm 80% thời gian" nhưng không nguồn rõ ràng | Chỉ giữ các nguồn có hyperlink chính thức; không dùng số liệu không verify được |
| Problem Statement | Nhờ AI phản biện PS v0 | Chỉ ra boundary chưa nói rõ "không tự xác lập hiệu lực khi thiếu metadata" | AI đề xuất thêm nhiều metric phức tạp không phù hợp pilot | Chỉ giữ 4 metric cốt lõi mà nhóm có thể đo trong pilot |
| Rule / Workflow / Agent | Nhờ AI so sánh 3 mức cho PolicyMate | Bảng so sánh rõ ràng, giúp thấy Rule đủ cho metadata/hiệu lực nhưng không đủ cho câu hỏi ngôn ngữ tự nhiên | AI ban đầu thiên về Agent với lý do "linh hoạt hơn" | Nhóm thống nhất Workflow vì chưa cần AI tự lập kế hoạch; giảm permission risk |
| Decision | Nhờ AI kiểm tra logic quyết định Not Yet | Xác nhận các gate chưa đạt là hợp lý | AI gợi ý "có thể Go với scope rất nhỏ" — nhưng chưa có baseline | Giữ Not Yet vì Go khi chưa đo baseline sẽ biến target thành tuyên bố không bằng chứng |

## Reflection câu hỏi mở

- **Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Nhiều bạn trong nhóm đưa ra problems về tra cứu văn bản nội bộ — một bài toán mà trước đó tôi chưa nghĩ tới vì bản thân tôi tập trung vào góc nhìn sinh viên. Khi nghe pitch, tôi nhận ra rằng pain tìm đúng văn bản có hiệu lực là bài toán có actor rõ hơn, workflow rõ hơn và metric dễ đo hơn so với bài toán roadmap học tập của mình. Điều này giúp tôi hiểu rằng problem tốt không phải problem mình quen thuộc nhất, mà là problem có thể vẽ workflow và đặt metric cụ thể.

- **Nhóm có lúc nào bị solution-first không?**

Có. Lúc đầu có một số thành viên muốn xây Agent tra cứu ngay vì nghe "cool". Tôi challenge bằng cách hỏi: "Agent cần permission gì? Ai kiểm tra khi AI sai?" — và nhóm nhận ra Workflow an toàn hơn, dễ audit hơn. Ngoài ra, nhóm cũng suýt bỏ qua bước chuẩn hóa dữ liệu (process fix) vì tập trung vào phần AI.

- **Tôi có thay đổi ý kiến sau khi bị challenge không?**

Có. Ban đầu tôi muốn push candidate roadmap học tập vào shortlist mạnh hơn, nhưng khi nhóm challenge rằng domain quá rộng, chưa có competency framework và metric đánh giá "roadmap phù hợp" rất khó đo, tôi đồng ý rằng PolicyMate có workflow và metric rõ hơn cho lab.

- **Tôi đóng góp gì thật sự vào artifact cuối?**

Đóng góp chính: tổng hợp 11 candidates thành 4 clusters, lập shortlist và tính scorecard. Tôi cũng challenge việc chọn theo cảm tính, yêu cầu nhóm dùng cùng 7 tiêu chí cho mọi candidate. Kết quả là quá trình hội tụ được ghi nhận minh bạch — ai cũng giải thích được vì sao PolicyMate được chọn.

- **Điều khó nhất khi viết Problem Statement là gì?**

Tách metric. Lúc đầu nhóm gộp chung "tìm đúng và trích dẫn đúng" thành một metric duy nhất. Nhưng khi phản biện, tôi và nhóm nhận ra citation đúng file chưa đồng nghĩa văn bản còn hiệu lực — nên phải tách thành answer correctness, citation accuracy và version accuracy.

- **Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**

Tôi sẽ push nhóm validate sớm hơn. Nhóm dành khá nhiều thời gian xây cấu trúc report nhưng chưa thực hiện phỏng vấn hoặc đo baseline. Nếu làm lại, tôi sẽ đề xuất chia đôi: một nửa nhóm xây report, một nửa nhóm đi phỏng vấn và đo baseline song song, để đến lúc chốt quyết định Go/Not Yet đã có dữ liệu thật.

## Bài học

- Problem tốt không phải problem mình quen nhất, mà là problem có actor rõ, workflow vẽ được và metric đo được. Bài toán roadmap học tập của tôi có pain thật nhưng thiếu metric cụ thể, trong khi PolicyMate có tất cả.
- Vẽ workflow trước khi chọn AI giúp thấy rõ phần nào rule/process fix đã đủ. Trong case PolicyMate, metadata và chuẩn hóa kho là bước bắt buộc trước khi nghĩ đến AI.
- Agent không phải đích đến mặc định. Nhóm chọn Workflow vì các bước cố định, có human review và dễ audit hơn. Agent làm tăng permission và khó truy vết.
- Research không phải để copy tool, mà để tìm pattern. Nhiều hệ thống (NotebookLM, Azure AI Search) đều có chung pattern: AI draft + citation + người thật kiểm tra.
- Not Yet là quyết định hợp lý khi chưa có bằng chứng. Chọn Go khi thiếu baseline, audit và owner sẽ biến target thành lời hứa rỗng.

## Nếu làm lại

```text
1. Tôi sẽ validate với người dùng thật sớm hơn, không chỉ dựa vào trải nghiệm cá nhân hoặc giả định.
2. Tôi sẽ push nhóm đo baseline song song với xây report, thay vì để validation sau cùng.
3. Tôi sẽ thu hẹp bài toán roadmap học tập của mình theo một nghề/kỹ năng cụ thể trước khi pitch, để metric rõ hơn.
```

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 10 problems (vượt mức 5) và top 3 Problem Cards đầy đủ.
- [x] [12đ cá nhân] Tôi đã pitch rõ top 3 và challenge nhóm về việc chọn theo cảm tính.
- [x] Nhóm có nhật ký hội tụ từ 11 candidates về 1 bài (PolicyMate).
- [x] [15đ nhóm] Nhóm có workflow trước/sau (current 8 bước, future 9 bước).
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric (85%, 95%, 100%, 0) và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Not Yet và lý do rõ (thiếu baseline, audit, owner).
- [x] [10đ cá nhân] Reflection có vai trò trong nhóm, cách dùng AI, bài học và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi giải thích được: problem (tìm đúng văn bản có hiệu lực) → workflow (8 bước tra cứu) → metric (4 metric tách biệt) → boundary (không tự diễn giải, fail closed) → Workflow phù hợp hơn Agent.

---
