---
layout: default
---


## [Amazon S3](https://www.youtube.com/watch?v=e6w9LwZJFIA)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.


## How it works
Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize data, and configure fine-tuned access controls to meet specific business, organizational, and compliance requirements.

![](https://d1.awsstatic.com/s3-pdp-redesign/product-page-diagram_Amazon-S3_HIW.cf4c2bd7aa02f1fe77be8aa120393993e08ac86d.png)

## Some of It's Features
Amazon S3 has various features you can use to organize and manage your data in ways that support specific use cases, enable cost efficiencies, enforce security, and meet compliance requirements. Data is stored as objects within resources called “buckets”, and a single object can be up to 5 terabytes in size. S3 features include capabilities to append metadata tags to objects, move and store data across the S3 Storage Classes, configure and enforce data access controls, secure data against unauthorized users, run big data analytics, and monitor data at the object, bucket levels, and view storage usage and activity trends across your organization. Objects can be accessed through S3 Access Points or directly through the bucket hostname.

Storage management and monitoring
Amazon S3’s flat, non-hierarchical structure and various management features are helping customers of all sizes and industries organize their data in ways that are valuable to their businesses and teams. All objects are stored in S3 buckets and can be organized with shared names called prefixes. You can also append up to 10 key-value pairs called S3 object tags to each object, which can be created, updated, and deleted throughout an object’s lifecycle. To keep track of objects and their respective tags, buckets, and prefixes, you can use an S3 Inventory report that lists your stored objects within an S3 bucket or with a specific prefix, and their respective metadata and encryption status. S3 Inventory can be configured to generate reports on a daily or a weekly basis.

## Storage management
With S3 bucket names, prefixes, object tags, and S3 Inventory, you have a range of ways to categorize and report on your data, and subsequently can configure other S3 features to take action. S3 Batch Operations makes it simple, whether you store thousands of objects or a billion, to manage your data in Amazon S3 at any scale. With S3 Batch Operations, you can copy objects between buckets, replace object tag sets, modify access controls, and restore archived objects from Amazon S3 Glacier, with a single S3 API request or a few clicks in the Amazon S3 Management Console. You can also use S3 Batch Operations to run AWS Lambda functions across your objects to execute custom business logic, such as processing data or transcoding image files. To get started, specify a list of target objects by using an S3 Inventory report or by providing a custom list, and then select the desired operation from a pre-populated menu. When an S3 Batch Operation request is done, you will receive a notification and a completion report of all changes made. Learn more about S3 Batch Operations by watching the video tutorials. 

Amazon S3 also supports features that help maintain data version control, prevent accidental deletions, and replicate data to the same or different AWS Region. With S3 Versioning, you can easily preserve, retrieve, and restore every version of an object stored in Amazon S3, which allows you to recover from unintended user actions and application failures. To prevent accidental deletions, enable Multi-Factor Authentication (MFA) Delete on an S3 bucket. If you try to delete an object stored in an MFA Delete-enabled bucket, it will require two forms of authentication: your AWS account credentials and the concatenation of a valid serial number, a space, and the six-digit code displayed on an approved authentication device, like a hardware key fob or a Universal 2nd Factor (U2F) security key.

With S3 Replication, you can replicate objects (and their respective metadata and object tags) to one or more destination buckets into the same or different AWS Regions for reduced latency, compliance, security, disaster recovery, and other use cases. S3 Cross-Region Replication (CRR) can be configured to replicate from a source S3 bucket to one or more destination buckets in different AWS Region. Amazon S3 Same-Region Replication (SRR), replicates objects between buckets in the same AWS Region. Amazon S3 Replication Time Control (S3 RTC) helps you meet compliance requirements for data replication by providing an SLA and visibility into replication times.

Amazon S3 Multi-Region Access Points accelerate performance by up to 60% when accessing data sets that are replicated across multiple AWS Regions. Based on AWS Global Accelerator, S3 Multi-Region Access Points consider factors like network congestion and the location of the requesting application to dynamically route your requests over the AWS network to the lowest latency copy of your data. S3 Multi-Region Access Points provide a single global endpoint that you can use to access a replicated data set, spanning multiple buckets in S3. This allows you to build multi-region applications with the same simple architecture that you would use in a single region, and then to run those applications anywhere in the world.

You can also enforce write-once-read-many (WORM) policies with S3 Object Lock. This S3 management feature blocks object version deletion during a customer-defined retention period so that you can enforce retention policies as an added layer of data protection or to meet compliance obligations. You can migrate workloads from existing WORM systems into Amazon S3, and configure S3 Object Lock at the object- and bucket-levels to prevent object version deletions prior to a pre-defined Retain Until Date or Legal Hold Date. Objects with S3 Object Lock retain WORM protection, even if they are moved to different storage classes with an S3 Lifecycle policy. To track what objects have S3 Object Lock, you can refer to an S3 Inventory report that includes the WORM status of objects. S3 Object Lock can be configured in one of two modes. When deployed in Governance mode, AWS accounts with specific IAM permissions are able to remove S3 Object Lock from objects. If you require stronger immutability in order to comply with regulations, you can use Compliance Mode. In Compliance Mode, the protection cannot be removed by any user, including the root account.







### I hope this was useful to how to setup Apache Server and being expose to more Linux


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
