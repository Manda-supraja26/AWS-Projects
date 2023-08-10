# Evolution of a website: Going from single server to serverless

ABC Ice Cream hires you to create and maintain their website. In this lab, you follow the growth of the business and how it evolves their website’s infrastructure.

You start by creating the company’s static website hosted on Amazon Simple Storage Service (S3) that displays the ice cream flavors. The business starts to gain popularity among the locals and flavors start to sell out before the day is up. The business owners ask you to migrate to a server where they can have you push updates. They decide to migrate their static site to Amazon Elastic Compute Cloud (EC2) with a Linux, Apache, MySQL, PHP (LAMP) stack built on it.

This will allow the website to update and react dynamically. Demand for AnyCompany’s ice cream surges after a viral video and the infrastructure and maintenance becomes difficult to manage. To scale with demand, you suggest migrating sections of their LAMP stack to serverless services, starting with the MySQL database. The MySQL database will be replaced with Amazon DynamoDB serverless database.