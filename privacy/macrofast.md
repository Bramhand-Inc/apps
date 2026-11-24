# Privacy Policy — MacroFast

**Last updated: November 24, 2026**

## Summary
MacroFast stores all your data on your device, with an optional backup copy in your own private iCloud Drive. We do not collect, transmit, or share your personal information.

## Data We Store
All data is stored locally on your device using Apple's SwiftData framework:
- Food entries (name, calories, macros, serving size, date, meal type)
- Meal photos (stored on-device only)
- Daily nutrition goals and glucose goal range
- Fasting window history
- Subscription status (cached locally via UserDefaults)

## iCloud Drive Backup
If you are signed in to iCloud with iCloud Drive turned on, MacroFast can save a backup file to the app's private folder in **your own iCloud Drive**. A backup is made when you tap **Back Up Now** in the Goals tab, and automatically about once a week while the app is in use.

A backup contains your food entries (name, calories, macros, fiber, serving size, date, meal type, barcode) and your daily nutrition goals, plus the app version, the backup date, and your device's name so you can tell backups from different devices apart. Meal photos and glucose data are not included.

Backups are stored and synced by Apple under your Apple Account. We have no access to them. To delete them, go to **iPhone Settings → [your name] → iCloud → Manage Account Storage → MacroFast**. If iCloud Drive is off, no backup is made.

## Apple Health (HealthKit)

MacroFast may interact with Apple Health in two ways, both entirely on-device:

**Reading glucose data:** MacroFast requests read-only access to blood glucose data stored in Apple Health. This data is displayed locally in the Glucose tab and is never uploaded, transmitted, or shared.

**Writing nutrition data (opt-in):** If you choose to enable "Sync meals to Apple Health" in Goals, MacroFast will write your logged calorie, protein, carbohydrate, and fat data to Apple Health. This is off by default. You can disable it or revoke access at any time.

You can manage HealthKit permissions at any time in **iPhone Settings → Privacy & Security → Health → MacroFast**.

## Data We Do Not Collect
- We do not collect, store, or transmit any health or fitness data — all HealthKit data is read or written entirely on-device and never leaves it
- We do not collect your name, email, or any personal identifiers
- We do not use analytics or crash reporting tools
- We do not track your location
- We do not share any data with third parties
- We do not have servers or a backend — there is no user account

## Camera and Photos
The app requests camera and photo library access solely to let you attach photos to food log entries. Photos are stored on your device only and never transmitted.

## Network Requests
The app makes network requests only for:
- **Barcode scanning**: product nutrition data is fetched from [Open Food Facts](https://world.openfoodfacts.org), a public open-source food database. No personal data is sent — only the barcode number.
- **USDA food search**: uses a bundled local database — no network request.
- **Subscription purchases**: handled entirely by Apple's StoreKit. We never see your payment information.

## Subscriptions
Subscription purchases and management are handled by Apple. We receive only a verified transaction confirmation. See Apple's Privacy Policy at https://www.apple.com/legal/privacy for details on how Apple handles payment data.

## Children's Privacy
This app is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy
We may update this policy. Continued use of the app after changes constitutes acceptance. The "Last updated" date above will reflect any changes.

## Contact
Questions? Email us at: app AT bramhand DOT com
