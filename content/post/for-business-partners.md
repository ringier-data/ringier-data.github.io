---
title: For business partners
subtitle: Those who require access only to specific RC+ SSO protected resources 
date: 2023-08-12
---

We are committed to providing a seamless user experience for Connect+ Platform by designing it to be as straightforward as possible.
Therefore, we ensure that all the complexity is hidden behind the scenes. Single Sign-On is an intuitive approach that we offer our
business partners, engineers and scientists to enhance their developer experience. Since Connect+ involves multiple tools, services,
and SaaS solutions, we separate authentication from authorization to provide more flexible and granular permission control.

The authentication process is managed by the Ringier central SSO instance for all Ringier employees or external users. Meanwhile, a
dedicated SSO server handles authorization, which has all the users federated from the Ringier central instance.

## Prerequisites

You must have a Ringier corporate account and have completed the standard Okta enrollment process.

If you are not sure, please try logging in to https://ringier.okta.com, and you should see a dashboard.

## Connect+ SSO enrollment

Please visit https://rcplus.okta.com, enter your @ringier.ch email address as the username, and click the Next button.
If you have not logged in, you will be redirected to https://ringier.okta.com for authentication. Just use your existing Ringier
corporate account credential to log in.

Once you have been successfully authenticated with the Ringier Okta instance, you will be redirected back to the Connect+ SSO dashboard.
This completes the enrollment process.

## Special notes

### Alloy Cockpit

Please contact one of the following colleagues to grant you the initial access:
* Zhao Wang
* Andrea Artaria
* Erik Jonsson Thorén

Without it, https://rcplus.okta.com would authenticate you successfully without authorizing you for anything except for seeing an error
page.

Once you finished the steps of RC+ enrollment, please navigate to https://platform.alloy.ch. It would bring you an empty Alloy Cockpit.
Please contact the administrators again telling them you need a proper role for Alloy Cockpit. 

### AWS Billing Dashboard for costs and invoices

Please contact one of the same administrators above mentioning that you need to access the billing admin role of the AWS Organization.
