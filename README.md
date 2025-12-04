# ⭐ Flex — Multi-Tenant ERP Built with Django

**Flex** is a lightweight, modular ERP built with **Python/Django**, designed to offer an affordable and customizable management solution for small and medium-sized businesses in Côte d’Ivoire. Its purpose is to deliver essential business tools to SMEs and service companies without the complexity of traditional enterprise systems.

Flex uses a **schema-based multi-tenant architecture**, where each client (tenant) has its own PostgreSQL schema. This provides clear data isolation, improved security, and the ability to customize features per tenant when needed. Access to each tenant environment is handled via **subdomain-based routing**, such as `client.flex.com`, ensuring a clean and intuitive separation.

In production, Flex relies on a modern containerized stack using **Docker**, with **Gunicorn** as the WSGI server and **Nginx** acting as the reverse proxy for routing and SSL termination. This setup ensures stability, consistent deployments, and smooth scalability for multiple client instances.

Core features include **Sales**, **Billing**, **Human Resources**, and **Client Management**, covering the essential operational needs of most SMEs and service-oriented structures. Thanks to its Django foundation, new modules and customizations can be added quickly and safely.

Flex’s mission is simple: provide a robust, accessible ERP that adapts to local business realities while remaining easy to deploy, maintain, and extend.

---

Live demo 
👉 ![FLexLiveDemo]()(http://demo.flextls.tech)
