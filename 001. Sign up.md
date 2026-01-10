
---

# Microsoft Intune Free Trial (30 Days) – Complete Notes

## Introduction

This session explains how to sign up for a Microsoft Intune free trial account for 30 days. Microsoft Intune provides Mobile Device Management (MDM) and Mobile Application Management (MAM) through a secure, cloud-based service. It is managed using the Microsoft Endpoint Manager Admin Center. Intune ensures corporate data, devices, and applications are properly configured, securely accessed, updated, and compliant with organizational policies.

Before using Microsoft Intune for any organization, an Intune tenant must be configured.

---

## Trial Eligibility and Account Options

If you do not already have access to the Intune portal, Microsoft allows you to sign up for a free 30-day trial.

There are two possible scenarios:

* If you already have a work or school account, you can sign in using that account and add Intune to your subscription.
* If you do not have an account, you can create a new Microsoft account specifically for Intune.

---

## Accessing the Sign-Up Page

A web browser is opened (Microsoft Edge in this demonstration).
The Microsoft Intune trial sign-up URL is pasted into the address bar and opened. This takes you directly to the Intune sign-up form.

---

## Starting the Registration

You must enter an email address and click Next.
After entering the email address, Microsoft indicates that a new account must be created.
Select the option to create a new account.

---

## Entering Organization Details

You are required to provide the following information:

* Full name
* Business phone number
* Company name
* Company size
* Country or region

The country or region selection is extremely important. This setting determines regional services and cannot be changed later. In this demonstration, India is selected as the country.

After filling in all required details, click Next.

---

## Phone Number Verification

Click Send verification code.
A verification code is sent to the provided phone number.
Enter the received code and click Verify.

---

## Tenant Domain and Admin Account Setup

You must now create a tenant domain that represents your organization. The domain follows this format:

yourdomain.onmicrosoft.com

Microsoft provides a suggested domain name, but it can be changed.

In this example:

* The username is set to **intuneadmin**
* The tenant domain is set to **msftintunelab01.onmicrosoft.com**

This results in the admin sign-in account:
[intuneadmin@msftintunelab01.onmicrosoft.com](mailto:intuneadmin@msftintunelab01.onmicrosoft.com)

A password is then created for this account.
After entering the password, click Next.

---

## Account Creation Process

A message appears stating that the account is being created and the page should not be refreshed.
Do not refresh or close the browser during this step.

---

## Additional Details

You are prompted to enter address and other basic user or organization details.
After completing the information, click Save.

Next, you are asked to enter a Tax ID or PAN registration number (India-specific requirement).
Enter the number and click Save again.

Another message appears asking you not to refresh the page.

---

## Account Confirmation

Once the process completes:

* Your username is displayed on the screen.
* A confirmation email is sent to the email address used during sign-up.
* The email confirms that your Microsoft Intune trial subscription is active.

Click Get Started to proceed.

---

## Microsoft 365 Admin Center Access

You are redirected to the Microsoft 365 Admin Center.
At this stage:

* A new Azure Active Directory–backed tenant has been created.
* The Microsoft Intune subscription is hosted inside this tenant.

---

## Verifying Azure Active Directory Tenant

In the Microsoft 365 Admin Center:

* Click Show all
* Select Azure Active Directory

The tenant name is displayed as:
msftintunelab01.onmicrosoft.com

From Azure Active Directory, you can create and manage users, groups, and access settings.

---

## Verifying Microsoft Intune License

Return to the Microsoft 365 Admin Center.
Navigate to Billing and then Licenses.
Select Microsoft Intune.

The license information shows:

* Total licenses: 25
* Used licenses: 1

One license is assigned to the admin user created during setup.

Click Manage subscription details to view more information.
The subscription type is Microsoft Intune Trial, and the expiry date is shown, confirming the 30-day validity.

---

## What You Can Do During the Trial

With the Intune trial active, you can:

* Add users and devices
* Assign Intune licenses
* Deploy and manage applications
* Configure device configuration policies
* Configure compliance policies
* Configure security and protection policies
* Begin modern endpoint management

---

## Conclusion

The Microsoft Intune 30-day free trial account has been successfully created.
You now have:

* A working Azure Active Directory tenant
* An active Microsoft Intune trial subscription
* Administrative access to configure and manage endpoints

The trial remains valid for 30 days.

---

## End of Notes
