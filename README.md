1| <div align="center">
2| 
3| # Adarsh V H
4| 
5| <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Systems+Engineer;Backend+Developer;Database+%26+Distributed+S[...]
6| 
7| I build software at the intersection of systems, backend engineering, databases, and cloud infrastructure.
8| 
9| I care deeply about understanding what’s under the hood: how data moves, how systems fail, how databases execute, where latency comes from, and how software interacts with the hardware beneath it[...]
10| 
11| [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarsh-v-h-2005abc)
12| [![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adarshvh2005@gmail.com)
13| [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://adarsh-v-h.github.io/)
14| 
15| </div>
16| 
17| ---
18| 
19| ## About me
20| 
21| - Third-year CSE student at JSS Bengaluru
22| - Interested in: systems programming, backend architecture, SQL and database internals, distributed systems, cloud, and performance engineering
23| - Passionate about building reliable, fast, and observably correct software
24| 
25| ---
26| 
27| ## Featured projects
28| 
29| ### 1) Agentic-KSP
30| A deployed crime-intelligence platform for Karnataka State Police.
31| 
32| - Officers ask questions in English or Kannada
33| - LLM generates MySQL queries on AWS RDS with a self-correction loop
34| - Answers stream back over SSE
35| - Access is read-only and scoped using JWT, RBAC, and a C++20 SQL-AST filter
36| 
37| Tech: Python, FastAPI, gRPC, MySQL, AWS RDS, SSE, RAG
38| 
39| Repository: https://github.com/adarsh-v-h/AgenticAI-KSP
40| 
41| ### 2) Universal Log Framework (ULPF)
42| A vendor-agnostic log platform for Syslog, CEF, LEEF, and JSON inputs.
| 
44| - Preserves raw events and normalizes them into a single schema in ClickHouse
45| - Built the Java backend for batched writes, integrity checks, and schema mapping
46| - Includes SHA-256 Merkle-tree validation for event integrity
47| - Local ONNX embedding model for schema mapping
48| - Load-tested at ~995 events/sec with ~77 ms P95 latency
49| 
50| Tech: Java 21, Spring Boot, SQLite, ClickHouse, Podman
51| 
52| Repository: https://github.com/adarsh-v-h/ULPF
53| 
54| ### 3) MeetInMin
55| Meeting assistant that records browser-tab audio without a bot joining the call.
56| 
57| - Produces transcript, summary, key decisions, and action items
58| - Uses Zoho Zia speech-to-text in 4-minute chunks
59| - Extracts decisions with Zoho GLM and confidence scores
60| - Maintains per-project memory from meetings and project docs
61| - Reads Gmail context for decisions and follow-ups
62| 
63| Tech: Python, FastAPI, React, Chrome Extension MV3, Gmail OAuth
64| 
65| Repository: https://github.com/adarsh-v-h/MeetInMin
66| 
67| ### 4) High-Performance Limit Order Book
68| An evolving low-latency C++ matching engine.
69| 
70| - Focused on cache-aware structures, concurrency, deterministic hot paths, and memory layout
71| - Built to learn how latency is shaped by data structure and system design decisions
72| 
73| Tech: C++, low-level design, performance engineering
74| 
75| Repository: https://github.com/adarsh-v-h/Order_book
76| 
77| ### 5) Themis's Domain — CRMS
78| A crime record management system centered on relational data and backend services.
79| 
80| - Authentication, authorization, indexing, connection pooling, and caching
81| - Strong hands-on exposure to backend service design and data management
82| 
83| Tech: Backend services, relational design, auth, indexing, pooling
84| 
85| Repository: https://github.com/adarsh-v-h/Crime_DB
86| 
87| ### 6) Software-Defined FADEC Simulation
88| A fault-tolerant engine control simulation built in C++.
89| 
90| - Closed-loop engine dynamics
91| - Telemetry and safe-state failover logic
92| - Reliability-focused control architecture
93| 
94| Tech: C++, simulation, control systems, fault tolerance
95| 
96| Repository: https://github.com/adarsh-v-h/Software-Defined-FADEC-Simulation
97| 
98| ---
99| 
100| ## Stack & tools
101| 
102| ### Backend
103| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
104| ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
105| ![gRPC](https://img.shields.io/badge/gRPC-1C7CE5?style=flat-square&logo=grpc&logoColor=white)
106| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
107| ![Spring%20Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
108| 
109| ### Databases
110| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
111| ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=white)
112| ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
113| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
114| 
115| ### Systems & low-level
116| ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
117| ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
118| ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
119| ![Memory](https://img.shields.io/badge/Memory-Design-8A2BE2?style=flat-square)
120| ![Concurrency](https://img.shields.io/badge/Concurrency-Design-FF7F50?style=flat-square)
121| 
122| ### Cloud & infra
123| ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
124| ![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
125| 
126| ### Security & auth
127| ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
128| ![RBAC](https://img.shields.io/badge/RBAC-Access_Control-4B5563?style=flat-square)
129| ![OAuth](https://img.shields.io/badge/OAuth-2.0-3C7CFF?style=flat-square)
130| 
131| ---
132| 
133| ## Currently exploring
134| 
135| - Distributed systems fundamentals: replication, partitioning, consistency, and failure modes
136| - Database internals and query execution
137| - PostgreSQL internals and performance tuning
138| - Low-level design in C++
139| - Core Java and Spring Boot
140| - Cloud architecture beyond RDS
141| - Advanced FastAPI patterns
142| - Reinforcement learning for intelligent systems
143| - Performance-oriented systems programming
144| 
145| ---
146| 
147| ## A quick principle
148| 
149| > I don’t just want software that works — I want software that is efficient, understandable, resilient, and built on strong system-level intuition.
150| 
151| ---
152| 
153| <div align="center">
154| 
155| <img src="https://komarev.com/ghpvc/?username=adarsh-v-h&label=Profile%20views&color=brightgreen&style=flat-square" alt="profile views" />
156| 
157| </div>
158| 