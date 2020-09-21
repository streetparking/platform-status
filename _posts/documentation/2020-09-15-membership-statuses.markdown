---
layout: post
title:  "Membership statuses"
date:   2020-09-15 14:24:13 -0600
categories: documentation

---
Membership statuses explained, most likely a refresher of incompelte vs incomplete expired.

**Active**
The subscription is in good standing and the most recent payment was successful. It's safe to provision your product for your customer.

**Trialing**
The subscription is currently in a trial period and it’s safe to provision your product for your customer. The subscription transitions automatically to active when the first payment is made.
- user is on hold
- users billing date moved

**Incomplete**
Payment failed when the subscription was created. A successful payment needs to be made within 23 hours to activate the subscription. See the payments section for details on resolving subscriptions with this status.

**Incomplete Expired**
The initial payment on the subscription failed and no successful payment was made within 23 hours of creating the subscription. These subscriptions do not bill customers. This status exists so you can track customers that failed to activate their subscriptions.

**Past due**
Payment on the latest invoice either failed or wasn't attempted.

**Unpaid**
The latest invoice hasn't been paid but the subscription remains in place. The latest invoice remains open and invoices continue to be generated but payments aren't attempted.

**Canceled**
The subscription has been canceled. During cancellation, automatic collection for all unpaid invoices is disabled (auto_advance=false).