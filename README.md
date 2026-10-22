👨‍💻 About Me

I am a Computer Science & Engineering undergraduate (LEET entry) at Amritsar Group of Colleges (AGC) with a prior Computer Systems Technology Diploma from Mohawk College (Canada) and 6 years of international operational experience.

I build software from first principles. Instead of relying on heavyweight relational drivers or treating high-level libraries as black boxes, I focus on what happens at the hardware and memory boundary:

Contiguous unpadded binary memory layouts (#pragma pack(push, 1)) and direct stride random access O(1)).
Custom dynamic containers (td_array with geometric doubling, open-addressing hash maps) and hybrid algorithms (Musser's Introsort with depth limiting).
Autonomous data ingestion pipelines coupling local AI models (Ollama) with binary serialization for maximum storage efficiency.
🛠️ Technical Focus & Stack
Languages & Core Systems: Modern C++ (C++20, STL), Python 3.11 (OOP), SQL, Bash / Shell Scripting
Systems & Architecture: Binary File I/O, Fixed-Stride Addressing, Cache Locality, IPC Daemons, RAII Transactions, Zero-Fragmentation Updates
Data Structures & Algorithms: Custom Dynamic Arrays (td_array), Separate-Chaining & Open-Addressing Hash Tables, Quicksort / Heapsort / Introsort
Applied AI & Tools: Local LLMs (Ollama with JSON schema enforcement), Few-Shot Prompt Engineering, Django, Git & GitHub, CMake, Ninja, Linux CLI
🚀 Featured Engineering Projects
🔹 News Record Manager (LDBMS)

Modern C++20 | 2,772 Lines of Code | Zero External Dependencies

Engineered a binary database engine managing fixed 1,188-byte unpadded POD records on physical disk with constant-time O(1) random-access traversal.
Implemented custom memory containers (td_array) and Musser's hybrid Introsort with recursion depth limiting NlogN to eliminate worst-case O^2 degradation.
Built atomic .tmp file swap commits and in-place mutation routines for zero file fragmentation.
🔹 Autonomous News AI Ingestion & Binary Packing Pipeline

Python 3.11 | Local LLM (Ollama) | Background Daemons | Binary Serialization

Built an automated ETL pipeline extracting real-time BBC RSS XML feeds with persistent URL deduplication.
Orchestrated local Ollama LLMs with strict JSON constraints for 12-class categorization and length-bounded summarization (100–250 chars) with zero cloud API overhead.
Serialized structured records into 1,188-byte POD C-structs via struct.pack, reducing physical disk storage by 65% compared to raw JSON.
🔹 IntelliGate AI — Automated Campus Vehicle Access System

Collaborative Hackathon Project | System Architect & ALPR Developer

Built the local computer vision / OCR plate recognition module and decoupled mobile capture from backend processing using an asynchronous Firebase Realtime Database queue, delivering a 4s backend latency and 10s operational gate loop frequency.
🏆 Recent Honors & Milestones
🥇 1st Place Winner — ACES Yuva Utsav Debate & Elocution Competition (Department of CSE, AGC, 2026)
📜 Top Trainee (Certificate of Excellence) — 5-Day Intensive Python Programming Workshop ("From C Syntax to Pythonic Thinking", Er. Ajay Sharma, AGC, 2026)
🎓 Ontario College Diploma (GPA: 80% / 3.6) — Computer Systems Technology, Mohawk College, Canada (2021)
📬 Connect With Me
💼 LinkedIn: linkedin.com/in/ranvir-singh-810a971a6
📧 Email: r4ranvirsingh@gmail.com
📍 Location: Amritsar, Punjab, India
