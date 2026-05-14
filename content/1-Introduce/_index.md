---
title : "Introduction"
date: 2024-01-01
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

#### Introduction

Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to help you discover, monitor, and protect sensitive data in your AWS environment.

Macie automates the discovery of sensitive data, such as personally identifiable information (PII) and financial data, to provide you with a better understanding of the data that your organization stores in Amazon Simple Storage Service (Amazon S3). Macie also provides you with an inventory of your S3 buckets, and it automatically evaluates and monitors those buckets for security and access control. Within minutes, Macie can identify and report overly permissive or unencrypted buckets for your organization.

If Macie detects sensitive data or potential issues with the security or privacy of your data, it creates detailed findings for you to review and remediate as necessary. You can review and analyze these findings directly in Macie, or monitor and process them by using other services, applications, and systems.

![Launch EC2](/images/1/00014.png?featherlight=false&width=90pc)

#### Features of Amazon Macie

Automate the discovery of sensitive data
With Macie, you can automate discovery and reporting of sensitive data by creating and running sensitive data discovery jobs. A sensitive data discovery job analyzes objects in S3 buckets to determine whether they contain sensitive data. If Macie detects sensitive data in an object, it creates a sensitive data finding for you. The finding provides a detailed report of the sensitive data that Macie found.

You can configure a job to run only once, for on-demand analysis and assessment, or on a recurring basis for periodic analysis, assessment, and monitoring. You can also choose various options to control the breadth and depth of a job's analysis—the S3 buckets to analyze, the sampling depth, and custom include and exclude criteria that derive from properties of S3 objects. With these scheduling and scope options, you can build and maintain a comprehensive view of the data that your organization stores in Amazon S3 and any security or compliance risks for that data.

Discover a variety of sensitive data types
When you create a sensitive data discovery job, you can configure the job to use built-in criteria and techniques, such as machine learning and pattern matching, to analyze objects in S3 buckets. These criteria and techniques, referred to as managed data identifiers, can detect a large and growing list of sensitive data types for many countries and regions, including multiple types of personally identifiable information (PII), financial data, and credentials data.

You can also configure the job to use custom data identifiers. A custom data identifier is a set of criteria that you define to detect sensitive data—a regular expression (regex) that defines a text pattern to match and, optionally, character sequences and a proximity rule that refine the results. With this type of identifier, you can detect sensitive data that reflects your particular scenarios, intellectual property, or proprietary data, and supplement the managed data identifiers that Macie provides.

To fine tune the analysis, a job can also use allow lists. Allow lists define specific text and text patterns that you want Macie to ignore in S3 objects—for example, the names of public representatives for your organization, public phone numbers for your organization, or sample data that your organization uses for testing.

Evaluate and monitor data for security and access control
When you enable Macie, Macie immediately generates and begins maintaining a complete inventory of your S3 buckets, and it begins evaluating and monitoring the buckets for security and access control. If Macie detects a potential issue with the security or privacy of a bucket, it creates a policy finding for you.

In addition to specific findings, a dashboard gives you a snapshot of aggregated statistics for your buckets. This includes statistics that indicate how many of your buckets are publicly accessible, are shared with other AWS accounts, or don’t encrypt objects by default. You can drill down on each statistic to review the supporting data.

Macie also provides detailed information and statistics for individual buckets in your inventory. This data includes breakdowns of a bucket’s public access and encryption settings, and the size and number of objects that Macie can analyze to detect sensitive data in the bucket. You can browse the inventory, or sort and filter the inventory by certain fields. When you choose a bucket, a panel displays the bucket’s details.

Review and analyze findings
In Macie, a finding is a detailed report of sensitive data in an S3 object or a potential policy-related issue with the security or privacy of an S3 bucket. Each finding provides a severity rating, information about the affected resource, and additional details, such as when and how Macie found the issue.

To review, analyze, and manage findings, you can use the Findings pages on the Amazon Macie console. These pages list your findings and provide the details of individual findings. They also provide multiple options for grouping, filtering, sorting, and suppressing findings. You can also use the Amazon Macie API to query, retrieve, and suppress findings. If you use the API, you can pass the data to another application, service, or system for deeper analysis, long-term storage, or reporting.

Monitor and process findings with other services and systems
To support integration with other services and systems, Macie publishes findings to Amazon EventBridge as finding events. EventBridge is a serverless event bus service that can route findings data to targets such as AWS Lambda functions and Amazon Simple Notification Service (Amazon SNS) topics. With EventBridge, you can monitor and process findings in near-real time as part of your existing security and compliance workflows.

You can configure Macie to also publish findings to AWS Security Hub. Security Hub is a service that provides a comprehensive view of your security posture across your AWS environment and helps you check your environment against security industry standards and best practices. With Security Hub, you can more easily monitor and process your findings as part of a broader analysis of your organization's security posture in AWS.

Centrally manage multiple Macie accounts
If your AWS environment has multiple accounts, you can centrally manage Macie for accounts in your environment. You can do this in two ways, by integrating Macie with AWS Organizations or by sending membership invitations from Macie.

In a multiple-account configuration, a designated Macie administrator can perform certain tasks and access certain Macie settings, data, and resources for accounts that are members of the same organization. Tasks include reviewing information about S3 buckets that are owned by member accounts, reviewing policy findings for those buckets, and running sensitive data discovery jobs to detect sensitive data in the buckets. If the accounts are associated through AWS Organizations, the Macie administrator can also enable Macie for member accounts in the organization.

Develop and manage resources programmatically
In addition to the Amazon Macie console, you can interact with Macie by using the Amazon Macie API. The Amazon Macie API gives you comprehensive, programmatic access to your Macie account and resources.

To develop and manage resources with the Amazon Macie API, you can send HTTPS requests directly to Macie or use a current version of an AWS command line tool or an AWS SDK. AWS provides tools and SDKs that consist of libraries and sample code for various languages and platforms, such as PowerShell, Java, Go, Python, C++, and .NET.

![Launch EC2](/images/1/00013.png?featherlight=false&width=90pc)