# Tips for Integrations

## Recommendations

- **Check integration health weekly** — A quick health check catches connection problems before they affect patient data.

- **Review sync history after EHR changes** — Whenever your EHR/EMR system is updated or reconfigured, check Mediyn's sync history to confirm data is still flowing correctly.

- **Keep configuration details documented** — Store your integration settings securely so you can quickly re-enter them if you ever need to reconnect.

- **Set up integrations early** — Connect your EHR/EMR during your initial Mediyn setup so data stays in sync from day one.

- **Address degraded connections promptly** — A degraded status may resolve on its own, but do not ignore it. Investigate if it persists for more than a day.

- **Coordinate with your IT team** — Your EHR vendor or IT team can provide the configuration details you need. Loop them in before starting the setup process.

## Common Questions

**Q: How often does Mediyn sync data with my EHR system?**
A: Syncs happen automatically on a regular schedule. You can also trigger a manual sync at any time.

**Q: Will a manual sync create duplicate records?**
A: No. Manual syncs are safe to run at any time without creating duplicates.

**Q: What EHR systems does Mediyn support?**
A: Mediyn currently supports FHIR-compatible EHR/EMR systems. Contact Mediyn support to confirm compatibility with your specific system.

**Q: Can I connect more than one EHR system?**
A: Yes. You can set up multiple integrations if your practice uses more than one external system.

**Q: What should I do if my integration keeps failing?**
A: Check the sync history for error patterns, verify your configuration details, and confirm your EHR system is online. Contact Mediyn support if the issue persists.

**Q: Who can manage integrations?**
A: Only clinic administrators can set up, view, and manage integrations.
