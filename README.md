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
    specialization: cloud-enthusiast
    location: bengaluru-in
spec:
  containers:
  - name: main-stack
    image: mern/spring-boot:latest
    ports:
    - containerPort: 4200 # Angular Frontend
    - containerPort: 8080 # Spring Boot / Go / Node Backend
    - containerPort: 5000 # Socket.IO / Real-time
    env:
    - name: PASSION
      value: "building-scalable-systems"
    - name: CORE_TECH
      value: "JavaScript, TypeScript, Go, Java, Python"
    - name: LEARNING_GOAL
      value: "mastering-distributed-systems"
    - name: CURRENT_STATUS
      value: "busy-coding"
