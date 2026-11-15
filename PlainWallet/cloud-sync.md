# Cloud Sync

Cloud sync is optional. It keeps your cards in step across your devices by storing a copy with an online storage service. If you only use one device, you can skip this page.

> **Before you start:** PlainWallet does not encrypt your cards before sending them to a provider. The provider receives your card data as it is. Read [Privacy and Security](privacy-and-security.md) and decide whether this suits you.

## Choose a provider

PlainWallet supports three separate storage services:

- **ExtendsClass**
- **JSONBin.io**
- **JsonStorage.net**

You can use **one provider at a time**. Turning on one automatically turns off the other two.

> **Note about ExtendsClass:** Settings currently shows a warning that its JSON storage service may not be working. Check that the service is available before you rely on it.

Accounts, limits, and terms belong to the provider, not to PlainWallet.

## How sync works

- When the Home screen opens, PlainWallet downloads your cloud copy and merges it with the cards on your device.
- **Pull down** on the card list to download again at any time.
- When you add, edit, or delete a card, the change is uploaded.
- If something goes wrong, PlainWallet shows an error message. Check your internet connection and your provider details.

Turning sync on does not stop you from using the app offline. Your local cards are always available.

## Set up sync on your first device

1. Create an account with your chosen provider and get the credentials listed below.
2. In PlainWallet, open the menu (☰) and tap **Settings**.
3. Tick the checkbox for your provider.
4. Enter the credentials. **Leave the ID fields blank** so PlainWallet can create a new cloud copy.
5. Tap **Apply**.
6. On the Home screen, let the app sync (or pull down to refresh). PlainWallet creates the cloud copy on its first sync.

## Set up sync on another device

Use the **same credentials** and the **IDs of the existing cloud copy**. Use the QR code shortcut below, or type them in by hand.

1. Open **Settings** and tick the same provider.
2. Enter the same credentials and IDs.
3. Tap **Apply**.
4. On the Home screen, pull down to download your cards.

## What you need for each provider

Each provider has a **What's this?** link in Settings that opens setup notes inside the app.

### ExtendsClass

| Field | What to enter |
|-|-|
| **Api-key** | Your ExtendsClass API key. |
| **Security-key** | Your security key. It is sent along with each request. It is not used to encrypt your cards. |
| **Bin id** | Leave blank on the first device to create a bin. Use the same ID on other devices. |

### JSONBin.io

| Field | What to enter |
|-|-|
| **X-Access-Key** | An access key from JSONBin.io that is allowed to create, read, and update a bin. |
| **Bin ID** | Leave blank on the first device to create a bin. Use the resulting ID on other devices. |

### JsonStorage.net

| Field | What to enter |
|-|-|
| **API key** | An API key from JsonStorage.net that is allowed to read, create, and modify items. |
| **User ID** | Leave blank on the first device. |
| **Item ID** | Leave blank on the first device. |

After the first sync, PlainWallet saves the IDs it receives. Enter those same IDs on your other devices. The **What's this?** link shows how to find them in your provider account.

## Share your setup with a QR code

Instead of typing everything on a second device, you can use a QR code.

**On the device that is already set up:**

1. Open **Settings**.
2. Tap the provider's **Share** button. A QR code appears.

**On the new device:**

1. Open **Settings** and tap the provider's **Scan** button.
2. Allow camera access if asked.
3. Point the camera at the QR code.

A QR code can only be shown once all required credentials and IDs are filled in. If you just created a new cloud copy, sync first so its ID is saved.

> **Keep the QR code private.** It contains your provider credentials. Anyone who scans or photographs it may be able to reach your cloud copy. Show it only to someone you trust, and do not keep screenshots of it.

## Switch providers or turn sync off

1. Open **Settings**.
2. Untick the provider's checkbox.
3. Tap **Apply**.

PlainWallet stops using that provider. Two things to remember:

- Your cards stay on your device.
- The copy stored at the provider is **not deleted**, and switching providers does **not** copy your data to the new one. To move your cards, [export a backup](backup-and-restore.md) first and import it after you switch, or connect to the cloud copy you want.

## Wi-Fi only option

In Settings, **Access the internet only when connected to Wi-Fi** makes ExtendsClass.com, JSONBin.io and JsonStorage.net wait for Wi-Fi before syncing. It also applies to the background logo update.

## Having trouble?

See [Troubleshooting and FAQ](troubleshooting.md#cloud-sync).
