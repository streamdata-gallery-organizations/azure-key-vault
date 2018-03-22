---
name: Azure Key Vault
description: Azure Key Vault offers an easy, cost-effective way to safeguard keys
  and other secrets in the cloud by using hardware security modules (HSMs). Protect
  cryptographic keys and small secrets like passwords with keys stored in HSMs. For
  added assurance, import or generate your keys in HSMs that are certified to FIPS
  140-2 level 2 and Common Criteria EAL4+ standards, so that your keys stay within
  the HSM boundary. Key Vault is designed so that Microsoft does not see or extract
  your keys. Create new keys for Dev-Test in minutes and migrate seamlessly to production
  keys managed by security operations. Key Vault scales to meet the demands of your
  cloud applications without the hassle required to provision, deploy, and manage
  HSMs and key management software.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-enhance-data-protection.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Security
- Microsoft
- Management
- Authentication
created: "2018-03-21"
modified: "2018-03-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-key-vault/master/_listings/azure-key-vault/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Key Vault API
  description: Azure Key Vault offers an easy, cost-effective way to safeguard keys
    and other secrets in the cloud by using hardware security modules (HSMs)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-enhance-data-protection.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags:
  - Stack Network
  - Security
  - Microsoft
  - Management
  - Authentication
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-key-vault/master/_listings/azure-key-vault/subscriptions-subscriptionid-resources-get.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/key-vault/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/key-vault/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/key-vault/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/key-vault/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---