## 📡 From Global Playlist to Personalized Streaming — Introducing [M3USe](https://m3use.projectmoose.xyz)

Hey folks — if you've used or followed this repo in the past, you might remember it started as an automated GitHub Actions workflow that created a public M3U playlist of livestreams. You could request channels, and I'd manually add them to the playlist for everyone.

But things have evolved.

### 🎉 Meet [M3USe](https://m3use.projectmoose.xyz) — A Web App for Custom Livestream Playlists

✅ Add livestreams from **YouTube**, **Twitch**, and **Dailymotion**  
✅ Build your **own playlist** — no more global list  
✅ Use with **any IPTV player** (VLC, Kodi, TiviMate, etc.)  
✅ Your playlist, your links, your rules

💡 No more waiting for manual updates or one-size-fits-all playlists. You just paste the channel URL, and the backend takes care of the rest.

---

> This is an indie passion project powered by the [Project Moose Discord](https://discord.gg/dmgYmAEdee) — and it’s live now.  
> 🚀 Try it out: [https://m3use.projectmoose.xyz](https://m3use.projectmoose.xyz)

Got ideas, feedback, or requests? Drop by the Discord or open a discussion here!

---

[![Live App](https://img.shields.io/badge/Live%20App-M3USe-green?style=flat-square)](https://m3use.projectmoose.xyz)


--------------------------- END (old content below) ---------------------------

<h1 align="center"> Dailymotion_to_m3u </h1>

[![M3U generator for Dailymotion](https://github.com/benmoose39/dailymotion_to_m3u/actions/workflows/grabber.yml/badge.svg)](https://github.com/benmoose39/dailymotion_to_m3u/actions/workflows/grabber.yml)

`https://raw.githubusercontent.com/benmoose39/dailymotion_to_m3u/main/dailymotion-{PREFERRED SERVER}.m3u`
m3u links of Dailymotion live channels, auto-updated everyday.

### Usage
Paste one of the following URL based on your location, to avoid buffering: 

`https://raw.githubusercontent.com/benmoose39/dailymotion_to_m3u/main/dailymotion-US.m3u`

`https://raw.githubusercontent.com/benmoose39/dailymotion_to_m3u/main/dailymotion-EU.m3u`

`https://raw.githubusercontent.com/benmoose39/dailymotion_to_m3u/main/dailymotion-SG.m3u`

### Run the tool on your local machine
``` bash
git clone https://github.com/benmoose39/dailymotion_to_m3u.git
cd dailymotion_to_m3u
chmod +x autorun.sh
./autorun.sh
```

### Use proxy to grab m3u
`python3 dailymotion_m3ugrabber.py <proxy_server_ip:port>`

eg: `python3 dailymotion_m3ugrabber.py 192.168.13.13:1337`

### Add more channels
Connect on discord and request new channels or create a pull request

If running locally, edit `dailymotion_channel_info.txt` to add more dailymotion channels.

Connect: https://discord.gg/dmgYmAEdee


### Support

🙂 https://www.buymeacoffee.com/benmoose39
