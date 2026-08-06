# High availability and scalability

- When you're deploying an application, a service, or any IT resources, it's important the resources are available when needed.
- High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.
- SLA = (Azure) Service Level Agreement
  - uptime guarantees depending on the service

<img width="951" height="687" alt="image" src="https://github.com/user-attachments/assets/9c0bd68f-6208-4084-ad26-7471b3450e39" />


- Another major benefit of cloud computing is the **scalability** of cloud resources.
  -  ability to adjust resources to meet demand
  - you only pay for what you use
- **Vertical Scaling**
  - focused on increasing or decreasing the capabilities of resources
  - add more CPUs or RAM to the virtual machine
  - Lisätään tehoa yhdelle palvelimelle
- **Horizontal Scaling** 
  - adding or subtracting the number of resources
  - add additional virtual machines or containers
  - Lisätään useita palvelimia jakamaan kuormaa.

<img width="1041" height="732" alt="image" src="https://github.com/user-attachments/assets/7d3ad2d9-0e6d-4ea0-8fa2-96c6245f441a" />

--- 

# Reliability and predictability

- **Reliability** is the ability of a system to recover from failures and continue to function
  - decentralized design = the cloud enables you to have resources deployed in regions around the world
  - if one region has a catastrophic event other regions are still up and running

<img width="1082" height="776" alt="image" src="https://github.com/user-attachments/assets/3962d0b8-3690-41d3-b08b-d7f8a13ab933" />


- **Predictability** in the cloud lets you move forward with confidence
  - Predictability can be focused on **performance** predictability or **cost** predictability
  - **Performance**
    - focuses on predicting the resources needed to deliver a positive experience for your customers
    - Autoscaling, load balancing, high availability
    - If you suddenly need more resources, autoscaling can deploy additional resources to meet the demand, and then scale back when the demand drops
    - if the traffic is heavily focused on one area, load balancing will help redirect some of the overload to less stressed areas
  - **Cost** 
    - focused on predicting or forecasting the cost of the cloud spend
    - rack your resource use in real time
    - monitor resources to ensure that you’re using them in the most efficient way
    - apply data analytics to find patterns and trends that help better plan resource deployments

<img width="1084" height="664" alt="image" src="https://github.com/user-attachments/assets/609e179e-ed2d-43c1-b24b-c8c28737312a" />

--- 

# Security and governance

<img width="1089" height="486" alt="image" src="https://github.com/user-attachments/assets/22305f62-b980-47ed-988d-92ba44a70db4" />

--- 

# Manageability

Voidaan jakaa kahteen osaan: **Management of the Cloud** ja **Management in the Cloud**

**Management of the cloud** speaks to managing your cloud resources. In the cloud, you can:
*   Automatically scale resource deployment based on need.
*   Deploy resources based on a preconfigured template, removing the need for manual configuration.
*   Monitor the health of resources and automatically replace failing resources.
*   Receive automatic alerts based on configured metrics, so you're aware of performance in real time.

<img width="582" height="350" alt="image" src="https://github.com/user-attachments/assets/e7fe056b-40fd-4b1c-b90f-49527618cdc9" />


Management in the cloud speaks to how you're able to manage your cloud environment and resources. You can manage these:
*   Through a web portal.
*   Using a command line interface.
*   Using APIs.
*   Using PowerShell.
For example, an operations team can deploy resources from templates, monitor health in the portal, and automate recurring tasks with CLI or PowerShell scripts. This combination reduces manual effort and helps maintain consistent configurations.

<img width="571" height="343" alt="image" src="https://github.com/user-attachments/assets/b9c8360a-49f7-463b-9e53-ccfbb14ebdb8" />

# Sustainability considerations
