---
sidebar_position: 2
---

Tap To Pay -- User Guide


## Table of Contents

- [Abbreviations and Acronyms](#abbreviations-and-acronyms)
- [Introduction \& Overview](#introduction--overview)
- [Objective \& Scope](#objective--scope)
- [Prerequisites ](#prerequisites)
  - [ISO Requirements](#iso-requirements)
  - [Merchant Requirements](#merchant-requirements)
  - [Device Requirements](#device-requirements)
  - [Application Requirements](#application-requirements)
- [ISO Tap to Pay Notification](#iso-tap-to-pay-notification)
- [Enabling Tap to Pay for Merchants](#enabling-tap-to-pay-for-merchants)
- [Automated Email Notifications](#automated-email-notifications)
  - [Merchant Starter Email](#merchant-starter-email)
- [Application requirement for Android Tap to Pay](#application-requirement-for-android-tap-to-pay)
  - [Install the Tap to Pay Ready Application Before a Transaction](#install-the-tap-to-pay-ready-application-before-a-transaction)
  - [](#)
  - [In-App Notification to Install the Tap to Pay Ready Application](#in-app-notification-to-install-the-tap-to-pay-ready-application)
- [Performing a Tap to Pay Transaction](#performing-a-tap-to-pay-transaction)
- [PIN Validation](#pin-validation)
- [Settlement Workflow](#settlement-workflow)
- [Tap to Pay Demo](#tap-to-pay-demo)
- [Conclusion \& contact details](#conclusion--contact-details)

#  Abbreviations and Acronyms 

This section provides a list of abbreviations and acronyms with their
appropriate full forms to improve user comprehension.

| Abbreviation | Full form |
| --- | --- |
| VT | Virtual Terminal |
| ISO | Independent Sales Organization |
| POS | Point of Sale |
| EPI | End point Identifier |
| NFC | Near Field Communication |
| MID | Merchant Identification Number |
| TID | Terminal Identification Number |

# Introduction & Overview

Tap to Pay on Mobile enables eligible merchants to accept contactless payments through the GeminiPay Mobile App on a supported iOS or Android mobile phones, without using a separate card reader.

After Tap to Pay is enabled for an ISO account, the ISO can enable the feature for eligible merchants and Virtual Terminal EPIs in Gemini Portal. Once enabled, merchants receive a starter email and can process Tap to Pay transactions using the GeminiPay Mobile App.

# Objective & Scope

The objective of this guide is to help ISOs and merchants enable and use Tap to Pay on Mobile through Gemini Portal and the GeminiPay Mobile App.

This guide covers the steps to enable Tap to Pay for eligible merchants, select the required Virtual Terminal EPIs, complete the mobile app setup, and process Tap to Pay transactions using a supported iOS or Android Mobile phone.

This guide is intended for ISO Admins, ISO Operators, Merchant Admins, and Merchant Operators who are authorized to configure or use Tap to Pay on Mobile

# Prerequisites 

Before using the Tap to Pay feature, ensure the following requirements are met:

## ISO Requirements

-   Tap to Pay on Mobile must be enabled for the ISO account.

-   The merchant must be boarded under a supported processor, such as TSYS or Elavon.

## Merchant Requirements

-   The merchant must be eligible to use Tap to Pay on Mobile.

-   The merchant must have at least one eligible Virtual Terminal EPI.

-   The appropriate MCC code must be assigned while enabling Tap to Pay.

-   The merchant must have valid credentials to log in to the GeminiPay Mobile App.

## Device Requirements

-   The merchant must use an NFC supported iOS or Android device.

-   For iOS, the device must be iPhone XR or later with iOS 18.4 or later.

-   For Android, the device must be NFC-enabled and must run Android OS 12 or later.

> Note: Android tablets are not supported for Tap to Pay on Mobile.

-   Android device must have Tap to Pay Ready Application installed from Play store.

## Application Requirements

-   The Version 3.1.1 of the GeminiPay Mobile App must be installed.

-   The device must have a stable Wi-Fi or cellular connection.

-   Parameter download must be completed after Tap to Pay is enabled.

-   NFC must be enabled on the device before processing Tap to Pay transactions.

# ISO Tap to Pay Notification

When Tap to Pay on Mobile is enabled for an ISO account, an automated email is sent to the ISO users. This email confirms that Tap to Pay is enabled for the ISO account and provides the next steps to enable the feature for eligible merchants.

The ISO can then enable Tap to Pay for merchants who are boarded under supported processors, such as TSYS or Elavon, and who use the GeminiPay Mobile App.

<div align="center">

<img src="images/Image%202.png" style="width: 5.925in; height: 2.9993055555555554in;" />

</div>

Fig 01: Automated mail for ISO from Gemini portal.

# Enabling Tap to Pay for Merchants

Tap to Pay must be enabled at the **device (EPI) level** for each merchant. Follow the steps below to activate Tap to Pay for a merchant
device

1.  Log into the **Gemini Portal** using **ISO credentials**.

2.  Navigate to the **Merchant Management** module.

3.  Select the required **Merchant DBA Name**.

4.  On the **Merchant Overview** page, select **Settings** from the right pane.

<div align="center">

<img src="images/Image%203.png" style="width: 7.260416666666667in; height: 3.59375in;" />

</div>

Fig 02: Settings option on the Merchant Overview
page.

5.  Select the **Tap to Pay** tab.

6.  Select the appropriate **Generic MCC Code** from the available list.

*Note: The MCC Code configured here is only used to identify what icon to be displayed on the Tap to Pay present card screen.

<div align="center">

<img src="images/Image%204.png" style="width: 7.260416666666667in; height: 3.59375in;" />

</div>

Fig 03: Tap to Pay configuration with MCC code and eligible EPIs.

1.  In the **Eligible VT EPIs** section, select the EPIs that require Tap to Pay activation.

> You can:

-   Select individual EPIs.

-   Select **Select All EPIs** to enable Tap to Pay for all available eligible Virtual Terminal EPIs.

8.  Select **Enable** to apply the configuration.

After Tap to Pay is enabled, the merchant receives a starter email with the next steps to use Tap to Pay on Mobile in the GeminiPay Mobile App.

# Automated Email Notifications

Tap to Pay for Mobile sends automated email notifications when the feature is enabled or updated at the merchant level. These emails help merchants understand the current Tap to Pay status and the next steps required to use the feature.

## Merchant Starter Email

When Tap to Pay on Mobile is enabled or updated for a merchant, anautomated email is sent to the Merchant Admin. The email includes the merchant details, Tap to Pay status, effective date and time, and the user who updated the configuration.

The email also provides the next steps for the merchant, including:

-   Verifying that the mobile device meets the required hardware and     operating system requirements.

-   Installing or updating the supported GeminiPay Mobile App.

-   Logging in with valid merchant credentials.

-   Using the Tap to Pay-enabled EPI to start accepting contactless payments.

<div align="center">

<img src="images/Image%205.png" style="width: 5.159722222222222in; height: 4.6in;" />

</div>

Fig 04: Automated mail for Merchant when Tap to Pay configuration is updated.

# Application requirement for Android Tap to Pay

Merchants enabled with Tap to Pay in Gemini Portal must install the external **Tap to Pay Ready** application by Visa Inc. to process Tap to Pay transactions on Android devices.

## Install the Tap to Pay Ready Application Before a Transaction

1.  To install the Tap to Pay Ready application, follow these steps:

2.  Open **Google Play Store** on the Android device.

3.  Search for **Tap to Pay Ready**.

4.  Select the **Tap to Pay Ready** application from the search results.

5.  Select **Install**.

<div align="center">

<img src="images/Image%206.png" style="width: 2.085509623797025in; height: 4.6in;" />

</div>

Fig 05: Installed Tap to Pay Ready application from Google Play store orApp store.

## 

## In-App Notification to Install the Tap to Pay Ready Application

If the Tap to Pay Ready application is not installed, the GeminiPay Mobile App displays a requirement prompt when the merchant attempts to process a transaction with Tap to Pay as a payment method.

From the prompt, the merchant can select **Install App**. The device redirects the merchant to the Tap to Pay Ready application listing in Google Play Store.

<div align="center">

<img src="images/Image%207.png" style="width: 2.0723108048993875in; height: 4.6in;" />

</div>

Fig 06: In-app notification to install the Visa Tap to Pay Ready application


# Performing a Tap to Pay Transaction

To process a Tap to Pay transaction using the GeminiPay Mobile App, follow the steps below:

1.  Log into the **GeminiPay Mobile App** using valid **Merchant or Operator credentials**.

2.  Initiate a new transaction, by entering the transaction amount and    select Process Payment.

<div align="center">

<img src="images/Image%208.png" style="width: 2.085521653543307in; height: 4.6in;" />

</div>

Fig 07: Initiating a Sale Transaction from the Gemini Pay Mobile Application.

3.  Select **Tap** as the payment method.

<div align="center">

<img src="images/Image%209.png" style="width: 1.8134864391951007in; height: 4.0in;" />

</div>

Fig 08: Available Payment Methods for the merchant to select.

4.  Enter customer details, if required (based on portal configuration).

<div align="center">

<img src="images/Image%2010.png" style="width: 1.8134864391951007in; height: 4.0in;" />

</div>

Fig 09: Capturing Customer details against a Sale Transaction.

5.  Select **Pay** to initiate the Tap to Pay process.

<div align="center">

<img src="images/Image%2011.png" style="width: 1.6321391076115486in; height: 3.6in;" />

</div>

Fig 10: Tip and Summary screen prior processing Payment (Based on Gemini Portal Configuration).

6.  Complete the device-specific Tap to Pay flow.

-   [**For iOS Device:**]{.mark} During the first Tap to Pay transaction     on the device, the user is prompted to provide consent to enable Tap to Pay with the registered Apple ID.

<div align="center">

<img src="images/Image%2012.png" style="width: 1.6321391076115486in; height: 3.6in;" />

</div>

Fig 11: Consent Screen for Merchant to accept payments using Tap to Pay.

-   **For Android Device:** The system uses the installed Tap to Pay Ready application and prompts the user to tap the card when ready.

<div align="center">

<img src="images/Image%2013.png" style="width: 2.085509623797025in; height: 4.6in;" />

<img src="images/Image%2014.png" style="width: 2.085509623797025in; height: 4.6in;" />

</div>

Fig 12: Enrolling an Android device with the Tap to Pay Ready
application to accept payments.

7.  The customer taps a supported contactless card, mobile wallet, or NFC-enabled device on the merchant's phone.

Note: In case of a contactless card read failure, there is no dedicated fallback flow within the Tap to Pay journey. The user will be redirected back to the Sale screen and must reinitiate the transaction.

8.  The application processes the transaction and displays a real-time **Approved** or **Declined** response on the merchant device.

<div align="center">

<img src="images/Image%2015.png" style="width: 2.085509623797025in; height: 4.6in;" />

<img src="images/Image%2016.png" style="width: 2.085509623797025in; height: 4.6in;" />

</div>

Fig 13: Approval and Decline Response against an initiated Sale Transaction.

Once approved, the transaction is recorded in the Gemini Portal and added to the active Tap to Pay batch.

# PIN Validation

For Tap to Pay transactions that require cardholder verification, [PIN validation](https://docs.koard.com/docs/security/apple/pin-validation) is securely handled through the integrated SDK. When a customer taps their card and PIN authentication is required (based on card rules, amount, or processor settings), the application automatically displays a secure PIN entry screen on the device. The customer enters their PIN directly on the mobile device.

The PIN is encrypted within the secure SDK environment and transmitted directly to the processor for validation. Gemini does not store, access, or log any PIN information.

Once validated, the transaction response (Approved or Declined) is returned to the mobile application and recorded in the Gemini Portal

# Settlement Workflow

Tap to Pay transactions are maintained in a separate batch from other transaction types. During settlement, both the Tap to Pay batch and the Manual Transaction batch are submitted for settlement.

After settlement is completed, funding is processed by the merchant's processor based on the merchant's existing funding schedule and processor configuration.

**Note:** If the Manual batch or Tap to Pay batch fails during
settlement, an error notification is displayed to the user for review and reconciliation.

<div align="center">

<img src="images/Image%2017.png" style="width: 2.0855074365704285in; height: 4.6in;" />

</div>

Fig 14: Batch Settlement Error notification.

# Tap to Pay Demo

Follow the link below to view a demo video on initiating a Tap to Pay transaction from an iPhone.

[Click here to be routed to the tutorial
video](https://netorg269189-my.sharepoint.com/:v:/g/personal/leo_merchantindustry_net/IQA13R6YAmbhQqTflT3YWeIVAZuyVxDJqEiDmIPbcyGtuu8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=d3rI7O)

# Conclusion & contact details

This User Journey reflects Gemini's continued commitment to delivering secure, reliable, and innovative payment solutions. By following the outlined steps, ISOs and merchants can seamlessly enable Tap to Pay feature and process transaction through the Gemini Pay Mobile
Application.

We appreciate your partnership and remain dedicated to supporting your success.

For any questions or assistance:
