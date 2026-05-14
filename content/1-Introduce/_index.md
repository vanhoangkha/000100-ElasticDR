---
title : "Introduction"
date: 2024-01-01
weight : 1
chapter : false
pre : " <b> 1. </b> "
---

# Introduction

AWS Elastic Disaster Recovery (AWS DRS) helps minimize downtime and data loss with the ability to quickly and reliably recover applications on-premises and in the cloud using available storage. Reasonable cost, minimal computing resources, and point-in-time recovery.

![AWS Elastic Disaster Recovery Workshop](/images/1/0001.png?featherlight=false&width=60pc)

This lab simulates an on-premises environment that allows customers to replicate disaster recovery to AWS.

The simulation environment is supported by Amazon EC2 instances and configured in a way suitable for many customer environments. The network includes
private and public subnets,
a DNS service,
pre-installed applications, and
a Windows host bastion server.

The image below is a basic network diagram for the AWS Elastic Disaster Recovery service (DRS). The simulation environment matches the service requirements.

![AWS Elastic Disaster Recovery Workshop](/images/1/0002.png?featherlight=false&width=60pc)

#### Basic knowledge
This is a lab for Solution Architects, SysOps, ServerOps, InfraOps, and other professionals.

To get the most out of this lab, you must be familiar with the following:

- Connect to Microsoft Windows server using Remote Desktop Protocol (RDP)
- Connect to Linux server using SSH