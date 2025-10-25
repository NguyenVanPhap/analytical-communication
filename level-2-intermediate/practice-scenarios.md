# Practice Scenarios - Cấp Độ 2: Trung Cấp

## 🎯 Bài Tập 4: Technical Design Presentation (Tuần 7-9)

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

### Scenario 4.2: Database Migration Strategy
**Tình huống**: Plan migration từ MySQL sang PostgreSQL

**Presentation Structure**:
```
BUSINESS DRIVER
- Cost reduction: 40% lower licensing costs
- Performance improvement: 30% faster queries
- Feature requirements: JSON support, better analytics

TECHNICAL APPROACH
- Zero-downtime migration strategy
- Data consistency validation
- Performance benchmarking
- Rollback plan

MIGRATION TIMELINE
- Phase 1: Parallel setup (2 weeks)
- Phase 2: Data migration (1 week)
- Phase 3: Application switch (1 week)
- Phase 4: Validation (1 week)

RISK MITIGATION
- Data backup strategy
- Performance monitoring
- Team training
- Support escalation
```

## 🎯 Bài Tập 5: Crisis Communication (Tuần 10-12)

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

### Scenario 5.2: Security Breach Response
**Tình huống**: Phát hiện potential security breach, cần communicate với stakeholders

**Crisis Communication Structure**:
```
INCIDENT OVERVIEW
- Type: Potential data exposure
- Scope: User email addresses
- Timeline: Detected 2 hours ago
- Status: Investigation ongoing

IMMEDIATE ACTIONS
- Security team activated
- System isolation implemented
- Forensic analysis started
- Legal team notified

COMMUNICATION STRATEGY
- Internal: All-hands meeting
- External: Customer notification prepared
- Regulatory: Compliance team engaged
- Media: Press statement ready

NEXT STEPS
- Complete investigation (24 hours)
- Customer notification (48 hours)
- System restoration (72 hours)
- Post-incident review (1 week)
```

## 🎯 Bài Tập 6: Technology Selection Debate (Tuần 13-14)

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

**Node.js Arguments (15 phút)**
```
BUSINESS CASE:
- Market trend: Growing adoption
- Developer availability: Larger talent pool
- Cost efficiency: Single language (JavaScript)
- Innovation: Faster feature development

TECHNICAL ADVANTAGES:
- Non-blocking I/O cho high concurrency
- JSON-native (perfect for APIs)
- Rich npm ecosystem
- Real-time capabilities (WebSockets)
- Microservices-friendly

PERFORMANCE CONSIDERATIONS:
- Excellent for I/O intensive applications
- Lower memory footprint
- Faster startup time
- Better horizontal scaling

RISK ASSESSMENT:
- Medium technical risk (newer for team)
- Medium team risk (learning curve)
- High innovation potential
- Good scalability for specific use cases
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

### Scenario 6.2: Cloud Provider Selection
**Tình huống**: Choose giữa AWS, Azure, và Google Cloud

**Comparison Framework**:
```
EVALUATION CRITERIA:
1. Cost (25%)
2. Performance (25%)
3. Team expertise (25%)
4. Feature set (25%)

AWS ADVANTAGES:
- Market leader với comprehensive services
- Strong enterprise support
- Mature ecosystem
- Global infrastructure

AZURE ADVANTAGES:
- Microsoft integration
- Enterprise security features
- Hybrid cloud capabilities
- Windows/.NET optimization

GOOGLE CLOUD ADVANTAGES:
- AI/ML capabilities
- Data analytics tools
- Kubernetes expertise
- Competitive pricing

RECOMMENDATION PROCESS:
1. Proof of concept với each provider
2. Cost analysis cho 3-year projection
3. Team training requirements
4. Migration complexity assessment
```

## 📝 Practice Templates

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

*Các scenarios này được thiết kế đặc biệt cho Cấp Độ 2, tập trung vào việc xử lý các tình huống phức tạp và thuyết phục stakeholders.*
