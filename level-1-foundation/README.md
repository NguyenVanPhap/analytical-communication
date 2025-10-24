# Cấp Độ 1: Nền Tảng (4-6 tuần)

## 🎯 Mục Tiêu Cấp Độ 1
Phát triển nền tảng vững chắc cho Analytical Communication, tập trung vào:
- Hiểu được cấu trúc cơ bản của Analytical Communication
- Luyện tập diễn giải các khái niệm kỹ thuật đơn giản
- Phát triển tư duy logic và có cấu trúc

## 📚 Kỹ Năng Cần Rèn Luyện

### 1. Cấu Trúc Thông Tin Theo Logic
- **Nguyên tắc MECE** (Mutually Exclusive, Collectively Exhaustive)
- **Cấu trúc Pyramid Principle**
- **Phương pháp 5W1H** (What, Why, When, Where, Who, How)

### 2. Diễn Giải Khái Niệm Kỹ Thuật
- Từ thuật ngữ kỹ thuật → ngôn ngữ thường
- Sử dụng analogies và metaphors
- Ví dụ cụ thể và thực tế

### 3. Kỹ Năng Trình Bày Cơ Bản
- Cấu trúc: Mở đầu - Thân bài - Kết luận
- Sử dụng visual aids hiệu quả
- Kiểm soát tốc độ và tone giọng

## 🎯 Bài Tập Thực Hành

### Bài Tập 1: Giải Thích Thuật Ngữ Kỹ Thuật (Tuần 1-2)
**Mục tiêu**: Diễn giải các khái niệm Java cơ bản cho người không chuyên

**Tình huống**: Bạn cần giải thích cho BA về các khái niệm sau:
- Object-Oriented Programming
- Inheritance và Polymorphism
- Exception Handling
- Collections Framework

**Yêu cầu**:
- Thời gian: 3-5 phút cho mỗi khái niệm
- Đối tượng: Business Analyst không có background kỹ thuật
- Phương pháp: Sử dụng analogies từ cuộc sống hàng ngày

**Cấu trúc đề xuất**:
```
1. Định nghĩa ngắn gọn (1 câu)
2. Ví dụ thực tế từ cuộc sống
3. Ví dụ cụ thể trong code
4. Lợi ích và ứng dụng
5. Tóm tắt và kết luận
```

### Bài Tập 2: Báo Cáo Bug Analysis (Tuần 3-4)
**Mục tiêu**: Trình bày phân tích lỗi một cách có cấu trúc

**Tình huống**: Phát hiện bug trong hệ thống, cần báo cáo cho Technical Lead

**Yêu cầu**:
- Thời gian: 10-15 phút
- Đối tượng: Technical Lead
- Bao gồm: Root cause analysis, impact assessment, solution proposal

**Cấu trúc đề xuất**:
```
1. Executive Summary (30 giây)
2. Problem Description
3. Root Cause Analysis
4. Impact Assessment
5. Proposed Solutions
6. Recommendation
7. Next Steps
```

### Bài Tập 3: Code Review Presentation (Tuần 5-6)
**Mục tiêu**: Giải thích code changes và rationale

**Tình huống**: Trình bày code changes trong sprint review

**Yêu cầu**:
- Thời gian: 5-7 phút
- Đối tượng: Team members (mix technical levels)
- Focus: Business value và technical improvements

## 📊 Đánh Giá Cấp Độ 1

### Rubric Đánh Giá (1-5 scale)

#### Cấu Trúc và Logic (25%)
- [ ] Thông tin được trình bày theo thứ tự hợp lý
- [ ] Có mở đầu và kết luận rõ ràng
- [ ] Sử dụng transitions cơ bản
- [ ] Evidence hỗ trợ cho main points

#### Clarity và Precision (25%)
- [ ] Ngôn ngữ rõ ràng, không jargon không cần thiết
- [ ] Examples cụ thể và relevant
- [ ] Tránh ambiguity cơ bản
- [ ] Appropriate level of detail cho audience

#### Audience Adaptation (25%)
- [ ] Tailor content cho audience cơ bản
- [ ] Address audience concerns cơ bản
- [ ] Use appropriate tone và style
- [ ] Manage expectations cơ bản

#### Engagement và Impact (25%)
- [ ] Maintain audience attention cơ bản
- [ ] Handle questions adequately
- [ ] Achieve intended outcomes cơ bản
- [ ] Professional presentation skills cơ bản

### Weekly Self-Assessment Form
```
TUẦN: _____
NGÀY: _____

BÀI TẬP THỰC HÀNH:
□ Giải thích thuật ngữ kỹ thuật
□ Bug analysis presentation
□ Code review presentation

ĐÁNH GIÁ PERFORMANCE (1-5):
Cấu trúc và Logic: ___/5
Clarity và Precision: ___/5
Audience Adaptation: ___/5
Engagement và Impact: ___/5

ĐIỂM MẠNH:
- ________________________________
- ________________________________
- ________________________________

ĐIỂM CẦN CẢI THIỆN:
- ________________________________
- ________________________________
- ________________________________

FEEDBACK TỪ COLLEAGUES:
- ________________________________
- ________________________________
- ________________________________

KẾ HOẠCH TUẦN SAU:
- ________________________________
- ________________________________
- ________________________________
```

## 🎯 Tình Huống Thực Hành Chi Tiết

### Scenario 1.1: Object-Oriented Programming
**Tình huống**: BA hỏi "OOP là gì và tại sao chúng ta cần nó?"

**Cách tiếp cận**:
```
1. Định nghĩa ngắn gọn: "OOP là cách tổ chức code giống như cách chúng ta tổ chức cuộc sống"

2. Analogy từ cuộc sống:
   - Như một công ty có các phòng ban (classes)
   - Mỗi nhân viên (object) thuộc về một phòng ban
   - Mỗi phòng ban có quy tắc riêng (methods)

3. Ví dụ cụ thể:
   - Class: Car
   - Objects: Toyota Camry, Honda Civic
   - Methods: start(), stop(), accelerate()

4. Lợi ích:
   - Code dễ maintain và reuse
   - Giảm bugs và tăng productivity
   - Team có thể work parallel trên different parts
```

**Practice Script**:
> "Hãy tưởng tượng bạn đang xây dựng một hệ thống quản lý thư viện. Thay vì viết code cho từng cuốn sách riêng lẻ, chúng ta tạo một 'template' gọi là 'Book'. Mỗi cuốn sách cụ thể sẽ có cùng cấu trúc (title, author, ISBN) nhưng với giá trị khác nhau. Điều này giúp chúng ta dễ dàng thêm sách mới, tìm kiếm, và quản lý."

### Scenario 1.2: Exception Handling
**Tình huống**: Manager hỏi "Tại sao có lỗi trong production mà không crash app?"

**Cách tiếp cận**:
```
1. Định nghĩa: "Exception handling là cách app 'bắt' và xử lý lỗi một cách graceful"

2. Analogy: Như một người lái xe có kỹ năng xử lý tình huống bất ngờ
   - Không phanh gấp khi gặp đá nhỏ
   - Biết cách điều chỉnh khi trời mưa
   - Có plan B khi xe hỏng

3. Ví dụ thực tế:
   - User nhập sai format email
   - Database connection timeout
   - File không tồn tại

4. Business value:
   - User experience tốt hơn
   - System stability cao hơn
   - Easier debugging và monitoring
```

## 🚀 Tiến Độ và Chuyển Cấp

### Điều Kiện Chuyển Lên Cấp Độ 2
- Hoàn thành tất cả 3 bài tập cơ bản
- Đạt điểm trung bình 3.5/5 trên tất cả dimensions
- Nhận feedback tích cực từ ít nhất 3 colleagues
- Pass practical assessment với Technical Lead

### Kế Hoạch Tuần
- **Tuần 1-2**: Focus vào Bài tập 1 (Giải thích thuật ngữ)
- **Tuần 3-4**: Focus vào Bài tập 2 (Bug analysis)
- **Tuần 5-6**: Focus vào Bài tập 3 (Code review) + Review tổng thể

## 📝 Templates và Checklists

### Presentation Template Cấp Độ 1
```
SLIDE 1: TITLE SLIDE
- Presentation title
- Your name và title
- Date

SLIDE 2: AGENDA
- Overview of topics
- Time allocation
- Q&A information

SLIDE 3: MAIN CONTENT
- Problem/Challenge
- Solution/Approach
- Benefits/Outcomes

FINAL SLIDE: CONCLUSION
- Key takeaways
- Next steps
- Q&A invitation
```

### Communication Checklist Cấp Độ 1
```
BEFORE PRESENTATION:
□ Audience analysis completed
□ Key messages defined
□ Supporting data prepared
□ Visual aids created
□ Rehearsal completed

DURING PRESENTATION:
□ Clear structure followed
□ Appropriate pace maintained
□ Audience engagement checked
□ Questions handled effectively
□ Time managed properly

AFTER PRESENTATION:
□ Feedback collected
□ Follow-up actions defined
□ Lessons learned documented
□ Improvement areas identified
```

---

*Cấp độ 1 tập trung vào việc xây dựng nền tảng vững chắc. Hãy practice đều đặn và collect feedback để continuous improvement!*
