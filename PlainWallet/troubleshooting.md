# Troubleshooting and FAQ

Find your problem below. Each answer lists the quickest fix first.

## Cards and barcodes

### A barcode does not appear

- Check that the **Card number** is typed exactly as printed on your card.
- Check that the **Barcode type** matches your card. Some types only accept certain values.
- Try deleting the number and scanning the card with the camera instead. See [Barcodes](barcodes.md#scan-a-barcode).

### A store scanner will not read my barcode

- Open the card and use the slider to make the barcode wider or narrower.
- Turn up your screen brightness.
- Make sure the barcode type is correct.

### I cannot scan a barcode

- Allow PlainWallet to use the camera when Android asks. You can also allow it in your Android app settings.
- Hold the barcode steady and fill the camera view.
- Use the flashlight button in dim light, or the camera switch button to try another camera.

### I cannot find a card in my list

- Clear the **Filter cards...** box. A leftover filter hides other cards.
- The filter checks name, number, and notes, so try a different word.

## Logos

### I cannot select a logo

- For a logo from your device, open **Select Logo**, go to the **File** tab, and tap **Browse for image**.
- For a web logo, use the **Web** tab and make sure the address starts with `http` or `https`, and that the image loads in the preview.
- A web logo needs an internet connection and may stop working if the website removes the image.

## Backup and restore

### Import did not delete my other cards

That is intended. Import merges cards and never deletes cards that are missing from the file. See [Backup and Restore](backup-and-restore.md#how-import-combines-cards).

### I imported the same file twice

No problem. Importing the same backup again should not create duplicate cards.

### My new device is missing my cloud settings after import

Backups include cards only. Provider credentials are not exported. Set up [Cloud Sync](cloud-sync.md) again on the new device.

## Cloud sync

### Sync does not find my cloud cards

1. Check that the right provider is ticked in **Settings**.
2. Check that the keys and IDs match the ones used on your other device.
3. Tap **Apply**, return to Home, and pull down to refresh.
4. Check your provider's account and service status. If you use ExtendsClass, remember that Settings warns the service may not be working.

### A QR code is rejected

- Use a QR code made by PlainWallet for the **same provider**.
- On the source device, sync first so the resource ID is saved, then share again.
- Allow camera access when asked.

### The Share button will not show a QR code

All required credentials and IDs must be filled in first. If you just created a new cloud copy, sync once so the ID is saved.

### I see a sync error message

Check your internet connection and your provider credentials. If you turned on **Access the internet only when connected to Wi-Fi**, connect to Wi-Fi and try again.

## Quick answers

**Do I need an account?**
No. PlainWallet works fully on your device without any account.

**Do I need cloud sync?**
No. It is optional. Backup files are another way to move cards between devices.

**Are my cards encrypted in the cloud?**
No. PlainWallet does not encrypt card data before sending it. See [Privacy and Security](privacy-and-security.md).

**Can I use two cloud providers at once?**
No. Only one provider can be turned on at a time.

**Will I lose my cards if I uninstall?**
Possibly. Cards are stored on your device, so uninstalling or clearing app data can remove them. Keep a [backup](backup-and-restore.md) or use [Cloud Sync](cloud-sync.md).

**Does turning off sync delete my cloud copy?**
No. It only stops PlainWallet from using that provider.

**Which devices are supported?**
The current project targets Android.
