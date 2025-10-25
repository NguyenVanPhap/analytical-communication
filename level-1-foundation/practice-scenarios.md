# Practice Scenarios - Cấp Độ 1: Nền Tảng

## 🎯 Bài Tập 1: Giải Thích Thuật Ngữ Kỹ Thuật (Tuần 1-2)

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

### Scenario 1.3: Collections Framework
**Tình huống**: Junior developer hỏi "Tại sao cần Collections thay vì Array?"

**Cách tiếp cận**:
```
1. Analogy: Như việc chọn container phù hợp
   - Array: Như hộp cố định, biết trước size
   - List: Như túi có thể mở rộng
   - Map: Như từ điển, tìm theo key
   - Set: Như danh sách không trùng lặp

2. Ví dụ thực tế:
   - Array: Danh sách điểm cố định (5 môn)
   - List: Danh sách sản phẩm (có thể thêm/bớt)
   - Map: Cache user info (key = userID)
   - Set: Danh sách tags (không trùng)

3. Lợi ích:
   - Linh hoạt hơn Array
   - Có sẵn methods hữu ích
   - Performance tốt hơn cho các operations phức tạp
```

## 🎯 Bài Tập 2: Bug Analysis Presentation (Tuần 3-4)

### Scenario 2.1: Performance Issue
**Tình huống**: App chậm, cần báo cáo root cause và solution

**Template Structure**:
```
EXECUTIVE SUMMARY (30 giây)
"App response time tăng từ 2s lên 15s do database query không optimize. 
Đã identify root cause và có solution sẽ implement trong 2 ngày."

PROBLEM DESCRIPTION
- What: App response time degradation
- When: Started 3 days ago
- Who: Affecting 80% of users
- Where: Main dashboard và search functionality

ROOT CAUSE ANALYSIS
- Primary: N+1 query problem trong user dashboard
- Secondary: Missing database indexes
- Contributing factors: Increased user load

IMPACT ASSESSMENT
- User experience: Poor (15s load time)
- Business: Potential revenue loss
- Technical: Server resource consumption

PROPOSED SOLUTIONS
1. Immediate (1 day): Add database indexes
2. Short-term (2 days): Fix N+1 queries
3. Long-term (1 week): Implement caching

RECOMMENDATION
Prioritize immediate solution để restore service, 
followed by comprehensive fix.

NEXT STEPS
- Deploy indexes tonight
- Code review và testing tomorrow
- Monitor performance metrics
```

### Scenario 2.2: Memory Leak
**Tình huống**: Server memory tăng liên tục, cần explain cho team

**Cấu trúc báo cáo**:
```
PROBLEM SUMMARY
- Issue: Memory usage tăng từ 2GB lên 8GB trong 24h
- Impact: Server restart required mỗi ngày
- Users affected: 100% of users

TECHNICAL ANALYSIS
- Root cause: Objects không được garbage collected
- Location: Image processing service
- Pattern: Memory tăng 100MB/hour

SOLUTION APPROACH
1. Immediate: Restart service
2. Fix: Add proper object cleanup
3. Prevention: Add memory monitoring

BUSINESS IMPACT
- Downtime: 30 minutes/day
- Cost: $200/day in server resources
- Risk: Potential data loss
```

## 🎯 Bài Tập 3: Code Review Presentation (Tuần 5-6)

### Scenario 3.1: Refactoring Changes
**Tình huống**: Trình bày refactoring changes trong sprint review

**Structure**:
```
BUSINESS CONTEXT
"Refactoring này sẽ improve maintainability và reduce future bugs, 
saving team 20% development time cho similar features."

TECHNICAL CHANGES
- Extracted common validation logic
- Improved error handling consistency
- Added comprehensive unit tests

BENEFITS
- Code reusability: 40% reduction in duplicate code
- Bug reduction: Expected 30% fewer validation errors
- Developer productivity: Faster feature development

RISKS & MITIGATION
- Risk: Potential regression bugs
- Mitigation: Comprehensive test coverage (95%)

DEMONSTRATION
- Show before/after code comparison
- Highlight key improvements
- Explain testing approach
```

### Scenario 3.2: New Feature Implementation
**Tình huống**: Demo new feature cho stakeholders

**Presentation Structure**:
```
FEATURE OVERVIEW
- Name: User notification system
- Purpose: Improve user engagement
- Timeline: 2 weeks development

TECHNICAL IMPLEMENTATION
- Backend: REST API với Spring Boot
- Frontend: React components
- Database: New notification table
- Integration: Email service

USER EXPERIENCE
- Real-time notifications
- Customizable preferences
- Mobile responsive

BUSINESS VALUE
- Increased user engagement: 25%
- Reduced support tickets: 15%
- Better user retention: 10%

NEXT STEPS
- User testing phase
- Performance optimization
- Production deployment
```

## 📝 Practice Templates

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

*Các scenarios này được thiết kế đặc biệt cho Cấp Độ 1, tập trung vào việc xây dựng nền tảng vững chắc cho Analytical Communication.*
