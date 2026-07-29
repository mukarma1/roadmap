# 📆 Month 3: FastAPI, Redis & Task Engine

## 🎯 Month 3 Goals
- ✅ Advanced FastAPI (middleware, background tasks)
- ✅ Redis (caching, pub/sub, rate limiting)
- ✅ Celery (distributed task queues)
- ✅ Build FYP Task Engine (Python)
- ✅ Deploy on cloud

## 🚀 FYP Progress
- [ ] Task Engine built with Celery
- [ ] Redis setup for caching/queues
- [ ] Task scheduling implemented
- [ ] Worker pool configured

---

## 📊 Month 3 Checklist

- [ ] Week 1: Advanced FastAPI
- [ ] Week 2: Redis Deep Dive
- [ ] Week 3: Celery & Task Queues
- [ ] Week 4: FYP Task Engine

---

## Week 1: Advanced FastAPI

### Day 1 - Background Tasks
- [ ] Learn `BackgroundTasks`
- [ ] Implement email sending in background
- [ ] Learn `FastAPI` lifespan events
- [ ] Implement startup/shutdown events
- [ ] Push code to GitHub

### Day 2 - WebSocket Support
- [ ] Learn WebSockets in FastAPI
- [ ] Create WebSocket endpoint
- [ ] Implement chat between clients
- [ ] Learn connection management
- [ ] Push code to GitHub

### Day 3 - File Upload & Processing
- [ ] Learn `File` and `UploadFile`
- [ ] Implement file upload endpoint
- [ ] Process CSV/JSON files
- [ ] Store files in cloud storage
- [ ] Push code to GitHub

### Day 4 - Middleware & CORS
- [ ] Create custom middleware
- [ ] Implement request logging
- [ ] Implement response timing
- [ ] Advanced CORS configuration
- [ ] Push code to GitHub

### Day 5 - Performance Optimization
- [ ] Learn `Async` vs `Sync` performance
- [ ] Implement connection pooling
- [ ] Use `aiopg` for async PostgreSQL
- [ ] Benchmark with Locust
- [ ] Push code to GitHub

### Day 6 - Testing FastAPI
- [ ] Install `pytest` and `httpx`
- [ ] Write unit tests
- [ ] Write integration tests
- [ ] Write WebSocket tests
- [ ] Use `pytest-cov` for coverage
- [ ] Push tests to GitHub

### Day 7 - Week 1 Revision
- [ ] Revise advanced FastAPI
- [ ] Build mini "File Processing API"
- [ ] Deploy to Railway
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: Advanced FastAPI Complete**

---

## Week 2: Redis Deep Dive

### Day 8 - Redis Setup
- [ ] Install Redis locally
- [ ] Learn basic commands: SET, GET, DEL
- [ ] Learn Redis data types: String, List, Set, Hash
- [ ] Use Redis CLI
- [ ] Push notes to GitHub

### Day 9 - Python + Redis
- [ ] Install `redis-py` library
- [ ] Connect Python to Redis
- [ ] Implement CRUD operations
- [ ] Use Redis for session storage
- [ ] Push code to GitHub

### Day 10 - Caching
- [ ] Implement caching with Redis
- [ ] Cache API responses
- [ ] Set TTL (Time To Live)
- [ ] Cache invalidation strategies
- [ ] Integrate with FastAPI
- [ ] Push code to GitHub

### Day 11 - Rate Limiting
- [ ] Implement rate limiting with Redis
- [ ] Use sliding window algorithm
- [ ] Implement per-user limits
- [ ] Implement global limits
- [ ] Push code to GitHub

### Day 12 - Pub/Sub
- [ ] Learn Redis Pub/Sub
- [ ] Implement publisher
- [ ] Implement subscriber
- [ ] Real-time notifications
- [ ] Push code to GitHub

### Day 13 - Redis in FYP
- [ ] Implement caching for API Gateway
- [ ] Store JWT tokens in Redis
- [ ] Session management with Redis
- [ ] Rate limiting for Gateway
- [ ] Push code to GitHub

### Day 14 - Week 2 Revision
- [ ] Revise Redis concepts
- [ ] Build mini "Rate Limiter Service"
- [ ] Deploy Redis on cloud (Redis Cloud)
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: Redis Complete**

---

## Week 3: Celery & Task Queues

### Day 15 - Celery Setup
- [ ] Install Celery, RabbitMQ, Redis
- [ ] Configure Celery with Redis as broker
- [ ] Create first Celery task
- [ ] Start Celery worker
- [ ] Push code to GitHub

### Day 16 - Celery Tasks
- [ ] Learn task definitions
- [ ] Learn task parameters
- [ ] Learn task return values
- [ ] Call tasks synchronously/asynchronously
- [ ] Push code to GitHub

### Day 17 - Task Scheduling
- [ ] Learn Celery Beat (scheduler)
- [ ] Schedule periodic tasks
- [ ] Configure `celery.schedules`
- [ ] Run scheduled tasks
- [ ] Push code to GitHub

### Day 18 - Task Chaining
- [ ] Learn `chain`, `group`, `chord`
- [ ] Implement task pipelines
- [ ] Learn `map`, `starmap`
- [ ] Error handling in chains
- [ ] Push code to GitHub

### Day 19 - Monitoring & Error Handling
- [ ] Install Flower (monitoring)
- [ ] Monitor workers
- [ ] Task retries with `retry`
- [ ] Error logging with Celery
- [ ] Push code to GitHub

### Day 20 - FastAPI + Celery
- [ ] Trigger Celery tasks from FastAPI
- [ ] Return task IDs
- [ ] Poll task status
- [ ] Cancel running tasks
- [ ] Push code to GitHub

### Day 21 - Week 3 Revision
- [ ] Build mini "Task Scheduler API"
- [ ] Use Flower for monitoring
- [ ] Deploy on cloud
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: Celery Complete**

---

## Week 4: FYP Task Engine

### Day 22 - Design Task Engine
- [ ] Design task types (compute, storage, API calls)
- [ ] Design task states (pending, running, completed, failed)
- [ ] Design task priorities
- [ ] Design task queues (high, normal, low)
- [ ] Create design document
- [ ] Push to GitHub

### Day 23 - Task Engine Core
- [ ] Create Task model (Python dataclass)
- [ ] Create TaskEngine class
- [ ] Implement submit_task() method
- [ ] Implement get_task_status()
- [ ] Implement cancel_task()
- [ ] Push code to GitHub

### Day 24 - Celery Integration
- [ ] Integrate Celery workers
- [ ] Define Celery tasks
- [ ] Implement task distribution
- [ ] Implement task results
- [ ] Push code to GitHub

### Day 25 - Task Scheduling
- [ ] Implement scheduled tasks with Celery Beat
- [ ] Create cron-based scheduling
- [ ] Create periodic tasks
- [ ] Push code to GitHub

### Day 26 - Task Management API
- [ ] Create FastAPI endpoints for tasks
- [ ] POST /tasks - Submit task
- [ ] GET /tasks/{id} - Get task status
- [ ] GET /tasks - List all tasks
- [ ] DELETE /tasks/{id} - Cancel task
- [ ] Push code to GitHub

### Day 27 - Testing & Deployment
- [ ] Write unit tests
- [ ] Write integration tests
- [ ] Deploy FastAPI + Celery + Redis + RabbitMQ
- [ ] Test all features on cloud
- [ ] Update documentation
- [ ] Push everything

### Day 28 - Month 3 Wrap-up
- [ ] Revise all Month 3 topics
- [ ] Complete FYP Task Engine
- [ ] Write Month 3 reflection
- [ ] Update main README
- [ ] Push everything to GitHub
- [ ] **🎉 Month 3 Complete!**

---

## 🎯 FYP Checkpoint: Month 3

### FYP Components Completed:
- ✅ FastAPI user service (from Month 2)
- ✅ Redis caching & rate limiting
- ✅ Task Engine with Celery
- ✅ RabbitMQ message broker
- ✅ Task scheduling with Celery Beat

### Next Month:
- Build API Gateway (Node.js)
- Connect all services

---

## 🚀 Deployment Resources

- [Redis Cloud](https://redis.com/redis-enterprise-cloud/)
- [CloudAMQP (RabbitMQ)](https://www.cloudamqp.com/)
- [Railway (FastAPI + Celery)](https://railway.app/)

---

## 📝 Month 3 Notes

*Add your daily learning here*

---

**Next: Month 4 → API Gateway & Microservices 🚀**
