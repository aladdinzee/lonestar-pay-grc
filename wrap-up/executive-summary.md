# Executive Summary Report : Lonestar Pay GRC Program

**Bottom Line**

Lonestar Pay now has the governance foundation needed for the SOC 2 Type II report : policies, a risk process, and a control framework. Today, though, only 1 of 10 key controls is ready. Two risks remain High, and 12-month SOC 2 goal is at risk unless fixes are completed by Mid-December. 

We Need your approval of the remediation plan, and a decision on interim Type I report, by November 6, 2026.

**Where We Stand**

1. Policies & Governance Documents :
    - 4 policies
    - Risk Method
    - Completed RACI Chart

2. Risks assessed : 
    - 8, with 2 still High after existing controls.

3. Key controls Tested : 
    - 10 : 1 Ready, 4 Partial, 5 Gap

4. Remediation Items :
    - 9, with all owners.

5. Vendors assessed :
    - 8 inventoried.
    - Payment Processor Reviewed.

6. AI systems Govered :
    - Fraud model and support chatbot assessed.

**Top risks, in plain terms**

1. Support chatbot could reveal one merchant's data to another. The chatbot has no filtering and has never been tested against manipulation. A leak would hurt customers and would likely require notification.

2. Our payment processor is a single point of failure. If it goes down or breached, we cannot take payments. Its audit report shows weaknesses, and our own gaps weaken the protection it offers us.

3. A developer could accidentally push a secret key in our code. Protection is switched off as of today. Turning it on is a low-cost fixe and closes one of the processor's requiremnet for us.

**Timeline**

A Type II report needs controls consistently running through an observation window, typically six months or more. The window cannot be realistaclly start before February since our Last fix is dated in January. A six-month window would end in August 2027, with the report following about a month later. A report within 12 months is therefore possible but tight, with little room for delay. 

**Recommendation**

Pursue Type I report in early 2027 as an interim milestone. It confirmes that our controls are designed properly in time and gives larger customers something concrete sooner, while the Type II window runs.

**Decisions Needed**

1. Approve the remediation plan and asisgn the owners in it by Nov 6.

2. Decide wheteher the pursue Type I report as an interim milestone by Nov 20.

3. Apporve a security training platform, an incident ticketing tool, and chat data loss protection by Nov 20.

4. Direct Legal to negotitate with with payment processor contract (24-hour breach notice, data use terms) before renewal of Contract.

**Next 90 days**

1. Close the quick wins : contractor MFA, secret scanning, encryption of 2 backup buckets.

2. Run the first access review and fix offboarding to meet the 24-hour standard.

3. Launch security training and incident ticketing.

4. Add filtering and manipulation testing for the support chatbot.

5. Complete vendor conditions for the payment processor and begin readiness for the audit window.

