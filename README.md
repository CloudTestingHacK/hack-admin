# Hackathon Administration Repository

Welcome to the MOJGHCPHack4Testers hackathon administration repository!

## Ì∫Ä Self-Service Team Onboarding

Teams can onboard themselves using the automated workflow.

### How to Onboard

1. Go to [Actions tab](../../actions/workflows/self-service-onboarding.yml)
2. Click "Run workflow"
3. Fill in:
   - **Team name**: Unique, lowercase (e.g., `alpha-squad`)
   - **Team members**: GitHub usernames, comma-separated (optional)
   - **Azure location**: Select a region
4. Wait 1-2 minutes

### What Gets Created

‚úÖ GitHub Team with org admins as maintainers
‚úÖ Azure Resource Group in selected region
‚úÖ GitHub Repository with pre-configured workflows
‚úÖ Automated deployment setup

## Ì¥ê Authentication

All repositories have access to organization secrets for Azure OIDC authentication.

## Ì±• Admins

- Dominic Batstone (@Dominic-Batstone)
- Paromita Roy (@Paromita-Roy)
- Ian Curtis (@iancurtis)

## Ì≥ç Available Regions

- UK West, East US, West Europe, North Europe, West US

---

**Happy Hacking! Ìæâ**
