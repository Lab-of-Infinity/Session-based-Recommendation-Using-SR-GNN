> ## **Session-based Recommendation Using SR-GNN**
- ***In this project we are building Session Based Recommendation system Using Graph Neural Network.***
- ***We have used real world E-comm data which available on Kaggle : Retail Rocket Dataset.***
- ***For Implementing Graph Neural Network we have utiliesd PyGeometric Package which build on top of Pytorch.***

- ***Author : Lokesh Baviskar***
- ***Email Id : lokeshbaviskar4@gmail.com***

---

- **On gross level Project flow as below:**

    *1. Constructing Session Graphs*

    *2. Learning Item Embeddings on Session Graphs*

    *3. Generating Session Embeddings*
    
    *4. Making Recommendation and Model Training*

### Data Set Information

- We Have Utilised **Retail Rocket Dataset ( Which is real world data collected from ecommerce platform ) for building Session Based Recommender**.
- You can download the data from 🔗[this kaggle competition](https://www.kaggle.com/retailrocket/ecommerce-dataset). 
- The behaviour data, i.e. events like clicks, add to carts, transactions, represent interactions that were collected over a period of 4.5 months. 
- A visitor can make three types of events, namely “view”, “addtocart” or “transaction”.
-  **In total there are 2,756,101 events** including 2,664,312 “view”, 69,332 “addtocart” and 22,457 “transaction” **produced by 1,407,580 unique visitors.** 
- The file with item properties includes 20,275,902 rows, i.e. different properties, describing 417,053 unique items.
- **We will only use the `events.csv` file.**


![image](https://user-images.githubusercontent.com/90597433/232551930-1c72243b-d80e-452b-b1c9-fc5fd9918b80.png)
