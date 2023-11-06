# Cafe-static-website
Challenge Lab 2: Creating a Static Website for a Café on Amazon S3

Table of Contents
Scenario
Lab Overview and Objectives
Prerequisites
Architecture Overview
Getting Started
Step 1: Host a Static Website Using Amazon S3
Step 2: Implement Data Protection
Step 3: Implement a Data Lifecycle Strategy
Step 4: Implement Disaster Recovery Strategy
Cleanup
Conclusion

Scenario
Frank and Martha are a husband-and-wife team who own and operate a small café business that sells desserts and coffee. Their daughter, Sofía, and their other employee, Nikhil—who is a secondary school student—also work at the café. The café has a single location in a large city.

The café currently doesn’t have a marketing strategy. They mostly gain new customers when someone walks by, notices the café, and decides to try it. The café has a reputation for high-quality desserts and coffees, but their reputation is limited to people who have visited, or who have heard about them from their customers.

Sofía suggests to Frank and Martha that they should expand community awareness of what the café has to offer. The café doesn’t have a web presence yet, and it doesn’t currently use any cloud computing services. However, that situation is about to change.

Lab Overview and Objectives
In this lab, you will use Amazon Simple Storage Service (Amazon S3) to build a static website and implement architectural best practices to protect and manage your data.

After completing this lab, you should be able to:

Host a static website by using Amazon S3
Implement one way to protect your data with Amazon S3
Implement a data lifecycle strategy in Amazon S3
Implement a disaster recovery (DR) strategy in Amazon S3
Prerequisites
Before you start this lab, you should have the following:

An AWS account with sufficient permissions to create Amazon S3 buckets, configure bucket policies, and perform other necessary actions.
Familiarity with basic AWS services and concepts.
Basic knowledge of HTML for website content.
Architecture Overview
In this lab, you will build a static website for the café using Amazon S3. You will also implement data protection, data lifecycle management, and disaster recovery strategies. The high-level architecture will look like this:

Architecture Diagram

Getting Started
To get started with this lab, follow the steps outlined below. Please ensure that you have the required AWS CLI and SDKs installed, and that you are authenticated with your AWS account.

Step 1: Host a Static Website Using Amazon S3
In this step, you will create an Amazon S3 bucket and configure it to host your static website. You will also upload your website content to the bucket.

Detailed instructions for Step 1 can be found in the Step1-HostStaticWebsite.md file.

Step 2: Implement Data Protection
In this step, you will implement data protection for your website by configuring Amazon S3 bucket policies and applying proper permissions.

Detailed instructions for Step 2 can be found in the Step2-ImplementDataProtection.md file.

Step 3: Implement a Data Lifecycle Strategy
In this step, you will implement a data lifecycle strategy to manage the versioning and expiration of your website content in Amazon S3.

Detailed instructions for Step 3 can be found in the Step3-ImplementDataLifecycle.md file.

Step 4: Implement Disaster Recovery Strategy
In this step, you will implement a disaster recovery (DR) strategy for your website hosted on Amazon S3. This includes enabling cross-region replication.

Detailed instructions for Step 4 can be found in the Step4-ImplementDisasterRecovery.md file.

Cleanup
After completing the lab, it's essential to clean up the resources to avoid incurring unnecessary charges. Follow the cleanup instructions in Cleanup.md.

Conclusion
By completing this lab, you have successfully created a static website for the café using Amazon S3 and implemented data protection, data lifecycle management, and disaster recovery strategies. This will help Frank and Martha expand community awareness of their café and ensure the security and availability of their website.

If you encounter any issues or have questions, please refer to the lab documentation or contact AWS Support for assistance.

Thank you for taking this challenge lab and best of luck with your café's online presence!
