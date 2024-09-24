![](Aspose.Words.121a1232-b2b8-4a06-bd93-535a03dadded.001.jpeg)

**How Applications and their components work together**

**Three Tier Applications**

Three-tier architecture is a well-established software application architecture that organizes applications into three logical and physical computing tiers: the presentation tier, or user interface; the application tier, where data is processed; and the data tier, where the data associated with the application is stored and managed.

The chief benefit of the three-tier architecture is that each tier runs on its infrastructure, can be developed simultaneously by a separate development team, and can be updated or scaled without impacting the other tiers.

### **Presentation tier**
The presentation tier is the application's user interface and communication layer, where the end-user interacts with the application. Its main purpose is to display and collect information from the user. This top-level tier can run on a web browser, as a desktop application, or a graphical user interface (GUI). Web presentation tiers are usually developed using HTML, CSS, and JavaScript. Desktop applications can be written in various languages depending on the platform.

### **Application tier**

The application tier, the logic tier or middle tier, is the heart of the application. In this tier, information collected in the presentation tier is processed - sometimes against other information in the data tier - using business logic, a specific set of business rules. The application tier can also add, delete or modify data in the data tier.

The application tier is typically developed using Python, Java, Perl, PHP or Ruby and communicates with the data tier using API calls. 

### **Data tier**

The data tier, sometimes called database tier, data access tier, or back-end, is where the information processed by the application is stored and managed. This can be an RDBMS (Relational database management system) such as PostgreSQL, MySQL, MariaDB, Oracle, DB2, Informix, or Microsoft SQL Server, or in a NoSQL Database server such as Cassandra or MongoDB.

In a three-tier application, all communication goes through the application tier. The presentation tier and the data tier cannot communicate directly with one another.



App Tier

Web Tier

Db tier
![](Aspose.Words.121a1232-b2b8-4a06-bd93-535a03dadded.002.png)![](Aspose.Words.121a1232-b2b8-4a06-bd93-535a03dadded.003.png)![](Aspose.Words.121a1232-b2b8-4a06-bd93-535a03dadded.004.png)![A picture containing logo

Description automatically generated](Aspose.Words.121a1232-b2b8-4a06-bd93-535a03dadded.005.png)


Reference **draw.io** for diagrams












