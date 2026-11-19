# Hydration Tracker

A small iPhone-friendly installable web app. It stores entries in the browser's local storage on the device.

## Included
- Five one-tap routine entries: 16, 16, 21, 21, 21 oz (95 oz planned total)
- Customizable daily goal, plus 80 / 95 / 100 oz presets
- Personalized tracker title
- Custom bottle size with full- and half-bottle quick-add buttons
- Editable ounce amounts for each of the five routine check-ins
- Additional custom-ounce entries
- 14-day history, 7-day average, goal-days count, and current goal streak
- Exportable JSON backup
- Editable reminder times and optional in-app notifications while the app is open

## Put it on your iPhone
This is a static Progressive Web App. It needs to be served from HTTPS (for example, GitHub Pages) before iOS can install it as a Home Screen web app.

1. Create a GitHub repository (for example `hydration-tracker`).
2. Upload **all files in this folder** to the repository's root.
3. In GitHub, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Open the published `https://...github.io/...` URL in Safari on your iPhone.
6. Tap **Share → Add to Home Screen**. Open it from the new Home Screen icon.

## Reminders on iPhone
The reminder times in this app are saved and checked while the app is open. iOS does not let an ordinary locally hosted web app reliably schedule background local notifications after it has been closed. For dependable alerts, create repeating reminders in Apple's Reminders app at the same times. The app's optional in-app notifications are best-effort and require notification permission plus the app being open.

Suggested initial reminder times (change to match your schedule):
- Morning: 8:00 AM
- Lunch / work: 12:00 PM
- After work / gym: 4:00 PM
- Dinner: 7:00 PM
- Evening: 9:00 PM

## Data and privacy
No account or server is used by this app. Water entries, goal, and reminder settings remain in this browser on this device. They do not automatically sync to another device. Export your history periodically. Clearing Safari website data can erase the saved data.

## Important
The 95 oz goal is a personal tracking target, not a medical prescription. Adjust based on thirst, activity, heat, sweating, and any clinician advice. Avoid forcing large amounts of water quickly.
