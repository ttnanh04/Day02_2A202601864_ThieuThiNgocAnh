case: Tổng hợp các nội dung hoạt động sau 1 cuộc họp
nhân vật: 1 nhóm sinh viên gồm 5 người. Mỗi chủ nhật sẽ họp khoảng 60 phút để cập nhật tiến độ. Lan là trưởng nhóm sẽ ghi lại thông tin từ ghi chú, tin nhắn mess và nội dung từng người báo cáo việc đã làm được trong tuần

## Scan rộng

Lan scan 10 problems, vượt mức tối thiểu 5.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi chủ nhật sẽ có 1 cuộc họp nhóm | các thành viên trong nhóm | Mất khoảng 60 phút/tuần |
| 2 | Lặp lại | Nhắc từng thành viên cập nhật tiến độ | nhóm trưởng | Lặp lại 2-3 lần/tuần |
| 3 | Tốn thời gian | Tìm tài liệu cho nội dung từng phần, từng chương | sinh viên | 20-30p/lần |
| 4 | Lặp lại | Chuyển nội dung báo cáo thành slide | người làm slide | 30 phút/buổi |
| 5 | AI có thể tốt hơn | Đọc bài báo dài để xác định nội dung liên quan | sinh viên nghiên cứu | 30-40p/bài |
| 6 | AI có thể tốt hơn | Kiểm tra nội dung các thành viên viết có trùng lặp không | nhóm trưởng | chỉ phát hiện khi ghép báo cáo |
| 7 | Pain từ người khác | Thành viên không nhớ rõ mình đã nhận việc gì | cả nhóm | thường hỏi lại sau cuộc họp |
| 8 | Pain từ người khác | Giảng viên khó theo dõi tiến độ thực tế của nhóm | giảng viên hướng dẫn |
| 9 | Lặp lại | Chuẩn hóa format tài liệu từ nhiều thành viên | người tổng hợp | 40-45p/lần |
| 10 | Dễ xảy ra lỗi | Deadline được ghi ở nhiều nơi khác nhau | cả nhóm | các nền tảng ghi thông tin nội dung không đồng bộ |
Phần scan này mạnh:
- Không bắt đầu bằng ý tưởng “xây chatbot”.
- Quan sát nhiều vấn đề trước khi chọn.
- Mỗi vấn đề đều có actor cụ thể.
- Có dấu hiệu thực tế và tần suất xảy ra.
- Có cả vấn đề cá nhân và vấn đề của người xung quanh.
## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp action items sau họp | Lặp lại hằng tuần, workflow rõ, dễ đo thời gian và lỗi | AI có xác định đúng người và deadline không |
| 2 | Chuyển báo cáo thành slide | Tốn nhiều thời gian, đầu ra rõ | Chất lượng thiết kế khó đánh giá tự động |
| 3 | Tìm và đọc tài liệu tham khảo | Pain phổ biến, AI có thể hỗ trợ mạnh | Scope rộng, rủi ro nguồn không đáng tin |
## Problem Card #1 — Tổng hợp action items sau họp

**Problem 1 câu:**  
Sau mỗi buổi họp, nhóm trưởng mất khoảng 60 phút tổng hợp quyết định, nhiệm vụ, người phụ trách và deadline từ nhiều nguồn; một số nhiệm vụ vẫn bị ghi thiếu hoặc không rõ trách nhiệm.

**Actor:**  
Lan - nhóm trưởng của 1 nhóm gồm 5 sinh viên

**Thời điểm / bối cảnh:**  
Sau buổi họp nhóm vào mỗi chủ nhật hàng tuần, cần chuyển thông tin họp thành danh sách action items rõ ràng cho cả nhóm.

**Current workflow:**

```text
1. Nghe lại nội dung buổi họp nhóm
2. xem lại ghi chú, nội dung, note công việc trong tuần đã làm của từng người
3. Tóm tắt quyết định và nhiệm vụ
4. Ghi lại người phụ trách, dealine và trạng thái
5. Chia sẻ cho cả nhóm
```

**Bottleneck:**  
Bước tổng hợp và chuyển đổi thông tin từ nhiều nguồn thành một danh sách action items rõ ràng là bottleneck chính. Vì dễ bị bỏ sót thông tin, trùng lặp hoặc ghi thiếu trách nhiệm.

**Impact:**  
Mỗi tuần nhóm trưởng mất khoảng 60 phút cho việc này. Nếu thông tin không rõ, các thành viên có thể hiểu sai nhiệm vụ, quên deadline hoặc không biết mình phải làm gì. Điều này làm giảm hiệu quả làm việc nhóm và làm tăng số lần hỏi lại sau họp.

**Success metric:**  
Giảm thời gian tổng hợp từ khoảng 60 phút xuống còn dưới 20 phút, đồng thời giảm số action item bị thiếu thông tin hoặc không rõ người phụ trách.

**Non-AI alternative:**  
Có thể dùng template ghi chú họp, checklist action items hoặc một bảng tracking chung. Tuy nhiên, cách này vẫn cần người thủ công nhập và sắp xếp thông tin, nên chưa giải quyết hết vấn đề về thời gian và độ chính xác.

**AI hypothesis:**  
AI có thể hỗ trợ tóm tắt nội dung họp, trích xuất action items, gán người phụ trách và đề xuất deadline dựa trên nội dung ghi chú. Nhóm trưởng vẫn giữ vai trò kiểm tra và chỉnh sửa trước khi gửi cho cả nhóm.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 60 phút

[1 Nghe/đọc nội dung họp: 15']
→ [2 Tổng hợp thông tin từ nhiều nguồn: 20']
→ [3 Ghi action items: 10']
→ [4 Review lại và chỉnh sửa: 15']
```

### Draft future workflow

```text
FUTURE STATE — 20 phút

[1 AI tóm tắt nội dung họp: 5']
→ [2 AI trích xuất action items: 3']
→ [3 AI đề xuất người phụ trách/deadline: 2']
→ [4 Lan review và chỉnh sửa: 10']

```

## Problem Cards #2: Chuyển báo cáo thành slide

**Problem 1 câu:**  
Sau mỗi buổi họp hoặc mỗi lần hoàn thành báo cáo, người làm slide mất khoảng 30 phút để chuyển nội dung thô thành slide có cấu trúc rõ ràng và dễ trình bày.

**Actor:**  
Một thành viên trong nhóm phụ trách làm slide.

**Thời điểm / bối cảnh:**  
Sau khi nhóm đã có nội dung báo cáo hoặc tổng hợp tiến độ, trước khi chia sẻ cho cả nhóm hoặc giảng viên.

**Current workflow:**

```text
1. Nhận nội dung báo cáo từ nhóm
2. Tóm tắt thông tin chính
3. Chuyển thành các slide
4. Chỉnh sửa bố cục, tiêu đề và màu sắc
5. Gửi file slide
```

**Bottleneck:**  
Bước chuyển nội dung thô thành slide dễ đọc và đẹp mắt là bottleneck chính. Đây là bước tốn thời gian vì cần vừa tóm tắt vừa sắp xếp bố cục.

**Impact:**  
Mỗi lần làm slide mất khoảng 30 phút, làm chậm việc chuẩn bị cho buổi trao đổi hoặc nộp bài. Nếu nội dung cập nhật liên tục, công việc này phải làm nhiều lần.

**Success metric:**  
Giảm thời gian làm slide từ 30 phút xuống còn dưới 10 phút, đồng thời giữ được tính rõ ràng và dễ hiểu của nội dung

**Non-AI alternative:**  
Có thể dùng template slide sẵn hoặc mẫu bố cục chuẩn. Tuy nhiên, vẫn cần người thủ công chỉnh sửa và sắp xếp từng nội dung.

**AI hypothesis:**  
AI có thể hỗ trợ tóm tắt nội dung, đề xuất cấu trúc slide và tạo bản nháp đầu tiên, rồi người làm slide chỉnh sửa lại.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 30 phút

[1 Nhận nội dung: 5']
→ [2 Tóm tắt ý chính: 10']
→ [3 Chuyển thành slide: 10']
→ [4 Chỉnh sửa bố cục: 5']
```

### Draft future workflow

```text
FUTURE STATE — 10 phút

[1 AI tóm tắt nội dung: 2']
→ [2 AI đề xuất bố cục slide: 2']
→ [3 Người làm slide chỉnh sửa: 6']

```
## Problem Cards #2: Tìm và đọc tài liệu tham khảo

**Problem 1 câu:**  
Khi cần tìm tài liệu tham khảo cho một phần công việc, sinh viên mất nhiều thời gian để tìm đúng nguồn, đọc qua nhiều bài dài và xác định nội dung có liên quan hay không.

**Actor:**  
Sinh viên trong nhóm đang tìm tài liệu để viết hoặc trình bày nội dung của phần mình phụ trách.

**Thời điểm / bối cảnh:**  
Khi chuẩn bị nội dung cho report, bài thuyết trình hoặc phần trình bày nhóm.

**Current workflow:**

```text
1. Tìm tài liệu trên internet hoặc thư viện
2. Đọc nhiều bài báo hoặc tài liệu dài
3. Chọn phần có liên quan
4. Ghi chú lại nội dung chính
5. Dùng trong báo cáo hoặc slide
```

**Bottleneck:**  
Bước tìm và đọc tài liệu là bottleneck chính vì phải lọc ra nguồn phù hợp và xác định phần nào thực sự liên quan.

**Impact:**  
Mỗi lần tìm tài liệu có thể mất 30–40 phút. Nếu tìm sai nguồn hoặc đọc quá nhiều nội dung không liên quan, thời gian bị lãng phí và tiến độ nhóm chậm lại.

**Success metric:**  
Giảm thời gian tìm và đọc tài liệu từ 30–40 phút xuống còn dưới 10 phút, đồng thời tăng độ phù hợp của tài liệu được chọn.
**Non-AI alternative:**  
Có thể dùng từ khóa tìm kiếm tốt hơn, dùng công cụ lọc tài liệu hoặc hỏi bạn cùng nhóm. Tuy nhiên, cách này vẫn cần nhiều thao tác thủ công.

**AI hypothesis:**  
AI có thể hỗ trợ tìm tài liệu phù hợp, tóm tắt nội dung chính và chỉ ra phần nào liên quan trực tiếp đến chủ đề.

**Quick gut:**  
Agent / Workflow.

### Draft current workflow

```text
CURRENT STATE — 30-40 phút

[1 Tìm tài liệu: 10']
→ [2 Đọc nội dung dài: 20']
→ [3 Chọn phần liên quan: 10']
```

### Draft future workflow

```text
FUTURE STATE — 10 phút

[1 AI tìm và gợi ý tài liệu: 3']
→ [2 AI tóm tắt nội dung chính: 4']
→ [3 Sinh viên chọn và dùng: 3']

```
---
