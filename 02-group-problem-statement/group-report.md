## 1. Group Convergence (Tổng hợp 15 Vấn đề từ 5 Thành viên)


| # | Người đưa ra | Candidate problem | Người gặp vấn đề (Actor) | Điểm nghẽn (Bottleneck) | Cảm nhận nhanh (Impact & Context) |
|---|---|---|---|---|---|
| 1 | Vũ Quang Huy | Checklist kiểm tra feature chưa đúng mô tả | Cả đội dev/QA | Dễ phát sinh lỗi so với testcase | Mất thời gian revert code, chờ đợi sửa feature, gây trễ deadline chung |
| 2 | Vũ Quang Huy | Leader tốn thời gian check PR nếu commit ngắn/mơ hồ | Leader, cả team dev | Dễ gây ra crash/sập hệ thống mà khó khoanh vùng lỗi | Mất thời gian review, rủi ro revert code cao |
| 3 | Vũ Quang Huy | Xuất hiện bug sau khi merge code | Cả team dev | Tìm nguyên nhân lỗi mất 30-60 phút | Chậm sửa bug, gián đoạn công việc của cả nhóm |
| 4 | Hoàng Đức Linh | Tổng hợp deadline từ nhiều kênh (LMS, Zalo, Email, Lời nhắc) | Sinh viên học nhiều môn | Đối chiếu thủ công giữa 4-5 kênh, dễ sót khi có cập nhật | Mất 20-40p/tuần, nộp muộn/bỏ sót deadline 1-2 lần/kỳ |
| 5 | Hoàng Đức Linh | Theo dõi tiến độ bài nhóm & trùng task | Nhóm sinh viên 3-5 người | Phân công & tiến độ bị chìm trong chat, tổng hợp thủ công | 5-10 tin nhắn hỏi lại/project, trễ task phát hiện sát deadline |
| 6 | Hoàng Đức Linh | Đọc tài liệu dài trước deadline | Sinh viên ôn thi/làm bài | Nối ý giữa tài liệu dài 30-60 trang với yêu cầu bài tập | Mất 30-60p/lần đọc dàn trải, vẫn không chắc đúng trọng tâm |
| 7 | Nguyễn Hoàng Sơn | Lập & dự phòng TKB tín chỉ khi portal nghẽn | Sinh viên đăng ký môn | Portal lag/sập, lớp chính full slot, hoảng loạn vỡ TKB | Mất 3-4 tiếng làm thủ công, rủi ro trễ tiến độ tốt nghiệp |
| 8 | Nguyễn Hoàng Sơn | Tra cứu & kiểm tra điều kiện môn tiên quyết | Sinh viên năm 3 | Dò thủ công từng môn điều kiện qua nhiều PDF quy chế rải rác | Mất 30-45p tra cứu, rủi ro bị hủy lớp đồ án muộn |
| 9 | Nguyễn Hoàng Sơn | Phân tích review giảng viên / môn học | Sinh viên chọn lớp | Review rải rác trên FB/Forum, thông tin nhiễu & mâu thuẫn | Mất 45-60p đọc bài, dễ chọn sai giảng viên không hợp phong cách |
| 10 | Thiều Thị Ngọc Ánh | Tổng hợp action items sau cuộc họp | PM, thành viên nhóm | Thông tin tổng hợp rải rác từ nhiều kênh nên dễ sót | Hiểu sai nhiệm vụ, quên deadline, giảm hiệu quả nhóm |
| 11 | Thiều Thị Ngọc Ánh | Chuyển báo cáo thô thành slide thuyết trình | Thành viên phụ trách slide | Bước chuyển nội dung thô thành slide vừa dễ đọc vừa đẹp | Mất ~30p mỗi lần làm slide, lặp lại nhiều lần khi nội dung đổi |
| 12 | Thiều Thị Ngọc Ánh | Tìm & lọc tài liệu tham khảo phù hợp | Cả nhóm làm nghiên cứu | Lọc nguồn phù hợp & xác định đoạn thực sự liên quan | Đọc tràn lan không liên quan, lãng phí thời gian cả nhóm |
| 13 | Nguyễn Đức Mạnh | Tìm lại quyết định cũ trong Discord/Slack | PM, team member | Đọc lại hàng chục/hàng trăm tin nhắn chìm trong chat | Mất 10-15p/lần tìm, gián đoạn công việc, hiểu sai quyết định cũ |
| 14 | Nguyễn Đức Mạnh | Quên deadline nhiệm vụ / Quên follow-up | PM, team member | Team member làm nhiều việc song song, không nhớ deadline | Trễ Sprint, PM mất công nhắn nhắc nhở, ảnh hưởng tiến độ |
| 15 | Nguyễn Đức Mạnh | Tổng hợp biên bản sau cuộc họp (Meeting note) | PM, note-taker | Tổng hợp meeting note từ ghi chú thô hoặc bản ghi âm | Mất ~30p sau mỗi cuộc họp, chậm triển khai công việc |


---


## 2. Gom trùng / Cluster


| Cluster | Candidates Included | Pattern chung | Ghi chú & Đánh giá |
|---|---|---|---|
| **A — Quản lý & Theo dõi Deadline / Tiến độ nhóm (CANDIDATE CHỌN)** | Linh (P1, P2), Ánh (P1), Mạnh (P2, P3) | Gom deadline rải rác, theo dõi tiến độ task nhóm, tự động tổng hợp action item & nhắc nhở | Pain xuất hiện ở hầu hết mọi nhóm sinh viên/dự án; impact lớn, đo lường rõ |
| **B — Quality Assurance & Code Merge (Dev Team)** | Huy (P1, P2, P3) | Kiểm tra checklist PR, review commit mơ hồ, truy vết bug sau merge | Phạm vi thiên về quy trình kĩ thuật lập trình (Software Engineering) |
| **C — Hỗ trợ Học tập & Đăng ký Tín chỉ cá nhân** | Sơn (P1, P2, P3), Linh (P3) | TKB dự phòng, tra cứu môn tiên quyết, tổng hợp review GV, đọc tài liệu | Mang tính cá nhân cao, tính lặp lại theo mùa (kỳ đăng ký môn) |
| **D — Truy xuất & Quản lý Tri thức Nhóm** | Mạnh (P1), Ánh (P3) | Tìm lại quyết định cũ trong Discord/Slack, lọc tài liệu tham khảo | Phù hợp bài toán RAG/Search; phụ thuộc dữ liệu chat/file |
| **E — Chuyển đổi Định dạng & Báo cáo** | Ánh (P2) | Biến văn bản thô/báo cáo thành slide thuyết trình | Thiên về bài toán Generative UI/Presentation AI |


---


## 3. Candidate nhóm chọn


```text
CANDIDATE CHỌN: THEO DÕI DEADLINE CỦA CẢ NHÓM (Group Deadline & Task Progress Tracking)
```


**Vì sao chọn:**
- **Actor vô cùng rõ ràng:** Sinh viên làm đồ án/project môn học, PM/Leader nhóm và các thành viên trong team.
- **Pain Point thực tế & nhói:** Deadline rải rác trên nhiều kênh (LMS, Zalo, Discord, Email), phân công công việc bị chìm trong chat, thành viên hay quên task, leader phải đi nhắn tin hỏi thủ công từng người.
- **Impact đo lường được:** Giảm 80% thời gian hỏi lại tiến độ, giảm 50% số task trễ deadline, tránh trùng task hoặc bỏ sót công việc trước ngày nộp.
- **Phù hợp scope bài Lab:** Bài toán có cấu trúc dữ liệu rõ (Task, Assignee, Deadline, Status), nguồn dữ liệu dễ thu thập (tin nhắn, meeting note, thông báo), dễ làm prototype và đo lường thành công.


**Cách giải quyết (Hướng tiếp cận đề xuất):**
- **Tự động gom & bóc tách Deadline/Task:** AI/Rule engine đọc & trích xuất thông báo từ LMS, Email, Chat (Zalo/Slack) và Meeting Notes để tạo danh sách Task chuẩn (Gồm: Task, Owner, Deadline).
- **Cơ chế Quick Check-in giảm ma sát:** Thành viên cập nhật tiến độ ngắn ngay tại kênh Chat (Micro-interaction) thay vì bắt mở dashboard/App phức tạp.
- **Nhắc nhở tự động thông minh (Digest Reminder):** Tự động tổng hợp & nhắc nhở 1-2 lần/ngày đẩy về Google Calendar hoặc Chat cá nhân để tránh spam thông báo.
- **Cảnh báo rủi ro trễ tiến độ (Risk Flagging):** Tự động phát hiện & flag các task chậm tiến độ cho Leader/PM trước 2-3 ngày deadline để hỗ trợ kịp thời.


**Workflow sơ đồ (Current vs Future Graph):**


* **1. Sơ đồ Quy trình Hiện tại (Current Workflow Graph — Tốn ~60-120 phút/tuần):**
  ```mermaid
  graph LR
      A["1. Thông báo rải rác<br/>(LMS, Email, Zalo)"] --> B["2. Chép tay thủ công<br/>(Tự tạo Note/Calendar)"]
      B --> C["3. Nhắn tin hỏi tiến độ<br/>(Leader nhắn 5-10 tin/tuần)"]
      C --> D["4. Phát hiện chậm trễ sát hạn<br/>(Trễ task & Sửa gấp)"]
  ```
  > `LMS / Email / Chat` ➔ `Chép tay thủ công` ➔ **`Leader nhắn hỏi thủ công (Bottleneck)`** ➔ `Sửa gấp sát hạn 24h`


* **2. Sơ đồ Quy trình Tương lai (Future Workflow Graph — Rút ngắn còn ~10-15 phút/tuần):**
  ```mermaid
  graph LR
      A1["1. Auto Pull & AI Parse<br/>(Gom & bóc tách Task chuẩn)"] --> B1["2. Con người Confirm<br/>(Human Boundary 1-Click)"]
      B1 --> C1["3. Quick Log & AI Digest<br/>(Check-in & Gom nhắc 1-2 lần/ngày)"]
      C1 --> D1["4. Auto Flag Risk & Report<br/>(Cảnh báo trễ trước 2-3 ngày)"]
  ```
  > `Auto Pull & AI Parse` ➔ **`Human Review & Confirm (Bảo mật)`** ➔ `Quick Log & Gom nhắc` ➔ `Cảnh báo rủi ro sớm`


**Vì sao không chọn các Candidate khác:**
- *Kiểm tra PR / Bug Merge:* Thiên nặng về kĩ thuật dev, khó tiếp cận cho người dùng phổ thông.
- *Lập TKB tín chỉ:* Tần suất lặp lại thấp (chỉ 1-2 lần/kỳ), phụ thuộc vào hệ thống portal trường.
- *Tìm quyết định cũ trong Discord:* Phụ thuộc chất lượng chat & log dữ liệu, chỉ là một phần nhỏ của bài toán quản lý nhóm.
- *Chuyển báo cáo thành slide:* Metric đánh giá thẩm mỹ mang tính chủ quan cao.


---


## 4. Validation (Kiểm chứng vấn đề) & Research (Giải pháp đã có)


### 4.1. Kết quả kiểm chứng thực tế (Quick Validation)


| Phương pháp | Quy mô / Mẫu | Tín hiệu xác nhận (Validation Signal) | Tín hiệu phản bác / Lưu ý (Invalidation Signal) | Điều chỉnh của Nhóm |
|---|---|---|---|---|
| **Hỏi nhanh (Quick Interview)** | 5 Leader nhóm sinh viên & 3 PM bài tập lớn | 100% thừa nhận phải nhắn 5-10 tin nhắn/tuần chỉ để hỏi "em xong chưa", "khi nào nộp". 4/5 nhóm từng bị trễ task do quên deadline chìm trong chat. | Một số thành viên ít nói thường ngại cập nhật tiến độ dù được hỏi. | Thiết kế kênh cập nhật cực nhanh (Quick check-in/Log) thay vì bắt viết báo cáo dài. |
| **Survey nhỏ (Micro Survey)** | 25 Sinh viên làm project nhóm | 84% cảm thấy phiền vì deadline nằm rải rác ở LMS, Zalo, Email. 76% muốn có 1 nơi duy nhất nhắc deadline tự động sang Google Calendar/Zalo. | 32% lo ngại nếu có quá nhiều thông báo nhắc nhở tự động (spam notification) sẽ gây ngó lơ. | Cần cơ chế gom thông báo thông minh (Aggregated Digest) 1-2 lần/ngày thay vì bắn notification liên tục. |
| **Review Log/Ticket/Chat** | 3 Box chat project môn học quá khứ (~500 tin nhắn) | Thấy rõ các mẫu tin nhắn lặp lại: *"ai làm phần này chưa?"*, *"slide nộp chưa mọi người?"*, *"hạn chót là mấy giờ vậy?"*. | Các tin nhắn chốt deadline thường không nằm ở 1 bài post cố định mà bị trôi sau các tin nhắn chém gió. | Cần AI/Rule bóc tách chính xác tin nhắn có chứa Task/Deadline/Assignee từ luồng chat. |
| **Quan sát trực tiếp** | 2 Buổi làm việc nhóm trước deadline | Thành viên mất 15-20 phút đầu buổi họp chỉ để đối chiếu lại ai đã làm xong gì, còn thiếu gì trước khi bắt tay vào làm. | Nếu dùng Trello/Notion thủ công, chỉ được 2-3 ngày đầu rồi team "bỏ hoang" bảng task. | Phải giảm tối đa ma sát (friction) khi log task, ưu tiên tự động bắt thông báo hoặc gõ lệnh cực ngắn. |


---


### 4.2. Nghiên cứu giải pháp hiện có trên thị trường (Market Research)


| Nguồn / Công cụ / Giải pháp | URL Link đã kiểm tra | Cách họ giải quyết | Điểm mạnh | Khoảng trống / Rủi ro | Bài học áp dụng cho nhóm |
|---|---|---|---|---|---|
| **Notion Projects & Notion AI** | https://www.notion.so/product/projects | Quản lý task dạng Kanban/Timeline, dùng AI auto-fill summary, gợi ý action items từ doc | Giao diện đẹp, tùy biến cao, tích hợp Docs + Tasks chung 1 nơi | Phụ thuộc kỷ luật người dùng tự nhập data thủ công; nếu team lười vào Notion thì data bị out-of-date | Cần tự động hóa khâu gom task/deadline từ nơi chat thay vì bắt dùng dashboard phức tạp |
| **Trello + Butler Automation** | https://trello.com/features/automation | Tạo rule tự động dịch chuyển card, gửi nhắc nhở deadline qua Email/Slack | Đơn giản, dễ dùng, rule rõ ràng | Không tự bóc tách được ngôn ngữ tự nhiên từ tin nhắn chat, không tự nhận biết ai đang kẹt task | Dùng Rule-based cho các nhắc nhở cố định, nhưng dùng AI để bóc tách tin nhắn tự nhiên |
| **Slack Reminder & RoutineBot** | https://slack.com/help/articles/208423427-Set-a-reminder | Đặt nhắc nhở theo cú pháp `/remind`, bot nhắc theo giờ cố định vào channel | Rất tiện ngay trên kênh chat, không cần mở app khác | Không có bức tranh tổng thể (Dashboard), nhắc xong dễ bị trôi, không theo dõi được trạng thái hoàn thành | Kết hợp cả 2: Nhắc nhở tại kênh chat (Micro-interaction) + Bảng tổng hợp tiến độ chung |
| **Asana Intelligence** | https://asana.com/product/ai | AI phân tích rủi ro trễ deadline (Health Score), tự động tạo subtask và tóm tắt tiến độ | Dự báo được rủi ro trễ tiến độ dựa trên lịch sử hoàn thành task | Chi phí đắt, quá phức tạp cho nhóm sinh viên/dự án nhỏ | Học tập tính năng "Flag rủi ro trễ deadline sớm" nhưng thiết kế tinh gọn cho nhóm 3-7 người |


---


### 4.3. Bằng chứng chắc chắn vs Giả định còn mở (Kèm Link Nguồn Kiểm Tra)


| Bằng chứng đã kiểm chứng (Chắc chắn / Evidence Confirmed) | Giả định còn mở (Chưa chắc chắn / Open Assumptions) & Link nguồn kiểm tra |
|---|---|
| **1. Kênh thông tin deadline bị phân tán là có thật:**<br>100% giảng viên và lớp học phân bổ thông báo rải rác trên LMS, Email trường, group Zalo/Facebook và lời nhắc miệng trên lớp.<br>*(Nguồn: Survey 25 sinh viên & log 3 box chat lớp)* | **Giả định 1: Sinh viên sẵn sàng cấp quyền đọc thông báo/chat:**<br>Chưa chắc sinh viên đồng ý cho Bot/App kết nối hoặc đọc thông báo từ Zalo/Messenger do lo ngại quyền riêng tư.<br>🔗 *Nguồn kiểm tra/tham khảo:* [Zalo Official Account API Privacy Policy](https://developers.zalo.me/docs/official-account/chinh-sach) & [Meta Graph API Permissions](https://developers.facebook.com/docs/permissions/) |
| **2. Bottleneck chính nằm ở khâu "TỔNG HỢP & NHẮC NỢ":**<br>Leader tốn 15-30p/tuần chỉ để hỏi từng thành viên và ghi chép lại tiến độ thủ công. Việc quên deadline xảy ra nhiều nhất ở tuần 4-8 của kỳ học.<br>*(Nguồn: Phỏng vấn 5 Leader & 3 PM sinh viên)* | **Giả định 2: Tự động gom deadline sẽ giúp giảm 80% tỷ lệ trễ:**<br>Chưa chắc trễ deadline là do "quên/không biết", có thể do "quá tải/lười/kĩ năng kém". Việc nhắc nhở không đảm bảo thành viên sẽ làm bài đúng giờ.<br>🔗 *Nguồn kiểm tra/tham khảo:* [ResearchGate - Student Procrastination & Academic Deadlines Study](https://www.researchgate.net/publication/320145892_Academic_Procrastination_and_Deadline_Impact) |
| **3. Giải pháp hiện tại (Trello, Notion, Excel) bị bỏ hoang:**<br>80% nhóm sinh viên tạo bảng Notion/Trello ở tuần đầu tiên nhưng bỏ không cập nhật sau tuần 2 vì ma sát nhập liệu thủ công quá lớn.<br>*(Nguồn: Quan sát trực tiếp & Phỏng vấn nhóm)* | **Giả định 3: Nhắc nhở trực tiếp trong Chat (Zalo/Slack) hiệu quả hơn App riêng:**<br>Giả định rằng nếu nhắc ngay tại nơi sinh viên nhắn tin hàng ngày sẽ giảm ma sát hơn bắt họ mở 1 Web/App mới.<br>🔗 *Nguồn kiểm tra/tham khảo:* [Slack ChatOps Best Practices Guide](https://slack.com/blog/productivity/what-is-chatops-beginners-guide) |
| **4. Các công cụ lớn (Asana, Jira) quá nặng cho nhóm nhỏ:**<br>Sinh viên không muốn học cách dùng các hệ thống Enterprise phức tạp chỉ để làm 1 bài thuyết trình/project 4 tuần.<br>*(Nguồn: Market research Asana, Jira, ClickUp)* | **Giả định 4: AI có thể bóc tách chính xác Task & Deadline từ tin nhắn chat tiếng Việt:**<br>Cần kiểm chứng xem LLM (GPT-4o/Gemini) có hiểu đúng các tin nhắn viết tắt, teen code, câu lệnh mập mờ trong chat Zalo (vd: *"thứ 7 nộp nhé", "mai t gửi slide"*) hay không.<br>🔗 *Nguồn kiểm tra/tham khảo:* [Vietnamese NLP Entity Extraction Benchmark - PhoNLP](https://github.com/vinai-io/PhoNLP) |
