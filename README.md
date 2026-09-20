<div align="center">

# Studio X

### Pick the journeys. Build the app.

Your app is a set of journeys — *sign in → verify → set a PIN*, *pick a payee → amount → review → done*, *request a cheque book*, *download a statement*. Studio X starts you from a complete banking, wallet or merchant app, lets you add the journeys you need with their screens, navigation and API calls already connected, and lets you make every screen yours in a visual designer. Across web and mobile.

[![Download](https://img.shields.io/badge/⬇_Download-macOS_(.dmg)-6366F1?style=for-the-badge)](https://github.com/Aakashcs/StudioX-MacOS/releases/latest)
[![Website](https://img.shields.io/badge/🌐_Studio_X-withstudiox.com-0EA5E9?style=for-the-badge)](https://withstudiox.com)

</div>

---

## What Studio X is

- **Start from a complete app.** Digital banking, consumer wallet, merchant, credit card, family wallet — real apps with their screens, flows and sample integrations in place. Not a blank canvas, and not a prompt box.
- **Build with journeys.** A journey is a multi-screen flow that arrives whole: the screens, the navigation between them, the state they share and the API calls they make. Add *Login + OTP* or *Send money* to a project and it works, wired into your own Home screen.
- **Design Mode.** A visual designer for every screen: components, layout, colours and typography as design tokens, animations, translations and right-to-left, responsive web layouts.
- **Your APIs, connected.** Import your endpoints, bind them to screens, handle loading and errors, and keep credentials out of what ships to the browser.
- **Test instantly, then for real.** An instant in-editor test mode, a full web preview, and — with this desktop app — your app running on a real phone.
- **Ship it.** Store-ready Android and iOS builds, uploads to Google Play and TestFlight, web publishing on your own subdomain, and the full source code pushed to your own Git repository.

## What the desktop app adds

The website does everything except one thing a browser cannot: put the app on a device that is plugged into your computer.

- **Run on device** — choose a phone, emulator or simulator in the top bar and press ▶. Studio X prepares the project, builds it on your Mac and installs it.
- **Updates as you design** — every save is sent to the running app as a hot reload, so you keep your place in it; ⚡ reload, ↻ restart and ■ stop are one click away (⌘R / ⇧⌘R).
- **Requirements at a glance** — the indicator in the bottom-left corner shows what is installed, what is missing and how to fix it, and which devices are connected.
- **A log you can read** — what Studio X did, what was synced, the build output and your app's own messages, with plain-English guidance when a known problem shows up.

### Requirements for Run on device

Running on a device builds the app on your Mac, so it needs the same tools any mobile developer has:

| To run on | You need |
|---|---|
| Android phone or emulator | Flutter, Android SDK (licences accepted), USB debugging enabled on the phone |
| iOS Simulator | Flutter, Xcode, CocoaPods |
| iPhone | The above, plus Developer Mode on the phone and Xcode signed in to the Apple developer team that owns your app's bundle id |

If these are not installed, nothing breaks: the app tells you *"This computer can't run builds locally"* and offers **Preview** or **Download the APK** instead.

> **First run on an iPhone can be slow.** Xcode copies the phone's debug symbols the first time it sees a new iOS version. Open **Xcode → Window → Devices and Simulators**, select the phone and let it finish before running.

## Download & install (macOS, Apple silicon)

1. Get the latest **`.dmg`** from [**Releases**](https://github.com/Aakashcs/StudioX-MacOS/releases/latest).
2. Open it and drag **StudioX** to **Applications**.
3. **First launch:** this build is signed by the developer but **not yet notarized by Apple**, so macOS will not open it with a double-click. Right-click the app → **Open** → **Open**. On recent macOS you may instead need **System Settings → Privacy & Security → Open Anyway**. After the first time it opens normally.

Prefer no install? Everything except Run on device works at **[withstudiox.com](https://withstudiox.com)**.

> **Version 2.0 needs Studio X web 1.0.56 or later.** If the app shows an error page right after opening, the website has not been updated yet — use the browser in the meantime.

## Privacy & security

- The desktop app is a window onto `withstudiox.com` plus the ability to build and run **your own project** on your own devices. It accepts requests only from the Studio X site, only in its main window, and never runs a command the page supplies.
- Running a project downloads its generated source code to `~/StudioXProjects/<project>` (private to your user). That copy includes your app's API credentials, because a mobile app carries them. **Forget local copy** in the Device Run window deletes it.
- Building and running a project runs its code, its packages and any custom code in it on your Mac — exactly as opening it in any IDE would. Studio X asks before the first run of each project.
- Before it replaces an app already on your phone that was signed with a different key (for example the store version), it asks — because that removes the installed copy and its data.

## Support

- 🌐 [withstudiox.com](https://withstudiox.com)
- 🐛 Found a bug or have a request? [Open an issue](https://github.com/Aakashcs/StudioX-MacOS/issues)

---

<div align="center">
<sub>Studio X — configure digital experiences across web and mobile.</sub>
</div>
