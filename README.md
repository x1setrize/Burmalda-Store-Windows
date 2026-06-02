# BurmaldaStore — Windows Desktop App

**BurmaldaStore** is a Windows desktop application for managing a skirt product catalog, local Excel tables, an online product database, accounts, cart synchronization, profile notifications and analytics.

Current version: **6.7 Stable**

---

## Download

The latest Windows build is available in the **Releases** section of this repository.

Download the archive:

**BurmaldaStore_Windows.zip**

After downloading, extract the archive and run:

```text
BurmaldaStore.exe
```

---

## Main features

* Online skirt catalog connected to the BurmaldaStore API.
* Local Excel table mode with autosave.
* Import and export support for Excel files.
* User account system with login and registration.
* Admin-only online product database editing.
* Shopping cart with synchronization.
* Account notifications for login, password changes and profile image changes.
* Analytics page with product statistics, top brands, colors, purposes and low-stock items.
* Dark neon interface with custom UI elements and smooth animations.
* Russian and English interface language support.

---

## Catalog modes

BurmaldaStore supports two main table modes:

### Online catalog

The online catalog is loaded from the server and synchronized through the BurmaldaStore API. Regular users can browse products and use the cart. Only the admin account can add products to the shared online database.

### Local table

The local table is stored on the user’s computer. It can be edited, imported from Excel, exported back to Excel and autosaved automatically.

---

## System requirements

* Windows 10 or Windows 11
* x64 system
* Internet connection for online catalog, accounts and cart synchronization
* .NET runtime may be required depending on the build type

---

## Notes

If Windows shows a security warning when launching the application, this is expected for unsigned student/project builds. Choose **More info** → **Run anyway** only if you downloaded the archive from the official BurmaldaStore release page.

---

## Project status

This release is intended for testing, demonstration and coursework purposes.

Planned improvements:

* Email verification codes
* Password recovery via email
* Android catalog version
* Improved website download page
* More polished final release packaging

---

## Author

Developed by Nikolay Zenov as part of the BurmaldaStore desktop application project.
