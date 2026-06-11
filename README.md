# Hi, I'm Yaseen Sharaf 👋

**Computer Science graduate (First Class Honours) · BSc, University of the West of England, Bristol**

Software engineer with hands-on experience building Android apps, backend systems, ML pipelines, and systems-level C++. I'm open to opportunities across Jordan and the GCC region.

📍 Amman, Jordan · 📧 yaseenammarsharaf@gmail.com · [GitHub](https://github.com/yaseensharaf) · [LinkedIn](https://linkedin.com/in/yaseen-sharaf)

---

## 🛠 Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | Python, Kotlin, C#, JavaScript, C++, SQL |
| **Backend** | Django, Flask, FastAPI, ASP.NET Core, REST APIs |
| **Mobile** | Android · Kotlin · MVVM · Jetpack · Firebase |
| **Databases** | PostgreSQL, SQL Server, Firebase Realtime Database |
| **ML / Data** | TensorFlow, Scikit-learn, Pandas, LSTM, ARIMA, Random Forest |
| **DevOps & Tools** | Docker, Docker Compose, GitHub Actions, Git, Postman, Gradle |
| **Methods** | Agile Scrum, TDD, CRISP-DM |

---

## 💼 Professional Experience

**`.NET Developer Intern` — SEDRAPAY for e-Payment Solutions, Amman** *(Jul – Sep 2024)*

- Contributed to an ASP.NET Core payment processing pipeline in a live production environment, working across architecture, business logic, and API security
- Optimised SQL queries in a transactional system, reducing redundant database calls and improving maintainability
- Participated in Agile sprint cycles: bug triage, regression testing, and backend feature validation alongside senior engineers

---

## 🚀 Projects

### [Daily Groceries — Android Shopping App](https://github.com/yaseensharaf/Grocery-Shopping-App-Kotlin)
*Kotlin · Firebase · MVVM · Jetpack · Android*

A production-grade native Android grocery app with real-time cart sync, full authentication flow, order history, and push notifications. Built on MVVM with Firebase Realtime Database as the backend — zero server management.

- Real-time cart updates via Firebase Realtime Database
- Email/password auth with persistent sessions via Firebase Authentication
- Complete purchase history with chronological order tracking
- Responsive layouts for phones and tablets (portrait, landscape, 600dp+)
- Firebase Cloud Messaging for order confirmation notifications

---

### [Intelligent Retail Demand Forecasting System](https://github.com/yaseensharaf/-DSP-)
*Python · TensorFlow · ARIMA · Flask · Pandas · Scikit-learn · Plotly*

A hybrid ARIMA-LSTM machine learning platform trained on H&M transactional data (2015–2023), forecasting product-level sales up to 5 years ahead (2024–2028) via an interactive Flask dashboard.

- Hybrid model: 90% ARIMA (linear trends) + 10% LSTM (non-linear residuals)
- 60-month forecasts for all eligible products across 3 retail datasets
- Business intelligence pages: trending products, lowest sellers, inventory recommendations
- Dark/light mode, responsive dashboard, per-product interactive charts
- Full CRISP-DM methodology; all forecasts exported as CSV + PNG

---

### [Real-Time Labor Demand Predictor](https://github.com/yaseensharaf/labor-demand-predictor)
*Python · FastAPI · React · Scikit-learn · Random Forest · Docker*

A full-stack ML application that forecasts daily workforce requirements for manufacturing and distribution facilities. Exposes predictions via a REST API and interactive React dashboard.

- Random Forest model: R² = 0.95, MAE ≈ 2.36 workers
- Factors: day of week, seasonality, holidays, industry type, weather events
- FastAPI backend with Swagger/OpenAPI docs; React + Vite frontend
- Fully containerised with Docker Compose for one-command deployment
- Human-readable demand explanations per prediction

---

### [IoT Log File Management System](https://gitlab.uwe.ac.uk/y2-sharaf/iot_starter)
*C++ · Make · SimpleTest*

A C++ IoT log processing system built across three progressive tasks: message extraction, log-level parsing, and line reformatting — with a full unit test suite using the SimpleTest framework.

- Modular design with a `Log` class separating parsing logic from I/O
- Five structured test cases covering file opening, sequential reads, and log-level extraction
- Progressive enhancement pattern: each task builds on the last

---

### [Fiber Scheduler — Cooperative Multitasking in C++](https://gitlab.uwe.ac.uk/y2-sharaf/asp_assignment)
*C++ · x86-64 Assembly · Clang*

A lightweight user-space fiber scheduler implementing cooperative multitasking from scratch — context switching, fiber abstraction, round-robin scheduling, and a yielding mechanism.

- Task 1: Raw context switching via x86-64 assembly (`get_context`, `set_context`, `swap_context`)
- Task 2: `Fiber` class + `Scheduler` with round-robin execution and shared data between fibers
- Task 3: `yield()` mechanism — fibers pause mid-execution and resume seamlessly after others complete

---

### [Custom String Class with Reference Counting](https://gitlab.uwe.ac.uk/y2-sharaf/asp_w1-w2)
*C++ · Dynamic Memory Management · Templates*

A from-scratch `my_string` class built across four progressive tasks, evolving from basic dynamic allocation to a fully templated reference counting system.

- Task 1: Dynamic memory allocation with shallow copy semantics (`getChar`, `setChar`, boundary-checked access)
- Task 2: Reference counting via `ref_count` pointer — memory freed automatically when the last reference is destroyed
- Task 3: Full lifecycle demonstration with visible ref-count tracking as objects go in and out of scope
- Task 4: Templated `ReferenceCounted<T>` class reusable across `int`, `double`, custom `point`, and `my_string` — eliminating per-type memory management boilerplate

---

### [Custom Bump Allocator with Benchmarking](https://gitlab.uwe.ac.uk/y2-sharaf/asp_w1-w2)
*C++ · Memory Allocators · SimpleTest · Benchmarking*

A high-performance bump allocator built in C++ with full unit tests and a comparative benchmark between upward and downward allocation strategies.

- Upward and downward bump allocators with alignment handling, thread safety via `std::mutex`, and a reset-on-zero-references deallocation model
- 8 unit tests using SimpleTest covering single/multiple allocations, alignment, exact-fit, overflow, and reset/reallocation
- Benchmarked across 4 allocation patterns (small, large, mixed, custom types); `-O3` optimisation dramatically reduced times
- Downward allocator showed a measurable edge on high-frequency small allocations due to simpler pointer arithmetic mirroring stack behaviour

---

### Security Data Analytics & Visualisation
*Python · Pandas · Matplotlib · Seaborn · NetworkX*

Investigated a simulated network attack on packet capture data using a multi-chart visualisation pipeline: packet volume over time, protocol distribution, source-destination scatter, node-link graph, and multi-protocol time series.

---

## 📄 About

- 🇯🇴 Jordanian National · 🇺🇸 U.S. Permanent Resident
- Open to relocation across Jordan and GCC countries
- BSc Computer Science — **First Class Honours**, UWE Bristol (2022–2025)
