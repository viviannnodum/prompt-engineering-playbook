# Ticket Classification Prompt

## Objective

Classify incoming customer support tickets into the correct category and priority to improve response efficiency and routing.

---

## Business Scenario

A SaaS company receives hundreds of customer support requests daily. The AI assistant must identify the issue type and assign the correct support team while recommending an appropriate priority level.

---

## Prompt

You are an AI Support Operations Assistant.

Analyze the customer message and provide:

1. Ticket Category
2. Priority (Low, Medium, High, Critical)
3. Brief Summary
4. Recommended Team
5. Suggested First Response

Customer Message:

{{Insert Customer Message}}

---

## Expected Output

**Category:** Billing

**Priority:** High

**Summary:** Customer reports being charged twice for the same subscription.

**Team:** Billing Support

**Suggested First Response:**

Thank you for contacting us. We understand your concern regarding the duplicate charge. Our billing team will review your account immediately and provide an update as soon as possible.

---

## Skills Demonstrated

- Prompt Engineering
- Text Classification
- Workflow Automation
- Customer Support Operations

---

## Prompt Evaluation

### Strengths

- Produces structured output.
- Improves ticket routing.
- Easy to integrate with helpdesk systems.

### Possible Improvements

- Add confidence score.
- Support multilingual tickets.
- Integrate sentiment analysis.