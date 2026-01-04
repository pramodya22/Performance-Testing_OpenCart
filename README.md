# OpenCart Performance Testing using Apache JMeter

This project focuses on performance testing of an OpenCart e-commerce application using Apache JMeter.  
The objective is to evaluate system behavior under different load conditions and analyze performance metrics such as response time, throughput, latency, and error rate.

---

## 📌 Project Overview

OpenCart is an open-source e-commerce platform widely used for online stores.  
Since e-commerce applications handle multiple concurrent users, performance testing is critical to ensure reliability, scalability, and stability.

In this project, Apache JMeter is used to perform various performance tests on an OpenCart application deployed on a local server.

---

## 🎯 Objectives

- To perform performance testing using Apache JMeter  
- To analyze response time, throughput, and error rate  
- To identify system behavior under different load levels  
- To evaluate application stability under stress and long-duration usage  

---

## 🧪 Types of Testing Performed

### 1. Functional Testing
- Verifies that key pages respond correctly
- Validates HTTP response codes and assertions

### 2. Load Testing
- Tests application performance under expected user load
- Measures average response time and throughput

### 3. Stress Testing
- Pushes the system beyond its capacity
- Identifies breaking points and failure behavior

### 4. Spike Testing
- Sudden increase in user load
- Observes system recovery and stability

### 5. Endurance (Soak) Testing
- Long-duration testing
- Detects memory leaks and performance degradation over time

---

## 🛠 Tools & Technologies Used

- Apache JMeter
- OpenCart
- PHP
- MySQL
- Localhost XAMPP
- Windows OS

---

## ⚙ Test Environment

| Component | Description |
|--------|------------|
| Operating System | Windows |
| Testing Tool | Apache JMeter |
| Application | OpenCart |
| Server | Localhost |
| Database | MySQL |

---

## 📊 Performance Metrics Analyzed

- **Response Time** – Time taken to complete a request  
- **Latency** – Delay before server starts responding  
- **Throughput** – Number of requests handled per unit time  
- **Error Rate** – Percentage of failed requests  

---

---

## 📈 Results Summary

- The application performed well under moderate load
- Response time increased significantly during stress testing
- Errors occurred when user load exceeded server capacity
- System remained stable during endurance testing with low concurrency

---

## ⚠ Limitations

- Testing performed only on localhost
- Real network latency not considered
- Limited hardware resources

---

## 🚀 Future Enhancements

- Distributed JMeter testing
- Cloud-based load testing
- CI/CD pipeline integration
- Security and penetration testing
- Real-time monitoring using Grafana

---

## 📚 References

- Apache JMeter Documentation  
- OpenCart Official Documentation  
- Software Testing Concepts and Practices  

---



