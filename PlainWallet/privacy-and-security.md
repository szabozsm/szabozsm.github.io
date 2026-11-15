# Privacy and Security

Your cards can include personal numbers, so it is worth knowing where your data lives and how to keep it safe.

## Where your data is stored

- **On your device:** Cards and settings are stored locally by the app. No account is required, and nothing leaves your device unless you choose to export or sync.
- **In backup files:** If you tap **Export**, the file contains your card numbers, notes, and logo data.
- **At a cloud provider:** Only if you turn on cloud sync. Then your card data is sent to that provider.

## Cloud sync and encryption

PlainWallet does **not** encrypt your card data on your device before sending it to a cloud provider. The provider receives your card data as it is.

The ExtendsClass **Security-key** is sent with each request as a header. Even though the in-app text may describe it differently, it does not encrypt your cards. Do not treat it as a guarantee that your data is end-to-end encrypted.

If that is not acceptable for your cards, leave cloud sync off and use [Backup and Restore](backup-and-restore.md) instead.

## Provider credentials

- Your provider keys are saved in the app's local settings on your device.
- A QR code made with **Share** contains those credentials. Anyone who scans or photographs it may be able to reach your cloud copy.

## Ways to protect yourself

1. **Keep exports private.** Store backup files in a private location and delete ones you no longer need.
2. **Share QR codes carefully.** Show them only to people you trust, in person, and delete any screenshots.
3. **Decide what to store.** Use the notes field for useful details, not for secrets such as PINs or passwords.
4. **Use provider accounts you control.** Choose strong, unique passwords and keys for your storage provider.
5. **Remember turning sync off is not deleting.** Untick a provider in Settings to stop using it. The copy at the provider stays there until you delete it in your provider account.

## Permissions

PlainWallet asks for camera access only when you scan a barcode or a QR code. You can continue to use the app without it by typing card numbers.
