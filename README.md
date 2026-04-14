# Sovereign Cloud Docs

Interactive reference showing which Azure services are available on **Azure Local** — including whether they run fully on-premises, as hybrid cloud-connected services, or in disconnected/air-gapped sovereign environments.

## 🌐 View the Page

Open `index.html` in any browser — no server required.

## Features

- **Products-by-Region style table** — inspired by [azure.microsoft.com/products-by-region](https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/table)
- **40+ Azure services** cataloged with status (GA / Preview)
- **Deployment model badges** — On-Premises vs Hybrid at a glance
- **Connected & Disconnected columns** — see what works air-gapped
- **Search & filter** — find services instantly by name, category, or status
- **Direct documentation links** — click any service to open Microsoft Learn docs
- **Hover tooltips** — get quick context without leaving the page

## Categories Covered

| Category | Examples |
|----------|----------|
| Compute | Arc VMs, AKS Arc, AVD, GPU Workloads, Trusted Launch |
| Application Platform | App Service, Azure Functions, API Management, Event Grid |
| Data Services | SQL MI (Arc), SQL Server (Arc), PostgreSQL, Managed Lustre |
| AI & ML | Foundry Local, IoT Operations, ML (Arc-enabled) |
| Identity & Security | Entra ID, Key Vault, Defender for Cloud, NSGs |
| Management & Governance | Azure Arc, Portal, Policy, Monitor, Update Manager |
| Networking | SDN, VPN/ExpressRoute, Extended Network |
| Storage | S2D, Azure Backup, Site Recovery, File Sync |
| Sovereign & Disconnected | Air-Gapped Ops, M365 Local, Azure Verification |
| Migration | Azure Migrate, VMware Migration |
| Observability | Observability, Remote Support, Log Analytics, Alerts |

## Contributing

PRs welcome! Add services to the `services` array in `index.html`.
