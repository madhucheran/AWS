![Time flies](https://quotefancy.com/media/wallpaper/800x450/6442742-Michael-Altshuler-Quote-The-bad-news-is-time-flies-The-good-news.jpg)

Hi everyone and now in this post I will be talking about the "Types of TIERS"
***
># Types Of Tiers
* 1-Tier
* 2-Tier
* 3-Tier

># 1-Tier Architecture
* In this tier , all components are located on a single machine. It is simple to implement but lacks scalability (Monolithic)
* A one-tier architecture refers to a system design where all components, including data, applications, and user interfaces, are located in a single process or container.
* This architecture is simple and easy.
># 2-Tier Architecture
* In this Tier the Database will be separated from both Business Logic Layer (BLL) and Presentation Layer(PL).
* It has a clear separation between data access (DB) and business logic.
* The DB server acts as an independent module that provides services to other modules through APIs.
># 3- Tire Architecture
***
### 1. The Presentation Tier(PL)
### 2. The Application Tier or Business Logic layer(BLL)
### 3. The Data Access Tier

># The Presentation Tier
***
* This Tier is responsible for the User Interface which is basically build by HTML,CSS,JS or React.js or Angular.js or any frontend development tools. This is the layer where the user will enter any information through website or web-based application 
* This layer will communicate to the Applcation TIER using Application Programming Interfaces (APIs).
***

># The Appliction Tier
***
* The Application Tier is responsible for processing requests from users, interacting with databases or other data sources, performing calculations, and generating responses that are sent back to the user's browser.
* This Tier is also called as Logical Tier
* It contains business logic, rules and algorithms that process data from the user or other systems.
* Communicates with both the Presentation Tier and the Data Access Tier.
* This Tier will be hosted in the Cloud or on the company's server depending upon the requirements.
***

># The Data Access Tier
* This tier contains of Database and the program for managing read and write operations from the database.
* This Tier is also called as the Storage Tier
* It can be also hosted On-premise or in the cloud
* Popular Tools for managing read/write access include MySQL, PostgreSQL etc., NoSQL databases such as MongoDB are also used.

># Advantage
***
* Horizontal scalability  - you can add more resources to handle a larger number of requests by adding servers/instances to a system 
* If somethig is changed in one tire, another tires will not get affected
* Reduces dependency among different components
* Improves the performance of the application by reducing network latency

># Disadvantage
***
* More complex to implement compared to 1-tier architecture
* Increases cost due to multiple servers/instances needed for each tier
* Debugging becomes more difficult if there are issues at any level
[Back To Top](#table-of-contents)