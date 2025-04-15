## Background & Problems
Developers often face challenges in identifying the right APIs to retrieve the necessary data for meeting business requirements. The process can be time-consuming and complex, whether dealing with third-party APIs or internal (private) APIs.
### Example 1: Third-Party APIs
When integrating with third-party services, such as AWS, developers must navigate a vast array of APIs to accomplish their tasks.
- For instance, if you need to store images, videos, or audio in S3 buckets and connect them with CloudFront for content delivery, you must first explore the AWS documentation to determine the required APIs and their parameters.
- The challenge lies in understanding the integration workflow between S3 and CloudFront, configuring permissions, and setting up the appropriate IAM roles.
- For developers unfamiliar with AWS APIs, this process can be overwhelming and time-consuming.
### Example 2: Private APIs
When collaborating with other teams, developers often need to access internal APIs to retrieve data.
- Unlike third-party APIs, internal APIs typically lack comprehensive documentation and may be recorded in various formats.
- Without proper documentation, developers must schedule meetings with other teams to understand API usage, leading to inefficiencies and delays.
This project aims to simplify the API discovery process, reducing the time and effort developers spend searching for and integrating the right APIs.