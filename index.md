<div align="center">

# 🥗 Foody

### Privacy Policy

**A food‑label scanner that checks ingredients, allergens & nutrition — privacy‑first by design.**

![Ads](https://img.shields.io/badge/Ads-None-2ea44f?style=for-the-badge)
![Trackers](https://img.shields.io/badge/Trackers-None-2ea44f?style=for-the-badge)
![Analytics](https://img.shields.io/badge/3rd--party%20Analytics-None-2ea44f?style=for-the-badge)
![Data](https://img.shields.io/badge/Your%20data-On%20device-1f6feb?style=for-the-badge)

<sub>Last updated: <strong>2026-06-28</strong></sub>

</div>

---

> **In one breath:** You can use the whole app **without an account**. There are
> **no ads, no trackers, no advertising ID, no third‑party analytics**. By default
> everything you enter lives **on your device**. The camera reads barcodes on‑device;
> images leave your phone only if you **choose** to send a product photo to help add
> it. Sign‑in is optional and only backs up your own data — which you can delete at
> any time.

---

## ✨ The short version

| | |
|---|---|
| 👤 **Account** | Optional. The app works fully without one. |
| 📵 **Tracking** | No ads, no analytics SDKs, no advertising ID, no trackers. |
| 📱 **Storage** | Diary, dishes, allergens, diets, calorie goal, language, region and scan history are stored **on your device** by default. |
| ☁️ **Cloud (only if you sign in)** | Profile, diary and dishes are backed up to a **private** space tied to your account, for restore & sync. |
| 📷 **Camera** | Reads barcodes **on‑device** (frames never uploaded). Optionally lets you photograph a *not‑found* product to send to us — only if you choose to. |
| 🗑️ **Deletion** | Delete your account and **all** cloud data anytime — in the app or from a web page. |

---

## 🧭 What data the app handles

### 📷 1. Camera
The app uses the camera to detect a product barcode in real time. These live
scanning frames are analysed **on‑device** by the operating system's barcode
scanner and are **never saved or transmitted**. Separately, the camera (or your
gallery) powers the optional **"help add a product"** action in section 5 — and
only the photos you explicitly submit there ever leave your device.

### 🔢 2. The barcode you scan
When you scan or type a barcode, the app sends that **number** over an encrypted
**HTTPS** connection to our product‑lookup service and receives back the product's
name, ingredients and nutrition. The barcode is not linked to your identity and
carries no personal information.

Product information comes primarily from **Foody's own product database**, which we
build and maintain, and is **supplemented by the open Open Food Facts database** to
fill in products we don't yet cover.

> Where Open Food Facts data is used, its own terms apply → <https://world.openfoodfacts.org/privacy>

### ✍️ 3. Information you create in the app
Your food diary, saved dishes/recipes, allergen & diet selections, calorie goal,
chosen language and region, and your local scan history are saved **on your device**.
If you are not signed in, this data stays on your device only.

### ☁️ 4. Optional account & cloud backup
If you choose to sign in (anonymously, with Google, or with an email address), the
app creates an account using **Google Firebase** (Authentication + Cloud Firestore)
and backs up your **profile** (body metrics, calorie goal, allergens, diets,
preferences), **diary**, and **dishes** to a private space tied to your account, so
it can be restored and kept in sync across your devices.

- 🔒 This data is readable and writable **only by you** (enforced by per‑user security rules).
- 🏢 It is processed by Google Firebase as our data processor → <https://policies.google.com/privacy>
- 🚫 We do **not** use this data for advertising, profiling, or analytics.
- 📷 Live camera frames and full scan history are **not** uploaded — only the profile, diary and dishes described above (plus any product photos you choose to submit under section 5).

### ➕ 5. Optional product photos ("help add a product")
When a scan returns **"not found"**, you can **optionally** take or pick **up to two
photos** of the product and submit them so we can add it to the database. Nothing is
sent unless you tap **Send**. When you do:

- 🔐 The photos are uploaded over **HTTPS** to our backend, which **forwards them to
  the developer's private messaging (Telegram)** solely to add the missing product.
- 🏷️ A short **sender label** is included so we can follow up — your display name or
  email **if signed in**, otherwise an anonymous identifier.
- 🗄️ The photos are **not stored** on our servers or in any database — they exist only
  in the forwarded message.

---

## 🤝 Data sharing

We do **not** sell or rent your data, and the app contains **no** advertising or
analytics SDKs. We share data only in these limited cases:

- the **barcode** you scan → our product‑lookup service (**Foody's own database**, supplemented by **Open Food Facts**);
- **if you sign in** → **Google Firebase** processes your profile/diary/dishes for backup & sync (not for ads or analytics);
- **any product photos you choose to submit** → forwarded to the developer (section 5).

There are no other recipients.

---

## 🗑️ Data retention and deletion

**On‑device data** — uninstalling the app removes the data stored on your device;
you can also clear your scan history inside the app.

**Cloud data (if you signed in)** — your backed‑up profile, diary and dishes are
kept until you delete them. You can delete your account and **all** of its cloud data:

- 📲 **In the app:** Profile → Account → **Delete account**
- 🌐 **On the web (no app needed):** <https://foody-alpha-seven.vercel.app/delete-account.html> — sign in and confirm.

> Deletion removes your Firestore data (profile, diary, dishes) **and** your
> authentication account. It cannot be undone.

---

## 🧒 Children

The app is a general‑purpose utility and is **not** directed at children.

## 📝 Changes to this policy

If this policy changes, the updated version will be posted at this same URL with a
new "Last updated" date.

---

<div align="center">

## 📬 Contact

Questions about this policy, or deletion requests:

**[foodysupport@gmail.com](mailto:foodysupport@gmail.com)**

<sub>Product data © Open Food Facts contributors — licensed under the Open Database License (ODbL) v1.0.</sub>

</div>
