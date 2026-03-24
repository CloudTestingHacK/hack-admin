# MOJGHCPHack4Testers - Self-Service Onboarding

Welcome to the **MOJGHCPHack4Testers** hackathon! This repository provides automated self-service onboarding for all teams.

---

## 🚀 Quick Start - Create Your Team

**Click the button below to get started:**

### ➡️ [**Run Team Onboarding Workflow**](https://github.com/CloudTestingHacK/hack-admin/actions/workflows/self-service-onboarding.yml)

Or manually navigate to: **Actions** → **Self-Service Team Onboarding** → **Run workflow**

---

## 📋 How to Onboard Your Team

1. **Click the workflow link above** (or go to the Actions tab)
2. Click the **"Run workflow"** button (green button on the right)
3. **Fill in the form:**
   - **Team name**: Choose a unique name (lowercase, alphanumeric, hyphens only)
     - ✅ Examples: `alpha-squad`, `team-innovators`, `cloud-champions`
     - ❌ Invalid: `Team Alpha`, `SQUAD_1`, `team.one`
   - **Team members** (optional): Add GitHub usernames, separated by commas
     - Example: `john-doe, jane-smith, dev-user`
     - ⚠️ You can add members later if needed
   - **Azure region**: Select your preferred deployment region
4. Click **"Run workflow"**
5. ⏱️ Wait ~30 seconds for completion

---

## ✨ What You Get

After the workflow completes, your team will have:

| Resource | Description |
|----------|-------------|
| **🔐 GitHub Team** | Private team with org admins as maintainers |
| **📦 GitHub Repository** | `team-{your-name}` repository with deployment workflows |
| **☁️ Azure Resource Group** | `rg-hack-{your-name}` in your selected region |
| **🔧 Deployment Workflow** | Pre-configured GitHub Actions for Azure deployments |
| **📝 Documentation** | README with links to your resources and deployment instructions |

### Your Team Repository Includes:

- ✅ **README.md** - Documentation with direct Azure portal link
- ✅ **.github/workflows/deploy.yml** - Automated Azure deployment on push
- ✅ **infra/main.bicep** - Infrastructure as Code template (ready to customize)
- ✅ **.gitignore** - Pre-configured for Azure/development files

---

## 🔒 Security & Authentication

### Organization Secrets

All team repositories automatically have access to organization-wide secrets for secure Azure authentication:

- `AZURE_CLIENT_ID` - Service principal client ID
- `AZURE_TENANT_ID` - Azure AD tenant ID  
- `AZURE_SUBSCRIPTION_ID` - Target Azure subscription

**These secrets are managed centrally - you don't need to configure anything!**

### Authentication Method

We use **Azure Workload Identity (OIDC)** - no passwords or keys needed. Your deployments authenticate securely using federated credentials.

---

## 🌍 Available Azure Regions

Choose from these regions when creating your team:

- 🇬🇧 **UK West** (`ukwest`)
- 🇺🇸 **East US** (`eastus`)
- 🇪🇺 **West Europe** (`westeurope`)
- 🇪🇺 **North Europe** (`northeurope`)
- 🇺🇸 **West US** (`westus`)

---

## 👥 Hackathon Administrators

Need help? Contact the admins:

- **Dominic Batstone** - [@Dominic-Batstone](https://github.com/Dominic-Batstone)
- **Paromita Roy** - [@Paromita-Roy](https://github.com/Paromita-Roy)
- **Ian Curtis** - [@iancurtis](https://github.com/iancurtis)

---

## ❓ FAQ

<details>
<summary><strong>Who can run the onboarding workflow?</strong></summary>

Any member of the CloudTestingHacK organization can run the workflow to create a new team.

</details>

<details>
<summary><strong>Can I add team members later?</strong></summary>

Yes! Team members are optional during onboarding. You can add collaborators to your team repository or GitHub team at any time.

</details>

<details>
<summary><strong>What if my team name is already taken?</strong></summary>

Choose a different team name. Team names must be unique across the organization.

</details>

<details>
<summary><strong>How do I deploy to Azure?</strong></summary>

Simply edit the `infra/main.bicep` file in your team repository and push to the main branch. The deployment workflow will automatically run and deploy your infrastructure to Azure.

</details>

<details>
<summary><strong>Can I change my Azure region later?</strong></summary>

Resource groups are created in a specific region during onboarding. To use a different region, modify your Bicep templates to deploy resources in other regions.

</details>

---

## 🎯 Subscription Information

**Subscription**: MOJGHCPHack4Testers  
**Subscription ID**: `d2e1eddd-6544-4763-9669-78a557c8531d`

---

**Happy Hacking! 🚀✨**
