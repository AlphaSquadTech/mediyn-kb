# How to Manage Redaction Policies

Mediyn lets you set up redaction policies to control how sensitive patient data is masked or hidden across your practice.

## Viewing Your Redaction Policies

1. Go to **Settings** or **Compliance** in Mediyn.
2. Select **Redaction Policies**.
3. You will see a list of all active redaction policy profiles.

## Understanding Redaction Policies

Redaction policies define rules for how sensitive information is handled. Each policy profile contains rules that determine:
- What types of data are checked
- How data is masked or hidden
- Which contexts the policy applies to

## PHI Masking Rules

In addition to redaction policies, Mediyn supports role-based PHI masking. These rules control which fields are visible to different roles in your practice. This means a front-desk staff member might see different patient details than a treating therapist.

To view your PHI masking rules:

1. Go to **Settings** or **Compliance**.
2. Select **PHI Masking** or **Data Visibility Rules**.

## Recording Redaction Events

When data is processed through a redaction policy, Mediyn records the outcome for compliance purposes. Each redaction event captures:

- Which session was involved
- Which redaction policy was applied
- Whether the check passed or found issues
- How many items were flagged

## What to Expect

Redaction policies work automatically in the background. Once configured, they apply to data as it flows through Mediyn. You do not need to manually redact information.

## Good to Know

- Redaction policies help your practice meet privacy and data protection requirements.
- PHI masking is based on team member roles. Changing someone's role may change what patient data they can see.
- Redaction events create an audit trail. This is useful for demonstrating compliance during reviews.
- Contact your Mediyn administrator if you believe your visibility settings need to be adjusted.
