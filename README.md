# MikroWizard — MikroTik System Controller

> A focused Windows controller for MikroTik RouterOS. Built for hotspot operators, WISPs, and network administrators who need fast, direct control over devices, accounts, profiles, active sessions, vouchers, and live traffic.

---

## 📌 Overview

**MikroWizard** is a lightweight, high-performance desktop controller designed to streamline network and hotspot administration on MikroTik hardware. It provides direct, atomic control over RouterOS devices, making bulk user management, voucher generation, and real-time monitoring seamless and efficient.

- **Version:** `0.6.0`
- **Platform:** Windows 11
- **Compatibility:** RouterOS v6 / v7
- **Protocol:** Native API
- **Developer:** splojagnes ([jaysonagnes@outlook.com](mailto:jaysonagnes@outlook.com))

---

## ✨ Features & Capabilities

### ⚡ Operations
* **Live Device Dashboard:** Monitor real-time system status and per-port throughput.
* **Hotspot Management:** Manage hotspot accounts, profiles, and active sessions with ease.
* **Bulk Processing:** Rapid account generation and archive-free deletion for large networks.
* **Printable Vouchers:** Generate clean, print-ready A4 voucher sheets with cut-out guidelines.
* **Session Details:** View per-session traffic rates and detailed connection metrics.

### 🛠️ Engineering & Security
* **Native Protocol:** Uses direct RouterOS API (`8728`) and API-SSL (`8729`).
* **RouterOS Support:** Fully compatible with both RouterOS v6 and v7.
* **Optimized Updates:** Incremental live updates without requiring full-table reloads.
* **Local Storage:** Built-in local SQLite state management and audit logging.
* **Data Protection:** Optional DPAPI-encrypted saved passwords for enterprise-grade security.

---

## ⚖️ Free vs. Pro Edition

MikroWizard comes with a fully functional **Free Edition** intended for small setups and read-only monitoring. Upgrading to the **Pro Edition** removes all operational limits and unlocks full administrative controls.

| Feature | Free Edition | Pro Edition |
| :--- | :---: | :---: |
| **Devices Allowed** | 1 Device | **Unlimited** |
| **Bulk User Generation (per job)** | 25 Users | **Unlimited** |
| **PDF Vouchers / Export Limit** | 25 Vouchers | **Unlimited** |
| **Profile & Account Admin** | — *(Read-Only)* | **Full Access** |
| **Active Session Control** | — *(Read-Only)* | **Full Access** |
| **Dashboard & Live Traffic** | View Only | **View Only** |
| **Voucher PDF Branding** | Yes | **Yes** |

> **Note:** The Free edition is intentionally read-only for administrative actions. Pro unlocks profile editing, account deletion, active-session controls, and unlimited bulk workflows.

---

## 🔑 Licensing & Activation

The **Pro Edition** uses a machine-bound activation system with a **perpetual license** (one-time purchase).

* **Activation Format:** `MW-XXXX-XXXX-XXXX-XXXX`
* **License Type:** Perpetual (Lifetime access for the activated machine)

For inquiries regarding Pro Edition license purchases or support, please reach out to **[jaysonagnes@outlook.com](mailto:jaysonagnes@outlook.com)**.

---

## 📄 Legal & Disclaimer

Please read carefully before deploying this software in a production environment:

1. **Warranty Disclaimer:** MikroWizard is provided *"as is"*, without warranty of any kind, express or implied. The developer is not liable for router misconfiguration, loss of data, loss of service, security incidents, revenue loss, or any direct or indirect damage resulting from the use of this software.
2. **User Responsibility:** You are solely responsible for maintaining network configuration backups and for using MikroWizard only on devices you own or are explicitly authorized to manage. **Deletions performed by the software are permanent.**
3. **Trademark Notice:** MikroTik® and RouterOS® are registered trademarks of MikroTik SIA. MikroWizard is an independent third-party tool and is not affiliated with, authorized, or endorsed by MikroTik SIA.

---

© 2026 **splojagnes**. All rights reserved.  
*Developed by splojagnes · [jaysonagnes@outlook.com](mailto:jaysonagnes@outlook.com)*
