# Risk Treatment Plan

**Prepared by:** GRC Analyst
**Approved by:** CEO (High Risks), CISO
**Version:** 1.0
**Review Cycle:** Quarterly

*Scores and actions are analyst porposals pending owner validation.*

**Prioritized Methods**

Risks are prioritized based on residual score. Where scores are equal, lower-cost and faster fixes are scheduled first.

# Priority 1 : R006 - Chatbot Reveal's another merchant data.
- Residual : 16 (High). Not acceptable above Medium without CEO approval.
- Owner : Head of Engineering
- Treatment : Mitigate
- Actions :
    1. Restrict chatbot data access to active merchant only.
    2. Add output filtering for sensitive data.
    3. Add adversarial and prompt-injecting testing to the release checklist.
    4. Log all chat conversations and review samples monthly.
- Target Date : Simulated Date
- Success measure : Test cases confirm that cross-merchant data cannot be retrieved. residual score target is 8 (L2 X I4)

# Priority 2 : Payment Processor Outage or Breach.
- Residual : 15 (High)
- Owner : CISO
- Treatment : Mitgate or Transfer
- Actions : 
    1. Collect processor's latest SOC 2 Type II and PCI-DSS reports.
    2. Legal reviews the contract for uptime gurrantee and breach notification terms.
    3. Obtain cyber insurance quotes.
    4. Establish annual vendor review.
- Target Date : Simulated Date
- Success Measure : Reports are reviewed and gaps documented. SLA and insurance in place. residual score target is 10 (L2 X I5)

# Priority 3 : Secret Committed to Github.
- Residual : 12 (Medium)
- Owner : Head of Engineering
- Treatment : Mitigate
- Actions : 
    1. Enable secret scanning with push protection on all repositories.
    2. Scan history for exisitng exposed secrets and rotating keys.
    3. Add a short secret-handling section to developer training.
- Target Date : Simulated Date
- Success Measure : Push protection on 100% of repositories. reisudal score target is 6 (L2 X I3)

**Other Risks**

R001, R002, R003, R007, and R008 are tracked in risk register with Medium residual ratings, and are reviewed quarterly.

