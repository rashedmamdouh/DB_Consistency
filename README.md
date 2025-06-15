# Cosmos DB Consistency Experiment
A Practical Study on Performance, Cost, and Data Accuracy Trade-offs in Geo-Distributed Databases Using Different Consistency Levels: A Case from E-Commerce


This project demonstrates a simple performance test on **Azure Cosmos DB** using Python.  
It simulates part of an e-commerce application and measures the latency of read operations under a given consistency level.

## 📌 What It Does

- Creates a **product item**
- Creates an **inventory record** for that product
- Performs multiple **read queries** on the product catalog
- Updates the inventory (simulating a purchase)
- Logs **read latency** and the update result

---

## 🛠️ Technologies Used

- Python 3
- Azure Cosmos DB SDK (`azure-cosmos`)
- Azure Cosmos DB SQL API

---

## 💻 Code Structure

```bash
📦cosmos-db-consistency-test/
 ┣ 📜main.py              # Main code to run simulation
 ┣ 📄README.md            # This file
