# Velvet Club privacy and support

Last updated: 3 October 2026

Velvet Club is an offline, single-player Windows game published by talktoai. It includes five-card draw poker, European roulette and a jewel-matching puzzle. All chips are fictional: they cannot be bought, sold, redeemed, transferred or exchanged for money or prizes. The game has no advertisements or in-game purchases.

## Information handled by the game

Velvet Club does not ask for an account, name, email address or other personal information. Its game code does not send gameplay records, advertising identifiers or analytics to the publisher, and it contains no advertising or analytics SDK. It does not request access to your microphone, camera, contacts or location.

The game stores progress and preferences locally on your computer. These include fictional chips, experience, table-round statistics, collected jewels, cosmetic progress, quiet mode and reduced-motion settings. It also records an unfinished table round so that a restart can preserve a dealt hand or safely finish an already determined result. This information stays in the local game profile; it is not uploaded by the game.

The Windows build uses Unity's persistent-data directory. With the current product settings, the normal profile location is:

`%USERPROFILE%\AppData\LocalLow\Shaf Games\Velvet Club`

The two progress files are `velvet-a.json` and `velvet-b.json`. They alternate to provide recovery if one file is damaged. Unity can also create local diagnostic logs in its application folders. The folder name reflects the local build's company setting; the Microsoft Store publisher is talktoai.

## Your control over local information

You can change quiet mode and reduced motion in the game's More panel. The free chip refill restores a low fictional-chip balance without deleting other progress.

The game has no separate progress-reset button. To remove its saved progress, close Velvet Club and delete both `velvet-a.json` and `velvet-b.json` from the profile folder. On the next launch, a new local profile starts with its initial fictional chips. Deleting only one file may restore progress from the other. You may delete the whole Velvet Club profile folder while the game is closed if you also want to remove local diagnostic files. Uninstalling the game may leave local saves behind.

## Microsoft Store and Windows

Microsoft may process purchase, account, payment, download, licensing, device or diagnostic information when you use Microsoft Store or Windows. That handling belongs to Microsoft's services and your Microsoft/Windows privacy settings. Velvet Club does not receive your payment-card information. See [Microsoft's Privacy Statement](https://privacy.microsoft.com/privacystatement) for Microsoft's practices.

## Email support

For help, contact **shaf@talktoai.org**. If you email us, your email address and the information you choose to include are used to respond to your request. Please avoid sending passwords, payment details or other sensitive information. Support email is separate from the offline game; sending it is voluntary.

## Changes and contact

This page may be updated when the game's data handling changes. The update date appears above. Questions about this policy or Velvet Club can be sent to **shaf@talktoai.org**.
