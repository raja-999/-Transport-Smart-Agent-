# 🚇 Transport Smart Agent  
### Chatbot + n8n + FastAPI + NSGA-II (Portfolio Project)

---

## 🎯 Goal

This project builds an intelligent agent that recommends the best transport mode to a user based on:

- Distance to school  
- Age  
- Current mode  
- Car / Bike ownership  
- Preferences (comfort, cost, environment, punctuality)

Pipeline:

1. User fills a transport form  
2. n8n receives the form  
3. n8n sends the data to a FastAPI backend  
4. The API runs a simplified NSGA-II model  
5. The chatbot returns a personalized recommendation  

---

## 🗂 Project Structure

