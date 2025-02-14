## Atlas fork with my preferences
- Add Copy path by default
- Disable Defender by default
- Disable Drivers update from Windows Update by default
- Disable Notification Suggestions
- Disable Search Indexing by default
- Disable SuperFetch by default
- No internet connection required
- Not change OEM information
- Not change Taskbar alignment
- Not change Taskbar pins previously set
- Not change Windows profile picture
- Not change Windows Start Menu pins previously set
- Not create shortcuts
- Not disable background apps
- Not disable Check Boxes in Explorer
- Not hide any Windows Settings page
- Not install any software
- Office recent files are still enabled
- Set theme to Windows (dark) by default
- Windows Search is not visible in Taskbar
- Windows Search with search history is still enabled

## Tips
If you want to use Atlas on an unsupported build (refer to the [Atlas documentation](https://docs.atlasos.net/install-faq/windows-version-support/)), you can manually add a line in `playbook.conf` with your preferred build. Keep in mind that this is just a workaround to bypass the restriction, it does not ensure that Atlas will function properly.
```
	<SupportedBuilds>
		<!-- 22H2 -->
		<string>19045</string>
		<string>19044</string>
		<!-- 24H2 -->
		<string>26100</string>
		<string>22631</string>
	</SupportedBuilds>
```

---

<h1 align="center">
  <a href="http://atlasos.net" target="_blank"><img src="https://gcore.jsdelivr.net/gh/Atlas-OS/branding@main/banners/banner-v3.png" alt="Atlas" width="800"></a>
</h1>
  <p align="center">
    <a href="https://github.com/Atlas-OS/Atlas/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/atlas-os/atlas?style=for-the-badge&logo=github&color=1A91FF"/></a>
    <a href="https://github.com/Atlas-OS/Atlas/graphs/contributors"><img alt="Contributors" src="https://img.shields.io/github/contributors/atlas-os/atlas?style=for-the-badge&color=1A91FF" /></a>
    <a href="https://github.com/Atlas-OS/Atlas/releases/latest"><img alt="Release" src="https://img.shields.io/github/release/atlas-os/atlas?style=for-the-badge&color=1A91FF" /></a>
    <a href="https://github.com/Atlas-OS/.github/blob/main/profile/CODE_OF_CONDUCT.md"><img alt="Code of Conduct" src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=for-the-badge&color=1A91FF" /></a>
  </p>
<p align="center">A transparent and lightweight modification to Windows, designed to optimize performance, privacy and usability.</p>

<p align="center">
  <a href="https://atlasos.net" target="_blank">🌐 Website</a>
  •
  <a href="https://docs.atlasos.net" target="_blank">📚 Documentation</a>
  •
  <a href="https://discord.atlasos.net" target="_blank">☎️ Discord</a>
  •
  <a href="https://github.com/Atlas-OS/Atlas/discussions" target="_blank">💬 Discussions</a>
</p>

## 📚 **Important Documentation**
- [Installation](https://docs.atlasos.net/getting-started/installation/)
- [FAQ & Common Issues](https://docs.atlasos.net/faq-and-troubleshooting/removed-features/)
- [Contribution Guidelines](https://docs.atlasos.net/contributions/)
- [Branding](https://docs.atlasos.net/branding/)

## 🤔 What is Atlas?

AtlasOS, or Atlas, is an open-source project that enhances Windows by conveniently applying privacy, usability, and performance optimizations, all while maintaining functionality and [customizability](https://docs.atlasos.net/getting-started/post-installation/atlas-folder/general-configuration/).

## 👀 Why Atlas?
### 🔒 Enhanced Privacy
Atlas removes the majority of telemetry embedded within Windows and implements numerous group policies to minimize data collection. However, it cannot ensure privacy outside the scope of Windows, such as browsers and other third-party applications.

### 📈 Optimized Performance
Atlas strikes a balance between performance and compatibility. It implements numerous meaningful changes to improve Windows performance and responsiveness without breaking essential features. Atlas will not do tweaks for a placebo effect or marginal gains, making Atlas more stable and compatible.

### 🛡️ Security Features
Most Windows modifications remove key security features most users need to maintain a secure system. On the other hand, Atlas allows users to customize their security at their own risk while informing users about each option's [pros and cons](https://docs.atlasos.net/getting-started/post-installation/atlas-folder/security/).

Some optional security features are:

- Windows Defender & SmartScreen
- Windows Update
  - Automatic updates are togglable
- CPU mitigations
- User Account Control
- Core isolation features

### ✅ Increased Usability
Atlas applies many modifications and default settings to make Windows easier to use. This includes removing commonly unneeded applications (which are reinstallable), configuring many aspects of the interface, disabling advertisements, and much more.

### 🔍 Open Source and Transparent

Unlike custom Windows ISOs, Atlas is more straightforward to audit due to the use of [AME Wizard](https://ameliorated.io). AME Wizard is controlled by Playbooks, a customizable script-esque system that can perform various tasks.

Playbooks are renamed **.zip** archives, with the password [`malte`](https://docs.ameliorated.io/developers/getting-started/creation.html). As they primarily consist of plain text, Playbooks enable transparency, unlike custom Windows ISOs, which have many entry points for malicious activity. The few binaries in the Playbook are open source in our [`utilities` repository](https://github.com/Atlas-OS/utilities), with the [hashes listed here](https://github.com/Atlas-OS/Atlas/blob/main/src/playbook/Executables/AtlasModules/README.md).

Although the GUI is not open source for AME Wizard, AME Wizard's entire backend (called [TrustedUninstaller](https://github.com/Ameliorated-LLC/trusted-uninstaller-cli)) is open source under MIT, which contains each action used to run Atlas. The Atlas Playbook is open source under the [GPLv3 license](https://github.com/Atlas-OS/Atlas/blob/main/LICENSE).

### 🔒 Legal Compliance
As Atlas doesn't redistribute a modified Windows ISO, it complies with [Windows's Usage Terms](https://www.microsoft.com/en-us/useterms/#areaheading-uid6738235). In addition, Atlas does not alter activation in Windows.

## 🎨 Brand kit
Want to create your own Atlas wallpaper with some original creative designs? Visit our [Branding Kit on Docs](https://docs.atlasos.net/branding/) and share your creations on our [GitHub Discussions](https://github.com/Atlas-OS/Atlas/discussions/categories/community-artwork)!

## 💙 Contributors
<a href="https://github.com/Atlas-OS/Atlas/graphs/contributors" target="_blank"><img src="https://contrib.rocks/image?repo=Atlas-OS/Atlas&columns=18" alt="Avatars of all contributors"></a>
