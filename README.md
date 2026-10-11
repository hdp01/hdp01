```console
$ whoami
harsh pashine — b.tech data science, rcoem nagpur (2024–27)

$ cat ~/.now
AI Developer Intern @ CyberSmithSecure              aug 2026 →
  claude tool-use pipelines over messy, large datasets
  archive recovery · zero-dependency search · owasp hardening
  ships as a container stack behind nginx + automated tls

$ whatidobest
the infrastructure around a model, not the model itself
```

### `$ gh pr list --author @me --state merged`

| repo | | |
|---|---|---|
| **aws/aws-cdk** | [#38888](https://github.com/aws/aws-cdk/pull/38888) | corrected the documented default for `arnFormat` |
| **openchamber** | [#4468](https://github.com/openchamber/openchamber/pull/4468) | restored window dragging on the session tab strip |
| **openchamber** | [#4406](https://github.com/openchamber/openchamber/pull/4406) | stopped the find panel covering the first lines |
| **openchamber** | [#4409](https://github.com/openchamber/openchamber/pull/4409) | lint fix that unblocked every open PR in the repo |
| **openchamber** | [#3903](https://github.com/openchamber/openchamber/pull/3903) | skipped unresolvable inline file mentions on send |
| **openchamber** | [#3224](https://github.com/openchamber/openchamber/pull/3224) | handled `XDG_CACHE_HOME` for remote bun installs |
| **floci-io/floci** | [#3769](https://github.com/floci-io/floci/pull/3769) | documented ten EC2 ops missing from the action table |

```console
$ gh issue list --author @me | wc -l
7   # reproduced, traced to a line, then written up
```

Confirmed by maintainers and picked up by other contributors in
[mlflow](https://github.com/mlflow/mlflow/issues/26435) and
[strix](https://github.com/usestrix/strix/issues/1458). Still open upstream in
[n8n](https://github.com/n8n-io/n8n/pull/37351),
[aws-cdk](https://github.com/aws/aws-cdk/pull/38860) and a few others.

### `$ ls ~/projects`

**[incident-response-bot/](https://github.com/hdp01/incident-response-bot)**
polls cloudwatch, asks bedrock for a root cause, posts the fix to slack in
under a minute — scrubbing PII before anything leaves the account

**[multi-cloud-deployment/](https://github.com/hdp01/multi-cloud-deployment)**
terraform running managed kubernetes on aws *and* azure, behind a
self-configuring nginx gateway with failover and cross-cloud discovery

**[azure-aws-sync-dwbi/](https://github.com/hdp01/azure-aws-sync-dwbi)**
s3 upload → containerised lambda → adls gen2 → data factory merge into azure sql

**[nova-cost-intelligence/](https://github.com/hdp01/nova-cost-intelligence)**
finops suite that explains *why* the bill moved, not just what it was

```console
$ cat ~/.toolbox
lang      python · c++ · bash
web       fastapi · next.js
data      postgresql · mysql · dynamodb · redis
cloud     aws — ec2 s3 iam lambda ecs ecr rds sqs ses cloudfront waf
          azure
infra     terraform · docker · kubernetes · ansible
ci/cd     github actions · jenkins
edge      nginx · caddy · linux
observe   prometheus · grafana
llm       claude tool use & function calling · rag · token budgeting

$ cat ~/.certs
aws certified solutions architect – associate
aws certified ai practitioner
```

### `$ cat ~/.contact`

[email](mailto:pashineharsh01@gmail.com) ·
[linkedin](https://www.linkedin.com/in/harsh-pashine-434ab4223/)
