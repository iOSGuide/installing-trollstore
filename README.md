# Install TrollStore 2 Without Jailbreak on All Devices - Full Guide

TrollStore 2 is a reliable and permanent IPA installer designed to support various iOS versions, including iOS 14.0, 15.0-16.6.1, and iOS 17.0. Functioning through AMFI/CoreTrust, it employs the root certificate for app signing, ensuring stability without revocation risks.

![Cover Image](link-to-cover-image.jpg)

*TrollStore is not a jailbreak tool. TrollStore 2 IPA Installer utilizes a codesign bypass and additional exploits for the permanent signing of apps with necessary entitlements.

## TrollStore and TrollStore 2 Install Methods 

| From                  | To                  | Install arm64 (A8 - A11)                   | Install arm64e (A12 - A17 / M1 - M2)           |
|-----------------------|---------------------|-----------------------------------|---------------------------------------|
| iOS 13.7 and earlier      | iOS  13.7 and earlier   |           Unsupported                         |        Unsupported         |
| iOS 14.0                  | iOS 14.8.1              | [Install TrollStore (TrollHelper)](/installing-trollhelper) | [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota) |
| iOS 15.0                  | iOS 15.5 beta 4         | [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota) |   [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota)                                    |
| iOS 15.5                  | iOS 15.5                | [Install TrollStore (TrollInstallerMDC)](/installing-trollhelper-mdc) | [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota) |
| iOS 15.6 beta 1           | iOS 15.6 beta 5         | [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota) |                                       |
| iOS 15.6                  | iOS 15.6.1              | [Install TrollStore (TrollInstallerMDC)](/installing-trollhelper-mdc) | [Install TrollStore (TrollHelperOTA)](/installing-trollhelperota) |
| iOS 15.7                  | iOS 15.7.1              | [Install TrollStore (TrollInstallerMDC)](/installing-trollhelper-mdc) |  [Install TrollStore (TrollInstallerMDC)](/installing-trollhelper-mdc)                                  |
| iOS 15.7.2               | iOS 15.7.2              | [Install TrollStore (TrollHelper)](/installing-trollhelper) | Coming Soon                            |
| iOS 15.7.3               | iOS 15.8                | [Install TrollStore (TrollHelper)](/installing-trollhelper) | Not Applicable                        |
| iOS 16.0                  | iOS 16.1.2              | [Install TrollStore (TrollInstallerMDC)](/installing-trollhelper-mdc) | Unsupported                            |
| iOS 16.2                  | iOS 16.5                | [Install TrollStore (TrollHelper)](/installing-trollhelper) | [Install TrollStore (Misaka)](/installing-trollhelper-misaka) |
| iOS 16.5.1               | iOS 16.5.1              | [Install TrollStore (TrollHelper)](/installing-trollhelper) | No Installation Method                 |
| 16.6 beta 1           | iOS 16.6 beta 1         | [Install  TrollStore (TrollHelper)](/installing-trollhelper) | [Install TrollStore (Misaka)](/installing-trollhelper-misaka) |
| iOS 16.6 beta 2           | iOS 16.6.1              | [Install TrollStore (TrollHelper)](/installing-trollhelper) | No Installation Method                 |
| iOS 16.7                  | iOS 16.7.2              |           Unsupported                         |        Unsupported         |
| iOS 17.0                  | iOS 17.0                | [Install TrollStore (TrollHelper)](/installing-trollhelper) | No Installation Method                 |

                                                                

## Best TrollStore Compatible Apps for iOS

The TrollsMe App is the ultimate TrollStore application, incorporating all TrollStore tools seamlessly into a single, comprehensive platform. Enjoy the convenience of having all TrollStore tools in one place.

![TrollsMe App Icon](link-to-app-icon-image.jpg)

[Download TrollsMe TrollStore](https://iospack.com/apps/trollsme-trollstore/)

## Adding Other IPA Files to TrollStore 2

Follow these steps to effortlessly add other IPA files to TrollStore 2:

1. [Download the IPA file](https://iospack.com/apps/trollsme-trollstore/) using Safari.
2. In the Downloads section, locate the IPA file and tap on it to open the share sheet.
3. Choose the TrollStore icon from the options to import the IPA into TrollStore 2.
4. Once completed, open the TrollStore 2 application to view and manage the installed IPAs. Access the home screen to conveniently launch the installed IPA apps.

## Uninstalling Permanent Signed IPA Applications

Unlike standard app deletions, permanently signed IPA applications cannot be removed from the home screen. Instead:

1. Open TrollStore and navigate to the list of installed applications.
2. Select the app you wish to uninstall.
3. Press on the app name, and a red "Uninstall App" button will appear.
4. Click on the button to successfully uninstall the application.

## Uninstalling TrollStore IPA Installer

TrollStore IPA Installer-installed applications can only be uninstalled through TrollStore. Take the following steps:

1. Open TrollStore and locate the installed application.
2. Click on the application or swipe right in the Applications tab.
3. Choose the "Uninstall TrollStore" option to remove the application seamlessly.

## Credits

- **Lars Fröder (opa334):** Developer of TrollStore Jailed iOS app, enabling the installation of IPAs permanently with arbitrary entitlements and root helpers.
- **alfiecg_dev:** Identified the CoreTrust bug, facilitating TrollStore's operation through patching and contributed to automating the bypass.
- **Google Threat Analysis Group:** Discovered the CoreTrust bug as part of an in-the-wild spyware chain and responsibly reported it to Apple.
- **LinusHenze:** Uncovered the installd bypass utilized for installing TrollStore on iOS 14-15.6.1 via TrollHelperOTA, along with the original CoreTrust bug employed in TrollStore 1.0.
- **TrollsMe Developer Team:** Developers behind the TrollsMe App, the comprehensive TrollStore application embedding all TrollStore tools seamlessly.
