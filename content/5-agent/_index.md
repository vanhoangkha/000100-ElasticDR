---
title : "Configure DRS Agent"
date: 2024-01-01
weight : 5
chapter : false
pre : " <b> 5. </b> "
---

#### Configure DRS Agent IAM User

To do this, we will create an **IAM User**

1. Access the **AWS Management Console** interface

   - Find **IAM**
   - Select **IAM**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0001.png?featherlight=false&width=90pc)

2. In the **AWS IAM** interface


- Select **User**
- Select **Add user**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0002.png?featherlight=false&width=90pc)

3. Create **user** with the name **drs-agent-user**

   - Then, select **Next:Permission**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0003.png?featherlight=false&width=90pc)

4. For **Set Permissions**

   - Select **Attach existing policies directly**
   - Find and select **AWSElasticDisasterRecoveryAgentInstallationPolicy**
   - Select **Next:Tags**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0004.png?featherlight=false&width=90pc)

5. Select **Next:Review**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0005.png?featherlight=false&width=90pc)

6. Select **Create user**

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0006.png?featherlight=false&width=90pc)

7. We will download **Download.csv** to save **Access Key** information for the next steps.

![AWS Elastic Disaster Recovery Workshop](/images/4-iam/0007.png?featherlight=false&width=90pc)