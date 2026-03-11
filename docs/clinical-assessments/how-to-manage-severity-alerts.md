# How to Manage Severity Alerts

Mediyn can notify you automatically when a patient's assessment score crosses a threshold you define, so you never miss a critical change.

## Creating an Alert Rule

1. Go to the **Assessment Alerts** settings.
2. Choose **Create Alert Rule**.

You'll need to provide:
- **Instrument** -- The screening tool this rule applies to (e.g., PHQ-9)
- **Threshold score** -- The score that triggers the alert
- **Comparison** -- When to trigger the alert. Available choices:
  - Score is **equal to or above** the threshold
  - Score is **above** the threshold
  - Score is **equal to or below** the threshold
  - Score is **below** the threshold
  - Score **equals** the threshold exactly
- **Who to notify** -- The roles that should receive the alert (e.g., therapist, clinic administrator)

### What to Expect

- The rule is created and starts monitoring immediately.
- Whenever a patient completes an assessment for the specified instrument and their score meets the condition, the designated roles receive a notification.

## Viewing Existing Alert Rules

- Open the **Assessment Alerts** settings.
- You see all alert rules for your practice.
- You can narrow down by instrument to find specific rules.

### What to Expect

- Each rule shows the instrument, threshold score, comparison type, and who gets notified.
- You can see who created the rule and when.

## Good to Know

- Alert rules apply across all patients in your practice. You do not need to set them up per patient.
- You can create multiple rules for the same instrument with different thresholds. For example, one alert at a moderate severity level and another at a severe level.
- Alerts are especially valuable when used with recurring assessments. They help you catch deterioration early.
- Severity alerts are notifications only. They do not change the patient's treatment plan or create any automatic actions. You decide how to respond.
- Common use cases include:
  - PHQ-9 score of 15 or above (moderately severe depression)
  - GAD-7 score of 10 or above (moderate anxiety)
  - Any instrument flagging suicide risk items
