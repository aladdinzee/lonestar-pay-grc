# Vendor Assessment Questionnaire

**Document Owner:** CISO
**Version:** 1.0
**Review Cycle:** Annual

**How is this Questionnaire used?**

1. For Critical (Tier 1) Vendors:
    - Full Questionnaire (Section A)plus SOC 2 report review.
    - Required for All Critical Questions.
    - Reviewed Annually

2. For High (Tier 2) Vendors:
    - Full Questionnaire (Section A).
    - Required for all Critical Questions
    - Reviewed Annually

3. For Medium (Tier 3) Vendors:
    - Short Checklist (Section B)
    - Self-attestation
    - Every 2 years.

4. For Low (Tier 4):
    - No assessment
    - None
    - None

Questions marked as **[C]** are Critical. A "No" or missing evidence on a Critical question requires a documented risk decision from the CISO before onboarding or renewal.

**Section A : Full Questionnaire**

1. Assurance :
    - [C] Do You Hold a current SOC 2 Type II report (issued within 12 months)?
    - Do You Hold PCI DSS, ISO 27001, or equivalent certification?
    - Where there any exceptions or qualified opinions noted in your last audit?

2. Access : 
    - [C] Is MFA Enforced for all employees and for all administrative access?
    - Is access reviewed at least quarterly?
    - Is access removed within 24 hours of employee leaving?

3. Data Protection :
    - [C] Is customer data encrypted in transit and in rest?
    - Is Lonestar's data logically separated from other customer's data?
    - Can Lonestar's data be deleted on request or at contract end?

4. Incident Response : 
    - [C] Will You notify Lonestar of a breach affecting our data within 24 hours?
    - Do you have documented incident response plan, tested in the last 12 months?

5. Subcontractors : 
    - Do you use subcontractors that handle our data?, if yes are they assessed?

6. Continuity :
    - [C] What is the your uptime commitment, and is it in the contract?
    - Do you have a tested disaster recovery plan, with recovery time stated?

7. Change Management :
    - Are production changes reviewed, tested, and approved?

8. Vulnerability Management :
     - Do you perform penetration tests at least annually?

9. Training : 
    - Do all employees complete security training annually?

10. AI (if applicable) : 
    - [C] Is Lonestar's data used to train your AI models?
    - Are AI model changes logged and validated?

**Section B : Short Checklist**

1. Do you enforce MFA for all employees?
2. Is our data encrypted in rest and in transit?
3. Will you notify us of a breach affecting our data within 72 hours?
4. Do you hold SOC 2 or ISO 27001 report?
5. Can our data be deleted at contract end?
6. Do you use subcontractors with access to our data?

**Review & Decision**

The vendor owner and GRC Analyst review responses. Gaps are recorded in the Vendor risk record with owner, remediation, or documented risk acceptance.