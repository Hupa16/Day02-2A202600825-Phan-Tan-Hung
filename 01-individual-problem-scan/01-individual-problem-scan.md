
---

# 01 — Individual Problem Scan

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

## Problem Card #1 — Weekly Report
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
