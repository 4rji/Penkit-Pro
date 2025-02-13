# PenKit Pro

**The ultimate tool for pentesting and cybersecurity.**

PenKit Pro is a Flutter-based application that brings together the best penetration testing tools in a sleek, intuitive interface designed for security professionals.

---

## 🚀 Features

- **Main Page**: Instantly search and access tools and resources. Simply type 'AA' to view all available content.
- **Tools Page**: Discover a curated selection of penetration testing tools integrated for seamless use.

---

## ⚙️ Installation

Download the latest version in DMG or AppImage format, or visit our website: [penkitpro.com](https://penkitpro.com)

### Running the Application

Launch the application in your preferred development environment.

### Requirements

- Flutter SDK
- Xcode (for iOS development)
- Android Studio (for Android development)

---

## 🤝 Contributing

Have ideas to enhance PenKit Pro? Contribute by submitting a pull request or opening an issue with your suggestions.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- **Flutter**: For providing a powerful development framework.
- **Open-Source Community**: For their ongoing support and contributions.


# Flutter Setup on Linux

Follow these steps to install Flutter on Linux and package your application using AppImage.

For more details, visit the [Flutter Linux installation guide](https://docs.flutter.dev/get-started/install/linux/web).

---
## DEBIAN - 


## 1. Update System & Install Dependencies

Update and upgrade your system packages:
```bash
sudo apt-get update -y && sudo apt-get upgrade -y
```

Install required dependencies:
```bash
sudo apt-get install -y curl git unzip xz-utils zip libglu1-mesa
```

---

## 2. Download Flutter SDK

Download the Flutter SDK archive:
```bash
wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.29.0-stable.tar.xz -P ~/Downloads/
```

---

## 3. Extract Flutter SDK

Extract the downloaded archive to your development directory:
```bash
tar -xf ~/Downloads/flutter_linux_3.29.0-stable.tar.xz -C ~/development/
```

---

## 4. Update PATH

Add Flutter to your PATH. For Zsh:
```bash
echo 'export PATH="$HOME/development/flutter/bin:$PATH"' >> ~/.zshenv
source ~/.zshenv
```

For Bash, update your `~/.bashrc`:
```bash
echo 'export PATH="$HOME/development/flutter/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

---

## 5. Verify Flutter Installation

Run the following command to check your installation:
```bash
flutter doctor
```

---

## 6. Install OpenJDK 17

Install OpenJDK 17 for Android development:
```bash
sudo apt install -y openjdk-17-jdk
```

---

## 7. Build Your Flutter Application for Linux

Build your application:
```bash
flutter build linux
```

---

## 8. Set Up AppImage Tool

Download the latest AppImageTool:
```bash
wget https://github.com/AppImage/AppImageKit/releases/latest/download/appimagetool-x86_64.AppImage
```

Make it executable:
```bash
chmod +x appimagetool-x86_64.AppImage
```

Move it to your local binaries:
```bash
sudo mv appimagetool-x86_64.AppImage /usr/local/bin/appimagetool
```

---
