# 17-Get-started-with-Azure-Stream-Analytics
In this exercise you'll provision an Azure Stream Analytics job in your Azure subscription, and use it to query and summarize a stream of real-time event data and store the results in Azure Storage.

---

## 🧠 Objectives

- Provision an Azure Event Hub to simulate incoming event data.
- Create an Azure Stream Analytics job to process the event stream.
- Configure input, query, and output for the analytics job.
- Store the summarized results in Azure Blob Storage.

---

## 🛠️ Prerequisites

- An active Azure subscription
- Azure CLI or Azure Portal access
- Basic familiarity with Azure resources (Event Hubs, Storage, Stream Analytics)

---

## 🚀 Steps

### 1. Create an Azure Event Hub

- Create a **Resource Group** (if not already created).
- Provision an **Event Hubs namespace**.
- Add an **Event Hub** inside the namespace.
- Generate a **shared access policy** with `Send` and `Listen` permissions.

### 2. Create a Storage Account

- Provision an **Azure Storage account**.
- Create a **container** to store Stream Analytics output.

### 3. Simulate Event Data

- Clone the lab repo:
  ```bash
  git clone https://github.com/MicrosoftLearning/dp-203-azure-data-engineer.git
  cd dp-203-azure-data-engineer/Allfiles/Labs/17


---



## Screenshot

![lab17](https://github.com/user-attachments/assets/6a06c0e1-51f4-4046-b6c6-b017bf341431)
![lab172](https://github.com/user-attachments/assets/c3bc15ee-d9c6-4c5d-8657-4e307f347ef0)
![lab173](https://github.com/user-attachments/assets/09933c49-342f-4316-b76e-3d53d60f7054)
![lab174](https://github.com/user-attachments/assets/5f6d089c-38bf-445e-812f-03bc10814026)
![lab175](https://github.com/user-attachments/assets/762c42e5-ec72-4118-9fef-3af20e4f7f87)
![lab176](https://github.com/user-attachments/assets/64fc1de6-a631-4f44-b420-f8b4c37deb66)
![lab176code](https://github.com/user-attachments/assets/a5fc03c4-0875-4fb6-a029-06936bf3c035)
![lab177conteiners0](https://github.com/user-attachments/assets/db5910e2-c49a-4972-bdce-63f638b5034c)
![lab177conteiners](https://github.com/user-attachments/assets/c666c636-817f-425d-9579-5ab6d079d37f)
![lab177conteiners2](https://github.com/user-attachments/assets/0247d07e-af84-42b2-b296-56f032d4a91b)
