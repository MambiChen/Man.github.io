# Info Tech In Business Society

#### **Session1. Value of IT**

**Case1: IT System of Ferrari - Behind the production**

- Comprehensive Information System - **ERP system (enterprise resource planning)** which supports production process
- Outsource IT solution - **Infor** which is a software supplier
- **Software suppliers eg: IBM, SAP...** 



**Key Components of Information Systems**

```
Information System = Hardware + Operating System + Software + Data + Business Process
```

![image-20230527171638488](/Users/anastasia/Library/Application Support/typora-user-images/image-20230527171638488.png)

- Hardware - Tangible device, takes Input
- OS - managed by Hardware
- Software - Eg. SQL language, infor
- Data - created by Software
- Business processes - structured by Data



**Eg: IT System - NBA's partnership with SAP**

- Software SAP provides real time data & updates for NBA's **<u>livestream</u>**.



**Case2: Metropolitan Opera House - MET's Challenge**

- **Value Chain** -  can consist of multiple stages of a product or service's lifecycle from R&D, sales, and everything in between.
- Met's case: a vicious cycle (limited value for investors, limit budget, shrinking viewership)
- Solution: IT for live streaming
- **IT as strategic necessity**



**Case3: Nasdaq & Facebook IPO - IT in financial market**

- **Financial Market** - significant shift from traditional floor trading to electronic trading systems (stock & trade company)

- **Initial Public Offereing IPO** - the first time shares of a company are sold to the general public (goes public), on a securities exchange

- HOWEVER, Nasdaq system crashed, but trade resumed

- What should companies do after the IPO - need backup system!!

  ```
  Short term <1wk: Technical fix
  Medium term 1wk-1m: contingency planning, improving backup system
  Long term >1m: Investment in tech and management, ongoing upgrade and test of the system, external auditing
  Overall: rethinking the IPO strategies and culture of the organization
  ```

- Nasdaq: a tech company with capital market roots

- Summary: IT issues = Business issues; companies should balance cost with perfomance (Benefit & Risk)

**Case4: Zara - Fashion & retail**

- **Characteristics:**
  - **Organization - Decentralized & Autonomy**
  - **Operation - vertical integration (controlling its own value chain)**
  - **Culture - human-centered. Efficiency > Accuracy**

- **4P Marketing Mix Model - Price & Product & Promotion & Place** 

  ```
  Zara: 
  Price: mid-range; 
  Product: trendy but low durability; 
  Promotion: doesn't rely on traditional advertising; 
  Place: high-trafic locations; 
  ```

- **Company's Internal structure should be well aligned with the company's overal strategy**

- **Zara's IT system: DOS -** a family of disk **<u>operating systems</u>** introduced in the 1980s for **personal computers (PCs)**

  - High stability, but hard to operate (need to memorize the commands)

- **Q: Should Zara upgrade its system?**

  - **Zara postponed its upgrade until the pandemic period, in a way to gain competitiveness over other companies / Turnaround. Also, current IT system was enough to operate.**

- **IT Strategic Alignment Model - Strategy & System & Structure**

  - **How firm should make decision with IT system**
  - **What role IT plays in company**

  ```
  Zara:
  Structure: Organization - Operations - Culture
  Strategy: Position - Purpose - Plan
  System: Strategy -> System; System -> Strategy
  
  Notes:
  1. For Zara, it's Strategy driving the system
  2. Strategy, Structure, System need to be aligned
  ```

- **IT Strategic Grid - to conceptualize IT's roles in organizations**

  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230606155457739.png" alt="image-20230606155457739" style="zoom:50%;" />

  - **Operational Dependence:** Is firm able to operate w/o the use of IT system?

  - **Stategic Importance:** Does firm relies on IT upgrades to Turnaround? i.e. gain advantages for competitiveness.

    

---



#### Session2: Technical Foundation

**I. Information Representation**

- Information: human (natural languages & decimal system) v.s. computers (binary bits, 0's and 1's)

  **Numbers**

  ```
  Binary --> Decimal conversion:
  10011011 = 1x2^0 + 1x2^1 + 0x2^2 + 1x2^3 +...+1x2^7 = 155 
  power of 2 progressively increases from right to left
  ```

  ```
  Decimal --> Binary conversion:
  takes the remainder of 2, Remainder = binary digits
  read from bottom (MSB) up (LSB).
  ```

​		**Text**

- **ASCII:** **American Standard Code for Information Interchange** (CS)

  - Created by **ASA (American Standards Association)**

  - ASCII defines the standard for encoding characters for electronic communication

  - Binary Character Table: 

    Letter a - z: 097 ~ 122	Letter A - Z: 065 ~ 090

​		**Image**

- To Digitie an image, might encounter information loss, but as .gif .jpeg .bmp... becomes bigger, image approaches to original

- Color can be represented by a binary string. With more bits, more colors can be represented, therefore a more realistic image being represented.

- **Color depth: the number of bits per pixel on a computer monitor to represent a specific color**

  1-bit = 21 or 2 colors **(2^1)**	4-bit = 24 or 16 colors **(2^4)**	8-bit = 28 or 256 colors **(2^8)**

​		**Sound**

- regular time intervals (x-axis) , amplitude being assinged in a value (y-axis).
- original sound wave v.s. sampled sound wave
- sample is converted into a binary code
- Eg. Microphone (Analog signal) -> **Analog-to-signal converter A/D** -> Digital signal processor -> **Digital-to-analog converter D/A** -> Analog signal

​		**Video**

- digital video consists of static images played consecutively at a high speed

- Typically: 24 frames / sec; if too high **(hyperealistic)**, visually feels dizzy 

  - Human brain can not process more than **48 fps**

- **How much hard drive memory (in Byte) is required to store a movie?**

  ```
  Standard definition
  	Resolution: 720 * 480 pixels 
  	Frames Per Second = 24
  	n hours long eg. n=2
  	Color Depth - assume 30 bit color(2^30 possible colors)
  1 Byte = 8 bits
  
  (720 x 480)pixels/frame x 24fps x (2x60x60)sec x 30 bits/pixel/8 = 2.2*10^11 bytes
  ```

  

**II. Information & Hardware**

 - computer represents information in **binary codes**:

 - Transistor:

    - small semiconductor electr onic device, with at least two input contacts and one output, operating essentially like a switch

   - comput ers process and store data using sequences of on/off = Strings of bits **1's and 0's**

     <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230528210750732.png" alt="image-20230528210750732" style="zoom:30%;" /><img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230531115536750.png" alt="image-20230531115536750" style="zoom:25%;" />

- Integrated circuit (foundation of computers):

  - A collection of **thousands or millions** of transistors placed on a small silicon chip

  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230528210826974.png" alt="image-20230528210826974" style="zoom:30%;" />

- Foundation of computers

  - Transistors are the fundamental building block of modern electronic computers.
  - **More transistors on a chip** means more powerful chips and computers.

- **Moore's Law** 

  - Gordon Moore, one of the co-founders of Intel, in 1965

  - Moore predicted that the number of transistors on a given chip would double approximately every two years, leading to *exponential growth* in computing power.

  - **Does it reach to a limit? Does it worth further advancement?**

    https://www.unite.ai/moores-law/

    <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230606153716348.png" alt="image-20230606153716348" style="zoom:50%;" />

    ```
    - Firms (developers) can plan ahead and develop better devices that match these upcoming more powerful chips
    - developers eg. IBM, Apple, Google, Yahoo, Sap
    - software companies eg. Intel
    ```

    - LIMITS?

      ```
      Argument: Moore's Law is dead
      Counter: new materials that goes around physical limitation 
      ```

      <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230531131431775.png" alt="image-20230531131431775" style="zoom:30%;" />  

    - Cloud era: collection of micro-chips (**macro** architectural  innovations)
    - Solution: combination of macro and micro to reach a breakthrough

  

  **III. Computer Architecture**

  **Basic Digital Computer Architecture** 

  (hasn't changed that much though chips have been constantly advanced)

  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230531132247228.png" alt="image-20230531132247228" style="zoom:50%;" />

- **CPU - Central Processing unit**: bridge b/t hardware and software, brain, interprets and executes software instructions, and **coordinates** the hardware devices to work together

  - Evolving: Intel 286 .. 486 ... Pentium I ... IV
  - Different firms make different cpu

  **Memory Devices: Memory & External Storage**

- **RAM - Random Access Memory**: temporary data storage (short term memory); access to data fast; keep data and applications while computer is running.

- **External Storage (Hard Drive)**: permenant data storage; access to data is slower; CD, DVD, tape etc.

- **I/O Controllers (devices)**

  - Input device: capture info and commands from the environment

    Keyboard, mouse

  - Output device: receive the results of info-processing requests

    Screen, speaker, printer, vibration



​	**IV. OS, Software - More about softwares**

- **Operating Systems: **A set of programs that manage and run our computer (boss). Manges memory, coordinates the running of application software, controls input/output hardware.  (smilar to cpu in hardware)

  - Microsoft, Mac, Linux etc.

  -  **graphical user interface - GUI:** modern OS
  - files that work with older versions of OS should also be <u>compatible</u> with the new versions
  - Others: **open-source** (Linux) v.s. **proprietary OS** (Microsoft, Mac)

- **Softwares:**

  - **Algorithm:** Step-by-Step blueprint (flowchart), repeatitive steps, readable by humans.

  - **Program:** Also structured sequences of instructions (flowchart), computers understand

    In order to make programs, we need:

  - **Programming Languages:** eg, C++, Java, JavaScript, Python

    - The Readability / **Intuitive** of programming languages trades of with **Efficiency**
    - eg, BASIC is the first programming language

  -  **Softwares:** A set / collection of related programs that work together to fulfill a specific information processing or tasks

    - Category eg. **Application software (app), software for specific personal and commercial activities.** 

    - **Apps can be categorized as:**

      - **Vertical -** multiple functions for a specific industry 

      - **Horizontal** - specific business **functions**, multiple industries

        eg, Business Process Management software - Horizontal, can be applied to different industries.

---



#### Session 3. Database & SQL

**I. Database**

- **Database:** A structured collection or repository of data, for efficient retrieval manipulation, and management 
  - Form eg. Tables
  - 7 Database Paradig ms: 1. Key-Value database (real time caching); 2. Wide Colulmn database 3. Document **4. Relational Database - Ted Cood - SQL** 5. Graph
    - **SQL database: Schema required**, ACID (data validity guaranteed)

- **Relational Database:** in the form of **tables** (comprehensive but inefficient with repetitive data)

  - Edgar Frank Codd (1923 - 2003)

  - Digital database is based on the **relational model** of data

    - cols and rows, with a **unique identifier** for each row

    - tables can capture **entities (nouns)** and **relationships (verbs)** between entities

      - eg. Customers (entity) Buy (relationship) Books (entity)

      - rather than using a single table, splitting into multiple tables with **unique identifier for each row** ensures **efficiency**

      - each entity and relationship has a table

      - ```
        Entity table 1: Book		identifier: Book ID
        Entity table 2: Customer		identifier: Customer Name 
        Relationships table: Purchase
        w/ Book ID and Customer Name (both identifier), and attributes of purchase
        ```

    - **Entity-relationship Model (ER Model)**: abstract and conceptual representation of data in software engineering, database design, etc.

      - developed from **Peter Chen**'s paper in 1976
      - intuitive but rigorous
  - bridges business concepts w/ technical design
  
- **Entity**: a thing which is recognized as being capable of an independent existence (a "Noun")
  
- **Relationship:** captures how two or more entities are related to one another (a "verb")
  
- **Attributes:** qualify the <u>entity and relationship</u>
  
- **Cardinality:**
  
      One to N cardinality: n-1 or 1-n
      M to N cardinality: m-n or n-m
      "multiple employees belong to a company"
      "multiple employees can be a part of a project, multiple projects can be done by one employee"
      Attributes:
      Employee - SSN, Name DOB
      Works - Contract period, Position
      Company - Registration ID, Name, Address
  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230602211125800.png" alt="image-20230602211125800" style="zoom:38%;" />
  
  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230602211101722.png" alt="image-20230602211101722" style="zoom:50%;" />
  
- **Expand** on ER model: can have multiple sides, for emphasizing on a entity (split the attribute as a new entity, assign it with associated attributes), but not necessarily optimal
  
  ![image-20230604145021768](/Users/anastasia/Library/Application Support/typora-user-images/image-20230604145021768.png)
  
- **Converting ER diagram into tables:**
  
  - Purpose: easy to understand business relationships, **efficient** to retrieve info, small consumption for **storage**, and **little redundancy**
  - using graphical description of entities, relationships, and attributes as a blueprint for creating a database
  - relational databases split the data into smaller tables as an ER model

---

**II. SQL**

- Why Database and collect data? - to retrieve data

- **Querying relational databases:**

  - **Database query:** a 'question' you ask your data base
  - **view:** the **answer** will be a virtual **table**
  - **structured query language (SQL):** a foundational approach to create queries.
  -  **Operations:** Every view is a result of a combination of select, project and/or join. 
    - **select (row)** a subset of rows (records)
    - **project (column)** a subset of columns (fields)
    - **join** two tables together, using identifier

- **SQL queries pattern: SELECT columns FROM table WHERE [condition]**

  - **select:** columns
    - Display the selected columns in the view
- **where:** optional filter, not using where means to select all columns
  
  ```SQL
  sample:
  - What are in the Customers table?
  SELECT * FROM Customers 
  '*': all columns
  
  - What is the product ID and price of all products?
  SELECT Product ID, Price FROM Products
  
  - WHat are the products cheaper than $10?
  SELECT * FROM Products WHERE Price < 10
  
  - FIGURE what the question will be:
  SELECT * FROM Products WHERE Price <> 10
  A: products with price not equal to 10.
  '<>' = '!=' : not equal
```
  
#### **More operators**
  
  ```SQL
  AND: return rows when all conditions are true
  OR: return rows when any conditions is true
  '': String variables	
  	eg. WHERE City = 'Boston'
```
  
#### Functions: computational activity
  
**<u>COUNT</u>**
  
  ```SQL
  //return the number of rows (ProductId)
  SELECT COUNT(field)
  FROM [table] 
  WHERE [optional condition]
```
  
**<u>AS</u>**
  
  ```SQL
  // create a newfield
  SELECT [field(s)], [function or operation] AS [newfield]
  FROM [table]
  
  // rename the field
  SELECT [function or operation] AS [newfield]
  FROM [table] 
  
  Eg. What would the prices of the products be under 10% discount?
  (i.e create a new col taking 10% off each price)
  
  SELECT *, Prcie * 0.9 AS SalePrice FROM Products
```
  
**<u>AVG</u>**
  
  ```SQL
  //return newfield with Average
  SELECT AVG(field) AS [newfield]
  FROM [table]
```
  
**<u>ORDER BY</u>**
  
  ```SQL
  // ORDER BY _ DESC: sort records in descending order, highest value first
  // ORDER BY _ ASC: sort records in ascending order, lowest value first
  
  SELECT [field(s)]
  FROM [table]
ORDER BY [field(s)] DESC
  ```

  **<u>LIKE</u>**
  
  ```SQL
  //used in a WHERE clause to search for specified pattern in a column 
  
  SELECT [field(s)],
  FROM [table]
  WHERE Unit LIKE ’%bottles’
  
  	%x: before x //ends with
  	x%: after x //starts with
	%x%: before or after x //include
  ```

  **<u>GROUP BY</u>**
  
  ```SQL
  //groups rows with the same values of a field into a summary row
  
  SELECT [field(s)]
  FROM [table]
GROUP BY [field(s)]
  ```

  **<u>CASE</u>**
  
  ```SQL
  //goes through conditions and returns a value when the first condition is met 
  //like an if-then-else statement
  
  SELECT [field(s)],
  CASE WHEN [condition]
  		 THEN [output if true]
  		 ELSE [output if false]
  END
  AS [new field] //optional, reset value
FROM [table]
  ```
  



---

#### **07 IT Outsourcing - Module 2. IT Management**

How to properly developing and managing IT projects or vendors?
- IT acquisisiton and implementation practices
- IT sourcing strategies
- IT-related risks



**Case: Healthcare.gov**

- objective of **ACA - Affordable Care Act, Obamacare**: provide affordable health insurance to Americans. 

- expected result:  make health insurance mandatory

- Behind the production:

  ```
  Voluntary -- Mandatory		to have health insurance
  Limited -- Broadened 		Coverage of health condition
  Decentralized -- Centralized 	 	Administration/marketplace
  * Market Driven -- Government-led		Governance
  
  Spectrum of Goverment Governance:
  US < US ACA < China,Korea	<	Canada
  ```

- Key functions of website: 
  - Create Account
  -  Verify Elegibility (borrow database from organizations eg. HHS, SSA, IRS)
  - List products
  - (Customers) Search&Select products
  - Purchase
  - Update record - to organizations who manage healthcare database
- **the initial rollout: a failure - technical bug: people couldn't sign up. Only 6 people out of millions who applied were able to enroll.**
- **consequence if not fiexed:** distrust and disappointed towards government; *lose faith*; *legislation could be **repealed (abandoned)***
- **Obama's reaction:** clarified the separation between legislation and tech department 
- Key players of project:
  - HHS - Health and Human Services: Oversees the federal agencies / The lead
  - CDC, **CMS - Centers for Medicare and Medicaid Services**, IRS: HHS hires contractors by selecting through <u>existing contracts</u>👇
    - CMS is the most in control (power), due to its experience and available funding
  - CGI, Serco, McKinsey, QSSI - government approved contractors.
    - **No open-bidding - no open competition, exclude the others in the market**



**Q: Why did the initial rollout fail?**

**Root Causes - IT Governance Framework**

- People:

  - Politics: political interest 
    -  eg. partisan/misaligned interest among contractors
  - Experience
  - Leaderships

- Process

  - Communication
  - Coordination
  - (Government) Procurement Politics

- Technology

  - Complexity
  - Compatibility
  - Legacy

  

**Q: Before the project fail, How Do we evaluate the risk?**

**Risk Cube of IT Projects**

<img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230623135743134.png" alt="image-20230623135743134" style="zoom:40%;" />

**Obamacare: High risk**

```
Scope: large, nationwide
Structure: fuzzy, unclear roles and responsibility
Experience: low, CMS is lack of experience in this specific project
```



**Tripple Constraint Model of IT projects**

<!-- Certain Aspect of IT project need to be Prioritized, while the rest have to be given up -->

- Time
- Cost
- Scope

**Obamacare:** prioritized work, focusing on the easiest problem first, one prob at a time.

---

**Obama's Action Plan**

1. Obama **didn't reach out** to existing contractors / huge companies / government bodies
2. Obama **reached out** to <u>Jeff Zients - Business and Gov</u>, <u>Todd Park - Whitehouse CTO</u>
3. Obama **Assembled** a group of tech wizards (team of 6) - w/ great expertise, share similar political identity, who fixed the website in a short time



**Action**

1. **Dashboard** to monitor the website performance, could assess coordination among the whole team
2. Sought to work with **incumbent vendors** first
3. **Prioritized** work, focusing on the easiest one at a time



**Fixing Healthcare.gov and their "rules"**

- No blame, no political issue, just **solve the problems**
- people who **know the most** should be doing the talking
- **stay focused** on the most urgent issues (prioritize work)



**The Save - medicate the risk in Risk Cube**

```
smaller scope - basic website
clearer structure - team of 6 expertise
high experience - each dealt w/ similar projects
```

<!--Risks were reduced by moving towards origin-->



#### Strategies:

**IT system launch strategies**

<img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230623171200067.png" alt="image-20230623171200067" style="zoom:40%;" />

**IT sourcing strategies: MAKE - Hierarchy or BUY - Market**

**pro of buy**

- **Invisible hand:** market is more efficient and reaches an equilibrium

**con of buy**

- **Transaction cost:** transactions in the market leads to **frictions / transaction cost**
  - eg. searching cost (suppliers); bargaining; monitoring

`Obamacare: Buy/outsource to 1.multiple contractors 2.team of 6 tech wizards`



**Two models for IT sourcing strategies: Make or Buy**

**1. Strategic alliances**

-  Long-term partnerships with **few large technology giants**, such as Accenture.
  -  **Benefits**: stability, trust, save cost, scale, client-specific knowledge.
  -  **Risks**: reliance on the vendor (hostage), lack of incentives

**2. Transactions**

-  Short-term contracts with **a large number of smaller technology startups**, such as fintech firms.
  -  **Benefits**: competition, innovation, cutting-edge tech
  -  **Risks**: onboarding and integration, vendor longevity



**It sourcing strategies: Future Model**

- The **Long - Tail Strategy for IT Outsourcing**: driven by a need for innovation, in addition to cost savings.
  - **Def: combine major partnerships(Long term) with many smaller contracts(Short term)**
- *Organizations need to* **govern** *the **vendor portfolio** (monitoring performance, rewarding top vendors, managing integration)*
- Ensures **innovation** (small companies) with **stability** (giants)

---



#### 07 Innovation - Module 3. IT Disruption

Emerging techs & How IT changes the business and social world

- social media
- mobile computing
- Big data, analytics, etc.



**Mobile Payment:** A **contactless way of paying** that involves device such as mobile phone

**Case: Starbucks**

- **key success factors of Starbucks**
  - On-premise shopping + quality products
  - many locations
  - clustering stores in selected areas, even intentionally operating at a loss

**Success Story**

- **Changing people's mental model about coffee**

  - **Mental model:** representation of a domain or situation that supports understanding, reasoning and prediction.
  - "Under what situation will you consume coffee / What does coffee mean to you"

  **Starbucks:**

  `Instant coffee --> Experience. Meet people, work, consume non-coffee beverages.`

- **IT innovation for sustained competitive advantage**

  - Innovation of products, IT, e-commerce, and business models

- **success in mobile payment**

  - Global leadership in mobile, digital, and loyalty
  - **IT innovation**: Starbucks Mobile App - mobile apps
  - Functionality, convenience, interface design, rewards...



**Technology Acceptance Model - TAM**

- First TAM appeared at late 1980s

<img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230623195622926.png" alt="image-20230623195622926" style="zoom:30%;" />

- **Drivers of technology adoption = "why people use technology"**

- **Perceived Usefulness: **functionality, value

  - eg. save time, convenience

- **Perceived Usability:** Easy to use? Intuitive? User friendly...

- **Behavioral Intention to Use:** 

  - **Intention might not necessarily transfer to Actual use**
  - Reasons: Price too high; habit of using old tech.
  - **Higher Intention to use results in Higher Actual use, but not 100% transferrable**

- **Perceived Security:** Data protected / secured enough?

  -  has become increasingly important 
  - leads to 1. Intention to use 2. Actual usage

- **Factors of Perceived Usefulness:**

  - "How Society thinks about tech in general"

  - Result Demonstrability, Output Quality, Job Relevance, Image, Subjective Norm, Experience, Voluntariness

  - **Exl1: Apple: Customers try and use new products before launching, so that people won't think the new technology as too hard to use**

    

- **Exl2: Sqaure Inc - a useful Mobile Payment app**

- Succeed by investing in Mobile Payment Company

- A **financial services merchant** that services mobile payments company

- Backed by investors

  

**Starbuck's: Digital Strategies**

- **How can Starbucks leverage its IT to drive its future growth? **

  - **Peer influence** - Technology adoption in a social network

  - Social network **promotes** Mobile Payment, **boosts** technology adoption

  - Nodes are linked, therefore **Non Adopters** are linked to **Prior Adopters**

    

**Diffusion of Innovations**

- Everett Rogers

- **Different strategies for different adopter groups**, because some people adopt innovation more quickly than others

  <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230623232237062.png" alt="image-20230623232237062" style="zoom:40%;" />



**Starbucks Reserve - Venues for experimentation**

- Alligned with Innovative Strategies

- Provides luxury experience, creative drinks, trendy style, high quality drinks

  

---

#### 08 Platforms - Module 3. IT Disruption

**Platform as a Business Model**

- Facilitates the transactions and interactions between the two (or multiple) external parties. 
  - Eg. Buyers v.s. Sellers
  - Platform Eg. Google, Amazon

- ```
  Examples: 3 main categories
  
  1. Social Medias/Networks
  	Users share contents and interact in virtual community
  	Exchange ideas in the format of text, image, video, etc.
  	Eg. Ins, Twitter, Youtube
  	
  2. Gig Economy
  	An Online Labor Platform at Digital Marketplace
  	Provides: 
  		Communication b/t workers and clients
  		ratings and reviews
  	Helps businesses connect w/ short term and flexible work opportunities
  	Eg. Uber
  	
  3. E-commerce
  	Enables businesses to conduct online commercial transactions
  	Buy or sell goods & services
  ```

- **Two-sided platform / multi-sided platform**

  - The two/multiple parties
  - **Platform** is not just a piece of technology, but also a **Business Model**.



**Why are platforms so powerful?**

- **Traditional 'linear' business** - **non-platform companies**

  - create value in the form of goods or services and then sell them to someone downstream in their supply chain
  - linear process
  - can also **monetize data, but limited**

- **Platform Business Model **

  Side 1 - Platform **/middle ground** - Side 2

  - Value from transactions, often **matching supply and demand, brokering a transaction.** / coordinates transaction

  - Monetize data collected from each side, sometimes giving away products or services to collect data

  - Asset light, no need for factory or distribution of products

  - **Leverage powerful network effect**

    - **gain lots of customers in short time**

      **Network effect / network externality:** the value of a good or services increases w/ the number of participants

      - Eg. Non-digital: telephone
      - Eg. Modern: Uber (positive)

      ```
      Side 1			Side 2
      	\						/
      	 \				 /
      		 Platform
      ```

      **Different Types of Network Effects:**

      - **Same-side positive:** users posting reviews increasing the value of website

      - **Cross-side positive:** sellers offering products / buyers bidding for items on eBay increases value of platform for buyers / sellers

      - **Same-side negative:** too many sellers could result in competition among sellers

      - **Cross-side negative:** too many ads (sellers) could reduce the value perceived by users (buyers)

        

      **Case1: Nasdaq**

      ```
      Different types network effects could happen simultaneously
      Traders <---> Nasdaq <---> Companies
      
      Positive 	more traders,						more traders,
      					higher liquidity				higher profit for listed firms
      																	Attract companies
      																	
      Negative	too many traders				too many traders
      					crashing platform				crashing platform
      					hurting other traders		hurting other companies
      					
      						Same side								Cross side
      ```

      

      **Case2: Google**

      **What network effects could exist on Google?**

      ```
      Users <---> Google <---> Advertisers
      
      Positive 	more users,								more users,
      					more data,								more data,
      					better search results			accurate ad targeting 											
      																	
      Negative	too many users						too many targeted ads
      					(using Google ads)				(collecting extensive data)
      					competition among users		some users might leave
      					
      					
      						Same side								Cross side
      ```

      

  - **"Winner Takes All" phenomenon - **the rich get richer, the poor get poorer, due to **network effect** in a platform business model
    - Increasing number of **Adopters** increases the **Value of product**, which attracts more **Adopters.** (Loop)
    - **an economic system where competition allows the best performers to rise to the top at the expense of the losers, and the ultimate result is oligopoly**.

<img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230626115710191.png" alt="image-20230626115710191" style="zoom:50%;" />

- **Competitive Strategies in Platform Economy**

  - **Q: How can companies compete in the digital economy, which tends to be dominated by the platform business model?**

  `	Few giants dominate the world's highest value platform, therefore the market is concentrated`				

   						 		<img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230626115932489.png" alt="image-20230626115932489" style="zoom:33%;" />

  **Strategy 1: New platform enters - Starting from scratch**

  - Entrants must offer **revolutionary and innovative functionality.**

  - Eg. Rent the Runway - fashion industry; Lemonade - leveraging AI - Insurance products

  

  **Strategy 2: Platform envelopment**

  - **Platform already operates at success. Now grows by sneaking into another platform market**

  - **combining its own functionality with the target’s** in a multi-platform **bundle** that leverages shared user relationships.

  - Eg. Microsoft bundles Media Player w/ OS - streaming platform

    **Type I: Enveloping of complements**

    - enveloping platforms that are closely related and adjacent
    - Eg. Uber v.s. Uber Eats - both delivers goods & services

    **Type II: Enveloping of substitutes**

    - enveloping a competing platform, which provides the exact same services
    - Eg. Amazon (acquire foods from Whole Foods) v.s. Whole Foods Market - Different Distribution Channel

    **Type III: Enveloping of functionally unrelated**

    - enveloping platforms that were previously meant for a different usage
    - Eg. Mobile phones v.s. video game devices - video game apps on phones



- **Social Impact and Regulation of Platforms**

  - **Imacts on Global Innovation**

    - (+) Digital platform companies make **large investments in research and development.**
    - (-) High levels of mergers and acquisitions, possible **‘killer acquisitions’.**
      - Killing startups and small, innovative companies
      - Target companies dominate the industry, forming oligopoly

    **Impacts on Society**

    - (+) **Stimulate innovation** in complementary products and services.
    - (+) Creation of **new jobs**. Gig economy. Sharing economy.
    - (-) **Fairness** issues.
    - (-) **Privacy and safety** issues.
    - (-) **Welfare** issues: Could be fired at any time?

    `There is a need for regulations to reduce negative impacts`

​				

---

#### 09 Industry Analysis - Module 3. IT Disruption

**Case: Apple and its competitors**

- **Apple-iOS:**

  - mobile operating system, released with the first-generation iPhone on June29, 2007
  - First smartphone
  - People thought that was the end of PC , though it's not.

- **Android: Key differences?**

  **Apple: **

  - more centralized, controling over IOS and apps, consistent among devices
  - more in-app purchases
  - high cost, high return, high <u>vertical integration</u>
  - high profitability
  - better interface design

  **Android:**

  - Open-source model
  - more ads
  - Low cost, low return, <u>horizontal integration</u>
  - high market share

  **vertical integration - business expands by acquiring another company that operates before or after them in the supply chain.**

  **horizontal integration - business grows by acquiring a similar company in their industry at the same point of the supply chain.**

- **iOS v.s. Android**

  - **global market share: ** iOS is more profitable
  - However, due to **Android's open-source OS,** it quickly took over and dominated the market shares

  **Co-operation Strategy**

  ● A strategy of **cooperating** and **competing** simultaneously

  ● Apple cooperates w/ Sumsung

- **Apple: What's Next** - **Should Apple enter the auto industry?**

  - Project Titan - Apple car

  - Apple Car - Tesla

    ```
    ● Founded in 2003 by Elon Musk, initially focusing on niche market
    ● 2010 Nasdaq IPO: the first automaker IPO after Ford (50+ years ago)
    ● Model S: The most popular luxury vehicle in North America
    ● Model 3 / Y: Targeting global mainstream
    ```

    **Car Industry:**

    **Incumbents**

    - The leader firms that possess the largest market share
    - Leads to a Crowded market in **car industry**, high level of **competition**
    - More entrants: NIO, Rivian, Lucid Motors...

    **New Entrants**

    - Potential competitors
    - eg. Google, Sony, Amazon...
    - All working on separate projects for autonomous vehicle

- **Industry Analysis: Five Forces**

  A model to analyze **how attractive an industry is**

  -  Competition is often looked at too narrowly.

  -  Aside from direct competitors, you’re fighting with a <u>broader set of competitors</u>.

    <img src="/Users/anastasia/Library/Application Support/typora-user-images/image-20230626173207742.png" alt="image-20230626173207742" style="zoom:50%;" />

  If you want to think about the **profitability** of a certain industry, it can be completely determined by a set of **5F**.

  - ●  **Porter's** argument is that based on the relation between these 5F, you can tell which industry will be profitable, and which will not.

  - ●  E.g. How IT is affecting transportation? Think about how IT affects these 5F.

    

  **Apple**

  ```
  Threats
  ● New Entrants 
  ● Substitutes of products&services:
  	laptops, mobile phones
  	
  Bargaining Power
  ● Suppliers: 
  	Intel, Microsoft(OS), Rambus...
  ● Buyers:
  	Users, corporate customers
  	
  ● Focal industry: PC manufacturing
  ● Existing firms: Dell, IBM...
  ```

  

  **Intra-Industry Rivalry**

  - **Intra-Industry Rivalry / Price competition decreases profits**

    Some factors that **increase** intra-industry rivalry

    -   Many firms in the industry
    -   Competing firms offer similar products, low differentiation

  - High: Food and beverages
  - Low: Telecom (low entry barrier + positive network effect)

  

  **Bargaining Power of Buyers**

  - When buyers have power, you **can’t raise prices**. Some factors that **increase** buyer power
    -  Buyers purchase in large volumes (Walmart as a buyer)
    -  Buyers can easily switch to a competitor (ZARA <-> H&M)
    -  Buyers know a lot about rivals’ prices (tripadvisor -> profit margin of hotels)
  - High: Airline during COVID
  - Low: Google Ads

  

  **Bargaining Power of Suppliers**

  - Analyze cost to make products or provide services

  - When Suppliers have power, **costs are higher** Some factors that **increase** bargaining power of suppliers
    - There are a few large suppliers (chip manufacturers as suppliers: Intel, AMD...)
    - If buyers find it difficult to switch from existing suppliers (Microsoft as supplier)

  - High: Aerospace manufacturing
  - Low: Supermarket

  

  **Threat of New Entrants**

  - If the threat of new entrants is high, firms **must lower prices.** Some factors that **decrease** the threat of new entrants

    - Economies of scale (large investments: Telecommunication, utilities!)

    - Learning experience curves (skilled labor: pharma)
    - Brand identity (soft drinks, Fashion)
    - Government Policy

  - High: online retail

  - Low: shipbuilding

  

  **Threat of Substitutes**

  - If **prices in an industry rise**, consumers seek substitutes. Some factors that **increase** the threat of substitutes
    - Alternative product has higher quality & better performance
    -  Alternative product is cheaper
    - Switching costs are low for the buyers
  - High: movie theater (videos/Air Vision Pro)
  - Low: healthcare



**Apple: Smartphone vs. Automobile**

- Assess each forces with low/medium/high

- So, should apple enter the automobile industry?

  **Smartphone**

  ```
  Threats
  ● New Entrants/(barriers): Medium
  ● Substitutes of products&services: Low
  
  Bargaining Power
  ● Suppliers: Medium
  ● Buyers: Medium
  	
  ● Rivalry Among Existing Competitors: High
  ```

  **Auto**

  ```
  Threats
  ● New Entrants/(barriers): Medium, but rising
  ● Substitutes of products&services: Medium, rising
  
  Bargaining Power
  ● Suppliers: Medium
  ● Buyers: High
  	
  ● Rivalry Among Existing Competitors: High
  ```

- **Conclusion:**

  **Apple’s ecosystem is slightly more attractive. That is why Apple has a capacity and money to enter into the auto industry even though this industry is less attractive**



---

#### More about SQL - Module I

**<u>LIMIT</u>**

```sql
//Get the "top N" rows from a query

SELECT [field(*)]
FROM [table]
ORDER BY [field] ASC/(DSC)
LIMIT N
//(Number)
//only meaningful when rows are ordered
```

**<u>JOIN</u>**

```sql
//Link tables by using a JOIN clause to display fields from multiple tables.
//Combine rows from two or more tables, based on a related column b/t them

SELECT [field(s)] //Join based on the multiple fields
FROM [table1] //[table2]
JOIN [table2]
ON Table.Field 1 = Table.Field 2
//this.format
```

**<u>CREATE TABLE</u>**

```sql
//create a new table in a database

CREATE TABLE [table] AS
SELECT [field(*)] FROM [table] WEHRE [condition]
```

