# Farbod Bigdeli

### Backend Engineer | Distributed Systems | Computer Science Ph.D. Student

I'm a Computer Science Ph.D. student at the University of Texas at Arlington with 4+ years of experience building backend systems in production.

At SnappFood, Iran's largest food-delivery platform, I built Go APIs for new microservices and a Redis caching service that cut database load by 70%. At Finnotex, I built an API gateway, authentication and payment services. My research focuses on reliable software and careful evaluation of machine learning and software artifacts.

I'm open to backend, platform and AI engineering internships.

---

## Research Interests

- Reproducibility and evaluation of software research artifacts
- Rigorous evaluation of machine learning models
- Complexity measures in spiking neural networks
- Distributed systems and consensus

---

## Selected Engineering Projects

| Project | Description | Technologies |
|---|---|---|
| [studyroom_booking_microservice](https://github.com/farbod-bigdeli/studyroom_booking_microservice) | Booking system split into an API gateway and auth, rooms and bookings services that talk over gRPC. | Go, gRPC, Gin, JWT, MongoDB, Docker |
| [studyroom_booking](https://github.com/farbod-bigdeli/studyroom_booking) | The same system as a layered service behind Nginx, with Redis-backed sessions and wrk load tests. | Go, Gin, MongoDB, Redis, Nginx, Docker |
| [library-raft](https://github.com/farbod-bigdeli/library-raft) | Team project. I implemented Raft (leader election, log replication, heartbeats) over gRPC for a 5-node book service. | Python, gRPC, Docker |
| [banking-2pc](https://github.com/farbod-bigdeli/banking-2pc) | Team project. I added two-phase commit (prepare, commit, abort over gRPC) for account creation. | Python, gRPC, Docker |
| [auth](https://github.com/farbod-bigdeli/auth) | Authentication service with SMS two-step login, JWT, and national-ID and bank-account verification. | Go, Gin, PostgreSQL, Docker |
| [roi-mammo](https://github.com/farbod-bigdeli/roi-mammo) | Pre-registered, reproducible evaluation of ROI cropping for mammography classifiers. | Python, PyTorch |

---

## Technical Skills

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

### Software Architecture and Engineering

- Distributed Systems: consensus and distributed transactions
- Microservices Architecture and API Gateways
- Event-Driven Architecture: Pub/Sub and message queues
- RESTful APIs and Asynchronous Messaging
- Layered Architecture
- Caching Strategies

### Backend and APIs

![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=gin&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)
![REST](https://img.shields.io/badge/REST_APIs-555555?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

### Infrastructure and DevOps

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F03C2E?style=flat-square&logo=git&logoColor=white)

### Testing

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

- Unit, integration, regression and load testing

### Artificial Intelligence and Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

- Large Language Models: local serving, structured outputs, grounding validation
- LLM Evaluation and Benchmarking
- Applied Machine Learning: CNN training and evaluation
- Reproducible Experiments: pre-registration, archived code and predictions

---

## Publications

**Region-of-Interest Augmentation for Mammography Classification under Patient-Level Cross-Validation**

Farbod Bigdeli, Mohsen Mohammadagha, and Ali Bigdeli.

*arXiv:2509.20585, 2025.* [Paper](https://arxiv.org/abs/2509.20585) · [Code](https://github.com/farbod-bigdeli/roi-mammo)

**SERR: AI-Assisted Evaluation of Software Research Artifacts**

Ali Bigdeli, Farbod Bigdeli, Junchi Liu, Bianca Trinkenreich, and Fabio De Abreu Santos.

*In preparation.*

**Neuron Order Can Create Apparent Topology Effects in Lempel–Ziv Perturbational Complexity**

Farbod Bigdeli and Ishfaq Ahmad.

*In preparation.*

---

## Connect with Me

- LinkedIn: [linkedin.com/in/farbod-bigdeli](https://www.linkedin.com/in/farbod-bigdeli/)
- Email: bigdeli.farbod@gmail.com
