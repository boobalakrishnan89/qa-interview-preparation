# 🎯 QA Automation — Interview Preparation & Documentation

> Senior QA Automation Engineer / SDET interview preparation materials built from a **real production framework** (Java 17 + Playwright + TestNG + REST Assured + MySQL + MongoDB).

### 🌐 [📖 Read Online → boobalakrishnan89.github.io/qa-interview-preparation](https://boobalakrishnan89.github.io/qa-interview-preparation/)

> Premium dark-themed HTML with sidebar navigation, full-text search (⌘K), collapsible Q&A cards, code highlighting, dark/light toggle, and print support.

---

## 📚 Documents

| # | Document | Description | Questions |
|---|---|---|---|
| 1 | [Senior Interview Q&A (75 Questions)](onsurity_java_playwright_interview_qa.md) | Comprehensive interview preparation for 10+ years experience | 75 |
| 2 | [CI/CD Setup & Configuration](cicd_documentation.md) | Complete CI/CD pipeline documentation with GitHub Actions | — |

---

## 🏗️ Interview Q&A — Structure

### Part A: Framework-Specific (Q1–Q35)
Real code examples from a production test automation framework:

| Category | Questions |
|---|---|
| System Architecture & Design Decisions | Q1–Q2 |
| Concurrency (ThreadLocal, ConcurrentHashMap) | Q3, Q9 |
| Configuration Management (4-tier resolution) | Q4 |
| Page Object Model (lazy locators, fluent API) | Q5 |
| Smart Retry (environmental vs assertion failures) | Q6 |
| API + UI Hybrid Testing | Q7 |
| Database Testing (MySQL HikariCP + MongoDB) | Q8 |
| Test Data Strategy & Collision Prevention | Q10, Q17 |
| Test Pyramid for FinTech | Q11 |
| CI/CD Pipeline (8 GitHub Actions workflows) | Q12 |
| Multi-boundary Authentication (OTP, SSO, JWT, OAuth) | Q13, Q25 |
| Flaky Test Investigation | Q14 |
| Observability & Health Checks | Q15 |
| Zero-code API Logging (Intercepting Filter) | Q16 |
| CDP Integration (Chrome DevTools Protocol) | Q18 |
| Pre-condition Setup & Data Cleanup | Q19 |
| Playwright Core (Tracing, Locators, Iframes, Waits) | Q20–Q22, Q32 |
| Docker Containerization | Q24 |
| Custom Annotations (@Owner, @Severity) | Q26 |
| Scaling Parallel Execution (5 → 20 threads) | Q28 |
| Shift-Left & ROI Measurement | Q29–Q30 |
| Production Incident Investigation | Q31 |
| Leadership & Mentoring | Q35 |

### Part B: Generic Senior QA / SDET (Q36–Q75)
Sourced from 2025/2026 interview trends at FAANG, FinTech, and top-tier companies:

| Section | Questions | Topics |
|---|---|---|
| Test Strategy & Philosophy | Q36–Q40 | Test Pyramid, what NOT to automate, risk-based testing |
| Java Concurrency Deep-Dive | Q41–Q47 | ThreadLocal, volatile, Atomic, CompletableFuture, Streams, Builder |
| REST Assured & API Architecture | Q48–Q53 | Framework design, API chaining, JSON Schema, OAuth, negative testing |
| GoF Design Patterns | Q54–Q58 | 10 patterns mapped, Singleton vs DI, Strategy, Observer |
| Microservices & Contract Testing | Q59–Q63 | Pact CDC, async messaging, Service Virtualization, API versioning |
| Performance & Security | Q64–Q67 | OWASP Top 10, memory leaks, load/stress/soak testing |
| AI & Modern Trends | Q68–Q70 | GenAI in testing, non-deterministic outputs, self-healing |
| Scenario-Based Whiteboard | Q71–Q73 | Payment API design, CI debugging, test data pool |
| Leadership & Behavioral STAR | Q74–Q75 | Flakiness reduction, quality advocacy |

---

## 🛠️ Tech Stack Covered

| Technology | Version | Role |
|---|---|---|
| Java | 17 | Core language |
| Playwright | 1.49.0 | Browser automation |
| TestNG | 7.9.0 | Test framework |
| REST Assured | 5.4.0 | API testing |
| HikariCP | 5.1.0 | MySQL connection pooling |
| MongoDB Driver | 4.11.x | MongoDB operations |
| Extent Reports | 5.1.2 | HTML reporting |
| Jackson | 2.16.x | JSON parsing |
| Log4j2 | 2.22.x | Structured logging |
| Docker | Multi-stage | Containerized execution |
| GitHub Actions | v4 | CI/CD pipelines |
| Maven | 3.9.x | Build tool |

---

## 📖 How to Use

1. **Interview Prep** — Start with the [75-question Q&A](onsurity_java_playwright_interview_qa.md). Focus on Part A for framework-specific depth, Part B for generic breadth.
2. **CI/CD Reference** — Use the [CI/CD documentation](cicd_documentation.md) for pipeline setup questions.
3. **Quick Reference** — Jump to the "Master Quick Reference" table at the end of the Q&A doc for a one-page cheat sheet.

---

## 📌 Key Design Patterns (10 GoF Patterns Applied)

| Pattern | GoF Category | Framework Usage |
|---|---|---|
| Singleton (DCL) | Creational | ConfigManager, APIClient, DatabaseUtils |
| Factory Method | Creational | BrowserFactory |
| Builder | Creational | PartnerApiPayloadBuilder |
| Template Method | Behavioral | BasePage, BaseTest |
| Strategy | Behavioral | SmartRetryAnalyzer |
| Observer | Behavioral | ExtentReportListener, RetryListener |
| Fluent Interface | Idiom | Page object method chaining |
| Intercepting Filter | Enterprise | ExtentReportApiFilter |
| Page Object | Domain | All page classes |
| Module | Structural | TestDataManager.ModuleData |

---

*Created by Boobala Krishnan — Senior QA Automation Engineer*
