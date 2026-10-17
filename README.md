<!-- Soji — GitHub profile README -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,45:0E7490,100:7C3AED&height=200&section=header&text=Soji&fontColor=F8FAFC&fontSize=72&fontAlignY=36&desc=AI%20Infrastructure%20%C2%B7%20DevOps%20%C2%B7%20MLOps&descSize=20&descAlignY=58&animation=fadeIn" alt="Soji — AI Infrastructure · DevOps · MLOps" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=21&pause=1100&color=22D3EE&center=true&vCenter=true&width=760&lines=Platforms+that+run+production+AI;Multi-cluster+EKS+%C2%B7+Istio+mesh+%C2%B7+Argo+CD+GitOps;GenAI+on+Bedrock+%C2%B7+SageMaker+MLOps;policy-as-code+%C2%B7+everything+as+IaC" alt="" />
</p>

### ◢ whoami

```python
class Soji:
    role   = "DevOps Lead — MLOps & AI Platform"
    former = "AWS Solutions Architect"
    focus  = ["AI infrastructure", "Kubernetes platforms", "MLOps", "GenAI / agentic"]
    ships  = "production AI workloads @ 99.9% uptime"
    motto  = "a team should onboard with one YAML file"
```

I build the platforms that run production AI — **EKS fleets, service mesh, GitOps, and the
inference pipelines** that let scientists ship models without touching infrastructure.
Currently leading DevOps for an enterprise **MLOps & GenAI** platform; formerly an **AWS Solutions Architect**.

### ◢ what I build

- **Multi-cluster EKS fleets** in Terraform — one cluster per workload class, each self-reconciling via **Argo CD** `ApplicationSets` (no central hub).
- **Zero-trust mesh** — Istio + Envoy **mTLS**, `AuthorizationPolicy`, Envoy ext-authz → **OPA that fails closed**.
- **GenAI & MLOps** — agents on **Bedrock AgentCore** (Strands SDK, MCP tools); **SageMaker** real-time/batch inference; pipelines that cut deploy time **50%**.
- **Guardrails & scale** — OPA Gatekeeper, Pod Security, default-deny netpol, IRSA; **Karpenter** (Spot/GPU) + ParallelCluster HPC.

### ◢ stack

<table border="0">
  <tr>
    <td valign="middle"><sub><b>Cloud</b></sub></td>
    <td>
      <img height="38" alt="AWS" title="AWS" src="https://raw.githubusercontent.com/github/explore/main/topics/aws/aws.png" />&nbsp;&nbsp;
      <img height="38" alt="Azure" title="Azure" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" />&nbsp;&nbsp;
      <img height="38" alt="Google Cloud" title="Google Cloud" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>K8s&nbsp;&amp;&nbsp;Mesh</b></sub></td>
    <td>
      <img height="38" alt="Kubernetes" title="Kubernetes" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" />&nbsp;&nbsp;
      <img height="38" alt="Istio" title="Istio" src="https://raw.githubusercontent.com/cncf/artwork/master/projects/istio/icon/color/istio-icon-color.svg" />&nbsp;&nbsp;
      <img height="38" alt="Argo CD" title="Argo CD" src="https://raw.githubusercontent.com/cncf/artwork/master/projects/argo/icon/color/argo-icon-color.svg" />&nbsp;&nbsp;
      <img height="38" alt="Open Policy Agent" title="Open Policy Agent" src="https://raw.githubusercontent.com/open-policy-agent/opa/main/logo/logo.png" />&nbsp;&nbsp;
      <img height="38" alt="Docker" title="Docker" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>IaC</b></sub></td>
    <td>
      <img height="38" alt="Terraform" title="Terraform" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" />&nbsp;&nbsp;
      <img height="38" alt="Pulumi" title="Pulumi" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pulumi/pulumi-original.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>AI&nbsp;/&nbsp;ML</b></sub></td>
    <td>
      <img height="38" alt="Amazon Bedrock" title="Amazon Bedrock" src="https://raw.githubusercontent.com/github/explore/main/topics/aws/aws.png" />&nbsp;&nbsp;
      <img height="38" alt="Amazon SageMaker" title="Amazon SageMaker" src="https://icon.icepanel.io/AWS/svg/Machine-Learning/SageMaker.svg" />&nbsp;&nbsp;
      <img height="38" alt="MLflow" title="MLflow" src="https://raw.githubusercontent.com/mlflow/mlflow/master/assets/icon.svg" />&nbsp;&nbsp;
      <img height="38" alt="Snowflake" title="Snowflake" src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>Observe</b></sub></td>
    <td>
      <img height="38" alt="Prometheus" title="Prometheus" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" />&nbsp;&nbsp;
      <img height="38" alt="Grafana" title="Grafana" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>CI&nbsp;/&nbsp;CD</b></sub></td>
    <td>
      <img height="38" alt="GitHub Actions" title="GitHub Actions" src="https://raw.githubusercontent.com/github/explore/main/topics/actions/actions.png" />&nbsp;&nbsp;
      <img height="38" alt="GitLab CI" title="GitLab CI" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" />
    </td>
  </tr>
  <tr>
    <td valign="middle"><sub><b>Code</b></sub></td>
    <td>
      <img height="38" alt="Python" title="Python" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />&nbsp;&nbsp;
      <img height="38" alt="Bash" title="Bash" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
    </td>
  </tr>
</table>

### ◢ certs

`NVIDIA-Certified — AI Infrastructure & Operations` · `AWS Solutions Architect – Associate` · `AWS Developer – Associate` · `AWS AI Practitioner`

<p>
  <a href="https://www.linkedin.com/in/adesoji-adetunji-a61b34163"><img height="28" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:meet-soji@outlook.com"><img height="28" src="https://img.shields.io/badge/Email-0E7490?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
</p>
