# Privacy Policy — Fajr Calendar

_Last updated: 12 May 2026_

## Introduction

Blink22 built the **Fajr Calendar: Prayers Sync** app as a freemium application with optional auto-renewable subscriptions. This Privacy Policy explains what information the app collects, how it is used, and the choices available to you. By using the app you agree to the practices described in this policy. We will not share your information beyond what is described here.

If you have questions, contact us at the address at the bottom of this page.

## Information Collection and Use

To provide its core functionality — syncing Islamic prayer times into your personal calendar and helping you plan around them — Fajr Calendar collects the following information:

### Account information

When you sign in with your Google or Microsoft account, the app receives your **name, email address, and profile picture URL** from the chosen provider. These are stored on our servers and associated with your Fajr Calendar account so that we can authenticate you on subsequent sessions and personalize your experience.

### Calendar data

The app accesses your Google Calendar or Microsoft Outlook Calendar on your behalf via the official Google Calendar API and Microsoft Graph API. To enable prayer time sync and event creation:

- We read calendar metadata (event titles, start/end times, busy status) needed to display your schedule and avoid overlap with prayer events. This data is read directly from Google or Microsoft and is **not** stored on our servers.
- When you create an event from inside Fajr Calendar, the event details you enter (title, start and end times, color, busy status, and any guest email addresses you add) are sent through our servers only to relay the creation request to Google Calendar or Microsoft Graph on your behalf. We do **not** retain event content on our servers after the request is completed.
- We do **not** sell or share your calendar content with third parties for advertising.

### Contacts

With your permission, the app reads your contacts from Google People API or Microsoft Graph (read-only) so that you can invite people to events you create. Contact data is used in-memory on the device for the autocomplete experience and is not persisted on our servers.

### Location data

With your permission, the app uses your **device location** to compute accurate prayer times for your area. Location is requested only while you are using the app ("When In Use"). You can choose to share precise or approximate location at the system prompt, and you can decline this permission entirely and enter a city manually instead; in that case no device location data leaves your device.

### Prayer and app settings

We store your preferences — calculation method, madhab, prayer reminders, language, calendar selection, and similar — on our servers so that they remain consistent across devices.

### Subscription information

If you purchase a subscription, Apple processes the payment through the App Store. Apple shares with us a subscription receipt indicating which plan you bought and its status. We do **not** receive your credit card number, billing address, or any other payment details.

### Usage analytics

To understand how the app is used and improve its quality, we collect **anonymized usage analytics** through Firebase Analytics — for example, which screens are visited, which features are used, and aggregated counts of events such as logins, prayer-sync completions, and subscription purchases. These events do not contain the content of your calendar or your contacts.

### Device information

We collect non-identifying device data (device model, operating system version, app version) to diagnose issues and ensure compatibility.

## Third Party Access

We only share information with third parties to the extent necessary to provide the app's functionality. The third parties used by Fajr Calendar are:

- **Google Sign-In and Google Calendar / People APIs** — to authenticate you and to read or write calendar events and contacts you have authorized. See Google's privacy policy: https://policies.google.com/privacy
- **Microsoft Authentication Library (MSAL) and Microsoft Graph** — to authenticate you and to read or write calendar events and contacts you have authorized. See Microsoft's privacy statement: https://privacy.microsoft.com/privacystatement
- **Apple App Store / StoreKit** — to process auto-renewable subscriptions. See Apple's privacy policy: https://www.apple.com/legal/privacy/
- **Firebase Analytics and Remote Config (Google)** — to collect anonymized usage analytics and remotely configure feature flags. See Firebase's privacy information: https://firebase.google.com/support/privacy

We may also disclose information when required by law, to enforce our terms, to investigate fraud, or to protect the safety of our users.

## Permissions Used by the App

| Permission | Why it is requested |
|---|---|
| Calendar (via OAuth) | Read your events to avoid overlap with prayer times; write prayer and user-created events |
| Contacts (via OAuth) | Suggest contacts when you invite guests to events |
| Location (When In Use) | Compute accurate prayer times for your location |
| Notifications | Deliver prayer and event reminders locally on your device |

All permissions are optional except those strictly required for the feature you are using. The app will continue to function in reduced form if you decline any optional permission.

## Account Deletion

You can delete your Fajr Calendar account at any time directly from inside the app, under **Profile → Delete Account**. Deleting your account:

- Removes your profile, app preferences, and saved settings from our servers.
- Revokes the OAuth tokens we hold for your Google or Microsoft account.
- Removes prayer events created by the app from your connected calendar.

Account deletion is permanent and cannot be undone. Events you created manually in your own calendar are not deleted — those remain under your control in Google or Microsoft. If you have an active subscription, you may need to cancel it separately in your Apple App Store subscriptions settings.

If for any reason you are unable to delete your account from the app, email us at the address below and we will process the request within a reasonable time.

## Opt-Out and Data Retention

You can stop further data collection at any time by signing out, revoking the app's access from your Google or Microsoft account settings, or uninstalling the app. Information already collected is retained only as long as your account is active or as needed to provide the service. After account deletion, residual data is removed from active systems within a reasonable period, except where retention is required by law.

You can request a copy of your data, or request its earlier deletion, by emailing us at the address below.

## Subscriptions

Fajr Calendar offers optional auto-renewable subscriptions. Payment is charged to your Apple ID at confirmation of purchase. Subscriptions automatically renew unless auto-renew is turned off at least 24 hours before the end of the current period. You can manage and cancel subscriptions in your Apple ID account settings. Refund requests are handled by Apple. The terms governing subscriptions are described in the app's Terms of Use (EULA).

## Children's Privacy

Fajr Calendar is not directed to children under 13 and we do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will promptly delete it.

## Security

We use commercially reasonable safeguards to protect the information collected by the app, including encrypted transport (HTTPS) for all network traffic and encryption of sensitive values stored on your device. No method of transmission or storage is 100% secure, so we cannot guarantee absolute security.

## Changes to this Policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top of this page indicates when the latest revision was published. Continued use of the app after a change constitutes acceptance of the revised policy.

## Contact Us

If you have questions or requests regarding this Privacy Policy or your data, contact us at:

**Email:** developer@blink22.com
**Developer:** Blink22
