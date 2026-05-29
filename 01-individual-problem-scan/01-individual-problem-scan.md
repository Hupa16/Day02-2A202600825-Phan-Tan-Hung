
---

# Individual Problem Scan

## Scan rộng

| # | Lăng kính          | Problem quan sát được                                                                                           | Ai đang đau?                             | Dấu hiệu thật                                                                        |
| - | ------------------ | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------------ |
| 1 | Tốn thời gian      | Phải cài nhiều thư viện và setup môi trường khác nhau cho từng project/lab trước khi bắt đầu code               | Sinh viên IT, người mới học AI/lập trình | Mỗi lần setup project mới mất 1-3 tiếng để fix lỗi thư viện, version hoặc môi trường |
| 2 | Pain từ người khác | Thông tin học tập bị phân tán trên nhiều nền tảng như Zalo, Gmail, Discord nên dễ bỏ sót deadline hoặc tài liệu | Sinh viên học nhiều môn/project          | Phải check nhiều app mỗi ngày, từng bị miss deadline hoặc không thấy file quan trọng |
| 3 | Tốn thời gian      | Có quá nhiều tài liệu tham khảo nhưng không biết nên đọc tài liệu nào trước                                     | Người mới học AI/coding                  | Lưu rất nhiều link/video nhưng không đọc hết, học lan man và mất định hướng          |
| 4 | AI có thể tốt hơn  | Chưa biết sử dụng hiệu quả các công cụ AI hỗ trợ như Cursor, Codex, Claude Code                                 | Sinh viên mới tiếp cận AI tools          | Chủ yếu vẫn code thủ công, chưa biết cách để AI hỗ trợ debug/code nhanh hơn          |
| 5 | Lặp lại            | Mỗi lần gặp lỗi code phải tự search Google hoặc StackOverflow rất lâu                                           | Sinh viên lập trình                      | Một lỗi nhỏ có thể mất vài tiếng để sửa vì không biết nguyên nhân                    |
| 6 | Pain từ người khác | Làm việc nhóm khó đồng bộ source code và môi trường giữa các thành viên                                         | Nhóm làm project                         | Máy của mình chạy được nhưng máy bạn khác lại lỗi dependency hoặc version            |
| 7 | AI có thể tốt hơn  | Không biết roadmap học AI/lập trình theo thứ tự phù hợp                                                         | Người mới học công nghệ                  | Học nhiều khóa/course nhưng vẫn không biết nên tiếp tục học gì                       |
| 8 | Lặp lại            | Có quá nhiều notification từ lớp học, CLB, project khiến khó tập trung                                          | Sinh viên                                | Mỗi ngày có hàng trăm tin nhắn từ Zalo, Discord, Messenger                           |


## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Phải cài nhiều thư viện và setup môi trường khác nhau cho từng project/lab trước khi bắt đầu code | Mất nhiều thời gian fix lỗi môi trường hơn cả thời gian code, đặc biệt với người mới | Chưa xác định được giải pháp tốt nhất là tool tự động setup hay guideline chuẩn |
| 2 | Có quá nhiều tài liệu tham khảo nhưng không biết nên đọc tài liệu nào trước | vì tài liệu quá nhiều và phân tán, người học dễ bị overload thông tin và mất định hướng | Chưa rõ có thể đo hiệu quả cải thiện bằng metric nào ngoài thời gian tiết kiệm |
| 3 | Không biết roadmap học AI/lập trình theo thứ tự phù hợp | Người mới thường học lan man, không biết nên bắt đầu từ đâu hoặc build project gì tiếp theo | Khó cá nhân hóa roadmap vì mỗi người có nền tảng và mục tiêu khác nhau |


# Problem Card 1

```text
Problem 1 câu:
Sinh viên AI/lập trình mất rất nhiều thời gian để cài thư viện và setup môi trường trước khi có thể bắt đầu code.

Actor:
Sinh viên IT, người mới học AI/lập trình.

Thời điểm / bối cảnh:
Khi bắt đầu một lab, project mới hoặc clone source code từ GitHub.

Current workflow 3-7 bước:
1. Clone/download source code
2. Đọc requirement hoặc tutorial
3. Cài Python, CUDA, thư viện cần thiết
4. Fix lỗi version/dependency
5. Test chạy project
6. Tiếp tục fix lỗi môi trường nếu chạy fail

Bottleneck:
Fix lỗi môi trường và dependency do khác version hoặc thiếu thư viện.

Impact:
Mất nhiều thời gian trước khi bắt đầu học/code thật sự, dễ gây nản cho người mới.

Success metric:
Giảm thời gian setup project từ 2-3 tiếng xuống dưới 30 phút.

Non-AI alternative:
Viết guideline setup chuẩn hoặc dùng Docker/requirements.txt.

AI hypothesis:
AI có thể tự detect lỗi môi trường và gợi ý cách fix theo project cụ thể.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

# Problem Card 2

```text
Problem 1 câu:
Người mới học AI/coding bị overload vì có quá nhiều tài liệu tham khảo nhưng không biết nên đọc cái nào trước.

Actor:
Sinh viên học AI, người mới học lập trình.

Thời điểm / bối cảnh:
Khi bắt đầu học một công nghệ mới hoặc làm đồ án/research.

Current workflow 3-7 bước:
1. Search tài liệu/video/course trên Google hoặc YouTube
2. Lưu nhiều link khác nhau
3. Đọc thử từng nguồn
4. Không biết nguồn nào phù hợp trình độ
5. Chuyển qua lại nhiều tài liệu
6. Học lan man hoặc bỏ cuộc giữa chừng

Bottleneck:
Không biết tài liệu nào phù hợp và đáng ưu tiên đọc trước.

Impact:
Mất định hướng học tập, tốn nhiều thời gian nhưng hiệu quả thấp.

Success metric:
Giảm số tài liệu cần đọc thử trước khi bắt đầu học chính từ 10 nguồn xuống còn 2-3 nguồn phù hợp.

Non-AI alternative:
Giảng viên hoặc senior đưa curated learning list.

AI hypothesis:
AI có thể phân loại tài liệu theo trình độ, mục tiêu học và gợi ý roadmap đọc phù hợp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

# Problem Card 3

```text
Problem 1 câu:
Người mới học AI/lập trình không biết roadmap học phù hợp nên học lan man và thiếu định hướng.

Actor:
Sinh viên mới học AI/lập trình.

Thời điểm / bối cảnh:
Khi mới bắt đầu học AI hoặc muốn chuyển sang một lĩnh vực mới.

Current workflow 3-7 bước:
1. Search roadmap trên mạng
2. Xem nhiều video/course khác nhau
3. Học theo cảm hứng
4. Không biết phần nào quan trọng
5. Không biết nên build project gì
6. Mất động lực vì học không thấy tiến bộ rõ ràng

Bottleneck:
Không có lộ trình học cá nhân hóa theo trình độ và mục tiêu.

Impact:
Học nhiều nhưng thiếu nền tảng, dễ bỏ cuộc hoặc mất thời gian học sai thứ tự.

Success metric:
Người học có thể xác định roadmap và project phù hợp trong dưới 1 ngày thay vì mất nhiều tuần tìm hiểu.

Non-AI alternative:
Dùng roadmap cố định từ trường học hoặc mentor.

AI hypothesis:
AI có thể tạo roadmap học cá nhân hóa dựa trên trình độ, mục tiêu và thời gian học của người dùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```
# Draft Workflow — Problem Card 1

## Setup thư viện và môi trường quá mất thời gian

```text
CURRENT STATE — 2-3 tiếng

[Clone project từ GitHub: 5']
→ [Đọc README/tutorial: 15']
→ [Cài Python/CUDA: 20']
→ [Cài thư viện bằng pip/conda: 20']
→ [Lỗi version/dependency: 40']  <-- bottleneck
→ [Search Google/StackOverflow: 45']
→ [Fix thử nhiều cách: 30']
→ [Chạy thử project: 10']

FUTURE STATE — 20-30 phút

[Clone project: 5']
→ [AI scan requirements + môi trường: 2']
→ [Auto generate setup script: 3']
→ [AI detect lỗi dependency: 5']
→ [User confirm & run fix: 10']  <-- human boundary
→ [Project chạy thành công: 5']

Fallback:
Nếu AI fix sai → user dùng guideline setup chuẩn hoặc Docker image có sẵn.
```

---

# Draft Workflow — Problem Card 2

## Quá nhiều tài liệu tham khảo, không biết đọc gì trước

```text
CURRENT STATE — 5-7 tiếng

[Search tài liệu/course: 30']
→ [Mở nhiều tab/video khác nhau: 20']
→ [Đọc thử từng tài liệu: 2-3 tiếng]
→ [Không hiểu mức độ phù hợp: 1 tiếng]  <-- bottleneck
→ [Tiếp tục search thêm nguồn: 1 tiếng]
→ [Bị overload thông tin: 30']
→ [Học lan man hoặc bỏ cuộc]

FUTURE STATE — 1-2 tiếng

[Nhập mục tiêu học: 5']
→ [AI phân tích trình độ user: 5']
→ [AI lọc & xếp hạng tài liệu: 10']
→ [AI tạo learning path: 10']
→ [User review roadmap: 15']  <-- human boundary
→ [Bắt đầu học theo roadmap]

Fallback:
Nếu roadmap AI không phù hợp → user chọn curated list từ giảng viên/senior.
```

---

# Draft Workflow — Problem Card 3

## Không biết roadmap học AI/lập trình phù hợp

```text
CURRENT STATE — Nhiều tuần mất định hướng

[Search roadmap trên mạng: 1 tiếng]
→ [Xem nhiều video/course: 3-4 tiếng]
→ [Học theo cảm hứng: nhiều ngày]
→ [Không biết kiến thức nào quan trọng]  <-- bottleneck
→ [Không biết build project gì]
→ [Mất động lực vì không thấy tiến bộ]
→ [Đổi roadmap liên tục]

FUTURE STATE — 1 ngày để có roadmap rõ ràng

[User nhập mục tiêu + level hiện tại: 10']
→ [AI phân tích kỹ năng còn thiếu: 5']
→ [AI generate roadmap cá nhân hóa: 10']
→ [AI đề xuất project phù hợp: 5']
→ [User review & chỉnh roadmap: 20']  <-- human boundary
→ [Bắt đầu học theo milestone rõ ràng]

Fallback:
Nếu roadmap AI quá khó/dễ → user chỉnh lại mục tiêu hoặc dùng roadmap cố định từ mentor.
```
# Chọn card muốn pitch nhất 


---

# Problem Card 3 — Không biết roadmap học phù hợp

Card tôi muốn pitch:

```text id="c3p1"
Problem Card 3 — Không biết roadmap học AI/lập trình phù hợp
```

Vì sao:

```text id="c3p2"
Đây là vấn đề dài hạn mà rất nhiều học viên gặp phải khi mới học AI hoặc chuyển sang lĩnh vực mới.

Người học thường:
- học theo trend
- xem quá nhiều roadmap khác nhau
- không biết kiến thức nào quan trọng
- không biết khi nào nên build project

Workflow hiện tại thiếu định hướng rõ ràng nên dễ mất động lực hoặc học sai thứ tự.

Impact lớn vì ảnh hưởng trực tiếp đến tốc độ học và khả năng phát triển kỹ năng lâu dài.

Bài toán này cũng có tiềm năng dùng AI Agent vì cần:
- hiểu mục tiêu người dùng
- đánh giá kỹ năng hiện tại
- lập kế hoạch nhiều bước
- cập nhật roadmap theo tiến độ học
```

Câu hỏi tôi muốn nhóm challenge:

```text id="c3p3"
1. Roadmap có thể cá nhân hóa đủ tốt bằng AI không?

2. Làm sao AI đánh giá đúng trình độ thực tế của người học?

3. Có cần AI Agent tự theo dõi tiến độ học hay chỉ cần workflow recommendation là đủ?
```

# Nếu dùng AI ở phase này

## Không biết roadmap học phù hợp

```text id="fb3"
1. Actor chưa đủ cụ thể.
Người mới học AI/lập trình quá rộng:
- học để đi làm AI engineer?
- học để build AI app?
- sinh viên năm mấy?

2. Workflow có thật.
Pain này phổ biến với sinh viên IT.
Cần chỉ rõ:
- user đang lấy roadmap từ đâu?
- decision point nào khiến user bị stuck?
- bước nào tốn thời gian nhất?

3. Bottleneck tương đối rõ.
Thiếu roadmap cá nhân hóa là pain thật.
Nhưng chưa chắc bottleneck nằm ở roadmap.
Có thể vấn đề thật là:
- thiếu discipline
- thiếu mentor
- thiếu project thực tế
- không có feedback loop

4. Metric còn mơ hồ.

Cần metric dài hạn hơn:
- completion rate sau 1 tháng
- số project hoàn thành
- thời gian đạt milestone
- mức độ consistency khi học

5. Rule/process fix chưa được đánh giá đủ.
Roadmap template theo từng role:
- AI Engineer
- Data Scientist
- Backend AI Developer

có thể đã giải quyết được phần lớn problem mà chưa cần AI personalization.

6. Có dấu hiệu nhảy sang Agent hơi sớm.
Hiện tại chưa có bằng chứng cần autonomous agent.
Workflow recommendation + periodic adjustment có thể đủ.

Agent chỉ hợp lý nếu:
- system cần theo dõi tiến độ dài hạn
- tự cập nhật roadmap
- chủ động đề xuất next step
- integrate nhiều nguồn learning data
```

