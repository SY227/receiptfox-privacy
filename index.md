# ReceiptFox Privacy Policy

**Effective date:** February 03, 2026

ReceiptFox stores your receipts locally on your device by default, and can optionally sync and share folders using Apple iCloud/CloudKit. This Privacy Policy explains how **ReceiptFox** (“the App”) handles information when you use it.

If you have questions, contact: **Simon Yam — Simon.Yam227@gmail.com**

---

## Summary (plain English)

- ReceiptFox lets you **snap** a receipt with the camera or **import** one from Photos, then extracts key fields to build your receipt history.
- Receipt images are saved to the app’s private Documents storage (for example: `Documents/ReceiptFoxImages`).
- iCloud is optional. If you sign into iCloud, ReceiptFox can sync receipts and enable shared folders using **Apple CloudKit**.
- When you scan/import a receipt for extraction, ReceiptFox sends the receipt **image** and a **prompt** to **Google Gemini** (via Firebase AI Logic) to return structured results.
- ReceiptFox does **not** sell your data and does **not** use ad tracking.

---

## Information ReceiptFox uses

### 1) Camera and Photos (permissions)
ReceiptFox may request access to:
- **Camera** (to take receipt photos)
- **Photos** (to import a receipt image you select)

### 2) Receipt content you provide
ReceiptFox processes receipt images to extract information such as merchant, date, totals, category, and (when legible) line items.

### 3) Data stored on your device
ReceiptFox stores locally (in the app’s private storage):
- Receipt images (stored in `Documents/ReceiptFoxImages`)
- Receipt records (merchant/date/total/category/notes/flags, etc.)
- Local fallback data used when iCloud is unavailable or you are signed out

This data stays on your device until you delete it in the app or remove the app from your device.

### 4) iCloud / CloudKit sync and sharing (optional)
If you are signed into iCloud, ReceiptFox can:
- Sync personal folders using **CloudKit private database**
- Join/shared folders using **CloudKit shared database**
- Create and share folders using **CloudKit sharing invitations**

If you are not signed into iCloud, ReceiptFox will keep your receipt vault on this device.

### 5) AI receipt extraction (Google Gemini via Firebase AI Logic)
When you scan/import a receipt for extraction, ReceiptFox sends:
- The receipt **image**
- A **text prompt** instructing the model how to extract fields

to **Google Gemini** via Firebase AI Logic, and receives structured JSON results.

---

## Data sharing

ReceiptFox shares data only in these situations:

1) **Apple iCloud / CloudKit (optional):** If you use iCloud features, your receipts (and receipt images as CloudKit assets) are stored and processed by Apple to provide sync and sharing.  
2) **Google Gemini (receipt extraction):** If you scan/import a receipt for extraction, the receipt image and prompt are transmitted to Google Gemini via Firebase AI Logic.  
3) **User‑initiated export/share:** When you export and share files, ReceiptFox uses Apple’s Share Sheet to share content to the destination you choose.

**Third‑party protections:** Any third party that processes user data for ReceiptFox (such as Apple CloudKit/iCloud or Google Gemini through Firebase AI Logic) is expected to provide the same or equal protection of user data as stated in this policy and as required by Apple’s App Review Guidelines. ReceiptFox uses these services only to deliver the requested app functionality.

ReceiptFox does **not** sell your data. ReceiptFox does **not** share data with advertisers. ReceiptFox does **not** perform cross‑app tracking.

---

## Data retention & deletion

### On‑device retention (ReceiptFox)
- **On‑device storage:** Receipts remain on your device until you delete them in the app.
- **Deleting in the app:** Deleting a receipt removes it from local storage; if iCloud sync is enabled, the associated CloudKit record is also deleted from the selected CloudKit database (subject to Apple services).
- **Deleting the app:** Removing the app removes locally stored app data on your device.

### Third‑party retention (Apple / Google / share destinations)
- **Apple CloudKit/iCloud:** If iCloud features are used, Apple may process and retain synced content according to Apple’s policies.
- **Google Gemini:** When you use receipt extraction, the content you submit and the model output may be processed and retained according to Google’s Gemini policies. Google’s Gemini API documentation states prompts and outputs may be retained for up to **55 days** for abuse monitoring.
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
If you subscribe to ReceiptFox Pro, payment is processed by Apple via your Apple ID. ReceiptFox does not receive your full payment card details.

---

## Security
ReceiptFox uses Apple’s standard app sandboxing. Data is stored in the app’s private container on your device. No method of storage or transmission is 100% secure.

---

## Children’s privacy
ReceiptFox is intended for a general audience and does not knowingly collect personal information from children under 13. If you believe a child has provided personal information through the App, contact us and we will take appropriate steps consistent with applicable law.

---

## Changes to this policy
We may update this Privacy Policy from time to time. The “Effective date” above will reflect the latest version.

---

## Contact
For questions or requests, contact: **Simon Yam — Simon.Yam227@gmail.com**
