# Installing Musico on your iPhone 🎸

Musico isn't on the App Store, so it's installed with a free tool called **AltStore**. The setup takes about 20 minutes once — after that, the app keeps itself working automatically.

You'll need:

- Your iPhone
- A computer (Windows or Mac) — ideally your own, since it keeps the app refreshed
- Your charging cable
- Your Apple ID email + password

---

## Part 1 — Set up the computer (one time)

**Windows:**
1. Install **iTunes** and **iCloud** from Apple's website — important: the versions from [apple.com](https://support.apple.com/en-us/106372), *not* from the Microsoft Store.
2. Download and install **AltServer** from [altstore.io](https://altstore.io) (choose "AltStore Classic").

**Mac:**
1. Download **AltServer** from [altstore.io](https://altstore.io) and drag it into Applications.

## Part 2 — Put AltStore on the iPhone (one time)

1. Plug the iPhone into the computer with the cable and unlock it. If it asks "Trust This Computer?", tap **Trust**.
2. Start AltServer — it appears as a small diamond icon in the system tray (Windows, bottom-right) or menu bar (Mac, top-right).
3. Click the AltServer icon → **Install AltStore** → choose your iPhone.
4. Enter your Apple ID and password when asked. (This goes to Apple, not to anyone else — AltServer uses it to register the app to *you*.) If you have two-factor, approve it on the phone.
5. A new app called **AltStore** appears on the iPhone. Before it opens, tell the phone to trust it:
   **Settings → General → VPN & Device Management** → tap the profile with your Apple ID → **Trust**.
6. If the phone asks to enable **Developer Mode** (Settings → Privacy & Security → Developer Mode → on, then restart) — say yes, that's expected.

## Part 3 — Install Musico

1. On the **iPhone**, open Safari and go to:
   **[github.com/musico-app/musico_releases/releases/latest](https://github.com/musico-app/musico_releases/releases/latest)**
2. Tap **`musico.ipa`** to download it (tap "Download" if asked).
3. Open the **AltStore** app → **My Apps** tab → tap **＋** in the corner → choose the downloaded `musico.ipa` (it's in Files → Downloads).
4. Wait for the progress bar — Musico appears on your home screen. Done! 🎉
5. Open Musico. The first launch prepares the song library (~11,000 songs) — give it a minute.
6. When jam sessions ask for Bluetooth permission, tap **Allow** — that's how you join sessions with friends.

## Part 4 — Keep it alive (automatic)

Apple limits free apps to 7 days, but AltStore renews Musico by itself. All it needs:

- **AltServer running on the computer** — set it to start automatically (it does by default; look for the diamond icon).
- The iPhone and the computer **on the same Wi-Fi** now and then (once a week is plenty — a home computer that's on in the evenings is perfect).
- Open the AltStore app occasionally; if it shows "7 days" counting down under Musico, tap **Refresh All** while on home Wi-Fi.

---

## If something's wrong

| Problem | Fix |
|---|---|
| "Untrusted Developer" when opening Musico | Settings → General → VPN & Device Management → Trust |
| Musico won't open and it's been over a week | Open AltStore → My Apps → **Refresh All** (same Wi-Fi as the computer, AltServer running). Worst case: redo Part 3 — your songs and playlists are kept. |
| AltServer doesn't see the iPhone | Use the cable, unlock the phone, tap Trust. On Windows, make sure iTunes is the apple.com version. |
| "Maximum number of apps reached" | A free Apple ID allows 3 sideloaded apps — remove one in AltStore. |
| New Musico version came out | Download the new `musico.ipa` and repeat Part 3 — it updates in place. |
