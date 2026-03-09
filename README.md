# 🛒 QuickPOS

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?logo=dart)
![Architecture](https://img.shields.io/badge/Architecture-Clean-green)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow)

**QuickPOS** is a fast, offline-first **Mobile Point of Sale (POS) & Billing App** built with **Flutter**.  
It helps retail businesses perform quick billing, manage products, scan barcodes, and print receipts via Bluetooth thermal printers.

---

# ✨ Features

- 📦 **Product Management**
  - Add, edit, delete inventory products
  - Barcode / QR code support

- 📷 **Barcode Scanner**
  - Scan product barcodes instantly using the device camera

- 🛒 **Smart Cart System**
  - Rapid checkout workflow
  - Automatic total calculation

- 🧾 **Receipt Generation**
  - Generate itemized digital receipts

- 🖨 **Bluetooth Thermal Printing**
  - Print receipts directly to POS printers

- ⚙ **Shop Settings**
  - Customize shop name, address, and receipt header

- 📴 **Offline First**
  - Works completely without internet

- ⚡ **High Performance Local Database**
  - Powered by Hive NoSQL storage

---

# 🛠 Tech Stack

| Technology | Usage |
|------------|-------|
| Flutter | Cross-platform mobile framework |
| Dart | Programming language |
| flutter_bloc | State management |
| get_it | Dependency injection |
| go_router | App routing |
| Hive | Local NoSQL database |
| json_serializable | Data serialization |
| equatable | Value comparison |
| fpdart | Functional programming |

### Hardware Integration

- **Barcode Scanner:** `mobile_scanner`
- **Thermal Printer:** `print_bluetooth_thermal`

---

# 📂 Project Structure

```
lib/
│
├── core/                       # Shared utilities and base components
│   ├── data/
│   ├── error/
│   ├── theme/
│   ├── usecase/
│   ├── utils/
│   └── widgets/
│
└── features/                   # Feature-based modules
    ├── billing/
    ├── product/
    ├── settings/
    └── shop/
```

The project follows **Feature-First Clean Architecture** ensuring scalability and separation of concerns.

---

# 🚀 Getting Started

## Prerequisites

- Flutter SDK `>=3.1.0`
- Android Studio / VS Code

---

## Installation

Clone repository

```bash
git clone https://github.com/yourusername/QuickPOS.git
```

Navigate to project

```bash
cd QuickPOS
```

Install dependencies

```bash
flutter pub get
```

Run code generation

```bash
dart run build_runner build --delete-conflicting-outputs
```

Run the app

```bash
flutter run
```

---

# 💡 Use Cases

- Retail shop billing system
- Offline POS for small businesses
- Barcode-based product checkout
- Bluetooth receipt printing

---

# 📱 Screenshots

_Add application screenshots here_

---

# 🤝 Contributing

Contributions are welcome!  
Please follow **Clean Architecture principles** and maintain code quality.

---

# 👨‍💻 Developer

**AH EMON**

---

# 📄 License

This project is licensed under the **MIT License**.