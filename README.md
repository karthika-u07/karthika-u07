<div align="center">

# 👋 Hey, I'm Karthika!

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=3F97F7&center=true&vCenter=true&random=false&width=600&lines=Backend+Developer;Python+%26+Django+Expert;Building+Distributed+Systems;API+Architecture+Enthusiast)](https://git.io/typing-svg)

### 🎯 Backend Developer • Python & Django • Distributed Systems

</div>

---
## 🧠 Backend Engineering Focus

- Designed **distributed backend systems** with async task queues  
- Built **REST APIs** handling concurrent requests with transaction safety  
- Implemented **message brokers** (Celery + Redis) for scalable processing  
- Integrated **LLM APIs** for intelligent data enrichment  
- Applied **rate limiting + abuse detection** middleware  
- Modeled **relational schemas** for real-world products  
- Applied **system design principles** (LLD + HLD)  
- Designed relational schemas and practiced query optimization on project databases

## ⭐ Highlight Projects

- AI Lead Intelligence Engine (Celery + Redis + LLM)
- Movie Ticket Booking System (Transactions + Concurrency)
- Splitwise Clone (Settlement Algorithms)
- Secure URL Shortener (Rate Limiting + Middleware)
---

## 🛠️ Technical Stack

<div align="center">

| **Backend** | **Database** | **Message Queue** | **Tools** | **Architecture** |
|:-----------:|:------------:|:-----------------:|:---------:|:----------------:|
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white) | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) | REST API Design |
| ![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white) | ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) | Async Workers | ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) | Distributed Systems |
| ![DRF](https://img.shields.io/badge/-DRF-ff1709?style=flat-square&logo=django&logoColor=white) | SQL Optimization | Message Brokers | ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) | Low-Level Design |

</div>

---

## 🚀 Backend Projects

<table>
<tr>
<td colspan="2">

### 🤖 AI Lead Intelligence Engine
**Distributed Backend System with LLM Integration**

```yaml
Tech Stack: Python, Django REST, Celery, Redis, MySQL, LLMs (Groq), Web Scraping (Tavily)
```

**Engineering Highlights:**
- Built **asynchronous lead enrichment pipeline** using Celery workers + Redis message queue
- Designed **non-blocking REST APIs** with background task orchestration
- Implemented **lifecycle-based state machine** (NEW → ENRICHING → ENRICHED → COMPLETED)
- Integrated **multi-source intelligence**: LinkedIn, company websites, recent news via Tavily API
- **LLM-powered analysis** using Groq for professional profile generation and lead scoring
- **Idempotent task execution** to prevent duplicate enrichment on retries
- Automated **email delivery** via SMTP with formatted intelligence reports
- Applied **production-grade patterns**: message brokers, retry handling, service decoupling
- Modeled **real-world SaaS architecture** separating API, task queue, AI inference, and persistence layers

**System Architecture:**
```
REST API → Celery Task Queue → Redis Broker → Background Workers
                                                      ↓
                                          [Tavily Enrichment]
                                                      ↓
                                            [Groq LLM Analysis]
                                                      ↓
                                              [MySQL Persistence]
                                                      ↓
                                              [Email Delivery]
```

[![Repo](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthika-u07/ai-lead-intelligence-engine)

</td>
</tr>
<tr>
<td width="50%">

### 🎬 BookMyShow Backend System
**Real-time Movie Ticket Booking Platform**

```yaml
Tech Stack: Django REST Framework, MySQL
```

**Engineering Highlights:**
- Atomic seat locking using DB transactions 
- Designed APIs with transactional handling for concurrent booking requests
- Prevented double booking under concurrency
- REST APIs for movies, shows & bookings
- Normalized schema for theaters & seats
- Multi-city, multi-theater architecture
- Booking lifecycle management (reserve → confirm → cancel)

[![Repo](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthika-u07/Book-My-Show-LLD)

</td>
<td width="50%">

### 💰 Splitwise Clone
**Expense Sharing & Settlement System**

```yaml
Tech Stack: Django, MySQL, Algorithms
```

**Engineering Highlights:**
- Smart balance simplification algorithms
- group expense settlement with scalable balance simplification
- Multiple split types (equal, percentage, exact)
- Graph-based debt settlement optimization
- Group expense management with transactions
- Relational modeling for users, groups & expenses
- Optimized settlement path calculations

[![Repo](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthika-u07/Splitwise-django-backend)

</td>
</tr>
<tr>
<td colspan="2">

### 🔗 URL Shortener with Security
**Enterprise-Grade Short URL Service**

```yaml
Tech Stack: Python, Django, Security Patterns
```

**Engineering Highlights:**
- Collision-free short URL generation using hashing
- Built to handle thousands of short URL redirects per day
- IP-based rate limiting middleware
- Abuse detection algorithms for spam prevention
- Click analytics and tracking system
- Custom slug validation with retry logic
- RESTful endpoint design with proper error handling

[![Repo](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthika-u07/Url-shortener-rate-limiter-abuse-detection-LLD)

</td>
</tr>
</table>

---

## 🏗️ Backend Architecture Experience

**Core Competencies:**
- REST API Design using Django REST Framework  
- **Distributed Systems** with Celery + Redis message queues  
- **Async Background Processing** for scalable workflows  
- **LLM Integration** for AI-powered features  
- Layered architecture (Views → Services → Repositories)  
- Database normalization & indexing strategies  
- Middleware implementation for cross-cutting concerns  
- UUID-based entity design for scalability  
- System design patterns (Booking, Wallet, Expense Management, Lead Intelligence)  
- Transactional integrity and concurrency handling
- **State Machines** for lifecycle management  
- **Idempotent Operations** for reliability  
- Basic unit testing for services and business logic
- Basic logging and debugging for production issues

**Actively Implementing:**
- Redis caching for hot endpoints  
- Dockerized Django apps  
- AWS EC2 + RDS deployment practice  
- Microservices architecture patterns  
- API rate limiting strategies  
- CI/CD pipelines

---

## 💻 What Drives Me

```python
class KarthikaBackendEngineer:
    def __init__(self):
        self.role = "Backend Developer"
        self.focus_areas = [
            "Distributed Systems with Celery + Redis",
            "Scalable REST APIs",
            "LLM Integration & AI-powered features",
            "System design patterns",
            "Database optimization",
            "Async background processing",
            "Clean architecture"
        ]
        self.current_goals = "Building production-ready distributed backend systems"
    
    def engineering_approach(self):
        return {
            "design": "Think about scale, concurrency, and edge cases first",
            "code": "Write maintainable, testable, idempotent solutions",
            "optimize": "Measure before optimizing, profile before scaling"
        }
    
    def recent_achievement(self):
        return "Built AI Lead Intelligence Engine with async workers + LLM integration"

me = KarthikaBackendEngineer()
print("Building distributed systems, not just features 🚀")
```

---

## 🌱 Engineering Roadmap


<div align="center">

![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Microservices](https://img.shields.io/badge/-Microservices-1572B6?style=flat-square&logo=micro&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

</div>

**Active Focus:**
- Advanced Django patterns and DRF best practices
- Celery + Redis for distributed task processing
- Docker containerization for deployment
- Cloud infrastructure (AWS EC2, S3, RDS)
- LLM API integration patterns
- Microservices architecture fundamentals

**Next on My List:**
- Kubernetes for container orchestration
- GraphQL API design
- Event-driven architecture
- System observability (logging, monitoring)

---

## 📌 What I Bring to a Team

- Strong backend fundamentals (Python + Django + Distributed Systems)
- Real-world system building experience (not toy projects)
- Clean architecture mindset with SOLID principles
- Ownership of features end-to-end
- Production-thinking: concurrency, idempotency, error handling
- Async processing expertise with Celery + Redis
- Modern tech integration: LLMs, web scraping, email automation
- Hungry to learn production-scale engineering
- Comfortable taking ownership of backend modules

---

## 🤝 Let's Connect!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthikau-40464722a)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthika-u07)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karthikakarthika0797@gmail.com)

</div>

---

<div align="center">

### 💡 Open to Backend Developer / Django Developer Roles

![Profile Views](https://komarev.com/ghpvc/?username=karthika-u07&color=brightgreen&style=flat-square)

**"Engineering scalable distributed systems with clean architecture and thoughtful design"** ⚡

</div>
