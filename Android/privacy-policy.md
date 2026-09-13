# Privacy Policy — Fajr Calendar for Android

_Last updated: 13 September 2026_

_This policy applies to the **Fajr Calendar: Prayers Sync** app for **Android**, distributed through Google Play._

## Introduction

Blink22 built the **Fajr Calendar: Prayers Sync** app as an application with free options and optional auto-renewable subscription plans. This Privacy Policy explains what information the Android app collects, how it is used, and the choices available to you. By using the app you agree to the practices described in this policy. We will not share your information beyond what is described here.

If you have questions, contact us at the address at the bottom of this page.

## Information Collection and Use

To provide its core functionality — syncing Islamic prayer times into your personal calendar and helping you plan around them — Fajr Calendar collects the following information:

### Account information

When you sign in with your Google or Microsoft account, the app receives your **name, email address, and profile picture URL** from the chosen provider. These are stored on our servers and associated with your Fajr Calendar account so that we can authenticate you on subsequent sessions and personalize your experience.

### Calendar data

The app accesses your Google Calendar or Microsoft Outlook Calendar on your behalf via the official Google Calendar API and Microsoft Graph API. To enable prayer time sync and event creation:

- We read calendar metadata (event titles, start/end times, busy status) needed to display your schedule and avoid overlap with prayer events. This data is read directly from Google or Microsoft and is **not** stored on our servers.
- When you create an event from inside Fajr Calendar, the event details you enter (title, start and end times, color, busy status, and any guest email addresses you add) are sent through our servers only to relay the creation request to Google Calendar or Microsoft Graph on your behalf. We do **not** retain event content on our servers after the request is completed.
- To keep your agenda readable while offline, the app may keep a copy of recently viewed events in **encrypted storage on your own device**. This on-device cache never leaves your device and is cleared when you sign out or delete your account.
- We do **not** sell or share your calendar content with third parties for advertising.

### Contacts

With your permission, the app reads your contacts from Google People API or Microsoft Graph (read-only) so that you can invite people to events you create. Contact data is used in-memory on the device for the autocomplete experience and is not persisted on our servers. The app does **not** read the contacts stored locally in your device's own address book, and does not request the Android `READ_CONTACTS` permission.

### Location data

With your permission, the app uses your **device location** to compute accurate prayer times for your area. Location is requested only while you are actively using the app — the app never requests or receives your location in the background, and does not declare the `ACCESS_BACKGROUND_LOCATION` permission. You can choose to share precise or approximate location at the system prompt, and you can decline this permission entirely and enter a city manually instead; in that case no device location data leaves your device.

If you search for a city by name instead, the text you type is sent to our servers, which query a place-search provider on your behalf and return the matching city. We do not associate these search queries with your account beyond what is needed to answer the request.

### Prayer and app settings

We store your preferences — calculation method, madhab, prayer reminders, language, calendar selection, and similar — on our servers so that they remain consistent across devices.

### Subscription information

If you purchase a subscription, the payment is processed by **Google Play Billing**. We never receive your credit card number, billing address, or any other payment details. Google shares with us a purchase token and subscription state indicating which plan you bought and its status.

### Crash reporting

The Android app uses **Firebase Crashlytics only**, for crash and error reporting. It does **not** include Firebase Analytics or Firebase Remote Config, and collects **no usage or behavioural analytics** — we do not track which screens you visit or which features you use.

Crash reports **never** contain the content of your calendar, your contacts, your location coordinates, your authentication tokens, or the contents of any network request or response. A crash report contains the crash or error itself, the device and app information listed below, a short breadcrumb trail of app activity (for example, that a request to a given endpoint returned an error status), and a **pseudonymous numeric account identifier** that lets us tie multiple reports to a single account. That identifier is not your name or email address, and your name and email address are never sent to Crashlytics.

### Device information

We collect non-identifying device data (device model, Android version, app version) to diagnose issues and ensure compatibility.

## Third Party Access

We only share information with third parties to the extent necessary to provide the app's functionality. The third parties used by the Android app are:

- **Google Sign-In and Google Calendar / People APIs** — to authenticate you and to read or write calendar events and contacts you have authorized. See Google's privacy policy: https://policies.google.com/privacy
- **Microsoft Authentication Library (MSAL) and Microsoft Graph** — to authenticate you and to read or write calendar events and contacts you have authorized. See Microsoft's privacy statement: https://privacy.microsoft.com/privacystatement
- **Firebase Crashlytics (Google)** — to report crashes and errors. See Firebase's privacy information: https://firebase.google.com/support/privacy
- **Google Play Billing** — to process auto-renewable subscriptions. See Google's privacy policy: https://policies.google.com/privacy

We may also disclose information when required by law, to enforce our terms, to investigate fraud, or to protect the safety of our users.

## Google API Services User Data Policy

Fajr Calendar's use and transfer of information received from Google APIs to any other app adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements.

Specifically, data obtained from the Google Calendar and Google People APIs is used only to provide and improve the user-facing features described in this policy; it is not transferred to others except as necessary to provide those features, to comply with applicable law, or as part of a merger or acquisition; it is not used for advertising of any kind; and no humans read this data except with your explicit consent, to comply with applicable law, or where the data is aggregated and anonymized for security or abuse-prevention purposes.

## Permissions Used by the App

**Requested through your Google or Microsoft account (OAuth)**

| Permission | Why it is requested |
|---|---|
| Calendar | Read your events to avoid overlap with prayer times; write prayer and user-created events |
| Contacts (read-only) | Suggest contacts when you invite guests to events |

**Android system permissions**

| Permission | Why it is requested |
|---|---|
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Compute accurate prayer times. Foreground use only — the app does not request background location access. |
| `POST_NOTIFICATIONS` | Show prayer and event reminders locally on your device |
| `USE_EXACT_ALARM` / `SCHEDULE_EXACT_ALARM` | Fire prayer reminders at the exact prayer time, which is the core purpose of the app |
| `RECEIVE_BOOT_COMPLETED` | Re-schedule your prayer reminders after the device restarts |
| `INTERNET` / `ACCESS_NETWORK_STATE` | Communicate with our servers and with Google/Microsoft |

All permissions are optional except those strictly required for the feature you are using. The app will continue to function in reduced form if you decline any optional permission.

## Account Deletion

You can delete your Fajr Calendar account at any time directly from inside the app, under **Profile → Delete Account**. Deleting your account:

- Removes your profile, app preferences, and saved settings from our servers.
- Revokes the OAuth tokens we hold for your Google or Microsoft account.
- Removes prayer events created by the app from your connected calendar.

Account deletion is permanent and cannot be undone. Events you created manually in your own calendar are not deleted — those remain under your control in Google or Microsoft.

If you have an active subscription, you may need to cancel it separately in the Google Play Store under **Payments & subscriptions → Subscriptions**.

**Requesting deletion without the app.** If you have uninstalled the app, or are otherwise unable to delete your account from inside it, follow the instructions on our Account Deletion page:

**https://github.com/FajrCalendar/fajr-calendar-privacy-policy/blob/main/Android/delete-account.md**

It describes both the in-app route and the email route, together with exactly which data is deleted and which is kept. Requests made by email are processed within 30 days.

## Opt-Out and Data Retention

You can stop further data collection at any time by signing out, revoking the app's access from your Google or Microsoft account settings, or uninstalling the app. Information already collected is retained only as long as your account is active or as needed to provide the service. After account deletion, residual data is removed from active systems within a reasonable period, except where retention is required by law.

You can request a copy of your data, or request its earlier deletion, by emailing us at the address below.

## Subscriptions

Fajr Calendar offers optional auto-renewable subscriptions. Subscriptions automatically renew unless auto-renew is turned off before the end of the current billing period. Payment is charged to the payment method on your Google account at confirmation of purchase.

You can manage and cancel subscriptions in the Google Play Store under **Payments & subscriptions → Subscriptions**. Refund requests are handled by Google Play in accordance with the Google Play refund policy.

## Children's Privacy

Fajr Calendar is not directed to children under 13 and we do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will promptly delete it.

## Security

We use commercially reasonable safeguards to protect the information collected by the app, including encrypted transport (HTTPS) for all network traffic and encryption of sensitive values stored on your device. No method of transmission or storage is 100% secure, so we cannot guarantee absolute security.

## Changes to this Policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top of this page indicates when the latest revision was published. Continued use of the app after a change constitutes acceptance of the revised policy.

## Your Consent

By using the app, you consent to the collection and processing of information as described in this Privacy Policy.

## Contact Us

If you have questions or requests regarding this Privacy Policy or your data, contact us at:

**Email:** developer@blink22.com
**Developer:** Blink22
