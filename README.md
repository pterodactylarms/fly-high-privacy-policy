# Privacy Policy for Fly High

**Last Updated:** September 30, 2026

Fly High ("the App") is an independent utility application designed to provide information regarding official U.S. flag proclamations, half-staff schedules, and flag etiquette guidelines. 

### 1. Data Collection & Privacy First Commitment
The developer of Fly High believes in strict user privacy. **The App does not collect, store, transmit, or share any Personally Identifiable Information (PII).**

* **No User Accounts:** You are not required to create an account, log in, or provide an email address to use the App. Ever.
* **No Tracking:** The App does not track your personal identity, device identifiers, or online activity.
* **No Analytics:** The App does not contain third-party tracking or advertising SDKs.

### 2. Location & ZIP Code Data
To provide accurate sunrise, sunset, and localized flag status information:
* The App requests a ZIP code during setup. 
* This ZIP code is processed locally on your device to fetch approximate geographical coordinates for solar timing calculations.
* Your ZIP code and location coordinates remain stored locally on your device using encrypted local storage (DataStore) and are **never uploaded to external servers or sold to third parties**.

### 3. Remote Data Requests
To keep calendar information current:
* The App periodically fetches a static, JSON configuration file containing national and state flag proclamations maintained by the developer on the developers personal webhosting.
* The App queries public astronomical data (SunriseSunset.io) strictly to calculate sunrise and sunset offsets based on local coordinates. These queries carry no personal user identifiers.

### 4. System Permissions
* **Notifications (`POST_NOTIFICATIONS`):** Used solely to deliver local daily reminders regarding flag status (full-staff vs. half-staff) at the user's requested time.
* **Internet Access (`INTERNET`):** Used strictly to download updated flag proclamation files and solar calculations.

### 5. Children's Privacy
Because the App does not collect any personal data, it fully complies with the Children's Online Privacy Protection Act (COPPA) and does not target or collect data from children under the age of 13.

### 6. Contact & Support
If you have questions regarding this privacy policy or the application, please reach out via the official developer support email provided on the Google Play Store listing.
