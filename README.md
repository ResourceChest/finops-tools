# FinOps Tools

[![License: MIT](https://img.shields.io/github/license/ResourceChest/finops-tools)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ResourceChest/finops-tools)](https://github.com/ResourceChest/finops-tools/commits/main)
[![GitHub Stars](https://img.shields.io/github/stars/ResourceChest/finops-tools)](https://github.com/ResourceChest/finops-tools/stargazers)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/ResourceChest/.github/blob/main/CONTRIBUTING.md)
[![Link Check](https://github.com/ResourceChest/finops-tools/actions/workflows/link-check.yml/badge.svg)](https://github.com/ResourceChest/finops-tools/actions/workflows/link-check.yml)

A curated list of tools, frameworks, and resources for **FinOps** (Cloud Financial Operations) -- the practice of bringing financial accountability to cloud spending. Whether you are a DevOps engineer tracking Kubernetes costs, an SRE right-sizing infrastructure, an engineering manager forecasting budgets, or a finance team member seeking cloud cost transparency, this list is for you.

FinOps combines systems, best practices, and culture to help organizations understand and manage cloud costs while maintaining the speed and agility that the cloud provides.

---

## Contents

- [Cost Visibility and Analytics](#cost-visibility-and-analytics)
- [Kubernetes Cost Optimization](#kubernetes-cost-optimization)
- [Infrastructure as Code Cost Management](#infrastructure-as-code-cost-management)
- [Cloud Provider Native Tools](#cloud-provider-native-tools)
- [Multi-Cloud Cost Management](#multi-cloud-cost-management)
- [Resource Optimization and Rightsizing](#resource-optimization-and-rightsizing)
- [FinOps Frameworks and Learning](#finops-frameworks-and-learning)
- [More from ResourceChest](#more-from-resourcechest)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

---

## Cost Visibility and Analytics

- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in pull requests, shifting FinOps left into the development workflow.
- [OpenCost](https://github.com/opencost/opencost) - CNCF incubating project for real-time cost monitoring of Kubernetes workloads and cloud costs.
- [Komiser](https://github.com/tailwarden/komiser) - Open-source cloud environment inspector that analyzes cost, usage, security, and governance across AWS, GCP, Azure, and more.
- [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian) - Rules engine for cloud security, cost optimization, and governance using declarative YAML policies.
- [Vantage](https://www.vantage.sh) - Cloud cost transparency platform with detailed reporting, budget tracking, and optimization recommendations across providers.

## Kubernetes Cost Optimization

- [Kubecost](https://github.com/kubecost/cost-analyzer-helm-chart) - Kubernetes cost monitoring and optimization platform providing real-time cost allocation and efficiency insights.
- [OpenCost](https://github.com/opencost/opencost) - Open-source, vendor-neutral cost monitoring for Kubernetes clusters with real-time visibility into spending.
- [Karpenter](https://github.com/aws/karpenter-provider-aws) - Kubernetes node autoscaler built for flexibility, performance, and simplicity, optimizing compute costs on AWS.
- [CAST AI](https://cast.ai) - Automated Kubernetes cost optimization platform that handles node scaling, spot instance management, and workload rightsizing.
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Utility that helps you identify starting points for Kubernetes resource requests and limits so they are "just right."

## Infrastructure as Code Cost Management

- [Infracost](https://github.com/infracost/infracost) - Shows cloud cost estimates for Terraform and OpenTofu in pull requests, enabling cost-aware infrastructure changes.
- [Spacelift](https://spacelift.io) - Infrastructure orchestration platform supporting Terraform, OpenTofu, Pulumi, and more, with built-in cost controls and policy enforcement.
- [env0](https://www.env0.com) - Cloud governance platform that automates IaC deployment with policy-based controls, cost tracking, and self-service environments.
- [Terragrunt](https://github.com/gruntwork-io/terragrunt) - Flexible orchestration tool for Terraform and OpenTofu that keeps configurations DRY and manageable at scale.

## Cloud Provider Native Tools

- [AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/) - Visualize, understand, and manage AWS costs and usage over time with built-in forecasting.
- [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/) - Automated checks across cost optimization, performance, security, fault tolerance, and service limits.
- [Azure Cost Management](https://azure.microsoft.com/en-us/products/cost-management/) - Monitor, allocate, and optimize Azure cloud costs with built-in analytics and budgets.
- [Google Cloud Cost Management](https://cloud.google.com/cost-management) - Tools for monitoring, controlling, and optimizing Google Cloud costs including billing reports and recommendations.
- [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) - Recommends optimal AWS compute resources by analyzing usage patterns to reduce costs and improve performance.

## Multi-Cloud Cost Management

- [Spot by NetApp](https://spot.io) - Cloud optimization platform that automates infrastructure management and cost reduction across providers.
- [Apptio Cloudability](https://www.apptio.com/products/cloudability/) - Multi-cloud FinOps solution for cost visibility, anomaly detection, commitment optimization, and unit economics.
- [CloudHealth by Broadcom](https://www.cloudhealthtech.com) - Cloud management platform for cost optimization, governance, and security across multi-cloud environments.
- [Flexera One](https://www.flexera.com/flexera-one) - Unified IT asset management, FinOps, and SaaS management platform providing visibility and cost optimization across hybrid IT.

## Resource Optimization and Rightsizing

- [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) - Analyzes resource utilization and recommends optimal AWS resources to reduce costs and improve performance.
- [Finala](https://github.com/similarweb/finala) - Open-source cloud resource scanner that detects wasteful and unused resources to help reduce unnecessary spending.
- [Steampipe](https://github.com/turbot/steampipe) - Query cloud infrastructure, SaaS, and more using SQL to find unused resources, policy violations, and optimization opportunities.
- [Cartography](https://github.com/lyft/cartography) - Python tool that maps infrastructure assets and relationships into a Neo4j graph database for security and cost analysis.

## FinOps Frameworks and Learning

- [FinOps Foundation](https://www.finops.org) - Official community and training hub for FinOps practitioners, offering certifications, events, and industry resources.
- [FinOps Framework](https://www.finops.org/framework/) - The official FinOps methodology covering principles, personas, phases, domains, and capabilities for managing cloud costs.
- [Cloud FinOps (Book)](https://www.oreilly.com/library/view/cloud-finops-2nd/9781492098348/) - Collaborative, real-time guide to cloud financial management by J.R. Storment and Mike Fuller (O'Reilly).

---

## More from ResourceChest

| Repository | Description |
|:--------|:------|
| [Chrome Privacy Extensions](https://github.com/ResourceChest/chrome-privacy-extensions) | Curated Chrome extensions for privacy and security |
| [Custom GPTs](https://github.com/ResourceChest/custom-gpts) | Community-curated catalog of useful Custom GPTs with ratings |
| [AI Agents](https://github.com/ResourceChest/ai-agents) | Practical AI agents, frameworks, and tools for developers |
| [Local-First Tools](https://github.com/ResourceChest/local-first-tools) | Local-first, offline-capable, privacy-respecting tools |
| [Dev Tools (No Signup)](https://github.com/ResourceChest/dev-tools-no-signup) | Free developer tools that work instantly without an account |
| [AI & LLM Papers](https://github.com/ResourceChest/ai-llm-papers) | Foundational and frontier AI/LLM research papers reading list |

> **[Follow ResourceChest](https://github.com/ResourceChest)** for more curated resource collections.

---

## Contributing

Contributions are welcome! If you know of a great FinOps tool that should be on this list, please open an issue or submit a pull request. Make sure the tool is actively maintained and genuinely useful for cloud cost management.

Please read our contribution guidelines before submitting.

## Disclaimer

This list is provided for informational purposes only. Inclusion of a tool does not constitute an endorsement. Commercial tools are listed alongside open-source alternatives for completeness. Always evaluate tools against your own requirements before adopting them. Links and descriptions are accurate as of the last update but may change over time.

---

If you find this list useful, please give it a star and share it with your team.
