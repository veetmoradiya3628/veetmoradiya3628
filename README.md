# Hi there 👋 I'm Veet Moradiya

<p align="left">
  <img src="https://img.shields.io/badge/Status-Online-success?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Bengaluru-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Role-Full--Stack%20Engineer-orange?style=flat-square" />
</p>

### ☁️ System Configuration (k8s-manifest.yaml)

```yaml
apiVersion: v1
kind: Developer
metadata:
  name: veet-moradiya
  labels:
    role: full-stack-engineer
    specialization: cloud-native-engineering
    location: bengaluru-in
    focus: distributed-systems

spec:
  containers:
  - name: main-stack
    image: mern/spring-boot:latest

    ports:
    - containerPort: 4200 # Angular Frontend
    - containerPort: 8080 # Spring Boot / Go / Node Backend
    - containerPort: 5000 # Real-time Services

    env:
    - name: PASSION
      value: "building-scalable-systems"

    - name: CORE_TECH
      value: "JavaScript, TypeScript, Go, Java, Python"

    - name: FRONTEND
      value: "Angular, React, RxJS, Tailwind"

    - name: BACKEND
      value: "Node.js, Spring Boot, Go"

    - name: DATABASES
      value: "PostgreSQL, MySQL, Redis"

    - name: CLOUD
      value: "Google Cloud Platform"

    - name: DEVOPS
      value: "Docker, Kubernetes, GitHub Actions"

    - name: ARCHITECTURE
      value: "Microservices, Event-Driven Systems"

    - name: INTERESTS
      value: "Distributed Systems, System Design, Cloud Internals"

    - name: CURRENT_PROJECTS
      value: "Kubernetes, Go, System Design Prototypes"

    - name: LEARNING_GOAL
      value: "Mastering Distributed Systems"

    - name: CURRENT_STATUS
      value: "Busy Coding"

    resources:
      requests:
        cpu: "500m"
        memory: "512Mi"

      limits:
        cpu: "2"
        memory: "2Gi"

status:
  phase: Running

  achievements:
    - REST API Development
    - Cloud-Native Applications
    - Dockerized Microservices
    - CI/CD Automation
    - Kubernetes Deployments
    - Real-Time Systems

  roadmap:
    - Distributed Systems Engineering
    - Database Internals
    - Kubernetes Internals
    - Cloud Platform Architecture
    - System Programming
```
