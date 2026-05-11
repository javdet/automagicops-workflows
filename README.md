# AutomagicOps Workflows

A collection of ready-to-use [n8n](https://n8n.io/) workflow templates designed to automate DevOps, SRE, and Platform Engineering processes. Each workflow leverages AI agents and MCP servers to handle routine operational tasks autonomously.

## Workflows

| Workflow | Description | n8n Template |
|----------|-------------|:------------:|
| [Alert Assistant](workflows/AlertAssistant/README.md) | Automatically analyzes infrastructure alerts from Alertmanager and suggests solutions before an on-call engineer even sees them. | X |
| [CI/CD Assistant](workflows/CI_CDAssistant/README.md) | Analyzes the causes of CI/CD build failures in GitLab and proposes fixes without involving DevOps engineers. | [Download](https://n8n.io/workflows/14129-analyze-gitlab-ci-job-failures-with-gpt-53-and-send-reports-to-slack/) |
|[Chat Assistant](workflows/chatAssistant/README.md) | A set of workflows that solves the problem of technical support in Mattermost | [Download](https://n8n.io/workflows/15051-classify-and-route-devops-chat-requests-with-mattermost-openrouter-and-google-calendar) |

## License

MIT. See [LICENSE](LICENSE). Use and redistribution are allowed; if you publish or distribute this project (or a derivative), you must keep the license and copyright notice, which includes a link to this repository.
