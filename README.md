## Harsh Pashine

B.Tech Data Science student in Nagpur, India. I work on the infrastructure side of
AI systems — the pipelines, deployment, and reliability work that sits around a
model rather than the model itself.

Right now I am an AI Developer Intern at **CyberSmithSecure**, building Python
tooling around Claude's tool-use APIs: batch recovery pipelines over large
archive datasets, a dependency-free search engine, and the hardening and
container deployment that ships it all.

---

### Open source

I spend a lot of time reading other people's codebases, reproducing bugs, and
sending small fixes upstream. Merged so far:

| | |
|---|---|
| [aws/aws-cdk#38888](https://github.com/aws/aws-cdk/pull/38888) | Corrected the documented default for `arnFormat` |
| [openchamber#4468](https://github.com/openchamber/openchamber/pull/4468) | Restored window dragging on the session tab strip |
| [openchamber#4406](https://github.com/openchamber/openchamber/pull/4406) | Stopped the Find panel covering the first lines of a document |
| [openchamber#4409](https://github.com/openchamber/openchamber/pull/4409) | Lint fix that unblocked every open PR in the repo |
| [openchamber#3903](https://github.com/openchamber/openchamber/pull/3903) | Skipped unresolvable inline file mentions at send time |
| [openchamber#3224](https://github.com/openchamber/openchamber/pull/3224) | Handled `XDG_CACHE_HOME` for remote bun installs |
| [floci-io/floci#3769](https://github.com/floci-io/floci/pull/3769) | Documented ten EC2 operations missing from the action table |

I also file bugs when I cannot fix them myself — reports in
[MLflow](https://github.com/mlflow/mlflow/issues/26435) and
[Strix](https://github.com/usestrix/strix/issues/1458) have been confirmed by
maintainers and picked up by other contributors. Open work sits in
[n8n](https://github.com/n8n-io/n8n/pull/37351), [AWS
CDK](https://github.com/aws/aws-cdk/pull/38860) and a few other projects.

### Projects

**[incident-response-bot](https://github.com/hdp01/incident-response-bot)** —
polls CloudWatch for errors, asks Amazon Bedrock for a root cause, and posts a
remediation summary to Slack within a minute. Scrubs PII before anything leaves
the account.

**[nova-cost-intelligence](https://github.com/hdp01/nova-cost-intelligence)** —
AWS cost analysis that goes past the billing dashboard, using Nova Micro and
Boto3 to explain *why* a bill moved.

**[multi-cloud-deployment](https://github.com/hdp01/multi-cloud-deployment)** —
Terraform orchestrating managed Kubernetes across AWS and Azure, behind a
self-configuring Nginx gateway doing failover, passive health checks and
cross-cloud service discovery.

**[azure-aws-sync-dwbi](https://github.com/hdp01/azure-aws-sync-dwbi)** —
cross-cloud pipeline: an S3 upload fires a container-based Lambda that lands
CSVs in ADLS Gen2, then a Data Factory run merges them into Azure SQL.

### Tools I reach for

`Python` `C++` `Bash` · `FastAPI` · `PostgreSQL` `MySQL` `DynamoDB`

AWS (EC2, Lambda, ECS, S3, RDS, SQS, CloudFront, WAF, IAM) · `Terraform`
`Docker` `Ansible` `GitHub Actions` · `Nginx` `Caddy` · `Linux`

Claude tool use and function calling, RAG pipelines, token budgeting

### Certifications

AWS Certified Solutions Architect – Associate · AWS Certified AI Practitioner

---

[Email](mailto:pashineharsh01@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/harsh-pashine-434ab4223/)
