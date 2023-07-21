# Reading: AWS: S3 and Lambda

>#### AWS S3
>1. **What is Amazon S3?**
>
>Amazon S3 is: object storage service that provided by **(AWS)**. It offers secure, scalable, and durable storage for different types of data, backups, including files also, and documents, images and videos.
>
>2. **Name some use cases for Amazon S3:**
>
>**-Static Website Hosting:** S3 can host static websites, allowing you to serve HTML, and CSS, JavaScript, and other web assets directly from S3.
>
>-**Backup and Restore**: S3 can be used to store and retrieve backups of critical data, ensuring data durability and easy recovery.
>
>-**Data Analytics**: S3 can serve as a central repository for storing and analyzing large volumes of data for data analytics workloads.
>
>-**Data Archiving:** S3 provides cost-effective storage for long-term archiving of data that needs to be retained but accessed infrequently.
>
>3. **Name some benefits of using Amazon S3**
>
>**Scalability:** S3 can seamlessly handle any amount of data, accommodating growing storage needs without the need for manual intervention.
>
>**Security:** S3 supports access controls, encryption options, and integration with AWS Identity and Access Management (IAM) for secure data storage and retrieval.
>
>**Easy Management & Integration:** S3 integrates with various AWS services, making it easy to manage and integrate data storage and retrieval within your AWS infrastructure.
>
>**Durability & Availability:** S3 ensures a huge durability and  availability for stored objects that will provide reliable access to data.
>
>**Cost-effectiveness:** S3 offers flexible pricing options, including pay-as-you-go pricing, allowing us to optimize costs based on our storage and usage requirements.
>
>#### AWS Lambda Basics
>1. **What is AWS Lambda?**
>
>**AWS Lambda is a serverless computing service**, AWS Lambda is an offering from Amazon Web Services (AWS). With Lambda, we can execute our code without the requirement of provisioning or handling servers. All we need to do is upload our code to Lambda, and the service seamlessly handles scaling, resource management, and code execution in response to specified events or triggers.
>
>2. **Name some use cases for AWS Lambdas.**
>
>**Real-time file processing:** Lambdas can process files as soon as they are uploaded to Amazon S3, allowing for immediate data transformations or analysis.
>
>**Scheduled tasks:** Lambdas can be scheduled to run at specific intervals, allowing you to automate tasks such as data backups, report generation, or data synchronization.
>
>**Web and mobile backend:** Lambdas can serve as the backend for web and mobile applications, handling API requests, authentication, and data processing.
>
>3. **Describe "serverless" to a non-technical friend.**
>
>"Serverless" denotes a computing methodology in which developers can concentrate solely on writing their code without the burden of server management. This concept is akin to renting a car when required, rather than purchasing and upkeeping one. Within a serverless environment, a cloud provider like AWS assumes responsibility for all server-related tasks, such as management and scaling, operating behind the scenes. This arrangement enhances developer productivity by allowing them to focus on application development while leaving server management to the cloud provider. Moreover, it offers cost efficiency since users are charged based on their actual code usage, eliminating expenses associated with maintaining idle servers.
>
>#### CDN
>1. **What is a CDN?**
>
>A Content Delivery Network **(CDN)** is a system comprising geographically dispersed servers that collaborate to efficiently and swiftly deliver web content to users.
>
>2. **How does a CDN work with relation to the website visitor?**
>
>When a user requests content, such as images or videos, from a website, the CDN directs that request to the server nearest to the user's location. This approach minimizes the content's travel distance, reducing latency and enhancing the website's overall performance. Consequently, the CDN server promptly delivers the requested content to the user, ensuring a quicker and more dependable user experience.
>
>3. **What are the benefits of employing a CDN?**
>
>Using a CDN provides numerous advantages, it boosts website performance by decreasing loading times and enhancing responsiveness, resulting in increased user satisfaction and engagement. Secondly, it effectively manages surges in traffic, preventing server overloads during peak periods and ensuring continuous website accessibility. Additionally, a CDN extends global reach by delivering content from servers scattered across various regions, allowing faster access for users worldwide. Lastly, it offers extra security benefits, as certain CDNs provide features like DDoS protection and SSL/TLS encryption to safeguard both the website and its content.
>
>

