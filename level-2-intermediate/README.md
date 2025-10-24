# Cấp Độ 2: Trung Cấp (6-8 tuần)

## 🎯 Mục Tiêu Cấp Độ 2
Phát triển kỹ năng Analytical Communication ở mức trung cấp, tập trung vào:
- Xử lý các tình huống phức tạp hơn
- Thuyết phục và đàm phán kỹ thuật
- Làm việc với stakeholders đa dạng

## 📚 Kỹ Năng Cần Rèn Luyện

### 1. Thuyết Phục Kỹ Thuật
- **Data-driven arguments**
- **Risk-benefit analysis**
- **Stakeholder mapping**

### 2. Xử Lý Conflicts và Objections
- **Active listening**
- **Reframing techniques**
- **Win-win solutions**

### 3. Cross-Functional Communication
- **Technical → Business translation**
- **Business → Technical translation**
- **Managing expectations**

## 🎯 Bài Tập Thực Hành

### Bài Tập 4: Technical Design Presentation (Tuần 7-9)
**Mục tiêu**: Trình bày technical design cho mixed audience

**Tình huống**: Propose new architecture cho microservices migration

**Yêu cầu**:
- Thời gian: 20-25 phút
- Đối tượng: CTO, Product Manager, Senior Developers, DevOps
- Bao gồm: Business case, technical approach, implementation plan

**Cấu trúc đề xuất**:
```
1. Business Context & Objectives
2. Current State Analysis
3. Proposed Solution Overview
4. Technical Deep Dive
5. Implementation Roadmap
6. Risk Assessment & Mitigation
7. Success Metrics
8. Q&A Preparation
```

### Bài Tập 5: Crisis Communication (Tuần 10-12)
**Mục tiêu**: Xử lý tình huống khủng hoảng kỹ thuật

**Tình huống**: Production system down, cần communicate với management và customers

**Yêu cầu**:
- Thời gian: 15-20 phút
- Đối tượng: CEO, Customer Success team, Development team
- Bao gồm: Incident summary, impact, resolution, prevention

**Cấu trúc đề xuất**:
```
1. Incident Summary (Executive Level)
2. Technical Details (For Technical Team)
3. Customer Impact Assessment
4. Resolution Timeline
5. Communication Plan
6. Post-Incident Actions
7. Prevention Measures
```

### Bài Tập 6: Technology Selection Debate (Tuần 13-14)
**Mục tiêu**: Thuyết phục team chọn technology stack

**Tình huống**: Debate giữa Spring Boot vs Node.js cho new project

**Yêu cầu**:
- Thời gian: 30 phút (15 phút mỗi side)
- Đối tượng: Development team, Architecture team
- Bao gồm: Pros/cons, performance comparison, team expertise

## 📊 Đánh Giá Cấp Độ 2

### Rubric Đánh Giá (1-5 scale)

#### Cấu Trúc và Logic (25%)
- [ ] Thông tin được organize theo logic rõ ràng
- [ ] Sử dụng effective transitions giữa các phần
- [ ] Có clear beginning, middle, end
- [ ] Supporting evidence phù hợp và relevant
- [ ] Sử dụng MECE principle (Mutually Exclusive, Collectively Exhaustive)

#### Clarity và Precision (25%)
- [ ] Ngôn ngữ precise và accessible
- [ ] Examples compelling và memorable
- [ ] Tránh ambiguity hoàn toàn
- [ ] Detail level perfectly matched với audience
- [ ] Sử dụng analogies và metaphors hiệu quả

#### Audience Adaptation (25%)
- [ ] Tailor content sophisticated cho audience
- [ ] Address audience concerns comprehensively
- [ ] Use nuanced tone và style
- [ ] Manage expectations effectively
- [ ] Adapt language và examples cho audience level

#### Engagement và Impact (25%)
- [ ] Maintain audience attention effectively
- [ ] Handle questions skillfully
- [ ] Achieve intended outcomes consistently
- [ ] Professional presentation skills tốt
- [ ] Use visual aids và storytelling hiệu quả

### Monthly Self-Assessment Form
```
TUẦN: _____
NGÀY: _____

BÀI TẬP THỰC HÀNH:
□ Technical design presentation
□ Crisis communication
□ Technology selection debate

ĐÁNH GIÁ PERFORMANCE (1-5):
Cấu trúc và Logic: ___/5
Clarity và Precision: ___/5
Audience Adaptation: ___/5
Engagement và Impact: ___/5

TÌNH HUỐNG THỰC TẾ:
- Scenario: ________________________________
- Audience: ________________________________
- Duration: ________________________________
- Outcome: ________________________________

CHALLENGES FACED:
- ________________________________
- ________________________________
- ________________________________

SOLUTIONS IMPLEMENTED:
- ________________________________
- ________________________________
- ________________________________

LESSONS LEARNED:
- ________________________________
- ________________________________
- ________________________________

GOALS FOR NEXT WEEK:
- ________________________________
- ________________________________
- ________________________________
```

## 🎯 Tình Huống Thực Hành Chi Tiết

### Scenario 4.1: Microservices Migration
**Tình huống**: Propose migration từ monolithic sang microservices architecture

**Detailed Structure**:

**1. Business Context & Objectives (3 phút)**
```
CURRENT CHALLENGES:
- Monolithic app khó scale
- Team conflicts khi deploy
- Technology lock-in
- Slow feature delivery

BUSINESS OBJECTIVES:
- Faster time-to-market (50% reduction)
- Independent team scaling
- Technology flexibility
- Improved system reliability

SUCCESS METRICS:
- Deployment frequency: Daily → Multiple daily
- Lead time: 2 weeks → 2 days
- MTTR: 4 hours → 30 minutes
- Team satisfaction: 6/10 → 9/10
```

**2. Current State Analysis (5 phút)**
```
ARCHITECTURE ASSESSMENT:
- Single codebase: 500K+ lines
- Shared database: 200+ tables
- Deployment: All-or-nothing
- Team structure: 15 developers, 1 codebase

PAIN POINTS:
- Merge conflicts: 2-3 per day
- Deployment risk: High (affects all features)
- Scaling bottleneck: Database
- Technology constraints: Java 8 only
```

**3. Proposed Solution Overview (7 phút)**
```
MICROSERVICES ARCHITECTURE:
- Domain-driven design approach
- Service boundaries based on business capabilities
- Independent databases per service
- API Gateway for external communication

SERVICE BREAKDOWN:
- User Service: Authentication, profiles
- Order Service: Order management, payments
- Product Service: Catalog, inventory
- Notification Service: Emails, SMS
- Analytics Service: Reporting, metrics

TECHNOLOGY STACK:
- Spring Boot 3.x
- PostgreSQL per service
- Redis for caching
- Docker + Kubernetes
- API Gateway (Kong)
```

### Scenario 5.1: Production System Down
**Tình huống**: E-commerce platform down trong Black Friday

**Communication Plan**:

**1. Immediate Response (First 15 minutes)**
```
INCIDENT COMMANDER: [Your name]
STATUS: CRITICAL - Production system down
IMPACT: 100% of customers affected
ETA: Investigating, will update in 15 minutes

IMMEDIATE ACTIONS:
- Incident response team activated
- Customer support notified
- Status page updated
- Social media monitoring started
```

**2. Executive Briefing (30 minutes)**
```
EXECUTIVE SUMMARY:
"E-commerce platform experiencing complete outage during peak traffic. 
Root cause identified as database connection pool exhaustion. 
Resolution ETA: 2 hours. Customer communication initiated."

TECHNICAL DETAILS:
- Issue: Database connection pool maxed out
- Trigger: Black Friday traffic spike (10x normal)
- Affected: All customer-facing functionality
- Data: No data loss, system intact

CUSTOMER IMPACT:
- Revenue impact: ~$50K/hour
- Customer satisfaction: High risk
- Brand reputation: Potential damage
- Competitive advantage: Lost opportunity

RESOLUTION PLAN:
- Immediate: Scale database connections
- Short-term: Implement connection pooling
- Long-term: Auto-scaling infrastructure

COMMUNICATION STRATEGY:
- Status page updates every 15 minutes
- Social media response team activated
- Customer support escalation
- Press statement prepared
```

### Scenario 6.1: Spring Boot vs Node.js
**Tình huống**: Choose technology stack cho new project

**Debate Structure**:

**Spring Boot Arguments (15 phút)**
```
BUSINESS CASE:
- Team expertise: 80% Java developers
- Learning curve: Minimal (team already skilled)
- Time to market: Faster development
- Maintenance: Lower long-term costs

TECHNICAL ADVANTAGES:
- Enterprise-grade features out of the box
- Strong ecosystem và community support
- Excellent ORM support (JPA/Hibernate)
- Built-in security features
- Comprehensive testing framework

PERFORMANCE CONSIDERATIONS:
- JVM optimization cho long-running applications
- Better memory management
- Mature garbage collection
- Enterprise monitoring tools integration

RISK ASSESSMENT:
- Low technical risk (proven technology)
- Low team risk (existing expertise)
- Low maintenance risk (familiar codebase)
- High scalability potential
```

**Decision Framework**:
```
EVALUATION CRITERIA:
1. Team expertise (40%)
2. Project requirements (30%)
3. Long-term maintainability (20%)
4. Performance requirements (10%)

SCORING:
Spring Boot: 8.5/10
- Team expertise: 10/10
- Project fit: 8/10
- Maintainability: 9/10
- Performance: 7/10

Node.js: 6.5/10
- Team expertise: 4/10
- Project fit: 9/10
- Maintainability: 6/10
- Performance: 8/10

RECOMMENDATION: Spring Boot
Rationale: Team expertise và project stability outweigh 
innovation benefits for this specific project.
```

## 🚀 Tiến Độ và Chuyển Cấp

### Điều Kiện Chuyển Lên Cấp Độ 3
- Hoàn thành tất cả 3 bài tập trung cấp
- Đạt điểm trung bình 4.0/5 trên tất cả dimensions
- Lead ít nhất 2 technical discussions
- Mentor ít nhất 1 junior colleague
- Pass advanced assessment với Technical Lead

### Kế Hoạch Tuần
- **Tuần 7-9**: Focus vào Bài tập 4 (Technical design)
- **Tuần 10-12**: Focus vào Bài tập 5 (Crisis communication)
- **Tuần 13-14**: Focus vào Bài tập 6 (Technology selection)

## 📝 Templates và Checklists

### Technical Design Template
```
SLIDE 1: PROJECT OVERVIEW
- Project name và objectives
- Timeline và scope
- Key stakeholders
- Success criteria

SLIDE 2: CURRENT STATE
- Existing system overview
- Pain points và challenges
- Performance metrics
- Technical debt

SLIDE 3: PROPOSED SOLUTION
- High-level architecture
- Key components
- Technology choices
- Integration points

SLIDE 4: TECHNICAL DETAILS
- Detailed architecture
- Data flow diagrams
- API specifications
- Security considerations

SLIDE 5: IMPLEMENTATION PLAN
- Phases và milestones
- Resource requirements
- Risk assessment
- Success metrics

SLIDE 6: NEXT STEPS
- Immediate actions
- Decision points
- Timeline
- Contact information
```

### Crisis Communication Checklist
```
IMMEDIATE RESPONSE (First 15 minutes):
□ Incident commander assigned
□ Status page updated
□ Customer support notified
□ Social media monitoring started
□ Technical team activated

EXECUTIVE COMMUNICATION (30 minutes):
□ Executive summary prepared
□ Technical details documented
□ Customer impact assessed
□ Resolution plan defined
□ Communication strategy activated

CUSTOMER COMMUNICATION:
□ Status page updates scheduled
□ Social media responses prepared
□ Customer support scripts ready
□ Press statement prepared
□ Follow-up communication planned

POST-INCIDENT:
□ Root cause analysis completed
□ Prevention measures implemented
□ Team retrospective conducted
□ Documentation updated
□ Lessons learned shared
```

---

*Cấp độ 2 tập trung vào việc xử lý các tình huống phức tạp và thuyết phục stakeholders. Hãy practice với real-world scenarios và collect comprehensive feedback!*
