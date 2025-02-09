---
title: "Deploy Your First Hybrid Mobile App"
url: /howto8/mobile/deploy-your-first-hybrid-mobile-app/
weight: 50
---

## Introduction

Besides boasting native functionality, another major advantage of a hybrid mobile apps is that you only need to go through the approval process once. Updates after the approval process only require a new deployment of your app in Mendix Cloud.

This how-to teaches you how to do the following:

* Open a hybrid example app
* Install the app on your device

## Prerequisites

Before starting this how-to, make sure you have completed the following prerequisites:

* Install the hybrid Mendix Developer App on you device, which makes it easy to see a hybrid application in action without the need to get it approved in the Mendix Marketplace (for details and download links, see [Getting the Mendix Developer App](/refguide8/getting-the-mendix-app/) in the *Studio Pro Guide*)

## Opening a Hybrid Example App

To open a hybrid example app, follow these steps:

1. Open Mendix Studio Pro, clikc **New App**, and under the **Starter Apps** tab click **Blank App**.
2. Click the **Use this starting point** button.
3. Adjust your configurations (be sure to keep **Enable online services** > **Yes** selected) and then click **Create app**.
4. Click **Run** to deploy this application to Mendix Cloud:

    {{< figure src="/attachments/howto8/mobile/hybrid-mobile/deploy-your-first-hybrid-mobile-app/18581186.png" class="no-border" >}} 

    Studio Pro will notify you as soon as the application is deployed. While you wait, go to **Navigation**, click the **Hybrid phone app online** tab, and make sure your **Default home page** is set to **MyFirstModule.Dashboard**.
5. Click the small arrow to open the **View App** menu and select **View Hybrid Mobile App**:

    {{< figure src="/attachments/howto8/mobile/hybrid-mobile/deploy-your-first-hybrid-mobile-app/18581185.png" class="no-border" >}} 

    This will open the **View Hybrid Mobile App** pop-up window:

    {{< figure src="/attachments/howto8/mobile/hybrid-mobile/deploy-your-first-hybrid-mobile-app/18581184.png" class="no-border" >}}

6. Open the Mendix Developer App on your device and tap **Scan QR Code**:

    {{< figure src="/attachments/howto8/mobile/hybrid-mobile/deploy-your-first-hybrid-mobile-app/18581190.png" class="no-border" >}}

7. Scan the QR code on the screen with your Mendix Developer App:

    {{< figure src="/attachments/howto8/mobile/hybrid-mobile/deploy-your-first-hybrid-mobile-app/18581189.png" class="no-border" >}}

You should see the example application running on your device.

## Installing the App on Your Device

If you want to install this application as a native mobile app on your device, you can install it via iTunes or publish it to one of the mobile app stores. For details on how to achieve this, see [How to Publish a Mendix Hybrid Mobile App in App Stores](/howto8/mobile/publishing-a-mendix-hybrid-mobile-app-in-mobile-app-stores/).

## Read More

* [Debug a Hybrid Mobile Application](/howto8/monitoring-troubleshooting/debug-a-hybrid-mobile-application/)
