# MealPing Privacy Policy

Effective date: July 16, 2026
Last updated: July 16, 2026

This policy is based on the MealPing Xcode project inspected on 2026-07-16 and should be completed with publisher details before publication.

## 1. Who We Are / Data Controller
MealPing is provided by the app publisher identified on MealPing’s App Store product page. Privacy contact: supportmealping@gmail.com. The role for local-only and private iCloud data is based on the current app implementation.

## 2. Scope
This policy explains how MealPing handles data in the iOS app, widgets, Live Activities, subscriptions, store search, notifications, and support communications.

## 3. Definitions
“User” means the person using MealPing. “Content” means recipes, ingredients, meal plans, shopping lists, pantry items, store entries, preferences, and notes. “Apple services” include iCloud/CloudKit, StoreKit/App Store, MapKit/Apple Maps, notifications, widgets, Live Activities, and Apple Intelligence/Foundation Models.

## 4. Summary
MealPing stores most app content locally on the device and, according to the inspected code, uses SwiftData with the user’s private iCloud/CloudKit database. MealPing does not collect advertising identifiers, health data, contacts, calendar data, microphone recordings, camera images, photo-library content or MealPing account passwords. 

## 5. Data You Provide
You may enter recipe names, descriptions, servings, categories, cooking instructions, times, ingredients, amounts, units, optional flags, meal titles, meal notes, dates, custom meal ingredients, shopping list items, pantry item names, stock status, low-stock thresholds, expiration dates, store names, addresses, coordinates selected from Apple Maps, geofence radius, and app preferences.

## 6. Data Generated Through Use
The App may generate shopping lists, pantry-based recipe suggestions, widget snapshots, Live Activity snapshots, checked/hidden shopping item states, notification identifiers, StoreKit entitlement state, and AI conversation output where supported.

## 7. Recipes and Meal Plans
Recipe and meal-plan data is used to organize meals, generate shopping lists, suggest meals, and display widgets. It is stored in the app and may sync through your private iCloud account. MealPing does not operate a separate server for this content. 

## 8. Pantry and Shopping Lists
Pantry and shopping-list data is used for stock tracking, low-stock logic, expiration reminders, list generation, widgets, and Live Activities. It is stored locally/SwiftData and some snapshots are stored in App Group UserDefaults for widgets and Live Activities.

## 9. Images, Camera, and Photo Library
MealPing does not currently collect camera images or photo-library content for recipes. 

## 10. Location Data
Location is optional and used for store search and store arrival reminders. Store search uses the device location, if permitted, to search Apple Maps/MapKit near the user. Saved stores include name, address, latitude, longitude, geofence radius, and notification preference. Store reminders require Always Location for background geofencing. Location data may be processed by Apple services; the inspected code does not send it to a Developer server.

## 11. Notification Data
MealPing may request notification permission for pantry expiration reminders and store arrival reminders. Notification content can include pantry item names or store names. Pending notification requests are handled by iOS.

## 12. Device and Technical Data
The App uses UserDefaults and App Group UserDefaults for onboarding state, appearance, geofence store names, widget snapshots, and Live Activity state. Privacy manifests declare UserDefaults required reason API `CA92.1` and tracking=false.

## 13. Subscriptions and Transactions
MealPing uses StoreKit 2 to load products, purchase subscriptions, restore purchases, listen for transaction updates, and check current entitlements for `mealping_premium_monthly` and `mealping_premium_yearly`. Apple processes payment. MealPing receives limited StoreKit product and transaction/entitlement information needed to unlock premium; it does not receive full card details.

## 14. Support Communications
If you contact support, you may provide email address, screenshots, device model, iOS version, app version, description of the problem, and any content visible in screenshots. Support messages are handled outside the inspected app code through supportmealping@gmail.com or the support link on MealPing’s App Store product page. Support messages are kept only as long as reasonably needed to handle the request and maintain necessary records.

## 15. Diagnostics, Analytics, and Crash Data
The inspected project does not include third-party analytics, telemetry, crash reporting, advertising, or tracking SDKs. Xcode/App Store/TestFlight/Apple may provide crash or diagnostics data under Apple’s terms. Any future SDK must be added to this policy and App Store privacy labels.

## 16. CloudKit and iCloud
The inspected app configures SwiftData with `cloudKitDatabase:.private("iCloud.com.erik.MealPing")`. This means content may sync through Apple iCloud in the user’s private CloudKit database. Apple processes this data as part of iCloud. Developer access to private database content is not shown in the app code and is based on the current app implementation against CloudKit/App Store configuration. 

## 17. Local Device Storage
If iCloud is unavailable, disabled, delayed, or fails, data may remain local, fail to sync, or produce startup/sync errors. Deleting the app, iCloud data, or device backups may delete data.

## 18. Third-Party Services and Subprocessors
MealPing uses Apple services including iCloud/CloudKit, StoreKit/App Store, MapKit/Apple Maps, UserNotifications, WidgetKit, ActivityKit/Live Activities and FoundationModels/Apple Intelligence where supported. 

## 19. Purposes and Legal Bases
We process data to provide requested app functionality, save content, sync through iCloud, generate lists, provide reminders, verify subscriptions, respond to support, prevent misuse, and comply with legal obligations. GDPR/EEA legal bases may include performance of a contract, legitimate interests, consent for optional permissions, and legal obligation. Final legal bases is based on the current app implementation.

## 20. Required or Optional Data
Recipe, meal, shopping, pantry, preference, and store data is optional in the sense that you choose what to enter, but some features need relevant data to work. Location, notifications, iCloud, Apple Intelligence, and subscription purchases are optional. If refused, related features may be unavailable or degraded.

## 21. Permission Choices
If you deny location permission, store search and geofence reminders may not work. If you deny Always Location, background store reminders may not work. If you deny notifications, reminders will not appear. If iCloud is disabled, sync may not work. If Apple Intelligence is unavailable, AI features may not work.

## 22. Data Sharing
MealPing does not intentionally share app content with a MealPing-operated server or non-Apple third parties. Data may be processed by Apple for iCloud, App Store purchases, Apple Maps search, notifications, widgets, Live Activities, and on-device Apple Intelligence functionality. Support communications are shared with whichever support channel is used. the support channel used by the publisher

## 23. International Transfers
Apple and support providers may process data in countries outside your own. Specific transfer mechanisms and processor details is based on the current app implementation.

## 24. Retention
Local/iCloud content remains until you delete it, delete the app, remove iCloud data, or it is otherwise removed by Apple/device settings. StoreKit transactions follow Apple retention. Support retention is only as long as reasonably needed to handle the request and maintain necessary records. Widget/Live Activity snapshots persist until overwritten or cleared by app logic or system behavior.

## 25. Security
MealPing relies on Apple platform security, iOS sandboxing, iCloud/CloudKit security, and StoreKit verification. We do not claim that data is completely secure, encrypted in a specific way beyond Apple platform behavior, anonymized, or impossible to access.

## 26. User Rights
Depending on your location, you may have rights to access, correct, delete, restrict, object, port, or withdraw consent for personal data. Contact supportmealping@gmail.com. Rights may apply differently to local-only data, private iCloud data controlled by your Apple ID, App Store transaction data controlled by Apple, and support communications.

## 27. Access and Correction
You can access and edit most app content directly in MealPing. For support records, contact supportmealping@gmail.com. For Apple account and App Store data, use Apple’s privacy tools.

## 28. Deletion
You can delete individual recipes, meals, stores, pantry items, shopping items, and related entries in the App where the UI supports it. MealPing does not currently provide a separate in-app account deletion flow because the app does not use a separate MealPing account. You may also delete app data by deleting the app and managing iCloud data in iOS/iCloud settings.

## 29. Portability and Export
MealPing does not currently provide a full data export feature. If needed, contact supportmealping@gmail.com, but data stored only locally/private iCloud may need to be exported manually by the user unless export functionality is added.

## 30. Withdrawal of Consent
You can withdraw optional permissions through iOS Settings, including Location and Notifications. Withdrawal may stop or degrade related features but does not automatically delete existing data.

## 31. Complaints
EEA users may complain to their local data protection authority. Norwegian users may contact Datatilsynet. This does not limit other rights available under law.

## 32. Account Deletion
MealPing does not appear to create a Developer-operated account in the inspected code. Apple ID/iCloud/App Store accounts are managed by Apple. If accounts are added later, this policy must be updated.

## 33. Children
MealPing is not directed to children under 13, or the minimum age required to consent in your country or region. If you believe a child has provided personal data through support or another channel, contact supportmealping@gmail.com.

## 34. Automated Decision-Making and Profiling
MealPing may generate suggestions and shopping lists based on user-entered content. These are planning aids, not legally or similarly significant automated decisions.

## 35. AI Processing
AI features use Apple Intelligence/FoundationModels according to inspected imports and code. These features are device/OS dependent and may be unavailable. MealPing does not send AI prompts to a MealPing-operated server. Apple’s system behavior and privacy terms should be reviewed. 

## 36. Changes
We may update this policy. Updated versions should be available at MealPings publiserte personvernlenke eller juridisk seksjon i appen and, where appropriate, in the App.

## 37. Contact
Privacy: supportmealping@gmail.com
Support: supportmealping@gmail.com
Website: MealPing’s official support or product page
Privacy: MealPing’s published Privacy Policy URL or the Legal section in the app
Terms: MealPing’s published Terms of Use URL or the Legal section in the app
