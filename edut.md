# High availability and scalability

- When you're deploying an application, a service, or any IT resources, it's important the resources are available when needed.
- High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.
- SLA = (Azure) Service Level Agreement
  - uptime guarantees depending on the service

![image.png](/.attachments/image-66ee6e50-b5bf-4788-a6e2-ead5b1560b7f.png)

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

![image.png](/.attachments/image-61b771c9-165c-429c-8ca7-e68ee9900cd1.png)

--- 

# Reliability and predictability

- **Reliability** is the ability of a system to recover from failures and continue to function
  - decentralized design = the cloud enables you to have resources deployed in regions around the world
  - if one region has a catastrophic event other regions are still up and running

![image.png](/.attachments/image-8c1a9f1c-1a5f-40db-b611-fcfcaf13cee4.png)

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

![image.png](/.attachments/image-1c011e53-d3db-4639-8fc1-08613a3db9af.png)

--- 

# Security and governance

![image.png](/.attachments/image-f6ad643f-b9ee-4aa7-830e-5f108d684d37.png)

--- 

# Manageability

Voidaan jakaa kahteen osaan: **Management of the Cloud** ja **Management in the Cloud**

**Management of the cloud** speaks to managing your cloud resources. In the cloud, you can:
*   Automatically scale resource deployment based on need.
*   Deploy resources based on a preconfigured template, removing the need for manual configuration.
*   Monitor the health of resources and automatically replace failing resources.
*   Receive automatic alerts based on configured metrics, so you're aware of performance in real time.

![image.png](/.attachments/image-3b294c92-c90b-42c8-93c6-3703df2b2eb8.png)

Management in the cloud speaks to how you're able to manage your cloud environment and resources. You can manage these:
*   Through a web portal.
*   Using a command line interface.
*   Using APIs.
*   Using PowerShell.
For example, an operations team can deploy resources from templates, monitor health in the portal, and automate recurring tasks with CLI or PowerShell scripts. This combination reduces manual effort and helps maintain consistent configurations.

![image.png](/.attachments/image-92eae092-3940-4185-9d42-79bc1757abbe.png)

# Sustainability considerations
