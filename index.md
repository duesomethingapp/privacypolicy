---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Privacy Policy

**Last Updated: September 15, 2026**

Due Something is designed to operate using Apple's system services without requiring an account or collecting your personal information on servers operated by Due Something. This Privacy Policy explains how information is handled when you use the Due Something app on supported Apple platforms.

## Information We Collect

Due Something does not require you to create an account and does not collect, transmit, sell, or share your personal information with the developer.

### Reminders Data

Due Something requests access to your Reminders data to provide the app's functionality. Your reminders, lists, and related information are accessed through Apple's Reminders framework and are read from and written to the Reminders database associated with your device and Apple account.

### Calendar

Due Something requests access to your calendars for two optional features, and for nothing else.

**Calendar Connect** reads the events in the calendars you choose so you can turn them into tasks. Events are read on your device when you open the import screen, and only the ones you select become tasks — importing never changes, moves, or deletes anything in your calendar. An imported task records the name of the calendar it came from in its notes.

**Add to Calendar** does the reverse: when you choose it on a task, Due Something writes that task to the calendar you pick as a new event.

Due Something also remembers which events you have already imported, so the same event isn't offered twice on any of your devices. This record is a per-event identifier and the date you imported it, and it is synced through your private iCloud account as described under _iCloud_ below. Which of your calendars are offered for import is stored only on the device where you set it and is not synced. Optional — Due Something works without calendar access, and it is controlled in Settings.

### Location

Due Something requests access to your location to support location-based reminders and to help you choose a place when setting one. When you create a location reminder, Due Something uses Apple's Core Location services to detect when you arrive at or leave a place you select, so the reminder can alert you at the right time. Granting "Always" access allows these reminders to trigger while the app is in the background. When you set a reminder's location, the app may also display a map and convert a place, name, or address you enter into coordinates using Apple's map services. Your location is processed on your device to power these features. Places you save for location snoozing, and the location rules you attach to individual tasks, are synced between your devices through iCloud as described under _iCloud_ below. Optional — controlled in Settings.

### Contacts

Due Something requests access to your Contacts only to make setting a location easier. When you choose to set a reminder's location from a contact, Due Something reads that contact's address so it can suggest it as a location for the reminder. Optional — Due Something works without it. Controlled in Settings.

### Microphone and Speech Recognition

Due Something requests access to your microphone and to speech recognition so you can dictate a task by voice, on iPhone, iPad, and Apple Watch. The microphone captures audio only while you are actively dictating, and Apple's speech recognition converts that audio into text for the task's title. Depending on your device and settings, Apple may process the audio on-device or on Apple's servers. Optional — controlled in Settings.

### Notifications

Due Something requests permission to send notifications so it can alert you when a task is due and let you snooze or complete it from the alert. Notifications are scheduled locally on your device. Due Something also registers for silent push notifications from Apple's iCloud service so that changes made on one of your devices reach your others promptly; these carry no content and are not shown to you. Controlled in Settings.

### Alarms

Due Something can set a system alarm for a task, for the few things a notification isn't enough for. Turning on **Create Alarm** in the task editor asks for permission to schedule alarms, and the alarm then rings at the task's due time using the system's own alarm sound and Stop control.

Alarms are scheduled locally on your device through Apple's AlarmKit. The alarm shows the task's title; no other information is included, and nothing is sent to the developer. Each device asks for this permission separately. Whether a task has an alarm is synced between your devices as described under _iCloud_ below; the alarms themselves are scheduled on each device from that preference. Optional — controlled in Settings.

### Camera and Photos

Due Something requests access to your camera so you can take a photo or scan a document to attach to a task. Photos attached from your photo library are chosen through Apple's photo picker, which shares only the items you select — Due Something cannot browse your library and does not request photo library access. Attached images and files are stored on your device alongside the app's data, may appear in that task's notifications, and are synced to your other devices through your private iCloud account as described under _iCloud_ below. They stay with the task through Recently Deleted and are removed when the task is permanently deleted. Attachments are never sent to the developer or to any third party. Optional — controlled in Settings.

### Web Links

When you add a web link to a task, Due Something may request that web page (and, for YouTube links, YouTube's public information service) to retrieve the page's title so it can label the task. This request goes to the website you provided; the result is used only on your device.

### Spotlight Search

So that you can find tasks from your device's search, Due Something adds your open tasks to Apple's on-device Spotlight index. The index is maintained by the operating system on that device and is not sent to the developer or to Apple's servers. Completed and deleted tasks are removed from it.

### Widgets, Controls, and Live Activities

Widgets, Lock Screen widgets, Control Center controls, and the overdue Live Activity display your task information outside the app. To make this possible, Due Something writes a small snapshot of the tasks being shown to a storage area shared between the app and its widgets on the same device. Live Activities are created and updated locally by the app; no remote service is used to push them. This information stays on your device and is visible wherever you have chosen to show it, including the Lock Screen.

### Apple Watch

The Due Something app on Apple Watch reads your reminders from the Watch's own copy of the Reminders database and shows the same tasks as your other devices. If you dictate a task on the Watch, Apple's speech recognition converts what you say to text as described under _Microphone and Speech Recognition_ above.

watchOS does not allow apps to change reminders directly, so completing, snoozing, or adding a task on the Watch is carried out by your iPhone on its behalf. What you did travels to your iPhone directly when it is nearby. When it isn't, the instruction — which for a new task includes the title you dictated — is held in your private iCloud account, end-to-end encrypted, until your iPhone can apply it, and is removed once it has. This is covered by the _iCloud_ section below.

### iCloud

Your reminders and lists sync through Apple's Reminders service. In addition, Due Something uses Apple's iCloud (CloudKit) to keep the app's own data the same on all devices signed in to your Apple account. This data is stored in the private iCloud database that belongs to your Apple account and includes:

* Flags, Emergent marks, and muted alerts on tasks
* Per-task snooze settings, snooze history, and location alerts
* Whether a task has an alarm
* Calendar events a task has written for itself through Add to Calendar
* Attachments
* List preferences such as icons, hidden lists, sort order, list order, and the order you have dragged tasks into
* Your Recently Deleted list
* Saved places for location snoozing
* A record of which calendar events you have imported
* Actions taken on an Apple Watch that are waiting for your iPhone to apply them
* App settings, in the sections you choose
* The history used for snooze suggestions

All of this information is end-to-end encrypted: it is encrypted on your device with keys that live in your iCloud Keychain, and neither the developer nor Apple can read it. Attachment files are protected by iCloud's standard encryption in transit and at rest. Due Something also stores a random identifier for each of your devices so that changes can be attributed to the device that made them; it contains no personal information.

Syncing is on automatically when you are signed in to iCloud. You can turn it off for a device, and choose which sections of settings are kept in sync, in the app under **Settings → iCloud Sync**. You can also turn Due Something off under your Apple account's iCloud settings on any device. Attachments stored in iCloud count toward your iCloud storage. The developer has no access to your iCloud account or to any of this data.

### Tips

Due Something's Tip Jar uses Apple's in-app purchase system. Payments are handled entirely by Apple; the developer does not receive or store your payment details, and the app does not collect personal information as part of a tip.

### Analytics and Crash Reports

Apple may collect diagnostic, usage, and crash information as part of its operating systems and services, depending on the privacy and analytics settings you have selected on your device. Due Something does not use a third-party analytics or tracking service. The developer may receive diagnostic or analytics information made available by Apple to identify problems, improve reliability, and improve the app.

## How We Use Information

Because Due Something does not collect personal information on developer-operated servers, we do not use your personal information for advertising, profiling, or marketing.

Due Something's snooze suggestions are generated by a model that runs entirely on your device and learns only from your own past choices. The history it learns from is synced between your devices through your private iCloud account, end-to-end encrypted, so that suggestions are consistent everywhere. It is never sent to the developer or shared.

Diagnostic and analytics information made available by Apple may be used to diagnose crashes, fix bugs, improve performance, and improve Due Something.

## Data Sharing and Sale

Due Something does not sell your personal information and does not share your Reminders data, calendar data, or other personal information with advertisers, data brokers, or other third parties.

## Data Retention and Deletion

Due Something does not maintain a developer-operated database containing your Reminders data or other personal information. You can view, modify, and delete your reminders using Due Something or Apple's Reminders app, and your events using Apple's Calendar app.

Deleted reminders are kept in the app's "Recently Deleted" list for 30 days so you can restore them from any of your devices, after which they are removed automatically. When you remove something that syncs — an attachment, a flag, a deleted reminder — a record of the removal is kept in your iCloud account for 30 days so your other devices can apply it, and attachment files are kept for the same period so a restored task can recover them. Data the app stores in iCloud can be removed through the controls Apple provides, such as your Apple account's iCloud storage settings. Removing the app may remove locally stored app data but may not automatically remove information stored through iCloud or Apple's other services.

## Security

Due Something is designed to minimize the collection and transmission of personal information. Reminders, Calendar, and iCloud data are accessed using APIs and services provided by Apple and are subject to the security protections of Apple's platforms. The app's own data in iCloud is end-to-end encrypted as described above. No method of electronic storage or transmission can be guaranteed to be completely secure.

## Children's Privacy

Due Something does not collect personal information from children or maintain user accounts or developer-operated databases containing children's personal information.

## Your Privacy Rights

Because Due Something does not maintain a developer-operated database of users' personal information, the developer generally does not possess personal information that can be accessed, corrected, exported, or deleted on a user's behalf — this includes rights described under laws such as the EU/UK General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA). Any personal information involved in using the app (such as Reminders, calendar, location, or iCloud data) is processed on your device or by Apple within your own Apple account, and you can exercise rights over that information using the privacy, iCloud, and account controls Apple provides.

If you have questions about privacy or believe information has been collected by Due Something unexpectedly, you may contact us using the information below.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes to Due Something, applicable laws, or the services the app uses. Any changes will be posted on this page, and the "Last Updated" date at the top of this policy will be revised accordingly.

## Contact Us

If you have questions about this Privacy Policy, contact us at [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com).
