## Architecture

**Domain Registrar**

We use NameCheap because of their scale and pricing. As the least strategic layer of our infrastructure, we focus primarily on cost effectiveness and reliability.

[Manage Registrar →]()

**Domain Name System (DNS)**

We use Cloudflare DNS because it delivers a secure and resilient DNS service with the fastest response time (11ms on average), unparalleled redundancy (locations in over 330 cities), and advanced security.

[Manage DNS →]()

**Serverless Cloud & Compute (AWS)**

We use AWS as the core of our entire infrastructure because we believe it allows us to focus more strategically while improving development velocity the most long-term. That is because AWS offers extremely low costs (pay per use), leading reliability (uptime), and handles all of the manual toil of engineering maintenance and improvement 24/7/365. We believe in always utilizing third-party owned, managed infrastructure whenever we can — which includes very heavy use of APIs.

[Manage AWS →]()

**Public Websites (Sites)**

We use a mixture of Framer (on newer sites) and Webflow (for large CMS sites) as the front ends for our public websites. They’re affordable and remove most of the manual labor historically involved in designing, building, and hosting a website.

[Manage Framer →]()
[Manage Webflow →]()

**Public Cloud Storage (Dropbox/S3)**

We use Dropbox (or Amazon S3) for all of our publicly facing documents, which are typically offered for download via blog post or linked to as a document.

[Manage S3 →]()
[Manage Dropbox →]()
