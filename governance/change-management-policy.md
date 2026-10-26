# Change Management Policy

**Document Owner:** Head of Engineering
**Approved by:** CISO
**Version:** 1.0(Draft)
**Effective Date:** Simulated date
**Review Cycle:** Annual

**Purpose**

To ensure changes to Lonestar Pay production systems are reviewed, tested, approved, and traceable, reducing the risk of errors, outage and unauthorized modifications.

**Scope**

Applies to all changes to production systems, including application code (Github), cloud infrastructure and configurations (AWS), indentity settings (Okta), and AI models.

**Roles & Responsibilities**

- Head of Engineering : Owns this policy and the deployment pipeline.
- Engineers : authors changes and perform peer reviews.
- CISO : approves exceptions and reviews high-risk changes.
- GRC Analyst : samples changes to verify compliance and retain evidence.

**Policy Statements**

1. Peer review : Every production change requires review from atleast one engineer other than the author.

2. Testing : Automated tests must pass before a change is eligible for deployment.

3. Deployment : Changes are deployed to production only through the automated pipeline after approval. Direct mannual deployment to production is prohibited.

4. Emergency changes : In an emergency, a change may bypass the normal process with verbal approval from Head of Engineering or CISO. Written Approval and a post change review must be completed within 24 hours.

5. AI Model changes : Retraining, updating, or replacing an AI model requires : (a) validation of accuracy and error rates against historical data. (b) review of training data sources, and (c) documented sign-off from Head of Engineering before release.

6. Traceability : Each change record must include the author, reviewer, test results, approval and deployment date.

**Exceptions**

Exceptions require written CISO approval and an expiration date.

**Enforcement**

Violations may result in access removal and disciplinary action.

**Review**

This policy is reviewed atleast annually, or after major incidents.