## **Technical Challenge**

**Introduction**

This exercise aims to evaluate how you articulate your ideas. Please outline all identified trade-offs in advance and provide reasoning for your responses.

**Exercise**

We have an API service deployed on two different cloud providers (AWS and GCP) that relies on a relational database. Both the API and database are hosted in Kubernetes. The setup is currently in an active-passive configuration, meaning only one provider is operational at any given time.
There are no restrictions on tools; feel free to utilize any resources you need to address the challenges and leverage existing solutions where applicable.


![Challenge](challenge.png =300x300)

---

1. Which database would you choose?
2. How would you manage deployments?
3. What approach would you take for backups?
4. How would you implement monitoring?
5. Identify any potential gray areas that could affect functionality and propose solutions.
6. If we want to transition to an active-active scenario, what modifications would be necessary?
