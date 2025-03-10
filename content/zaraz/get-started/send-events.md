---
pcx-content-type: how-to
title: Send events
weight: 5
meta:
  title: Send events to a third-party tool
---

# Send events to a third-party tool

Events are bundles of information Zaraz sends to a third-party tool when a particular trigger is matched. For example, you might want to track purchases in your website, and create a trigger that sends information about this to your Google Analytics account. Refer to [Zaraz Track](/zaraz/web-api/zaraz-track/) for more information.

To start using events, first create a trigger to determine when this bundle of information is sent to a third-party tool. If you have already [set up a trigger](/zaraz/get-started/create-trigger/), follow these steps to create an event.

1.  Log in to the [Cloudflare dashboard](https://dash.cloudflare.com/login), and select your account and website.

2.  Go to **Zaraz**.

3.  Under **Third-party tools**, click **Edit** on the third-party tool you want to send an Event to — for example, Facebook Pixel or Google Analytics.

4.  Click the **Create event**.

5.  Give the event a descriptive name.

6.  In the **Firing Triggers** field, choose the relevant trigger or triggers you [previously created](/zaraz/get-started/create-trigger/). If you choose more than one trigger, the event will only be sent to the third-party tool when all the selected triggers are matched.

7.  Depending on the tool you are adding, you might also have the option to choose an **Event type**.

8.  Click **Save**.

The new event will appear under **Tracking Events**. To edit an event, refer to [Edit tools and events](/zaraz/get-started/edit-tools-and-events/).
