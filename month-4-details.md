# 📆 Month 4: API Gateway & Microservices

## 🎯 Month 4 Goals
- ✅ Node.js microservices architecture
- ✅ RabbitMQ for service communication
- ✅ Build API Gateway (Node.js)
- ✅ Service discovery & load balancing
- ✅ Rate limiting & logging
- ✅ Connect all FYP components

## 🚀 FYP Progress
- [ ] API Gateway built (Node.js)
- [ ] Service registry implemented
- [ ] All services connected
- [ ] End-to-end testing complete

---

## 📊 Month 4 Checklist

- [ ] Week 1: Node.js Microservices
- [ ] Week 2: RabbitMQ Deep Dive
- [ ] Week 3: API Gateway
- [ ] Week 4: Integration & Testing

---

## Week 1: Node.js Microservices

### Day 1 - Microservices Architecture
- [ ] Learn Monolith vs Microservices
- [ ] Learn service decomposition
- [ ] Learn API Gateway pattern
- [ ] Learn service discovery
- [ ] Create architecture diagram
- [ ] Push to GitHub

### Day 2 - Node.js Fastify Setup
- [ ] Install Fastify (Node.js framework)
- [ ] Create first Fastify server
- [ ] Learn routes, middleware
- [ ] Learn plugins
- [ ] Push code to GitHub

### Day 3 - User Service (Node.js)
- [ ] Build User Service in Node.js
- [ ] Implement user CRUD
- [ ] Connect to PostgreSQL
- [ ] Implement JWT validation
- [ ] Push code to GitHub

### Day 4 - Task Service (Node.js)
- [ ] Build Task Service in Node.js
- [ ] Interface with Celery API
- [ ] Task submission endpoints
- [ ] Task status endpoints
- [ ] Push code to GitHub

### Day 5 - Auth Service (Node.js)
- [ ] Build Auth Service
- [ ] Implement login/register
- [ ] JWT generation & validation
- [ ] Refresh tokens
- [ ] Push code to GitHub

### Day 6 - Service Communication
- [ ] HTTP communication between services
- [ ] Implement service discovery
- [ ] Load balancing with HTTP
- [ ] Push code to GitHub

### Day 7 - Week 1 Revision
- [ ] Test all services locally
- [ ] Document service APIs
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: Node.js Microservices Complete**

---

## Week 2: RabbitMQ Deep Dive

### Day 8 - RabbitMQ Setup
- [ ] Install RabbitMQ locally
- [ ] Learn exchanges, queues, bindings
- [ ] Learn message acknowledgment
- [ ] Use RabbitMQ management UI
- [ ] Push notes to GitHub

### Day 9 - Python + RabbitMQ
- [ ] Install `pika` library
- [ ] Connect Python to RabbitMQ
- [ ] Send messages
- [ ] Receive messages
- [ ] Push code to GitHub

### Day 10 - Node.js + RabbitMQ
- [ ] Install `amqplib` library
- [ ] Connect Node.js to RabbitMQ
- [ ] Send messages
- [ ] Receive messages
- [ ] Push code to GitHub

### Day 11 - Work Queues
- [ ] Implement task distribution
- [ ] Multiple workers
- [ ] Fair dispatch
- [ ] Message durability
- [ ] Push code to GitHub

### Day 12 - Publish/Subscribe
- [ ] Implement fanout exchange
- [ ] Implement topic exchange
- [ ] Implement direct exchange
- [ ] Routing patterns
- [ ] Push code to GitHub

### Day 13 - RPC Pattern
- [ ] Implement RPC with RabbitMQ
- [ ] Request-reply pattern
- [ ] Correlation IDs
- [ ] Timeouts
- [ ] Push code to GitHub

### Day 14 - Week 2 Revision
- [ ] Build mini "Message Broker API"
- [ ] Test all patterns
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: RabbitMQ Complete**

---

## Week 3: API Gateway

### Day 15 - Gateway Design
- [ ] Design API Gateway architecture
- [ ] Authentication/Authorization
- [ ] Rate limiting
- [ ] Request routing
- [ ] Response aggregation
- [ ] Create design document
- [ ] Push to GitHub

### Day 16 - Gateway Setup (Node.js)
- [ ] Create Fastify API Gateway
- [ ] Load service configurations
- [ ] Implement health checks
- [ ] Push code to GitHub

### Day 17 - Routing Middleware
- [ ] Implement dynamic routing
- [ ] Route to appropriate service
- [ ] Path rewriting
- [ ] Load balancing
- [ ] Push code to GitHub

### Day 18 - Authentication Middleware
- [ ] Validate JWT tokens
- [ ] Extract user info
- [ ] Role-based permissions
- [ ] Pass user context to services
- [ ] Push code to GitHub

### Day 19 - Rate Limiting
- [ ] Implement rate limiting in Gateway
- [ ] Use Redis for rate limiting
- [ ] Per-user limits
- [ ] Per-route limits
- [ ] Push code to GitHub

### Day 20 - Logging & Monitoring
- [ ] Implement request logging
- [ ] Implement metrics collection
- [ ] API analytics
- [ ] Push code to GitHub

### Day 21 - Week 3 Revision
- [ ] Test Gateway with services
- [ ] Performance testing
- [ ] Push everything to GitHub
- [ ] **Weekly Milestone ✅: API Gateway Complete**

---

## Week 4: Integration & Testing

### Day 22 - Service Registry
- [ ] Implement service registry in Redis
- [ ] Service registration on startup
- [ ] Service heartbeat
- [ ] Service discovery
- [ ] Push code to GitHub

### Day 23 - Connect Services
- [ ] Connect all services to Gateway
- [ ] User Service (Node.js)
- [ ] Task Service (Node.js)
- [ ] FastAPI User Service (Python)
- [ ] Celery workers (Python)
- [ ] Push code to GitHub

### Day 24 - End-to-End Testing
- [ ] Test user registration flow
- [ ] Test login flow
- [ ] Test task submission
- [ ] Test task status
- [ ] Test all routes
- [ ] Push tests to GitHub

### Day 25 - Error Handling
- [ ] Global error handling in Gateway
- [ ] Retry mechanism
- [ ] Circuit breaker
- [ ] Fallback routes
- [ ] Push code to GitHub

### Day 26 - Performance Testing
- [ ] Install Artillery/Locust
- [ ] Load test Gateway
- [ ] Test concurrent users
- [ ] Monitor metrics
- [ ] Optimize bottlenecks
- [ ] Push results to GitHub

### Day 27 - Deployment
- [ ] Deploy all services on Render/Railway
- [ ] Deploy RabbitMQ on CloudAMQP
- [ ] Deploy Redis on Redis Cloud
- [ ] Update environment variables
- [ ] Test production deployment
- [ ] Push config files

### Day 28 - Month 4 Wrap-up
- [ ] Revise all Month 4 topics
- [ ] Complete FYP API Gateway
- [ ] Write Month 4 reflection
- [ ] Update main README
- [ ] Push everything to GitHub
- [ ] **🎉 Month 4 Complete!**

---

## 🎯 FYP Checkpoint: Month 4

### FYP Components Completed:
- ✅ API Gateway (Node.js)
- ✅ All microservices
- ✅ RabbitMQ communication
- ✅ Service discovery
- ✅ Rate limiting & logging
- ✅ End-to-end integration

### Next Month:
- Containerize everything with Docker
- Deploy with Kubernetes
- CI/CD pipeline

---

## 🚀 Deployment Resources

- [CloudAMQP (RabbitMQ)](https://www.cloudamqp.com/)
- [Redis Cloud](https://redis.com/redis-enterprise-cloud/)
- [Render](https://render.com/)
- [Railway](https://railway.app/)

---

## 📝 Month 4 Notes

*Add your daily learning here*

---

**Next: Month 5 → Docker & Kubernetes 🚀**
