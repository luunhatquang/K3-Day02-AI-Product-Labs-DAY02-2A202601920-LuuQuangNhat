# 03 — Individual Reflection

## Đóng góp của Lưu Quang Nhật trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems về lĩnh vực học tập (roadmap, skill gap, so sánh khóa học...) | Nhóm có thêm góc nhìn từ trải nghiệm sinh viên tự học |
| Pitch Problem Card | Pitch candidate #2 — "Người dùng không được cảnh báo khi văn bản sắp hết hiệu lực hoặc đã có văn bản thay thế" | Candidate được nhóm đánh giá cao về tác động nghiệp vụ, góp phần hình thành Cluster B |
| Challenge bài của bạn khác | Hỏi nhóm: nếu metadata văn bản chưa có trạng thái hiệu lực và quan hệ sửa đổi thì AI có thể xác định đúng không? | Nhóm bổ sung yêu cầu audit metadata trước khi xây AI, đưa vào điều kiện "Not Yet → Go" |
| Gom trùng / cluster | Gom các candidate #1 (tìm đúng điều khoản), #7 (nguồn phân tán), #8 (thiếu citation), #10 (OCR) thành Cluster A; gom #2 (hiệu lực) và #3 (diễn giải) thành Cluster B | Nhóm thấy rõ pain nằm trong cùng workflow tra cứu, từ đó gộp Cluster A + B + D thành PolicyMate |
| Chọn candidate problem | Hỗ trợ lập shortlist, tham gia chấm scorecard | PolicyMate được chọn với tổng điểm 30/35, cao nhất trong 3 candidates |
| Validation / research | Đóng góp ý kiến về cách thiết kế benchmark nội bộ và yêu cầu citation accuracy phải tách riêng version accuracy | Nhóm tách 2 metric riêng: citation accuracy và version/effectiveness accuracy |
| Workflow nhóm | Góp ý bổ sung bước "Rule xác định phiên bản có hiệu lực" vào future workflow | Future workflow có bước 4 riêng cho hiệu lực, không gộp chung với retrieval |
| Problem Statement | Góp ý field Boundary: AI không được tự xác lập hiệu lực khi metadata chưa rõ | PS v1 có boundary chặt hơn v0 |
| Rule / Workflow / Agent | Lập luận Workflow phù hợp hơn Agent vì các bước cố định, có checkpoint rõ | Nhóm thống nhất chọn Workflow, không chọn Agent |
| Decision | Ủng hộ Not Yet vì chưa có baseline và audit metadata | Nhóm chốt Not Yet với danh sách điều kiện cụ thể để chuyển sang Go |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problems theo góc nhìn sinh viên tự học | Giúp mở rộng lăng kính, nhớ thêm pain "không biết ưu tiên học gì" và "mỗi lần thấy khóa mới phải tự đánh giá" | Một số gợi ý quá rộng kiểu "xây trợ lý AI toàn năng cho sinh viên" | Bỏ các ý không có workflow thật, chỉ giữ ý có trải nghiệm cá nhân |
| Problem Card | Nhờ AI phản biện Problem Card theo 6 câu hỏi skeptical PM | Chỉ ra actor "sinh viên" chưa đủ cụ thể, metric "giảm thời gian" cần baseline rõ hơn | AI khen nhiều hơn chê, phản biện chưa sắc | Tự bổ sung bottleneck cụ thể hơn và thêm non-AI alternative |
| Workflow | Nhờ AI chuyển mô tả workflow thành dạng ASCII flow | Nhanh hơn khi format, giữ đúng cấu trúc bước | AI gộp bước "tìm tài liệu" và "đọc review" thành một bước | Tách lại vì bottleneck nằm ở bước tìm tài liệu, không phải đọc review |
| Research | Tìm tool và pattern giải pháp tương tự (NotebookLM, PowerDMS, Azure AI Search) | Gợi ý được các pattern grounded Q&A, document-level access control | Có claim "tiết kiệm 70% thời gian" không có nguồn | Chỉ giữ link chính thức, ghi rõ giới hạn của từng research |
| Problem Statement | Nhờ AI phản biện PS v0, chỉ ra field mơ hồ | Chỉ ra metric "giảm thời gian" chưa có baseline và boundary chưa đề cập hiệu lực | AI đề xuất thêm nhiều feature vượt scope lab | Giữ scope hẹp, thêm boundary "không tự xác lập hiệu lực khi thiếu metadata" |
| Rule / Workflow / Agent | Hỏi AI so sánh 3 mức cho bài toán tra cứu văn bản | Giải thích rõ khi nào Agent cần thiết (nhiều nhánh động, tự quyết) | AI thiên về đề xuất Agent vì nghe "thông minh hơn" | Nhóm hạ về Workflow vì workflow cố định và có human review |
| Decision | Không dùng AI để quyết định | — | — | Nhóm tự thảo luận và chốt Not Yet |

## Reflection câu hỏi mở

- **Tôi học được gì khi nghe top 3 problems của các bạn khác?**

```text
Tôi nhận ra các bạn trong nhóm có góc nhìn rất khác nhau dù cùng ngồi trong một lớp. 
Trong khi tôi tập trung vào pain học tập cá nhân (roadmap, skill gap), các bạn khác 
đưa ra pain về tra cứu văn bản, phân quyền, audit log — những thứ tôi chưa từng nghĩ tới. 
Điều này dạy tôi rằng scan rộng thật sự quan trọng: nếu chỉ nhìn từ một góc, 
sẽ bỏ lỡ những bài toán có workflow và metric rõ hơn.
```

- **Nhóm có lúc nào bị solution-first không?**

```text
Có. Lúc đầu khi nghe candidate "Roadmap học tập cá nhân", một số bạn nói ngay 
"làm chatbot gợi ý khóa học". Nhưng khi challenge lại, nhóm nhận ra chưa có 
competency framework hay cách đo "roadmap phù hợp" là gì. 
Từ đó nhóm quay lại problem-first và chọn PolicyMate vì workflow rõ hơn.
```

- **Tôi có thay đổi ý kiến sau khi bị challenge không?**

```text
Có. Ban đầu tôi nghĩ candidate học tập của mình mạnh nhất vì "ai cũng gặp". 
Nhưng khi nhóm challenge về metric và domain cụ thể, tôi phải thừa nhận 
bài toán tra cứu văn bản có actor, workflow và cách đo rõ hơn rất nhiều. 
Tôi chuyển sang ủng hộ PolicyMate và tập trung vào việc cluster + shortlist.
```

- **Tôi đóng góp gì thật sự vào artifact cuối?**

```text
Đóng góp chính của tôi là gom trùng các candidate thành cluster có logic 
(Cluster A, B, C, D) và giúp nhóm thấy rõ pain nằm trong cùng một workflow 
tra cứu văn bản. Ngoài ra, tôi góp ý tách citation accuracy và version accuracy 
thành 2 metric riêng, vì "trích dẫn đúng file nhưng file hết hiệu lực" 
vẫn là lỗi nghiêm trọng.
```

- **Điều khó nhất khi viết Problem Statement là gì?**

```text
Khó nhất là viết field Impact khi chưa có baseline đã xác nhận. 
Nhóm chỉ có một quan sát ban đầu (10-20 phút) từ Problem Scan cá nhân, 
chưa có interview hay task log. Phải cân bằng giữa việc ghi nhận tín hiệu 
mà không biến nó thành tuyên bố chắc chắn.
```

- **Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**

```text
Tôi sẽ push nhóm validate sớm hơn. Cụ thể, ngay sau khi gom cluster, 
nên dành 10 phút hỏi nhanh 2-3 giáo viên thật để xác nhận pain tra cứu 
trước khi đi sâu vào workflow và research. Hiện tại nhóm chọn Not Yet 
một phần vì thiếu validation — nếu làm sớm hơn, có thể đã đủ data 
để quyết định Go.
```

## Bài học

- Problem tốt không phải problem nghe "AI" nhất, mà là problem có actor cụ thể, workflow vẽ được và metric đo được. Candidate học tập của tôi có pain thật nhưng thiếu cách đo "phù hợp".
- Cluster giúp nhóm thấy các pain rời rạc thực ra nằm trong cùng một workflow. Đây là bước quan trọng nhất trong hội tụ.
- Tách metric rõ ràng (citation accuracy ≠ version accuracy) giúp nhóm không bị ảo tưởng rằng "trích dẫn đúng = trả lời đúng".
- Research không phải để chứng minh AI tốt, mà để thấy pattern: nhiều tool tốt đều để AI draft, người thật review, và cần process fix trước khi xây AI.
- Not Yet là kết luận tốt nếu lý do rõ. Không nên ép Go chỉ để có kết quả đẹp.

## Nếu làm lại

```text
Tôi sẽ dành thêm thời gian validate với giáo viên thật trước khi nhóm chốt decision. 
Baseline 10-20 phút hiện tại chỉ đến từ một quan sát cá nhân — nếu có thêm 3-5 data point 
từ interview, nhóm có thể tự tin hơn với target "dưới 5 phút" và có thể chuyển từ Not Yet sang Go.
Ngoài ra, tôi cũng sẽ challenge bài scan cá nhân của mình kỹ hơn: domain "học tập" quá rộng 
nếu không gắn với một nghề hoặc kỹ năng cụ thể.
```

---

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [x] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [x] [15đ nhóm] Nhóm có workflow trước/sau.
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

*Individual Reflection — Lưu Quang Nhật (2A202601920)*
