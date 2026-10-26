# Scoping Memo

**Purpose**

Lonestar Pay is establishing a formal GRC program to meet the security assurance expectations of largers customers and support business growth. The primary objective is to attain SOC 2 Type II attestation report within 12 months. Success means documented and approved policies, an operating risk management process, and controls running consistently through the audit observation period.

**Scope**

In-Scope Systems:

- AWS : Hosts the app and customer data. Includes storage, networking, logging and admin accounts.
- Okta : Single sign-on and MFA access for every other systems.
- Github : Holds production code and records who approved or deployed changes.
- AI Fraud Model : Makes automated decision based on sensitive transaction data.
- AI Support Chatbot : Talks directly to customers and there is a high probability of data leakage and prompt injection.
- Google Workspace : Stores policies, HR Records, and access review evidence. Employees may share customer data in email.
- Slack : Same risk of sensitive data in chat covered by the no customer data in chat rule.

Out of Scope Systems:

- Payment processor's own system : It is a third-party subservice organization. Lonestar collects and reviews their annual SOC 2 Type II report, and track it with vendor management.

In-Scope Data: 

- Merchant business and bank details, transaction records, employee HR data, and customer support conversations.

**Frameworks**

- Primary Audit Goal : SOC 2 because it is requested by largers customers and is the CEO's 12 month target.

- Mandatory Obligation : PCI-DSS beacuse organization enables card payment and processor holds card data.

- Supporting blueprint : NIST CSF 2.0 structures the program appropriately.

- Supporting guidance : NIST AI RMF governs the risk for the fraud model and support chatbot.

**Stakeholders**

- CEO : Sponsors the program, approves the budget, signs off the risk appetite.
- CISO : Owns the security program, approves policies, accountable for control effectiveness.
- Head of Engineering : Owns AWS, Github, and the AI Models, and make sure changes follow the approval process.
- IT admin : Runs access.
- HR : Handles background checks, security training, and employee exit steps.
- Legal : Reviews contract, privacy obligations, and vendor terms, including payment processor's
- GRC Analyst : Writes policies, runs the risk register, collects evidence, track gaps, and prepares for the audit.

**Assumptions**

- Lonestar's payment processor holds the card data, so PCI-DSS scope is reduced.
- Lonestar will pursue Security, Confidentiality and Processing Integrity in its SOC 2 Type II report.
- No formal policies or risk register exists today, so everything is built from scratch.
- Stakeholders will provide evidence on request with agreed timelines.
- The 12-month target includes the observation window, so controls must be live well before the audit.
