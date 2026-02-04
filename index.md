# ReceiptFox Privacy Policy

**Effective date:** February 03, 2026

ReceiptFox stores your receipts locally on your device by default, and can optionally sync and share folders using Apple iCloud/CloudKit. This Privacy Policy explains how **ReceiptFox** (“the App”) handles information when you use it.

If you have questions, contact: **Simon Yam** — **Simon.Yam227@gmail.com**

---

## Summary (plain English)

- ReceiptFox lets you **snap** a receipt with the camera or **import** one from Photos, then extracts key fields to build your receipt history. fileciteturn8file0L1208-L1288
- Receipt images are saved to the app’s private Documents storage (e.g., `Documents/ReceiptFoxImages`). fileciteturn8file0L5317-L5322
- ReceiptFox can store and sync receipts in **Apple CloudKit** (private database for personal folders; shared database for shared folders). iCloud is optional: if you aren’t signed into iCloud, the app keeps working with local storage. fileciteturn8file0L5377-L5454
- When you scan/import a receipt for extraction, ReceiptFox sends the receipt **image + a prompt** to **Google Gemini** (via Firebase AI Logic) to return structured JSON fields. fileciteturn8file0L5059-L5184
- ReceiptFox does **not** sell your data and does **not** use ad tracking.

---

## Information ReceiptFox uses

### 1) Camera and Photos (permissions)
ReceiptFox may request access to:
- **Camera** (to take receipt photos) fileciteturn8file0L1279-L1283
- **Photos** (to import a receipt image you select) fileciteturn8file0L1284-L1288

### 2) Receipt content you provide
ReceiptFox processes receipt images to extract information such as merchant, date, totals, category, and (when legible) line items. fileciteturn8file0L1457-L1476

### 3) Data stored on your device
ReceiptFox stores locally (in the app’s private storage):
- Receipt images (stored in `Documents/ReceiptFoxImages`) fileciteturn8file0L5317-L5322
- Receipt records (merchant/date/total/category/notes/flags, etc.) fileciteturn8file0L385-L401
- Local fallback data (a local receipts JSON file) used when iCloud is unavailable or you are signed out fileciteturn8file0L5317-L5337

This data stays on your device until you delete it in the app or remove the app from your device.

### 4) iCloud / CloudKit sync and sharing (optional)
If you are signed into iCloud, ReceiptFox can:
- Sync personal folders using **CloudKit private database**
- Join/shared folders using **CloudKit shared database**
- Create and share folders using **CloudKit sharing invitations** fileciteturn8file0L2444-L2466 fileciteturn8file0L2158-L2206

If you are not signed into iCloud, ReceiptFox will display that “iCloud is optional” and will keep your receipt vault on this device. fileciteturn8file0L5377-L5454

### 5) AI receipt extraction (Google Gemini via Firebase AI Logic)
When you scan/import a receipt for extraction, ReceiptFox sends:
- The receipt **image**
- A **text prompt** instructing the model how to extract fields

to **Google Gemini** via the Firebase AI Logic SDK, and receives structured JSON results. fileciteturn8file0L5059-L5184 fileciteturn8file0L1457-L1476

---

## Data sharing

ReceiptFox shares data only in these situations:

1) **Apple iCloud / CloudKit (optional):** If you use iCloud features, your receipts (and receipt images as CloudKit assets) are stored and processed by Apple to provide sync and sharing. fileciteturn8file0L5188-L5759  
2) **Google Gemini (receipt extraction):** If you scan/import a receipt for extraction, the receipt image and prompt are transmitted to Google Gemini via Firebase AI Logic. fileciteturn8file0L5059-L5184  
3) **User‑initiated export/share:** When you export and share files, ReceiptFox uses Apple’s Share Sheet to share content to the destination you choose. fileciteturn8file0L750-L753 fileciteturn8file0L4776-L4788

**Third‑party protections:** Any third party that processes user data for ReceiptFox (such as Apple CloudKit/iCloud or Google Gemini through Firebase AI Logic) is expected to provide the same or equal protection of user data as stated in this policy and as required by Apple’s App Review Guidelines. ReceiptFox uses these services only to deliver the requested app functionality.

ReceiptFox does **not** sell your data. ReceiptFox does **not** share data with advertisers. ReceiptFox does **not** perform cross‑app tracking.

---

## Data retention & deletion

### On‑device retention (ReceiptFox)
- **On‑device storage:** Receipts remain on your device until you delete them in the app.
- **Deleting in the app:** Deleting a receipt removes it from local storage; if iCloud sync is enabled, the associated CloudKit record will also be deleted from the selected CloudKit database (subject to Apple services). fileciteturn8file0L5737-L5755
- **Deleting the app:** Removing the app removes locally stored app data on your device.

### Third‑party retention (Apple / Google / share destinations)
- **Apple CloudKit/iCloud:** If iCloud features are used, Apple may process and retain synced content according to Apple’s policies.
- **Google Gemini:** When you use receipt extraction, the content you submit and the model output may be processed and retained according to Google’s Gemini policies. Google’s Gemini API documentation states prompts and outputs may be retained for up to **55 days** for abuse monitoring (see Google AI for Developers documentation).
- **Share destinations:** If you export/share files, the destination app or service (email provider, messaging app, cloud drive, etc.) may retain the shared file under their policies.

ReceiptFox cannot directly delete data retained by Apple, Google, or other destinations outside the app. Please refer to their policies for retention and deletion options:
- Apple: https://www.apple.com/legal/privacy/
- Google: https://policies.google.com/privacy

---

## Revoke consent & request deletion

**Revoke consent**
- You can stop camera usage by denying **Camera** permission in iOS Settings.
- You can stop photo importing by denying **Photos** permission in iOS Settings.
- You can stop iCloud sync/sharing by signing out of iCloud or disabling iCloud for ReceiptFox in iOS Settings.
- You can avoid AI receipt extraction by not scanning/importing receipts for extraction.

**Request deletion**
- You can delete receipts in‑app at any time.
- Deleting the app removes locally stored data from your device.
- For data retained by Apple (CloudKit/iCloud), Google (Gemini), or any export/share destinations, deletion requests are governed by their policies (links above).

---

## Subscriptions and payments (ReceiptFox Pro)
If you subscribe to ReceiptFox Pro, payment is processed by Apple via your Apple ID. ReceiptFox does not receive your full payment card details. fileciteturn8file0L556-L573

---

## Security
ReceiptFox uses Apple’s standard app sandboxing. Data is stored in the app’s private container on your device. No method of storage or transmission is 100% secure.

---

## Children’s privacy
ReceiptFox is not directed to children under 13.

---

## Changes to this policy
We may update this Privacy Policy from time to time. The “Effective date” above will reflect the latest version.

---

## Contact
For questions or requests, contact: **Simon.Yam227@gmail.com**
