<h1>Kachi</h1>

<p><strong><em>LLMs learn about your business from somewhere. Kachi makes sure it's from you.</em></strong></p>

Kachi is an on-domain answer engine optimization (AEO) service. We fix marketing
websites so LLMs, agentic browsers, and AI agents can read them, understand them,
and cite them — for B2B and B2C marketing teams.

### What we do

- **Read** — make your site legible to the crawlers and agents that feed the models.
- **Understand** — structure your content so the meaning survives extraction.
- **Cite** — get your business named in the answer, not just indexed near it.

### How Kachi works

`edge collect → normalize → query → surface`

A Cloudflare Worker on each client domain ships request events to a per-client
pipeline: API Gateway → Lambda → Firehose → S3, normalized into Athena/Glue, then
read back into a multi-tenant React dashboard showing AI bot behavior and LLM
conversions per site.

### Stack

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-A47864?style=flat-square&logo=cloudflare&logoColor=F5EFE8)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-A47864?style=flat-square&logo=awslambda&logoColor=F5EFE8)
![Amazon Athena](https://img.shields.io/badge/Athena_+_Glue-A47864?style=flat-square&logo=amazonaws&logoColor=F5EFE8)
![DynamoDB](https://img.shields.io/badge/DynamoDB-A47864?style=flat-square&logo=amazondynamodb&logoColor=F5EFE8)
![Cognito](https://img.shields.io/badge/Cognito_auth-A47864?style=flat-square&logo=amazonaws&logoColor=F5EFE8)
![Terraform](https://img.shields.io/badge/Terraform-436374?style=flat-square&logo=terraform&logoColor=F5EFE8)
![React](https://img.shields.io/badge/React-436374?style=flat-square&logo=react&logoColor=F5EFE8)
![TypeScript](https://img.shields.io/badge/TypeScript-436374?style=flat-square&logo=typescript&logoColor=F5EFE8)
![Astro](https://img.shields.io/badge/Astro-436374?style=flat-square&logo=astro&logoColor=F5EFE8)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-436374?style=flat-square&logo=githubactions&logoColor=F5EFE8)

### Links

- Site — [kachi.ai](https://kachi.ai)
- Dashboard — [dashboard.kachi.ai](https://dashboard.kachi.ai)
- Research — [kachi.ai/research](https://kachi.ai/research)
- Contact — [kachi.ai/contact](https://kachi.ai/contact)

<sub>勝 — teach the models, win the conversation.</sub>
