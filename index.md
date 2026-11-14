# Crux: AI Resume Checker — Privacy Policy

**Last updated: 2026-11-15**

## 1. Introduction

Crux: AI Resume Checker ("Crux", "the app", "we", "us") is an Android app that analyzes resumes using AI, checks them for applicant tracking system (ATS) compatibility, compares them to job descriptions, and writes cover letters. The app is published on Google Play under the developer account "Qwark". Package name: `com.crux.ai.resume`.

This policy explains what data the app collects, why, who receives it, how long we keep it, and what choices you have. It applies to the Crux Android app.

## 2. Summary

- You sign in with Google. We receive your name, email, Google user ID and profile picture URL.
- Resumes you upload are sent to Google's Gemini AI to be analyzed. We do not keep the original file.
- We do not run ads. We do not use analytics or crash-tracking SDKs. We do not sell personal information.
- You can ask us to send you your data or delete it by emailing us.

## 3. Information we collect

### 3.1 Information you provide or that comes from your Google account

- **Google account details.** When you sign in with Google, we receive your Google user ID, full name, email address and profile picture URL. Supabase Auth stores these.
- **Resume files.** PDF, Word, text files, or a photo you choose to take or select. These are sent to our server to be analyzed. See section 4 and section 6 for how they are handled.
- **Job descriptions.** Text you paste for the ATS Match and cover letter features. This is optional.
- **Analysis results.** Scores, feedback and improvement suggestions generated for you. We store these linked to your account. Depending on the feature, we may also store the text extracted from your resume, the job description, and generated cover letters, so you can see them again.

### 3.2 Information collected automatically

- **Free action counter.** The number of free actions you have used (3 free lifetime actions). Stored in our database.
- **Subscription status.** Whether you have an active Crux Pro subscription, the subscription product (monthly or yearly), its expiry date, and the Google Play purchase token. Stored in our database.
- **Purchase token on your device.** If a purchase cannot be verified immediately, the purchase token and product ID are temporarily saved on your device and retried later.
- **Standard server logs.** Our hosting provider (Supabase) keeps routine technical logs, which can include IP addresses and request details. We do not use them to profile or track you.

### 3.3 Information we do NOT collect

- No advertising SDKs. The app shows no ads.
- No analytics or tracking SDKs (such as Firebase Analytics, PostHog or Mixpanel).
- No crash-reporting SDKs (such as Sentry or Bugsnag). Google Play itself may give us anonymous crash and performance statistics through Android vitals.
- No location data.
- No contacts, SMS or call logs.
- No microphone access.
- No camera access, except when you choose to take a photo of a resume.
- No clipboard monitoring. Job descriptions are only read when you paste them into the app.
- No advertising ID.

## 4. How we use information

We use your information only to:

- Sign you in and keep your session.
- Analyze your resume and show you scores, feedback and suggestions.
- Check ATS formatting, match your resume to a job description, and generate cover letters.
- Show your past results to you.
- Enforce the 3 free action limit.
- Verify and manage Crux Pro subscriptions, including restoring purchases after reinstalling the app or changing phones.
- Respond to support, access and deletion requests.
- Protect the service from abuse and fraud, and meet legal and tax obligations.

We do not use your resume or personal data for advertising. We do not use it to train our own AI models.

## 5. How we share information

We do not sell your personal information. We do not share it for advertising. We share data only with the service providers below, which are needed to run the app.

| Provider | What they do | Data involved | Privacy policy |
|---|---|---|---|
| **Supabase** | Authentication, database, server functions | Account details, results, quota, subscription records, uploaded resume content while it is processed | https://supabase.com/privacy |
| **Google (Gemini API)** | AI analysis of resume content, job descriptions and cover letter requests | Resume content and job descriptions | https://policies.google.com/privacy |
| **Google (Sign-In)** | Login | Google account details | https://policies.google.com/privacy |
| **Google Play (Billing)** | Payments and subscription management | Purchase tokens, subscription state | https://policies.google.com/privacy |

**Important note about Gemini.** We use the free tier of the Google Gemini API. Under Google's terms for the free tier, content submitted may be used by Google to improve its products and services, and may be reviewed by human reviewers. Do not upload information you do not want processed this way. Google's handling of that data is described in its own terms and privacy policy, linked above.

We may also disclose information if the law requires it, to respond to valid legal requests, or to protect our rights, users or the service.

## 6. Data retention

| Data | How long we keep it |
|---|---|
| Original resume files (PDF, Word, text, photo) | Not kept. Used to produce your result, then discarded. |
| Text extracted from resumes, job descriptions, analysis results, cover letters | While your account exists. Deleted when your account is deleted. |
| Account details (name, email, Google ID, photo URL) | While your account exists. |
| Free action counter | While your account exists. |
| Subscription and purchase records | Up to 7 years, for financial and tax compliance. After you delete your account, we keep only what is needed for this purpose and remove the link to your name and email where possible. |
| Server logs | Kept by Supabase for its standard log period. |
| Data held by Google (Gemini, Sign-In, Play) | Governed by Google's own policies. |

If you delete your account, we delete the data listed above except the subscription and legal records described in this section.

## 7. Your rights

You can ask us to:

- **Access.** Send you a copy of the personal data we hold about you.
- **Portability.** Provide that copy in a common, readable format.
- **Correction.** Fix inaccurate data.
- **Deletion.** Delete your account and associated data (see section 6 for what we must keep).
- **Withdraw consent.** Stop using the app and cancel your subscription at any time. To cancel Pro, open Google Play, then Payments and subscriptions, then Subscriptions, and cancel Crux Pro. Cancelling does not delete your account.

To make a request, email **abdulmoizofficial07@gmail.com** from the address linked to your account. Use the subject line "Crux data request" or "Crux account deletion". We respond within 30 days. We may need to confirm your identity first.

**If you are in the EU/EEA or UK (GDPR).** We process your data to provide the service you asked for (contract), to verify subscriptions and meet tax laws (legal obligation), and to keep the service secure (legitimate interests). You can also object to or restrict processing, and complain to your local data protection authority.

**If you are in California (CCPA/CPRA).** You have the right to know, delete, correct, and opt out of the sale or sharing of personal information. We do not sell or share personal information as those terms are defined by California law. We will not discriminate against you for exercising your rights.

## 8. International transfers

Our servers are provided by Supabase and are located in Singapore (AWS ap-southeast-1). Google processes data in the countries where it operates, including the United States. This means your data may be processed outside your country. Where required, these providers rely on legal safeguards for transfers, such as standard contractual clauses.

## 9. Children's privacy

Crux is not directed at children under 13, and we do not knowingly collect their data. Signing in requires a Google account. If you believe a child has given us personal data, email us and we will delete it.

## 10. Security

- Data is encrypted in transit (HTTPS/TLS) between the app, our servers and the third parties above.
- Data stored with Supabase is encrypted at rest.
- Database access is restricted so that each user can read only their own records.
- Subscription status and free action counts can only be changed by our server, not by the app.
- Secret keys (the AI key and Google Play credentials) are stored on the server only and are never in the app.

No system is perfectly secure. If a breach affects your data, we will notify you and the authorities as the law requires.

## 11. Changes to this policy

We may update this policy. The latest version is always available at this page and through Settings, then Privacy policy, in the app. The "Last updated" date at the top shows when it last changed. If a change is material, we will say so in the app before it takes effect.

## 12. Contact us

- Email: **abdulmoizofficial07@gmail.com**
- Developer: Qwark (publisher of Crux: AI Resume Checker on Google Play)
- Source repository: https://github.com/AbdulMoizOfficial0/ResumeChecker
