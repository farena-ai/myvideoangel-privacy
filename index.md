# MyVideoAngel Privacy Policy

**Effective date:** October 6, 2026

MyVideoAngel ("the app") is a free app for keeping track of the movies and TV shows you own. It is built to be **local-first**: your collection lives on your device, not on our servers. This policy explains, in plain language, what information the app uses, where it goes, and what choices you have.

If you have questions, contact us at **privacy@mybookangel.com**.

---

## The short version

- **No accounts.** You never sign up or log in.
- **No ads.** The app shows no advertising and contains no ad networks.
- **No tracking or analytics.** We do not track you across apps or websites, and we do not use analytics tools to watch how you use the app.
- **Your collection stays on your device.** It is stored in a local database (SQLite) on your phone or tablet. We cannot see it.
- **The app only goes online for a few specific features**, described below. When it does, it sends only what that feature needs.
- **We do not sell or share your information** for advertising or any other purpose.

---

## 1. Information stored on your device

Everything you add to your collection (titles, formats, where you bought them, notes, ratings, cover photos you take, and similar details) is saved **only on your device**, in the app's private storage. It is not uploaded to us or to anyone else.

If you delete the app, this data is deleted with it, unless you have made a backup (see section 4).

## 2. When the app uses the internet

The app connects to the internet only for these features:

### a) Title search
When you search for a movie or show, the app sends the **search text you typed** (and the **year**, if you entered one) to a small server run by the developer (a Cloudflare Worker "proxy"). The proxy forwards the search to **The Movie Database (TMDB)** and passes the results back to the app.

- The proxy exists so that the app does not have to contain a secret TMDB key.
- The proxy does not receive your collection, your name, or any account information (there are no accounts).
- Like any web server, Cloudflare and TMDB may briefly process technical information needed to deliver the request, such as your IP address. We do not use the proxy to build a profile of you.

This product uses the TMDB API but is not endorsed or certified by TMDB. See TMDB's privacy policy at https://www.themoviedb.org/privacy-policy.

### b) Poster and cover images
Poster artwork is downloaded directly from TMDB's image server (**image.tmdb.org**). This works like loading an image on any website: TMDB's server receives a normal web request (including your IP address) for that image. Downloaded images may be kept in a cache on your device so they load faster next time.

### c) Barcode lookup (optional)
If you scan a barcode on a disc case (one at a time, in "Do I own this?" store mode, or in batch scan), the app may send **only the barcode number** (the UPC/EAN digits) to the developer's proxy, which asks **UPCitemdb**'s free lookup service (api.upcitemdb.com) and remembers the answer in a shared cache: just the barcode and the retail product name (for example "Heat (Blu-ray)"), so the next person who scans the same disc gets it instantly. The cache never stores who scanned it, your IP address, or anything about your collection. If the proxy is unavailable, the app may ask UPCitemdb directly with the same barcode number. A barcode already recorded in your library is answered on your device with no network request. You can always type a title instead of scanning. See UPCitemdb's policies at https://www.upcitemdb.com.

### c2) Wikidata title search (optional)
If you choose **Search Wikidata instead** (for example, when TMDB is unavailable), the **search text you typed** is sent to **Wikidata** (www.wikidata.org), a free database run by the Wikimedia Foundation, to find titles and years. See https://foundation.wikimedia.org/wiki/Policy:Privacy_policy.

### d) Crash reports (only if enabled)
Some builds of the app may include crash reporting through **Sentry** (sentry.io). If crash reporting is enabled, when the app runs into an error it may send an error report containing:

- a technical stack trace (which part of the app's code failed),
- your device model and operating-system version,
- the app's version number.

Crash reports **do not include** your library contents, titles, notes, photos, or your name. They are used only to find and fix bugs. They are not linked to your identity and are not used for tracking or advertising. See Sentry's privacy policy at https://sentry.io/privacy/.

## 3. Camera and photos

The app may ask for permission to use your **camera** or **photo library**. These are used only to:

- take a photo of a disc or case cover,
- scan a barcode, and
- read titles from a screenshot you choose (for example, a screenshot of a digital store library). This text reading happens **on your device**.

Photos and screenshots stay on your device. They are not uploaded to us. (Only a scanned barcode **number** may be sent, as described in section 2c.) You can turn these permissions off at any time in your device's Settings; the rest of the app keeps working.

## 4. Backups

The app keeps **automatic daily backups** of your collection (the last 7 days) in its own folder **on your device**, so a mistake can be undone. They never leave your device unless you move them yourself; on iPhone and iPad they are visible to you in the Files app, and on Android they stay out of Google's cloud backup. Deleting the app deletes them.

You can also export a backup of your collection as a file. That file is created **only when you ask for it**, and you decide where it goes (for example, your Files app, a cloud drive you choose, or email to yourself). We never receive a copy.

You can optionally protect a backup with a **password**, which encrypts the file. If you forget that password, we cannot recover the backup for you, because we never see the password or the file.

When you share or store a backup file with another service (such as iCloud, Google Drive, or email), that service's privacy policy applies to the copy you gave it.

## 5. What we do not do

- We do not collect your name, email, phone number, contacts, or location.
- We do not use advertising identifiers.
- We do not sell, rent, or trade information.
- We do not use your information for advertising or profiling.

## 6. Children

The app is not directed to children under 13, and we do not knowingly collect personal information from children. Because the app has no accounts and keeps your collection on your device, it does not ask anyone for personal information. If you believe a child has sent us personal information, contact us and we will delete it.

## 7. Your choices and rights

- **See or delete your data:** Your collection is on your device, so you can view, edit, or delete it in the app at any time, or delete the app to remove everything.
- **Turn off network features:** You can avoid online features by not using title search or barcode lookup, or by turning off internet access for the app in your device's settings.
- **Permissions:** Camera and photo permissions can be changed in your device's Settings.
- **Questions or requests:** Depending on where you live (for example, in the EU, UK, or California), you may have rights to access or delete personal information held about you. Because we do not keep your collection or an account, we usually hold no personal information about you. Crash reports, if enabled, are kept by Sentry for a limited time and are not linked to you. Contact us at **privacy@mybookangel.com** with any request.

## 8. Security

Data sent over the internet by the app uses encrypted connections (HTTPS). Data on your device is protected by your device's own security features (such as your passcode). Password-protected backups are encrypted.

## 9. Changes to this policy

If we change this policy, we will update the effective date at the top and post the new version at the same address. If a change is significant, we will mention it in the app's release notes.

## 10. Contact

Email: **privacy@mybookangel.com**

