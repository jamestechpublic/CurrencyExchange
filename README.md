# CurrencyExchange
## Currency Exchange Manager - Evaluation Project
by James Lombard (May 2024)

C# WebAPI & Test projects created in Visual Studio 2022

Note: Please review appsettings.json file connection strings.

### Source Code File Structure
- CurrencyExchange
  - CurrencyExchangeAPI
    - Controllers
    - DataAccess
    - Extensions
    - Models
    - Services
  - CurrencyExchangeTest
  - Screenshots

### Require
- A MySQL Database Scheme
- ![image](https://github.com/jamestechpublic/CurrencyExchange/assets/74446257/bfed9a4d-9690-4187-b325-7fe9cde1da6c)
  - exchangedb
    - exchangerate
      - Currency VARCHAR(3) PRIMARY NOT-NULL UNIQUE
      - Rate DECIMAL(25,15) NOT-NULL
      - LastUpdate VARCHAR(15) NOT-NULL
- A Redis cache, running in a Docker container at localhost:6379
- Currency Exchange Data is called from:  https://api.freecurrencyapi.com/v1/latest?apikey=fca_live_8yCAXG0RLiGkyt3KaMGchoLscTgNbW4u7dk4dPTp

### Screenshots
![image](https://github.com/jamestechpublic/CurrencyExchange/assets/74446257/7265a13c-8a10-43f6-a5c1-8bc32e81a4c9)

![image](https://github.com/jamestechpublic/CurrencyExchange/assets/74446257/cfc0a54b-ad0d-44a9-8e1b-292f0067a032)

![image](https://github.com/jamestechpublic/CurrencyExchange/assets/74446257/9ba48f57-c5ce-49f7-b5aa-6bc7cb4702ec)

  End of README.md








