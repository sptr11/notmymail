# NotMyMail

"I keep getting emails I never asked for! I need a way to make them stop!"

We've all been there - someone entered wrong email ID, your email ID, during their signup and you start getting bombarded with notifications. It's beyond frustrating!

NotMyMail provides a simple opt-out link empowering users to reclaim their inboxes.

## Take back control
This library gives developers an easy way to include an "Unsubscribe this address" link in any notification email. Recipients can opt-out in one click.

Be part of the solution and let people easily say "This is not my mail!" to regain their inbox bliss.

## Problem Context
Users often input incorrect email addresses unintentionally on signup flows. Products then send notifications to these addresses that the owners did not consent to. This creates negative experiences for both recipients and senders when unintended emails pile up.

There needs to be an easy opt-out method empowering recipients to remove the unwanted emails.

## Solution Overview
NotMyMail provides helper functions to include customizable one-click unsubscribe links in notification emails developers send. When recipients click the link, the developer is notified to remove that address.

## Features

- Easy-to-use Go interface generating tokenized links
- Secure encrypted tokens preventing tampering
- Customizable callback logic triggered on opt-out
- Handling of retries and complex workflows
