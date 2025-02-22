---
description: Enabling two-factor authentication on Docker Hub
keywords: Docker, docker, registry, security, Docker Hub, authentication, two-factor
  authentication
title: Enable two-factor authentication for Docker Hub
---

Two-factor authentication adds an extra layer of security to your Docker Hub
account by requiring a unique security code when you sign in to your account. The
security code is required in addition to your password.

When you enable two-factor authentication, you are also provided with a recovery
code. Each recovery code is unique and specific to your account. You can use
this code to recover your account in case you lose access to your authenticator
app. See [Recover your Docker Hub account](recover-hub-account/).


## Prerequisites

You need a mobile phone with a time-based one-time password authenticator
application installed. Common examples include Google Authenticator or Yubico
Authenticator with a registered YubiKey.

## Enable two-factor authentication

1. Sign to your Docker Hub account. 
2. Select your username and then from the drop-down menu, select **Account Settings**. 
3. Select the **Security** tab and then select **Enable Two-Factor Authentication**.
    The next page reminds you to download an authenticator app.
4. Select **Set up using an app**. 
    Your unique recovery code is sent to you.
5. Save your recovery code and store it somewhere safe.
    Your recovery code can be used to recover your account in the event you lose access to your authenticator app.

6. Select **Next** and then open your authenticator app. 
    You can choose between scanning the QR code or entering a text code into your authenticator app. 
7. Once you have linked your authenticator app, enter the six-digit code to in text field and then select **Next**.

Two-factor authentication is now enabled. The next time you sign
in to your Docker Hub account, you will be asked for a security code.