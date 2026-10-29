# Privacy Policy — Fajr Calendar

_Last updated: 29 October 2026_

## Introduction

Blink22 built the **Fajr Calendar: Prayers Sync** app as an application with free options and optional auto-renewable subscription plans. This Privacy Policy explains what information the app collects, how it is used, and the choices available to you. By using the app you agree to the practices described in this policy. We will not share your information beyond what is described here.

If you have questions, contact us at the address at the bottom of this page.

## Information Collection and Use

To provide its core functionality — syncing Islamic prayer times into your personal calendar, helping you plan around them, and tracking your habits — Fajr Calendar collects the following information:

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

### Habits

When you use Habits, the habits you create are stored on our servers and associated with your Fajr Calendar account, so that they stay in sync across your devices. This includes each habit's name, emoji, description, category, color, schedule, goal and unit, reminder times, checklist steps, whether it is paused, and your daily progress (the value you reached each day, whether it was completed, and when). If a habit is linked to Apple Health, we also store which kind of health data it is linked to (for example "steps" or "water"); see *Apple Health (HealthKit)* below.

A copy of your habits is kept on your device so that Habits works offline. Habit progress can also appear in widgets and Live Activities on your device; these are drawn on your device and are not sent anywhere. If you turn on calendar sync for Habits, our servers add your scheduled habits to the calendar you connected, as described under *Calendar data*.

### Apple Health (HealthKit)

Fajr Calendar can link a habit to **Apple Health**, so that the habit's progress fills in from data you, your Apple Watch, or your other apps have recorded (for example, your step count), and so that what you log in Fajr Calendar is saved to Apple Health too. Linking is optional and happens only when you turn on **Apple Health Sync** for a habit.

**What Fajr Calendar accesses.** Fajr Calendar asks Apple Health only for the data types used by the habits you have linked, and you choose what to allow on Apple's Health permission screen. The data types it can request are:

| Category | Health data types | Read | Write |
|---|---|---|---|
| Activity | Steps, Walking + Running Distance, Cycling Distance, Swimming Distance, Flights Climbed, Active Energy, Basal Energy | ✓ | ✓ |
| Activity | Exercise Minutes, Move Time, Stand Hours, Stand Minutes | ✓ | |
| Workouts | Workouts of the type you choose (for example walking, running, cycling, yoga), with their duration and either their active energy or their distance (walking and running, cycling, swimming, wheelchair, downhill snow sports, rowing, paddle sports, cross-country skiing or skating distance, depending on the workout) | ✓ | ✓ |
| Nutrition | Dietary Energy, Water, Caffeine, Protein, Carbohydrates, Fiber, Sugar, Total Fat, Saturated Fat, Monounsaturated Fat, Polyunsaturated Fat, Cholesterol, Sodium, Potassium, Calcium, Chloride, Chromium, Copper, Iodine, Iron, Magnesium, Manganese, Molybdenum, Phosphorus, Selenium, Zinc, Biotin, Folate, Niacin, Pantothenic Acid, Riboflavin, Thiamin, and Vitamins A, B6, B12, C, D, E and K | ✓ | ✓ |
| Mind and sleep | Sleep, Mindful Minutes | ✓ | ✓ |
| Mind and sleep | Time in Daylight | ✓ | |
| Other | Blood Glucose, Alcoholic Beverages, Handwashing, Toothbrushing | ✓ | ✓ |

Data types marked read only are recorded by Apple devices themselves; Fajr Calendar never asks to write them.

**How it is used.**

- **Reading:** for each linked habit, Fajr Calendar reads only that habit's data type, and only for the days in the habit's current goal period. With your permission, iOS can wake Fajr Calendar in the background when new data for a linked habit is saved to Apple Health (Apple Health "background delivery"), so that the habit stays up to date even when the app is closed. Background updates stop when you sign out or delete your account.
- **Writing:** when you log progress on a linked habit in Fajr Calendar (for example, one glass of water), that entry is saved to Apple Health as Fajr Calendar data. Resetting a day removes only the entries Fajr Calendar saved for that habit and day; data saved by Apple or by other apps is never changed or deleted.
- **What leaves your device:** the health data itself stays in Apple Health. What is sent to our servers is your habit's daily progress, which can include the total read from Apple Health (for example, "6,200 steps on 28 October"), together with the linked data type. This is what keeps the habit's history, statistics and streaks the same on all of your devices.
- Apple Health data is **not** sent to Firebase Analytics, and it is not stored in iCloud by Fajr Calendar.

**Your choices.** You can stop sharing at any time by turning off **Apple Health Sync** for a habit, or by turning off Fajr Calendar's access in **Settings → Privacy & Security → Health → Fajr Calendar**. To delete the data Fajr Calendar saved, open the **Health** app, tap your profile picture, then **Apps → Fajr Calendar**, and choose to delete its data. Deleting your Fajr Calendar account does not delete data stored in Apple Health, which stays under your control on your device; see *Account Deletion*.

### Subscription information

If you purchase a subscription, Apple processes the payment through the App Store. Apple shares with us a subscription receipt indicating which plan you bought and its status. We do **not** receive your credit card number, billing address, or any other payment details.

### Usage analytics

To understand how the app is used and improve its quality, we collect **anonymized usage analytics** through Firebase Analytics — for example, which screens are visited, which features are used, and aggregated counts of events such as logins, prayer-sync completions, and subscription purchases. For Habits, these events record actions such as creating, logging, pausing, resuming or deleting a habit, with the habit's tracking type (for example "count" or "timer"), its kind and goal period, and the number of habits in a day. These events do not contain the content of your calendar or your contacts, the names, notes or progress values of your habits, or any Apple Health data.

### Device information

We collect non-identifying device data (device model, operating system version, app version) to diagnose issues and ensure compatibility.

## Third Party Access

We only share information with third parties to the extent necessary to provide the app's functionality. The third parties used by Fajr Calendar are:

- **Google Sign-In and Google Calendar / People APIs** — to authenticate you and to read or write calendar events and contacts you have authorized. See Google's privacy policy: https://policies.google.com/privacy
- **Microsoft Authentication Library (MSAL) and Microsoft Graph** — to authenticate you and to read or write calendar events and contacts you have authorized. See Microsoft's privacy statement: https://privacy.microsoft.com/privacystatement
- **Apple App Store / StoreKit** — to process auto-renewable subscriptions. See Apple's privacy policy: https://www.apple.com/legal/privacy/
- **Firebase Analytics and Remote Config (Google)** — to collect anonymized usage analytics and remotely configure feature flags. See Firebase's privacy information: https://firebase.google.com/support/privacy

We may also disclose information when required by law, to enforce our terms, to investigate fraud, or to protect the safety of our users.

## Health Data (HealthKit)

Data that Fajr Calendar receives from Apple Health is used only to provide the Habits features described in this policy. It is not used for advertising, marketing or data mining, is not sold, and is not disclosed to any third party, including advertising platforms, data brokers and analytics providers. No humans read this data except with your explicit consent, to comply with applicable law, or for security purposes. Fajr Calendar never writes false or inaccurate data into Apple Health; it only saves the progress you log yourself.

## Permissions Used by the App

| Permission | Why it is requested |
|---|---|
| Calendar (via OAuth) | Read your events to avoid overlap with prayer times; write prayer and user-created events |
| Contacts (via OAuth) | Suggest contacts when you invite guests to events |
| Location (When In Use) | Compute accurate prayer times for your location |
| Notifications | Deliver prayer, event and habit reminders locally on your device |
| Health — read | Fill in progress for habits you link to Apple Health; only the data types those habits use are requested (see *Apple Health (HealthKit)*) |
| Health — write | Save the progress you log on a linked habit to Apple Health |
| Health — background delivery | Keep linked habits up to date when new Health data arrives while the app is closed |

All permissions are optional except those strictly required for the feature you are using. The app will continue to function in reduced form if you decline any optional permission.

## Account Deletion

You can delete your Fajr Calendar account at any time directly from inside the app, under **Profile → Delete Account**. Deleting your account:

- Removes your profile, app preferences, and saved settings from our servers.
- Removes your habits, their history and progress, and their Apple Health links from our servers.
- Stops Fajr Calendar's background updates from Apple Health.
- Revokes the OAuth tokens we hold for your Google or Microsoft account.
- Removes prayer events created by the app from your connected calendar.

Account deletion is permanent and cannot be undone. Events you created manually in your own calendar are not deleted — those remain under your control in Google or Microsoft. Data in **Apple Health** is not deleted either, because it is stored by Apple on your device, not by Fajr Calendar; you can delete the data Fajr Calendar saved there in the **Health** app under your profile → **Apps → Fajr Calendar**. If you have an active subscription, you may need to cancel it separately in your Apple App Store subscriptions settings.

If for any reason you are unable to delete your account from the app, email us at the address below and we will process the request within a reasonable time.

## Opt-Out and Data Retention

You can stop further data collection at any time by signing out, revoking the app's access from your Google or Microsoft account settings, turning off Fajr Calendar's access to Apple Health in **Settings → Privacy & Security → Health**, or uninstalling the app. Information already collected is retained only as long as your account is active or as needed to provide the service. After account deletion, residual data is removed from active systems within a reasonable period, except where retention is required by law.

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
