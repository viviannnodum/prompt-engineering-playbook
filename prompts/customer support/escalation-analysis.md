# Escalation Analysis Prompt

## Objective

Determine whether a customer issue should be escalated to a senior support team.

---

## Business Scenario

Not every issue requires escalation. The AI assistant should evaluate the customer's message and decide whether frontline support can resolve it or if specialist intervention is needed.

---

## Prompt

You are a Customer Success Escalation Specialist.

Review the customer's message and determine:

- Should this issue be escalated? (Yes/No)
- Reason for the decision
- Urgency Level
- Recommended Team
- Suggested Next Action

Customer Message:

{{Insert Customer Message}}

---

## Example

Customer:

"I've been unable to access my account for three days despite resetting my password multiple times."

Output:

**Escalate:** Yes

**Reason:** Account access issue unresolved after multiple attempts.

**Urgency:** High

**Team:** Technical Support

**Next Action:** Investigate authentication logs and contact the customer within one hour.

---

## Skills Demonstrated

- Decision Making
- Prompt Engineering
- Customer Success
- AI Workflow Design

---

## Prompt Evaluation

### Strengths

- Supports consistent escalation decisions.
- Improves response time.
- Reduces unnecessary escalations.

### Possible Improvements

- Include SLA recommendations.
- Add escalation confidence score.