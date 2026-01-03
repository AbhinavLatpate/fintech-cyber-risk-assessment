# FinTech Cybersecurity Risk Assessment – PayWave

## 1. Business Overview
PayWave is a FinTech company that provides digital wallet and payment
processing services for retail customers and small merchants across
the European Union. The platform enables users to store funds, make
peer-to-peer payments, and process merchant transactions through web
and mobile applications. PayWave generates revenue primarily through
transaction-based fees.

## 2. Core Business Functions
- Customer onboarding and identity verification (KYC)
- Digital wallet and balance management
- Payment processing and transaction authorization
- Merchant payment settlement
- API integrations with banks and third-party services

## 3. Critical Assets

### Information Assets
- Customer personal data (PII)
- Financial transaction records
- Authentication credentials
- API keys and cryptographic secrets

### Technical Assets
- Web and mobile applications
- Backend payment processing services
- Cloud infrastructure hosted on AWS
- Databases storing customer and transaction data

### Business Assets
- Company reputation and customer trust
- Regulatory compliance status (GDPR, PCI-DSS)
- Revenue generated from transaction fees
- Relationships with customers, merchants, and partners

## 4. High-Level System Architecture
Users access the PayWave platform through web and mobile applications.
Requests are routed through API gateways to backend microservices
hosted on cloud infrastructure. Customer and transaction data are
stored in managed databases, while third-party banking APIs are used
for payment settlement and verification.

## 5. Business Impact Dependencies
- Downtime in the payment processing system directly impacts revenue.
- Exposure of customer data may result in regulatory penalties and
  reputational damage.
- Compromise of APIs could lead to fraudulent transactions and
  financial losses.
- Service outages may result in SLA breaches with merchants and
  partners.
