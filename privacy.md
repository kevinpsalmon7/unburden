# Privacy Policy

**Unburden**
Last updated: 15 August 2026

Unburden is a private writing app. It asks you a question, gives you a page to answer it on, and then lets you keep that page or burn it. This document explains exactly what happens to what you write.

Unburden is published by Kevin Psalmon (Safe in Self). If you have a question about anything below, write to **kevinpsalmon@gmail.com**.

---

## The short version

- Pages you **burn** are never stored anywhere, on your phone or on our servers. They exist only in your phone's memory while you write them.
- Pages you **keep** are stored on your device and in your account, so they follow you to a new phone.
- When you finish a page, its text is sent once to Anthropic's Claude so that a closing message can be written back to you. It is used for that reply and nothing else. It is not stored by us, and Anthropic does not train on it.
- We do not sell your data, we do not advertise, and we run no analytics or tracking of any kind.

---

## What we collect

### Your account

When you create an account we store your **email address**. If you sign in with Apple and choose to hide your email, we only ever see the private relay address Apple gives us, and that is what we store.

Authentication is handled by **Firebase Authentication** (Google LLC). Your password is never visible to us: Firebase stores a salted hash of it.

### What you tell us about yourself

During onboarding we ask for a **first name** and whether you are **a woman, a man, or would rather not say**. Both are used for one purpose only: to write questions and replies that address you correctly. Neither is shared with anyone, used for advertising, or used to profile you.

### What you write

- **Kept pages.** The question, your answer, the space it belongs to and the date. These are stored on your device and in your account.
- **Open subjects.** When a subject stays open, we store the questions belonging to it and the dates. **We never store your answers as part of a subject.**
- **Questions already asked.** So that the same question is never put to you twice.
- **Burned pages.** Nothing at all. A burned page is overwritten in memory and dropped. It is never written to disk and never uploaded.

### What we do not collect

No analytics, no crash reporting tied to your identity, no advertising identifiers, no location, no contacts, no tracking across other apps or websites. Unburden contains no advertising SDK.

---

## Where it is stored

Kept pages, open subjects and your first name and gender are stored in **Google Cloud Firestore**, in the European Union (multi-region `eur3`, Belgium and the Netherlands), inside a document tree that only your signed-in account can read or write. Access is enforced by server-side security rules, not by the app.

They are also stored in a file on your own device, protected by iOS file protection, which means the file is unreadable while your phone is locked.

---

## Artificial intelligence

Unburden uses **Claude**, a large language model from Anthropic, for two things.

**1. The closing page.** When you finish writing and choose what happens to the page, the question, your answer, your first name, your gender and which sitting it was are sent to our own server, which passes them to Anthropic's API and returns a few lines written for you. This happens once. We do not store the request. Anthropic processes it to produce the reply.

**2. Questions written for you.** When you ask for a question to be written, up to three of your **kept** pages are sent the same way, so the new question can come from what you actually wrote. Burned and deleted pages are gone and can never be sent.

The API key belongs to us and lives on our server, never in the app. Under Anthropic's commercial terms, inputs and outputs sent through the API **are not used to train their models**.

If you would rather none of this happened, do not use the closing page or the generated questions. The rest of the app works without them.

---

## Speech

If you dictate a page, iOS turns your speech into text. Whenever your language supports it, this happens entirely **on your device**. If it does not, Apple's speech recognition servers are used, under Apple's own privacy policy. Unburden never records, stores or transmits audio.

---

## Notifications

If you allow them, Unburden schedules reminders on your device for subjects you have left open. They are scheduled locally by iOS. Nothing is sent to a server, and the text of your questions never appears in a notification.

---

## Subscriptions

Payment is handled entirely by Apple. We never see your card, your billing address or your Apple Account. We receive only whether your subscription is active.

---

## How long we keep it

For as long as your account exists.

- **Signing out** empties this device. Your account keeps everything, and signing back in restores it.
- **Deleting your account**, from Settings inside the app, permanently removes your account and everything stored with it: every kept page, every open subject, every question already asked, and your first name and gender. This cannot be undone. There is no backup we can restore from.

---

## Your rights

If you are in the European Union or the United Kingdom, you have the right to access, correct, export or erase your data, and to object to its processing. Deleting your account inside the app does all of this immediately. For anything else, write to **kevinpsalmon@gmail.com** and we will answer within 30 days.

The legal basis for processing is the performance of our contract with you, which is providing the app you subscribed to.

---

## Third parties

| Who | What they receive | Why |
|---|---|---|
| Google (Firebase Authentication) | Your email address | To sign you in |
| Google (Cloud Firestore, Cloud Functions) | Kept pages, open subjects, first name, gender | To store your account and run our server |
| Anthropic | The text of the page you just finished, or up to three kept pages | To write the closing page or a new question |
| Apple | Your purchase | To take payment, and to recognise your subscription |

Each of them is bound by its own terms to protect that data, and none of them is permitted to use it for advertising.

---

## Children

Unburden is not intended for anyone under 16, and we do not knowingly collect anything from a child. If you believe a child has created an account, write to us and we will delete it.

---

## Not medical care

Unburden is a writing tool. It is not therapy, not treatment, and not a substitute for a doctor or a psychologist. Nothing it writes back to you is medical advice. If you are in crisis, please contact a professional or your local emergency service today.

---

## Changes

If this policy changes in a way that affects what happens to your writing, we will tell you inside the app before it takes effect.
