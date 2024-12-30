## Technology Stack

**Domain Registrar (NameCheap)**

We use NameCheap because of their scale and pricing. As the least strategic layer of our infrastructure, we focus primarily on cost effectiveness and reliability.

[Manage Registrar ›](https://www.namecheap.com/myaccount/login/)
<br/><br/>

---

**Domain Name System (Cloudflare)**

We use Cloudflare DNS because it delivers a secure and resilient DNS service with the fastest response time (11ms on average), unparalleled redundancy (locations in over 330 cities), and advanced security.

[Manage DNS ›](https://dash.cloudflare.com/login)
<br/><br/>

---

**Serverless Cloud & Compute (AWS)**

We use AWS as the core of our entire infrastructure because we believe it allows us to focus more strategically while improving development velocity the most long-term. That is because AWS offers extremely low costs (pay per use), leading reliability (uptime), and handles all of the manual toil of engineering maintenance and improvement 24/7/365. We believe in always utilizing third-party owned, managed infrastructure whenever we can — which includes very heavy use of APIs.

Services we use:
* ECS
* RDS (PostgreSQL)
* EventBridge
* SQS
* Secrets Manager

[Manage AWS ›](https://us-east-1.console.aws.amazon.com/console/home)
<br/><br/>

---

**Data Orchestration (Dagster+)**

We use Dagster as our data orchestrator responsible for running all of our existing data pipelines, monitoring them in real-time, and quickly shipping new pipelines.

[Manage Dagster+ ›](https://dagster.cloud)
<br/><br/>

---

**Public Websites (Framer & Webflow)**

We use a mixture of Framer (on newer sites) and Webflow (for large CMS sites) as the front ends for our public websites. They’re affordable and remove most of the manual labor historically involved in designing, building, and hosting a website.

**[Manage Framer ›](https://login.framer.com/)**<br/>
**[Manage Webflow ›](https://webflow.com/login)**
<br/><br/>

---

**Public Cloud Storage (Dropbox & S3)**

We use Dropbox (or Amazon S3) for all of our publicly facing documents, which are typically offered for download via blog post or linked to as a document.

[Manage Dropbox ›](https://www.dropbox.com/login)<br/>
[Manage S3 ›](https://us-east-1.console.aws.amazon.com/s3/)
<br/>