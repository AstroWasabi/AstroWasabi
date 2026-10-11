## Hi there 👋

# Pranav Harithasa                                                                                                                                                                                 
                                                                                                                                                        
Systems researcher and software engineer based in Osaka, Japan. Currently pursuing an M.S. in Advanced Information Science and Engineering at Ritsumeikan University.                              
                                                                                                                                                                                                   
My work centers on low-level systems, cryptographic runtime efficiency (TLS 1.3 / Post-Quantum Cryptography), concurrent engines, and distributed backend infrastructure.                          
                                                                                                                                                                                                   
---                                                                                                                                                                                                
                                                                                                                                                                                                   
### What I'm Working On                                                                                                                                                                            
                                                                                                                                                                                                   
- **Graduate Systems Research (Advanced Network Laboratory):**                                                                                                                                     
  Evaluating concurrent hybrid post-quantum key exchange (ML-KEM, FrodoKEM, BIKE + ECDH) in TLS 1.3, hardware-aware dispatch using CPUID/sysfs telemetry, and tail-latency optimization across     
bare-metal and AWS virtualized environments.                                                                                                                                                         
- **Distributed Runtimes & Infrastructure:**                                                                                                                                                       
  Building robust asynchronous execution engines, task queues, and real-time telemetry systems in Python and C.                                                                                    
                                                                                                                                                                                                   
---                                                                                                                                                                                                
                                                                                                                                                                                                   
### Featured Projects                                                                                                                                                                              
                                                                                                                                                                                                   
- [**LightQueue**](https://github.com/AstroWasabi/lightqueue)                                                                                                                                      
  An asynchronous distributed task queue and execution engine in Python. Combines an `asyncio` network coordinator with a `ProcessPoolExecutor` worker pool to bypass the GIL, featuring priority  
min-heap and Redis Sorted Set scheduling, exponential backoff with jitter, dead-letter queues, and graceful POSIX signal draining.                                                                   
                                                                                                                                                                                                   
- [**PulseCheck**](https://github.com/AstroWasabi/pulsecheck)                                                                                                                                      
  A real-time API health and telemetry monitoring service built on FastAPI, LightQueue, and non-blocking SQLite (`aiosqlite`). Uses decentralized self-scheduling task loops instead of central    
cron jobs to track rolling uptime and latency distributions with live Chart.js sparklines.                                                                                                           
                                                                                                                                                                                                   
---                                                                                                                                                                                                
                                                                                                                                                                                                   
### Technical Focus                                                                                                                                                                                
                                                                                                                                                                                                   
- **Languages:** C, Python, SQL, Bash                                                                                                                                                              
- **Systems & Crypto:** Post-Quantum Cryptography (ML-KEM, BIKE, FrodoKEM), OpenSSL, liboqs, TLS 1.3, POSIX Multithreading (pthreads), Host Telemetry (CPUID, sysfs)                               
- **Backend & Distributed:** FastAPI, Redis, Asynchronous I/O (`asyncio`), Multiprocessing & IPC, `aiosqlite`, REST APIs, `pytest`                                                                 
- **Cloud & Tools:** Linux/Unix, AWS (EC2), Git, Uvicorn                                                                                                                                           
                                                                                                                                                                                                   
---                                                                                                                                                                                                
                                                                                                                                                                                                   
### Publications & Research                                                                                                                                                                        
                                                                                                                                                                                                   
- **IEICE IT** (Kyoto, May 2026) — Parallel Hybrid PQC Concurrency & Telemetry                                                                                                                     
- **IEICE CCS** (Sapporo, Aug 2026) — Parallel Hybrid PQC Concurrency & Telemetry                                                                                                                  
                                                                                                                                                                                                   
---                                                                                                                                                                                                
                                                                                                                                                                                                   
### Contact                                                                                                                                                                                        
                                                                                                                                                                                                   
- **Location:** Osaka, Japan                                                                                                                                                                       
- **Email:** [harithasapranav@gmail.com](mailto:harithasapranav@gmail.com)                                                                                                                         
- **LinkedIn:** [linkedin.com/in/pranav-harithasa](https://linkedin.com)  
