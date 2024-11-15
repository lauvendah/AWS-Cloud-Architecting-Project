Here’s an updated `README.md` file using the cost estimate information from the uploaded document:

---

# Cost Estimate for AWS Academy Cloud Architecting Capstone Project

## Project Overview
This repository contains the cost estimate for the Cloud Architecting Capstone Project. The goal is to design a scalable, cost-effective cloud architecture using AWS services while adhering to the Well-Architected Framework.

## Estimated Monthly Cost Breakdown

| **Service**              | **Usage**                                  | **Estimated Cost (USD)** |
|--------------------------|--------------------------------------------|--------------------------|
| Amazon EC2               | 2 t3.micro instances (On-Demand)           | $0.15                    |
| Elastic Load Balancing   | 2 Application Load Balancers               | $32.86                   |
| Amazon RDS (MySQL)       | 2 db.m1.small instances, 20 GB storage     | $11.61                   |
| AWS Secrets Manager      | 2 secrets, API calls (monthly)             | $0.80                    |
| **Total Estimated Cost** | **N/A**                                    | **$45.42/month**         |

## Additional Details
- **Region**: US East (N. Virginia)
- **Instance Types**: EC2 (t3.micro), RDS (db.m1.small)
- **Pricing Strategy**: On-Demand for consistent workload

## Annual Cost Estimate
| **Total 12 Months Cost** | **$545.04/year** |

## Cost Optimization Considerations
- **Use Free Tier**: Where applicable, leverage AWS Free Tier offerings.
- **Right-Sizing**: Review instance sizes and adjust based on actual workloads.
- **Enable Monitoring**: Use CloudWatch to optimize resource usage and reduce costs.
- **Cost Management Tools**: Utilize AWS Cost Explorer for real-time tracking and insights.

## Disclaimer
This cost estimate is approximate and may vary based on actual usage and AWS pricing updates. Check the [AWS Pricing Calculator](https://calculator.aws) for more details and up-to-date calculations.

---

This structure provides a clear summary of the estimated monthly costs and optimization recommendations based on the detailed information provided in the cost estimate file.
