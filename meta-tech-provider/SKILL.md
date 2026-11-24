---
name: meta-tech-provider
description: Run Meta Tech Provider onboarding for a product that serves customers' WhatsApp accounts, from account access, Business Verification and Cloud API tests through App Review, submission and decision tracking.
---

# Meta Tech Provider onboarding

Own the operational work. Open the screens, gather evidence, fill the forms, set up the authorized demo, run tests, record and upload evidence, and check saved results. Resolve what you can from authorized sources. Ask the person only for missing facts, business decisions, authorization for actions outside the current scope, and confirmations Meta requires from them personally. After a handoff, resume at the same screen.

For a new application, start without assuming that a developer account, business portfolio, Meta app or working integration exists. For an explicit resume or status request, use the existing app and submission and start at the relevant step.

Use the authorized browser and project tools available in the current environment. Follow the current app dashboard if labels or required fields differ from the guide. Confirm all application facts for the current company and product.

## 1. Establish account access and discover the product

For a new application, ask this first in the user’s language if the answer is unknown.

> Do you already have a Facebook account or a managed Meta account we can use to register the app?

- **Account exists.** Use the authorized active session. If it needs sign-in, open the official login and advance as far as supported. For a secret the user must supply, use the harness's secure secret mechanism when permitted for that account. Hand off personal sign-in, CAPTCHA, two-factor or device confirmation when required. Complete [developer registration](https://developers.facebook.com/async/registration/) if missing.
- **Account missing.** Explain that an eligible account is required. Open [official Facebook signup](https://www.facebook.com/register/) or the organization's managed-account process. Identify the fields requested, ask only for missing data and fill the permitted fields using the actual person's information. Let the account holder complete personal acceptance and identity, email or phone verification when required. Continue developer registration when the account becomes available.

When blocked by a personal step, open the correct first-party screen for the correct account or portfolio. Say what appeared, the exact action the person must take, and what success looks like. Reobserve and continue after they finish. Advance independent preparation while waiting. Keep credentials, codes and private records out of chat, notes, screenshots and recordings.

Ask for the product name and available site, demo, documentation or repository. Inspect those sources to learn who uses it, whether it serves other businesses' WhatsApp accounts, how users send or receive messages and create templates, which features are in scope and where Meta data flows. Ask only for gaps. If the product is early, identify the working demo, public pages and integration work required to support the claimed use case. Implement or prepare what is authorized and explain the specific missing dependency when you cannot proceed.

If the business will use only its own WhatsApp assets, check Meta's direct developer path. Continue with this workflow for WhatsApp services offered to other businesses. [WhatsApp App Review eligibility](https://developers.facebook.com/documentation/business-messaging/whatsapp/solution-providers/app-review)

## 2. Create the Meta app and prepare the verified business

1. Identify the legal operator, administrator, registered name and address, business identifier when applicable, phone, email and domain. Use supplied records and reliable sources. Ask the owner to resolve discrepancies or supply missing documents. Populate the fields yourself.
2. Open [Create app](https://developers.facebook.com/apps/creation/), enter the app name and contact email, and choose **Connect with customers through WhatsApp**. On **Business**, create the portfolio if needed or link the correct one. Save and read back the new app and portfolio IDs. [Create an app with WhatsApp](https://developers.facebook.com/documentation/business-messaging/whatsapp/get-started)
3. Open **Use cases → WhatsApp → Customize → Tech Provider onboarding**. Choose the agreed independent route or enter the Solution Partner's app ID if applicable. Start Business Verification from this screen. Prepare and fill the portfolio information and provide the authorized documents Meta requests. Prompt the business administrator only where Meta requires their confirmation. Read back **Verified** on the linked portfolio. [Tech Provider onboarding](https://developers.facebook.com/documentation/business-messaging/whatsapp/solution-providers/get-started-for-tech-providers/) · [Business Verification](https://developers.facebook.com/documentation/development/release/business-verification)
4. In **App Settings → Basic**, set the name, contact email, icon, category, privacy URL and applicable website platform, domain, terms and deletion fields. Prepare or fix the public pages within scope. Open them while signed out to confirm they identify the operator, give a privacy contact and explain how to request deletion. Use a public instructions page or the relevant section of the privacy policy when the dashboard asks for an instructions URL. [Basic Settings](https://developers.facebook.com/documentation/development/create-an-app/app-dashboard/basic-settings)

## 3. Prove the demo and fill Data Handling

1. In **Use cases → WhatsApp → Customize → Quickstart → Start using the API → API Setup**, connect or create the test messaging account and record its identifiers and test phone number ID. Add a recipient within the authorized test scope. Send a sample and verify that it arrives in WhatsApp. Configure the official channel in the product. For inbound messaging, configure the webhook callback and required events under **WhatsApp → Configuration**, then verify a reply reaches the same conversation. Verify template creation on the test account. If a temporary credential expires, use an appropriate credential scoped to the test assets. On an ambiguous send, check provider and recipient evidence before retrying. [Cloud API test setup](https://developers.facebook.com/documentation/business-messaging/whatsapp/get-started) · [Webhooks](https://developers.facebook.com/documentation/business-messaging/whatsapp/webhooks/overview) · [Access tokens](https://developers.facebook.com/documentation/business-messaging/whatsapp/access-tokens)
2. Set up an isolated demo using fictitious data. If it requires login, create a product demo account with the minimum role that can reach the recorded features. Sign in from a fresh session using the same URL and steps Meta will receive. Check access to the conversation and template screens. Give the reviewer a way to obtain a usable conversation, with an approved test template when needed outside the service window. [Reviewer access and reproducibility](https://developers.facebook.com/docs/resp-plat-initiatives/appreview/tutorial/rejection-guide/)
3. Open **Data Handling** and prepare truthful answers. Identify the controller and its country, providers that can access Meta data, what they access and where processing or operational access occurs. Use actual configuration and authoritative provider evidence. If AI is in scope, verify the real feature, the data passed to the provider, applicable terms and any human handoff claimed. Confirm national-security disclosures using the displayed period and exclusions. Confirm which authority-request procedures the business actually follows, such as legality review, challenging unlawful requests, limiting disclosure and keeping records. Enter the confirmed answers yourself and verify the saved values. [Meta Data Handling guide](https://developers.facebook.com/docs/resp-plat-initiatives/individual-processes/data-handling-questions/tutorial)

## 4. Record, submit and verify App Review

Open **Tech Provider onboarding → Begin App Review** and request **Advanced Access** for the two WhatsApp permissions. Prepare a separate explanation and video for each. Ask for additional permissions only when needed by the demonstrated product.

| Permission | What to show |
| --- | --- |
| `whatsapp_business_management` | Explain which assets the product manages for authorized businesses. Record creating a message template and show the resulting item in the same account. Meta also accepts WhatsApp Manager for this proof. |
| `whatsapp_business_messaging` | Explain who sends messages and how. Record composing and sending a message, then show that same message received in WhatsApp on mobile or web. Meta also documents a sending alternative in API Setup. |

If the new template is listed as `PENDING`, describe the video as proof of creation and report the visible status. Template approval is a separate decision.

Complete each card’s explanation, recording, permitted-use attestation and API test evidence as prompted. If the card counts successful calls, perform the action on the matching test assets and verify that the panel records the requirement as complete. Complete the fields for any permission included by the dashboard. [Meta permission-specific review requirements](https://developers.facebook.com/documentation/business-messaging/whatsapp/solution-providers/app-review)

Fill **Reviewer instructions** with the demo URL, exact navigation and expected results. Use the designated private field for demo credentials when required. Upload the recordings and complete the attestations within scope. Reopen the draft independently, play both videos in Meta's player and verify that the instructions, declarations, private fields and required call results persisted.

If the user already authorized submission of this app, submit after verification. If the owner reserved the final click, leave the correct draft open at **Submit for Review** with the verified draft link. Reopen **App Review → Submissions** or **Requests** and capture the submission ID and the observed in-review status.

## 5. Confirm the decision and hand off the next phase

Check **App Review → Submissions**, the request’s detailed feedback, **Required Actions** and the app’s **Alerts → Inbox**. Match the submission ID, report each permission decision, required actions, Data Use Checkup and publication status. A new draft can sit beside an existing decision. Follow the original request by its ID. If Meta asks for a correction, use the actual feedback, fix and retest the affected proof within scope, and follow the existing submission authorization.

Record approval per permission. Check the app’s publication state separately. Real customer onboarding also needs its own verification. Meta allows App Review before Embedded Signup is complete. Handle publication and a client pilot under their own authorized scope. Enable scheduled checks or notifications only when requested. [Publish a Meta app](https://developers.facebook.com/documentation/development/release/) · [Embedded Signup](https://developers.facebook.com/documentation/business-messaging/whatsapp/embedded-signup/overview/)
