# ReceiptFox Privacy Policy

**Effective date:** January 31, 2026

ReceiptFox stores your receipt library locally on your device by default. This Privacy Policy explains how **ReceiptFox** (“the App”) handles information when you use it.

If you have questions, contact: **Simon Yam** — **Simon.Yam227@gmail.com**

---

## Summary (plain English)

- ReceiptFox lets you **snap or import a receipt photo**, then extracts key fields (merchant/date/total/category/line items) to build your receipt history.
- Your receipts (and receipt images) are stored **on your device**. Receipt images are saved to the app’s Documents storage (e.g., `Documents/ReceiptFoxImages`).  
- **iCloud is optional**. If you sign into iCloud, ReceiptFox can sync receipts and enable **shared “Projects” (folders)** using Apple **CloudKit sharing**.
- When you scan/import a receipt for extraction, ReceiptFox sends the receipt **image + a text prompt** to **Google Gemini** (via Firebase AI Logic) to return structured results.
- ReceiptFox does **not** sell your data and does **not** use ad tracking.

---

## Information ReceiptFox uses

### 1) Camera and Photos (optional permissions)
ReceiptFox may request access to:
- **Camera** (to take a receipt photo)
- **Photos** (to import a receipt image you select)

### 2) Receipt content you provide
ReceiptFox processes the receipt image to extract:
- merchant, date, total, tax/tip (if present)
- currency and category
- optional line items, and confidence/warnings

### 3) Data stored on your device
ReceiptFox stores the following locally:
- receipt images (stored in the app’s Documents directory)
- extracted receipt fields and notes you add
- folder/project preferences and app settings

This data stays on your device unless you enable iCloud sync/sharing (below), until you delete it in the app or remove the app from your device.

### 4) iCloud / CloudKit (optional)
If you are signed into iCloud, ReceiptFox uses **Apple CloudKit** for:
- syncing your personal “My Receipts” vault
- syncing additional personal folders (“Projects”)
- enabling shared folders (“Shared Projects”) using CloudKit sharing invites

If you are not signed into iCloud, the app remains usable and keeps data locally (“iCloud is optional”).

### 5) AI receipt extraction (Google Gemini via Firebase AI Logic)
When you scan/import a receipt for extraction, ReceiptFox sends:
- the receipt **image**
- a **prompt** describing how to extract fields

to **Google Gemini** (through the Firebase AI Logic client SDK using the Google AI backend). The model returns structured JSON which ReceiptFox uses to populate receipt fields.

**Third‑party protections:** Any third party that processes user data for ReceiptFox (such as Apple CloudKit/iCloud or Google Gemini through Firebase AI Logic) is expected to provide the same or equal protection of user data as stated in this policy and as required by Apple’s App Review Guidelines. We use these services only to deliver the requested app functionality.

---

## Data sharing

ReceiptFox shares data only in these situations:

1) **Apple iCloud / CloudKit (optional):** If you are signed into iCloud, receipts (and receipt images as CloudKit assets) may be stored and processed by Apple to provide sync and sharing.
2) **Google Gemini (for extraction):** If you scan/import a receipt for extraction, the receipt image and prompt are transmitted to Google Gemini via Firebase AI Logic to return structured results.
3) **User‑initiated export/share:** If you export a PDF/CSV and share it, ReceiptFox uses Apple’s Share Sheet to share the file to the destination you choose.

ReceiptFox does **not** sell your data. ReceiptFox does **not** share data with advertisers. ReceiptFox does **not** perform cross‑app tracking.

---

## Data retention & deletion

### On‑device retention (ReceiptFox)
- **On‑device storage:** Receipts remain on your device until you delete them in the app.
- **Deleting in the app:** Deleting a receipt removes it from local storage; if iCloud sync is enabled, the associated CloudKit record will also be deleted from the selected CloudKit database (subject to Apple services).
- **Deleting the app:** Removing the app removes locally stored app data on your device.

### Third‑party retention (Apple / Google)
- **Apple iCloud / CloudKit:** If iCloud features are used, Apple may process and retain synced content according to Apple’s policies.
- **Google Gemini:** Google’s Gemini API usage policies state Google retains prompts/context/output for **55 days** for abuse monitoring. See: https://ai.google.dev/gemini-api/docs/usage-policies

ReceiptFox cannot directly delete data retained by Apple or Google outside the app. Please refer to their policies for retention and deletion options:
- Apple: https://www.apple.com/legal/privacy/
- Google: https://policies.google.com/privacy

---

## Revoke consent & request deletion

**Revoke consent**
- You can stop Camera access by denying **Camera** permission in iOS Settings.
- You can stop Photos importing by denying **Photos** permission in iOS Settings.
- You can stop iCloud sync/sharing by signing out of iCloud or disabling iCloud for ReceiptFox in iOS Settings.
- AI extraction occurs when you scan/import a receipt for extraction. You can avoid AI processing by not scanning/importing receipts.

**Request deletion**
- You can delete receipts in‑app at any time.
- Deleting the app removes locally stored data from your device.
- For data retained by Apple or Google as part of iCloud/CloudKit or AI processing, deletion requests are governed by their policies (links above).

---

## Subscriptions and payments (ReceiptFox Pro)
If you subscribe to ReceiptFox Pro, payment is processed by Apple via your Apple ID. ReceiptFox does not receive your full payment card details.

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
