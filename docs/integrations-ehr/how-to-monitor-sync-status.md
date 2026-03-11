# How to Monitor Sync Status

Mediyn lets you check the health of your integrations and review sync history to make sure data is flowing correctly.

## Checking Integration Health

1. Go to **Settings** and select **Integrations**.
2. Select the integration you want to check.
3. Select **Health** or **Diagnostics**.
4. You will see the current health status:
   - **Healthy** — The connection is working as expected
   - **Degraded** — The connection is working but experiencing some issues
   - **Failed** — The connection is not working

The health check also shows when the status was last verified.

## Viewing Sync History

1. Go to **Settings** and select **Integrations**.
2. Select the integration you want to review.
3. Select **Sync History** or **Sync Runs**.
4. You will see a list of all past sync events.

## Triggering a Manual Sync

If you need to send data to your EHR/EMR system right away:

1. Go to **Settings** and select **Integrations**.
2. Select the integration.
3. Select **Sync Now** or **Trigger Sync**.
4. Mediyn will start a new sync run immediately.

## What to Do If the Health Status Shows "Failed"

1. Check the sync history for recent errors or patterns.
2. Verify that your EHR/EMR system is online and accepting connections.
3. Review the integration configuration to confirm the settings are still correct.
4. If the issue persists, contact your EHR vendor or Mediyn support for help.

## What to Do If the Health Status Shows "Degraded"

A degraded status usually means the connection is working but slower or less reliable than expected. This may resolve on its own. If it persists:

1. Check the sync history for any failed runs.
2. Verify that the external system is not experiencing downtime.
3. Contact Mediyn support if the issue continues.

## Good to Know

- Health checks reflect the most recent connection test. The "last checked" date and time helps you understand how current the status is.
- Sync runs are recorded automatically. You do not need to manually trigger a sync under normal conditions.
- Manual syncs are safe to trigger at any time. They will not create duplicate records.
- Review sync history after any changes to your EHR/EMR system to confirm data is still flowing correctly.
