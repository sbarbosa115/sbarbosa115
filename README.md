<p align="center">
  <img src="./banner.svg" alt="Sergio Barbosa, Senior DevOps and Platform Engineer" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sbarbosa115"><img src="https://img.shields.io/badge/LinkedIn-Let's%20talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Clearwater%2C%20FL-Remote%20(US)-14707a?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Clearwater, FL, remote in the US">
  <img src="https://img.shields.io/badge/Experience-10%2B%20years-0b3b45?style=for-the-badge" alt="10+ years of experience">
</p>

**I build the platform developers stop filing tickets about.** I started out writing the apps (PHP, Python, React) and now run the cloud they live on, so I design infrastructure from the developer's side of the ticket.

## 🛠️ What I do

| | |
|---|---|
| ☁️ **Cloud automation** | Engines that provision and wire up AWS and Azure, so nobody clicks through a console or waits on a ticket. |
| ⚡ **Event-driven platforms** | EventBridge, SNS/SQS and Lambda: infrastructure that reacts to what happens instead of running on cron. |
| 🔄 **Zero-downtime modernization** | Old production systems upgraded to current versions while they keep serving traffic. |
| 🛡️ **Resilience and visibility** | Multi-cloud disaster recovery, plus ELK and New Relic so problems show up before customers notice. |
| 🤖 **AI-assisted engineering** | AI coding agents in real delivery work, and software built for them (MCP servers, agent workflows). |

## 📈 Results

<table>
  <tr>
    <td align="center" width="25%"><h2>90%</h2>less manual AWS/Azure provisioning</td>
    <td align="center" width="25%"><h2>100%</h2>of event-emitting cloud resources on one event bus</td>
    <td align="center" width="25%"><h2>0</h2>minutes of downtime across major upgrades</td>
    <td align="center" width="25%"><h2>8+</h2>third-party tools onboarded automatically</td>
  </tr>
</table>

- Upgrades on live platforms: **PHP 7.4→8.5, Python 3.7→3.13, Symfony 3.4→8.1, Vue 2→3, React 16→19**, with their CVEs cleared and about 4 years more support life.
- Test coverage on a client codebase from **0% to 40%**, and 25% fewer production bugs.

## 🧭 How my cloud automation works

```mermaid
flowchart LR
    subgraph Clouds
        A[AWS resources]
        Z[Azure resources]
    end
    A -- events --> B((Event bus<br/>EventBridge · SNS/SQS))
    Z -- events --> B
    B --> L[Automation workers<br/>Lambda · ECS · EKS]
    L --> T[Ticketing]
    L --> S[Security tools]
    L --> M[Monitoring]
    L --> D[(State<br/>DynamoDB)]
    TF[Terraform Cloud] -. provisions and DR .-> Clouds
```

Every change in AWS or Azure becomes an event. Workers pick it up and set up the ticketing, security and monitoring tools around the resource, with no manual step.

## 🧰 Stack

**Cloud**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![EventBridge](https://img.shields.io/badge/EventBridge-FF4F8B?style=flat-square&logo=amazonwebservices&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Infrastructure and operations**<br>
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Observability**<br>
![Elastic](https://img.shields.io/badge/ELK-005571?style=flat-square&logo=elasticstack&logoColor=white)
![New Relic](https://img.shields.io/badge/New%20Relic-1CE783?style=flat-square&logo=newrelic&logoColor=black)
![Sumo Logic](https://img.shields.io/badge/Sumo%20Logic-000099?style=flat-square&logo=sumologic&logoColor=white)

**Languages and frameworks**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL%20%2F%20MariaDB-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Architecture and AI**<br>
![Event-driven](https://img.shields.io/badge/Event--driven-0b3b45?style=flat-square)
![DDD](https://img.shields.io/badge/Domain--Driven%20Design-0b3b45?style=flat-square)
![Microservices](https://img.shields.io/badge/Microservices-0b3b45?style=flat-square)
![Disaster recovery](https://img.shields.io/badge/Disaster%20recovery-0b3b45?style=flat-square)
![AI agents](https://img.shields.io/badge/AI%20agents-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP%20servers-191919?style=flat-square)

## 🗺️ Career

```mermaid
timeline
    2018 : Full-stack Developer, digital agency
         : PHP (Symfony) and React, test coverage 0% → 40%
    2019 : Senior Software Engineer, automotive marketing
         : Replaced a slow WordPress system with Symfony + React
    2020 : Senior Software Engineer, payments and fintech
         : PHP monolith → event-driven AWS microservices
    2022 : Senior DevOps Engineer, cloud and managed services
         : Cloud automation engine, event bus, multi-cloud DR
    Now : Same role, plus a SaaS built end to end with AI agents
```

## 🚀 Right now

I'm designing, building and running a full SaaS product end to end with AI agents: Symfony + React, payments, background jobs on shared hosting, an MCP server for AI clients and a Telegram bot. That's most of my **5,000+ contributions** in the past year.

---

<p align="center"><b>Hiring for platform, DevOps or SRE?</b> The fastest way to reach me is <a href="https://www.linkedin.com/in/sbarbosa115">LinkedIn</a>.</p>
