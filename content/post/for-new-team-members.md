---
title: For new team members
subtitle: Those who will work with us as an integral part of the team 
date: 2023-08-13
---

Greetings!

We’ve never had someone quite like you on board, and that’s a huge compliment around here! We’re thrilled to have you along for the ride.
Looking so much forward to having you helping us make waves!

Adequate documentations and resources are available, but reasonably limited to authorized access. Your Ringier corporate account is the
key to get the access.

## Set up your Ringier corporate account

You should have received the initial credential and user manual either by postal mail or via your private email inbox to set up your
Ringier corporate account. Please go to https://ringier.okta.com, follow the instructions you received (if you do not have it,
[here is a copy in English](/assets/Okta_User_Guide_EN.pdf)) to set up your Ringier corporate account. In case of any issue, 
please contact Ringier Corporate IT HelpDesk
(email: helpdesk@ringier.ch, 
telephone: +41 44 259 33 33, 08:00-17:00, 
Monday to Friday).

The Ringier Okta instance is integrated with a service dynamically scoring the risk of the endpoint device to determine which verification
level is required for each authentication and authorization request. Those devices not managed by Ringier IT are ranked with very high
risk level therefore the MFA of Okta will be required very often.

Having the [Okta Verify](https://apps.apple.com/de/app/okta-verify/id490179405?l=en) installed _**directly on the laptop**_ (and of
course, properly configured) would save you a lot of time.

## Inform the administrators to grant you access to the RC+ SSO

Please go to https://mail.ringier.ch, get authenticated with Ringier Okta you just enrolled, and email one of the following
administrators to grant you the access to RC+ SSO:
* Andrea Artaria (andrea.artaria@ringier.ch)
* Erik Jonsson Thorén (erik.jonsson@ringier.ch)
* Zhao Wang (zhao.wang@ringier.ch)

When it is done, please continue to the next step.

## Set up the account federation for RC+

Please navigate to https://rcplus.okta.com, type in your @ringier.ch email address as the Username, and click the Next button. You will be
redirected back to https://ringier.okta.com for authentication if you are not logged in.

There is IdP federation configured behind the system: we ask the Ringier corporate tenant to authenticate you without requiring you to
create another set of credential.

Once you get in, you should be able to access the [2nd half of this document](https://doc.p.alloy.rcplus.io/dev/devenv/generic)
to continue setting up your work environment.
