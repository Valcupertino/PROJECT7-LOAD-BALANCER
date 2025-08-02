### Scalability and Future Improvements

* **Auto Scaling**: Add EC2 Auto Scaling groups to automatically add/remove web servers based on traffic
* **Monitoring**: Integrate with AWS CloudWatch for performance metrics
* **SSL/TLS Support**: Add HTTPS using Let’s Encrypt or AWS Certificate Manager
* **L4 Load Balancing**: Use AWS ELB (Elastic Load Balancer) for Layer 4/7 advanced routing

---

### **Conclusion**

Through this implementation, we've created a highly available and scalable web infrastructure using open-source tools on AWS. Apache serves as a cost-effective and powerful Layer 7 load balancer that efficiently distributes traffic across multiple web servers. This architecture not only enhances performance but also ensures reliability and resilience as your traffic scales.