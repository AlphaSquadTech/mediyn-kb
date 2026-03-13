# How to Set Up Integrations

Mediyn lets you connect your EHR/EMR system so patient data stays synchronized across platforms.

![Integrations](../images/clinic/settings-integrations.png)

## Steps

1. Go to **Settings** in Mediyn.
2. Select **Integrations**.
3. Select **Add Integration**.
4. Choose the integration type.
5. Provide the required configuration details.
6. Save and activate the connection.

## You'll Need to Provide

- **Integration type** — Currently, Mediyn supports FHIR connections
- **Configuration details** — The settings required to connect to your specific EHR/EMR system (your EHR vendor or IT team can provide these)

## What to Expect

After saving the integration:
- Mediyn creates the connection and sets the status to **Active**.
- Data will begin syncing between Mediyn and your EHR/EMR system.
- You can monitor the connection health and sync history at any time.

## Viewing Your Integrations

1. Go to **Settings** and select **Integrations**.
2. You will see a list of all your integration connections.
3. Each connection shows its type, status, and when it was created.

## What to Do If Setup Fails

If the integration status shows **Error** after setup:
- Verify that the configuration details are correct.
- Check with your EHR vendor or IT team to confirm the connection settings.
- Try removing the integration and setting it up again with corrected details.

## Good to Know

- Only clinic administrators can set up integrations.
- You can have multiple integrations if your practice uses more than one external system.
- Mediyn does not automatically disable a working integration. If the status changes to Error, it usually means something changed on the external system's side.
- Contact Mediyn support if you need help with configuration details for your specific EHR/EMR system.
