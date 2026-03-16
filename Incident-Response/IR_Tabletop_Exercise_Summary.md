### Incident #2026-042: Unauthorized Access Attempt
**Date:** March 10, 2026
**Summary:** An offshore support credentials were used from an unauthorized IP address.

**GRC Analysis:**
* **Policy Violation:** Violation of *POL-SEC-004 (Geofencing)*.
* **Regulatory Impact:** No PII was exfiltrated; therefore, GDPR/CCPA notification is **NOT** required.
* **Root Cause:** The offshore vendor failed to update their static IP range in our whitelist.
* **Corrective Action:** Update Vendor Security Agreement (VSA) to include financial penalties for failure to report infrastructure changes within 24 hours.
