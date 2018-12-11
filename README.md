# emergency-bot

[Azure Bot Service][1] app that authenticates users to Azure AD (Azure Active Directory) **v2** identity provider using OAuth 2.0 protocol.

## Usage

```bash
yarn
yarn start
```

# Deployment

```bash
az bot publish -n "emergency-bot" -g "BF"
```

## References
- [Azure Bot Service][1]
- [Add Authentication to your bot](https://docs.microsoft.com/azure/bot-service/bot-builder-authentication?view=azure-bot-service-4.0&tabs=javascript)

[1]: https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
