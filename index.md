# Privacy Policy — Foody

_Last updated: 2026-06-25_

Foody ("the app") is a food-label scanner that helps you check
ingredients, allergens and nutrition. This policy explains exactly what the app
does and does not do with your data. It is written to be accurate to the app's
actual behaviour.

## Short version

- **You can use the whole app without an account.** Sign-in is **optional** and
  exists only to back up and sync your data.
- **No ads, no third-party analytics, no trackers, no advertising ID.**
- By default, everything you enter (diary, dishes, allergens, diets, calorie
  goal, language, region, scan history) is stored **on your device**.
- **If you sign in**, your profile, diary, and dishes are also backed up to your
  private cloud space so you can restore them and sync across devices. You can
  **delete your account and all cloud data at any time** — in the app or from a
  web page (see "Data retention and deletion").
- The camera is used **only** to read a barcode. Camera frames are processed on
  the device and are **never stored or uploaded**.

## What data the app handles

### 1. Camera
The app requests camera access solely to detect a product barcode in real time.
Frames are analysed on-device by the operating system's barcode scanner. The app
does not take, save, or transmit photos or video.

### 2. The barcode you scan
When you scan or type a barcode, the app sends that **number** to our product
lookup service, which retrieves the product's name, ingredients, and nutrition
(sourced from the open Open Food Facts database) over an encrypted (HTTPS)
connection. The barcode is not linked to your identity and carries no personal
information. Open Food Facts' own terms apply to product data:
https://world.openfoodfacts.org/privacy

### 3. Information you create in the app
Your food diary, saved dishes/recipes, allergen and diet selections, calorie
goal, chosen language and region, and your local scan history are saved **on your
device**. If you are not signed in, this data stays on your device only.

### 4. Optional account & cloud backup
If you choose to sign in (anonymously, or with Google or an email address), the
app creates an account for you using **Google Firebase** (Authentication +
Cloud Firestore) and backs up your **profile (body metrics, calorie goal,
allergens, diets, preferences), diary, and dishes** to a private space tied to
your account, so it can be restored and kept in sync across your devices.

- This data is readable and writable **only by you** (enforced by per-user
  security rules).
- It is processed by Google Firebase as our data processor. Google's handling is
  governed by the Firebase Data Processing Terms and Google's Privacy Policy:
  https://policies.google.com/privacy
- We do **not** use this data for advertising, profiling, or analytics.
- Camera frames and full scan history are **not** uploaded — only the profile,
  diary, and dishes described above.

## Data sharing

We do **not** sell, rent, or share your data with anyone. The app contains no
advertising or analytics SDKs. The only third parties involved are the product
lookup source (Open Food Facts) and, if you sign in, Google Firebase as the
backup/sync provider described above.

## Data retention and deletion

- **On-device data:** uninstalling the app removes the data stored on your
  device; you can also clear your scan history inside the app.
- **Cloud data (if you signed in):** your backed-up profile, diary, and dishes
  are kept until you delete them. You can delete your account and **all** of its
  cloud data:
  - **In the app:** Profile → Account → **Delete account**.
  - **On the web (no app needed):**
    https://foody-alpha-seven.vercel.app/delete-account.html — sign in and
    confirm; this permanently deletes your account and all associated cloud data.

Deletion removes your Firestore data (profile, diary, dishes) and your
authentication account. It cannot be undone.

## Children

The app is a general-purpose utility and is not directed at children.

## Changes to this policy

If this policy changes, the updated version will be posted at this same URL with
a new "Last updated" date.

## Contact

Questions about this policy, or deletion requests: **foodysupport@gmail.com**

