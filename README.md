# Taskfolio

A simple daily task app that works like a filing cabinet. Tasks live in folders, and when you finish one it is filed in that folder's **Completed** list with the date. A separate calendar screen reminds you one day before every deadline.

It is one small web app: plain HTML, CSS and JavaScript, no frameworks and no build step.

![Tasks](screenshots/tasks.png)

## Features

- **Login and profile.** Create an account on your device. The profile page holds a photo, bio, phone number and email.
- **Four folders.** Work, Personal, Study and Urgent keep different parts of your life apart.
- **Incomplete and Completed.** Both are always one tap away. Finished tasks are saved in their own folder and can be shared as text or on WhatsApp.
- **Calendar and reminders.** Give a task a due date and it appears under *Upcoming Reminders* one day before the deadline. The calendar marks due days and reminder days.
- **Works offline.** Install it on a phone or computer and it keeps working without internet.
- **Light and dark mode** that follow your device.
- **Backup and restore** from the profile page.

![Calendar and reminders](screenshots/calendar.png)

## Try it

Open `index.html` in any browser. That is all.

To use it as a real app on your phone, host the files (for example with GitHub Pages) and open the address in Chrome, then choose **Install app**.

### Publish with GitHub Pages

1. Go to **Settings, then Pages** in this repository.
2. Under *Source* pick **Deploy from a branch**, choose `main` and the `/ (root)` folder, then save.
3. After a minute your app is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

### Make an Android APK

After publishing, paste your address into [pwabuilder.com](https://www.pwabuilder.com), choose Android and download the package.

## Privacy and limits

Everything is stored in the browser on your own device. There is no server, so:

- accounts and tasks do not sync between devices (use *Backup and restore* to move them),
- there is no password recovery,
- reminders show inside the app and do not send phone notifications.

## What is in this repository

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets browsers install it as an app |
| `sw.js` | Makes it work offline |
| `icons/` | App icons |
| `screenshots/` | Images used in this README |

![Mobile view](screenshots/mobile.png)
