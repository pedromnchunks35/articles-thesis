# Notes
- The paper brings into quesiton whether information systems should be centralized or decentralized to support business processes
- IBM research and development in the early ages of computing, the estimation was that three or possibly four big mainframes would give enough computing capacity for the industrialized world
- The MIsConcept in the 1960s (between 1965 and 1970)
  - They were developing a large project to support the total organization with a single system, generally referred to as the "management information system"
  - The Professor of the author hesitated, with the argument that total management systems will fail
  - This professor had a view between directive and local information and he argued the split between what we today refer as executive systems and systems to support local operations
  - He defended the creation of subsystems instead of total system approach
- Examples of centralized systems
  - VLDB in the 1970s
    - The assumption that each company must have one total database and methods were developed to handle the large data base to support the total organization
    - VLDB (Very large databases) conferences were arranged all over the world
  - The search for a total integrated conceptual model in the 1980s
    - This was after the focus on technical databases
    - Data modeling and the conceptual modeling became the dominant paradigms
    - People started to understand that it was not suitable to have all data processing in one system
    - Now different systems should refer to a central data model that refer to either a central database or a set of centrally controlled databases
    - This is still a centralized view, even with a number of systems
    - There is much dependencies between the different systems
    - They realized that for complex organizations it was not suitable to incorporate all the logic in a single place but instead having multiple projects for multiple enterprise scopes
    - In 1989 an IFIP conference on information systems in Belgium got has its main theme ways to integrate conceptual models(Integration of Information Submodels,levels of abstraction and discussion of decentralization of these submodels) where decentralization of these submodels was rejected
- The Emergence of Decentralized Information Systems
  - At 1970s when minicomputers and microcomputers began to be available at reasonable prices, the scene changed
  - Enterprises started to have their own infrastructure 
  - In healthcare this resulted in a lot of software island and the systems had no relation between them and a lot of those systems we had to enter basic data several times and the doctor couldnt see a total view of patient's medical record
  - In 1982 Professor Börje Langefors presented a report on Four Cases with decentralized management and local computers and also released another report where he discussed integrated versus decentralized information resource Management
  - This professor addresses a solution both to support users with local information from local systems, which exchange what langefors calls translocal information and at the same time maintain independence between these local systems
- The Problem and Principle of Independence between systems
  - In this paper they say decentralization define the basic demand for independence
  - Changes in one system should not create changes in another systems that support other business unit
  - 1 condition for interpendence is that each local system is delineated to support only a specified business unit
    - CRM supports the sales from the very beginning of a customer relation and holds all necessary information for the sales process until the company invoices the deliveries. The LOGistics systems contains modules for warehousing and delivery planning and supports logistics until a delivery order is completed
    - These are independent of each other but they do not interact
    - They are still two information islands
    - To be decentralized and not becoming islands we need to create communication between the two systems
  - This transfering of information between system was not widely discussed or used until the end of the century