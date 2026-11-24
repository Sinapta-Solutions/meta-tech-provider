# Meta Tech Provider skill

![Meta Tech Provider and WhatsApp App Review. A chat bubble, an application form, and a confirmation check.](assets/meta-tech-provider-banner.png)

Use this Codex skill to prepare and submit a Meta Tech Provider application for a product that serves other businesses' WhatsApp accounts. The agent sets up access, prepares Business Verification, tests the Cloud API, and assembles the App Review submission.

[Install the skill](#install) · [Read the approval case](#an-18-day-app-review-case)

## An 18-day App Review case

One application took **about 18 calendar days from submission to confirmed approval**. The team prepared the business account and demo before submitting. Review timelines vary by application.

| Date | What happened |
| --- | --- |
| November 6, 2026 | The owner submitted App Review after checking the saved declarations, reviewer access, and two permission videos. |
| November 24, 2026 | The Meta dashboard showed approval for both WhatsApp permissions and no outstanding actions. |

### What the application included

- **Business Verification and public information.** The app was linked to a verified business. The public pages described data use, provided a privacy contact, and explained how to request deletion.
- **A demo the reviewer could open.** The review package included a working demo login, exact navigation steps, and test data. The team reopened the saved draft and played both uploaded videos in Meta's player before submitting.
- **One video per permission.** Each recording showed a real action and its result.

| Permission | What the recording showed |
| --- | --- |
| `whatsapp_business_management` | The creation of a WhatsApp message template. The template appeared in the list as `PENDING`, the status shown when the video was recorded. |
| `whatsapp_business_messaging` | A message sent from the product's inbox. The same message appeared in the recipient's WhatsApp Web conversation. |

The approval covered App Review. Publishing the app and connecting a customer's WhatsApp account are separate steps. [Meta's App Review requirements](https://developers.facebook.com/documentation/business-messaging/whatsapp/solution-providers/app-review)

## What the agent handles

1. **Set up the application.** Start with the account you have, identify your product's WhatsApp use case, and prepare the app and business portfolio.
2. **Test the product.** Verify the Cloud API path, set up reviewer access, and collect a separate recording for each requested permission.
3. **Prepare and track the submission.** Complete the forms with your project's facts, check the saved evidence, and verify the decision in Meta's dashboard.

The agent asks you for missing facts, business decisions, and confirmations Meta requires from the account holder.

## Install

Paste this into Codex to install the skill.

```text
$skill-installer https://github.com/Sinapta-Solutions/meta-tech-provider/tree/main/meta-tech-provider
```

Invoke `$meta-tech-provider` in the project you want to onboard. The portable package is a single [SKILL.md](meta-tech-provider/SKILL.md).

## Official Meta guides

- [Become a Tech Provider](https://developers.facebook.com/documentation/business-messaging/whatsapp/solution-providers/get-started-for-tech-providers/)
- [Get started with the WhatsApp Cloud API](https://developers.facebook.com/documentation/business-messaging/whatsapp/get-started)
- [Connect customer accounts with Embedded Signup](https://developers.facebook.com/documentation/business-messaging/whatsapp/embedded-signup/overview/)
