# Windows Hello for Business

[![windows hello for business](redd.png)](https://icncomputer.com/windows-hello-for-business/)



At its core, Windows Hello for Business provides a new, non-password credential for Windows 10 devices. It implements 2FA/MFA, meaning multilayered security that is much more difficult to bypass than protection that hinges solely on a correct username and password combination.


## Windows Hello for Business Setup

Microsoft has two main methods to set up Windows Hello for Business: Cert-Trust and Key-Trust.

We are going to look at the Key-Trust (or the Hybrid Key Trust) Windows Hello for Business setup method here.

Follow the instructions below to set up Windows Hello for Business step by step.


## Prerequisites

Hybrid environments are distributed systems that allow organizations to use on-prem and Azure-based identities and resources.

In Windows Hello for Business, the existing distribution system is a foundation that enables organizations to provide two-factor authentication for a single sign-in. These technologies were built on distributed systems that involved multiple pieces of on-prem and cloud infrastructure, including:

* Directories
* Public Key Infrastructure
* Directory Synchronization
* Federation
* Multifactor authentication
* Device Registration
* To deploy Hybrid Key Trust, your organization has to register its domain joined devices to the Azure Active Directory.

To initiate Windows Hello for Business provisioning, allow access to the URL account.microsoft.com. This launches the next steps in the provisioning process and helps complete the process.
