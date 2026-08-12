# FibToMe — Privacy Policy

**[Terms of Service](TERMS.md)** · **[Support](SUPPORT.md)**

*Last updated 12 August 2026 · Applies to app version 1.0 and later*

> The short version. Your recordings stay on your phone. To analyse a recording, the video and its audio are sent to Google's Gemini service and we ask Google to delete them as soon as the analysis comes back. FibToMe's own servers never receive your video. You can delete everything from inside the app, and you can withdraw permission for AI processing at any time without losing access to the rest of the app.

## 1. Who is responsible for your data

FibToMe is operated by **eResonance**. For any privacy question, or to exercise any right described below, contact [info@eresonance.ch](mailto:info@eresonance.ch). We aim to respond within 30 days.

## 2. What the app collects, and why

### Recordings

When you record a scan, FibToMe captures video and audio (up to 10 seconds in Standard mode, up to 30 seconds in Extended mode). You can also import a video from your photo library.

**These files are stored on your device only.** They live in the app's private storage, in a folder specific to your account, and are never uploaded to a FibToMe server. Deleting a scan in the app deletes the file.

### Analysis performed on your device

Before anything leaves your phone, the app measures several things locally and they never leave the device on their own:

  - Face landmarks and expression events (Apple Vision framework)
  - Audio characteristics such as pitch, pauses and loudness
  - Speech transcription, which is performed *on-device* — the audio is not sent to Apple for this
  - An experimental pulse estimate read from small colour changes in facial skin

### Account information

If you create an account we store your email address, display name, chosen profile photo, and which sign-in method you used (Apple, Google, or email). If you use the app as a guest, an anonymous identifier is created instead and no email is collected.

### Usage and diagnostics

We record how many scans you have run in the current month (to enforce subscription limits), crash diagnostics, and basic analytics events such as "a scan started" or "a scan completed". These do not contain your video, audio, or transcript.

## 3. What is sent to third parties

| Who | What is sent | Why |
|---|---|---|
| Google (Gemini API) | Your recorded video and its audio track | To produce the behavioural analysis. This is the only service that receives your recording. |
| Google (Firebase) | Account details, analysis results (text and scores), subscription state, crash diagnostics, analytics events | Sign-in, syncing your history across devices, crash reporting |
| Apple | Purchase and subscription information | Processing subscriptions through the App Store. Apple handles payment; we never see your card details. |

We do **not** sell your personal data, and we do not share it with advertisers or data brokers.

### Your name and email are never sent to the AI service

Only the video and audio content is transmitted for analysis. Your name, email address, account identifier and device identifiers are not included in that request.

## 4. AI processing requires your explicit permission

The first time you start a scan, the app shows a disclosure describing exactly what is sent to Google Gemini and asks you to accept it. Analysis will not run without that acceptance — this is enforced in the app's analysis service, not only in the interface.

You can review that disclosure, and withdraw your permission, at any time under **Settings → Legal & Privacy → AI Data Processing**. Withdrawing stops future analyses. It does not delete reports you have already generated; delete those individually if you want them removed.

The app displays a visible indicator while AI analysis is active, in line with the transparency expectations of the EU AI Act.

## 5. How long data is kept

### On your device

Your recordings and reports remain until you delete them, or until you delete the app.

### On Google's Gemini servers

The video is uploaded for processing. FibToMe requests its deletion as soon as the analysis returns — including when the analysis fails. Google additionally expires uploaded files on its own schedule (currently 48 hours). Anything Google retains beyond our deletion request is governed by [Google's privacy policy](https://policies.google.com/privacy).

### On FibToMe's Firebase project

Account data and text analysis results are kept while your account exists, and are deleted when you delete your account.

## 6. Optional research participation

You may opt in to contribute anonymised data to improve the analysis. This is **off by default** and split into separate categories (behavioural, demographic, longitudinal) that you choose individually.

Contributed records are not stored against your account identifier. They are keyed by a value derived from your account identifier combined with a secret random value unique to your account. That secret never leaves your device.

When you delete your account, that secret is destroyed. Once it is gone, the contributed records cannot be linked back to you by anyone — including us — because the key cannot be recomputed. This is why we describe erasure of research contributions as making them permanently anonymous rather than deleting individual rows.

## 7. Community posts

If you choose to post a result to the FibToMe Community, that post is visible to other signed-in users. Posting is always a separate, explicitly confirmed action — sharing a video to another app never publishes anything to the Community. Posts contain your score and factor summary, not your video and not your name.

## 8. Your rights

Under the GDPR and comparable laws you have the right to access, correct, export, and erase your data, to restrict or object to processing, and to withdraw consent at any time. In the app:

  - **Erase everything** — Settings → Delete Account. This removes your account, your documents, your locally stored videos, and destroys the research key described above. If any part cannot be completed, deletion stops and tells you, rather than leaving data stranded.
  - **Withdraw AI consent** — Settings → Legal & Privacy → AI Data Processing
  - **Change research participation** — Settings → Research Participation
  - **Delete a single scan** — long-press it on Home or in your Profile

For anything not available in the app, write to [info@eresonance.ch](mailto:info@eresonance.ch). You also have the right to lodge a complaint with your local data protection authority.

## 9. What FibToMe is not

FibToMe is an educational tool for learning about behavioural signals. It is **not a lie detector**, and its output is not evidence of deception. Scores describe how consistent the measured signals were with one another; they are not calibrated against verified truth and are not probabilities.

The camera-based pulse estimate is **experimental and not a medical measurement**. It is excluded from scoring. Do not use it for any health decision.

## 10. Children

FibToMe is not directed at children and is not intended for anyone under 17. We do not knowingly collect data from children. If you believe a child has provided us data, contact [info@eresonance.ch](mailto:info@eresonance.ch) and we will delete it.

## 11. International transfers

Google's Firebase and Gemini services process data on infrastructure that may be located outside your country, including in the United States. These transfers rely on the safeguards Google offers for its services, including Standard Contractual Clauses where applicable.

## 12. Security

Data in transit is encrypted with HTTPS. Access to stored records is restricted by server-side security rules so that one account cannot read another's data. No system is perfectly secure, and we do not claim otherwise.

## 13. Changes to this policy

If we change how data is handled in a way that affects you, we will update this page and, where the change concerns AI processing, ask you to review and accept the disclosure again inside the app.
