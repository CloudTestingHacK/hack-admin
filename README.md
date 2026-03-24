# Hackathon Administration Repository

Welcome to the **MOJGHCPHack4Testers** hackathon administration repository!

## 🚀 Self-Service Team Onboarding

Teams can onboard themselves using the automated workflow.

### How to Onboard

1. Go to the [Actions tab](../../actions/workflows/self-service-onboarding.yml)
2. Click **Run workflow**
3. Fill in the following details:
   - **Team name**: Unique, lowercase (e.g., `alpha-squad`)
   - **Team members**: GitHub usernames, comma-separated (optional)
   - **Azure location**: Select a region
4. Wait 1–2 minutes for the workflow to complete

### What Gets Created

- ✅ GitHub Team with org admins as maintainers
- ✅ Azure Resource Group in the selected region
- ✅ GitHub Repository with pre-configured workflows
- ✅ Automated deployment setup

## 🔐 Authentication

All repositories have access to organisation secrets for Azure OIDC authentication.

## 👥 Admins

- Dominic Batstone ([@Dominic-Batstone](https://github.com/Dominic-Batstone))
- Paromita Roy ([@Paromita-Roy](https://github.com/Paromita-Roy))
- Ian Curtis ([@iancurtis](https://github.com/iancurtis))

## 🌍 Available Regions

| Region       |
|--------------|
| UK West      |
| East US      |
| West Europe  |
| North Europe |
| West US      |

---

**Happy Hacking! 🎉**
