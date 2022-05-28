## Description 

- **Create Data Ware House with Analysis Cube and Analysis Report and mdx query  using Bike Stores  Database**

------------
## Team members
- Abdulrahman Ragab Kabil
- Adhm Magdy
- Esraa Ragab
- Omar Hany
- Sara Alaa

------------


## DWH Goal:-
- We are creating the (“OrdersFact”) star schema for people who want to see the number of orders and quantity for all items ordered by a specific customer, in a specific store, within a specific category at a specific time (month - year)

**example:**
> customer of id=1 make number of orders in year=2020 that contain products from category_id=2 and from store_id=3 and these number of orders =5 and the quantity of items that he bought in all this orders =30 item


------------


### Requirements
- Microsoft Server 2019 developer edition (database engine - analysis server - report server)
- Microsoft Visual studio 2015 with business intelligence Package
- Microsoft excel 
- Report Builder

------------
### The project implementation Process

##### 1. setup "bikeStores" database on your database engine
##### 2. create ERD Database Schema
![Screenshot 2022-05-28 163231](https://user-images.githubusercontent.com/63946776/170831816-00a49269-3806-4cda-847f-e2e1ded8fc24.png)
##### 3. create DWH star schema based on your goal
![Screenshot 2022-05-28 163254](https://user-images.githubusercontent.com/63946776/170831883-6eb48117-5f4a-4ba1-a4e9-d640c88c7b4a.png)
##### 4. create New database  "bikestoresDWH" with your star schema tables
##### 5. start Extracting process **from**"bikeStores"**to** "bikeStoresDWH"
##### 6. create new Project in VS (**ananlysis services** Project type)  
##### 7. create your Cupe and hierarchies

![Screenshot 2022-05-28 175002](https://user-images.githubusercontent.com/63946776/170832822-4a18c937-1ec7-4a6f-80be-6ffe2761c799.png)


##### 8. process Cupe in your **data analysis server** 
##### 9. open your data analysis server you'll find Cupe and can create MDX queries 

![Screenshot 2022-05-28 175638](https://user-images.githubusercontent.com/63946776/170833062-4a29e7e5-5bb9-49cc-83fc-92290fe54608.png)

##### 10. create report and charts using excel and VS Report and Report Bulider app
- **excel Report and Chart**
![Screenshot 2022-05-28 175940](https://user-images.githubusercontent.com/63946776/170833167-8766eefa-1812-430c-a01d-7c0758c456a8.png)

- **VS Report**
![Screenshot 2022-05-28 180134](https://user-images.githubusercontent.com/63946776/170833238-947b53db-3732-4e23-b3b0-b77544668f0f.png)

- **Chart**
![Screenshot 2022-05-28 180307](https://user-images.githubusercontent.com/63946776/170833291-423e1f85-d971-4eb1-add8-5f8059db497a.png)










