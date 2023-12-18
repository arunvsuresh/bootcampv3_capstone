# bootcampv3_capstone

**Abstract Title:** Integrated Analysis of Software Development Trends Using GitHub and Stack Overflow Data

**Abstract:**
I'm aiming to provide comprehensive insights into software development trends by analyzing real-time data from GitHub and Stack Overflow. Utilizing an ETL pipeline that harnesses Flink and Spark, I will correlate development activities on GitHub with discussions and problem-solving patterns on Stack Overflow. This approach offers a multifaceted view of the software development landscape, revealing connections between active development projects and the developer community's challenges and interests.

**Data Sources:**
- **GitHub API:** Provides real-time repository activities and developer interactions.
- **Stack Overflow (Stack Exchange API):** Offers real-time developer discussions, questions, and answers.

**Join Strategy**
- I'll match the programming languages and topics from GitHub repos (using ghapi) with the tags on Stack Overflow questions. I'll also see if GitHub repo names pop up in the titles and content of Stack Overflow posts.

- In terms of tying this into a business case, it would help a business catch the latest tech waves and figure out what's trending in the software development world by linking what's being built on GitHub with the hot topics on Stack Overflow.

**Use Cases:**
- Track technology trends and development challenges.
- Guide project strategies and resources based on developer needs and interests.

**Technologies and Tools:**
- Real-time data streaming processing and management with Flink.
- Historical data analysis with Apache Spark.
- Data visualization tools (Looker) for insightful presentation of findings.

**Business Impact:**
The integration of GitHub and Stack Overflow data will enable technology companies and open-source communities to align their strategies with current trends, address prevalent issues in software development, and enhance developer engagement.
