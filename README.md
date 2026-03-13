# Mauritius (MBC) TV & Radio Channels Playlists

---

### List of Channels Included

## 📺 TV Playlist

| MBC 1 | MBC 2 | MBC 3 | MBC 4 | MBC 5 | MBC SAT | MBC 17 |
|------|------|------|------|------|------|------|

### 📥 [Download TV Playlist](https://raw.githubusercontent.com/tangymc/mbcchannels/main/playlists/tvchannels.m3u)
(Copy link or Save As)

## 📻 Radio Playlist

| Best FM | Kool FM | NRJ Mauritius | Radio Maurice | Radio Mauritius | Rodrigues FM | Taal FM |
|--------|--------|--------------|--------------|---------------|--------------|--------|

### 📥 [Download Radio Playlist](https://raw.githubusercontent.com/tangymc/mbcchannels/main/playlists/radiochannels.m3u)
(Copy link or Save As)

---

### ❗ IMPORTANT
The channels can **only be streamed within Mauritius**
Outside Mauritius, you may try using a **Mauritian VPN or proxy**.
This is due to MBC **geo-restricting** these channels to **Mauritius only**.

Some channels (such as **ZOOM** or others not included in **MBC Play**) **cannot** be added.  
However, **TV5Monde/TIVI5 is available on MBC 17**, so it is included.

Some of these channels may appear in unofficial IPTV playlists found online.  
I **do not promote piracy**. Use any third-party playlist at your own risk.

### 📺 How can I stream the playlists?
You can use any IPTV player listed here:  
https://github.com/iptv-org/awesome-iptv#apps

### 🔍 How did you find the streaming links?

I used **HttpCanary** on an Android device to sniff the traffic from the **MBC Play app**.

Older MBC Play versions had stream URLs directly inside the app code, but newer versions removed them.  
To extract them, I:

- Installed HttpCanary with its certificate (requires root)
- Bypassed SafetyNet using Magisk + modules
- Hid root from the MBC Play app
- Sniffed encrypted packets while playing each channel

This allowed me to retrieve all the stream URLs.

### 📅 Can you integrate TV Guide (EPG)?

Not yet — no EPG link has been found.  
If MBC publishes one or if it appears in the app, it may be added in the future.

