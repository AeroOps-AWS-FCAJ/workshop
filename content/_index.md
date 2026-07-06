---
title: "Secure Hybrid Access to S3"
date: 2024-01-01
chapter: false
---

# Secure Hybrid Access to S3 using VPC Endpoints

## Overview

**AWS PrivateLink** provides private connectivity to AWS services from VPCs and on-premises networks without exposing traffic to the public Internet.

In this workshop, you will create, configure, and test VPC endpoints that allow workloads to access Amazon S3 privately. The workshop covers both endpoint types used with Amazon S3:

- **Gateway endpoint** — routes Amazon S3 traffic privately from a VPC through its route tables.
- **Interface endpoint** — provides private IP addresses and DNS names for access from a VPC or an on-premises network.

## Workshop content

1. [Workshop overview](1-Workshop-overview/)
2. [Prerequisites](2-Prerequisite/)
3. [Access S3 from a VPC](3-S3-vpc/)
4. [Access S3 from an on-premises environment](4-S3-onprem/)
5. [VPC endpoint policies](5-Policy/)
6. [Clean up](6-Cleanup/)
