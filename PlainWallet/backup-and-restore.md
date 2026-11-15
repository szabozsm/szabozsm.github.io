# Backup and Restore

A backup is a file that holds all your cards. You can use it to keep a safe copy, move to a new phone, or share cards between your own devices without cloud sync.

> **Keep backups private.** A backup file contains your card numbers, notes, and logo data. Store it somewhere you trust.

## Create a backup (Export)

1. Open the menu (☰) and tap **Export**.
2. PlainWallet creates a file named like `plainwallet_export_....json`, with the date and time in the name.
3. The Android share sheet opens. Choose where to send the file, such as a private folder on your device or a storage location you trust.

### What the backup includes

- Included: card names, numbers, barcode types, notes, colors, and logo data.
- Not included: cloud provider credentials and other app settings. You will need to set those up again on a new device.

## Restore a backup (Import)

1. Open the menu (☰) and tap **Import**.
2. Select a PlainWallet backup file (the `.json` file you exported).
3. Read the result message that appears.

### How Import combines cards

Import **merges** the file into your current cards. It does not replace your whole list.

| Situation | Result |
|-|-|
| A card in the file is new to your device | It is added. |
| A card exists on both, and the file's copy is newer | The newer copy from the file is used. |
| A card exists on both, the timestamps match, but the contents differ | The copy from the file is used. |
| A card is on your device but not in the file | It is left alone, not deleted. |

Importing the same backup twice should not create duplicate cards.

## Move cards to a new phone

1. On the old phone, tap **Export** and send the file somewhere you can reach from the new phone.
2. Install PlainWallet on the new phone.
3. Tap **Import** and select the file.

If you use cloud sync, you can instead connect the new phone to your existing cloud copy. See [Cloud Sync](cloud-sync.md).

## Tips

- Make a backup before deleting several cards or before switching cloud providers.
- Make a fresh backup after adding many new cards.
- Delete old backup files you no longer need.
