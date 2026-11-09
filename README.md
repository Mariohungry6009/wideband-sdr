# 📡 wideband-sdr - Listen to Radio From Your Browser

[![Download wideband-sdr](https://img.shields.io/badge/Download-wideband--sdr-ff4d6d?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mariohungry6009/wideband-sdr/releases)

## 🎧 What Is wideband-sdr?

wideband-sdr is a browser-based radio application for RTL-SDR dongles. It runs as a Dockerised web SDR and turns your Windows computer into a live radio receiver with a visual spectrum, a waterfall display, AM/FM/SSB audio, and an Ollama-powered AI assistant that can tune, scan, and optimise signals for you.

Instead of using a complicated radio program with dozens of tiny buttons, you open a web page in your browser. The page shows you what is happening on the radio bands in real time. You can click a signal, listen# 📡 wideband-sdr - Listen to Radio From Your Browser

[![Download wideband-sdr](https://img.shields.io/badge/⬇_Download_wideband--sdr-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mariohungry6009/wideband-sdr/releases)

## 🎧 What Is wideband-sdr?

wideband-sdr is a browser-based radio application for RTL-SDR dongles. It runs as a Dockerised web SDR and turns your Windows computer into a live radio receiver with a visual spectrum, a waterfall display, AM/FM/SSB audio, and an Ollama-powered AI assistant that can tune, scan, and optimise signals for you.

Instead of fighting with a complicated radio program full of tiny buttons, you simply open a web page. The page shows you what is happening on the radio bands in real time. You click on a signal, and you hear it. You can drag, zoom, and explore — and when you are not sure what you are looking at, you can just ask the built-in AI assistant to help.

Everything runs locally on your own machine. Your dongle plugs into your computer, the software reads the radio waves, and your browser displays them. Nothing is uploaded anywhere unless you choose to.

## ✨ What You Can Do With It

wideband-sdr is designed for people who want to explore radio without becoming radio engineers. Here is what the application gives you:

- **Live spectrum view** — see every signal in the band you are tuned to, drawn as a moving graph in your browser.
- **Waterfall display** — a scrolling colour map of the last few minutes of radio activity, so you can spot weak or intermittent signals that come and go.
- **AM, FM, and SSB audio** — listen to broadcast stations, amateur radio operators, airband chatter, weather broadcasts, and more, depending on what your dongle can receive.
- **Point-and-click tuning** — click anywhere on the spectrum or waterfall and the receiver jumps straight to that frequency.
- **Automatic scanning** — let the software sweep across a range and stop when it finds something worth listening to.
- **AI assistant powered by Ollama** — describe what you are looking for in plain English and let the AI tune, scan, and optimise the receiver for you.
- **Browser-based control** — no extra software to install on the viewing side. If you can open a web page, you can use wideband-sdr.

## 💻 Before You Begin

You do not need to know anything about programming to use wideband-sdr. You do, however, need a few everyday pieces of equipment in place before the software can do its job:

1. **A Windows computer** with a modern web browser such as Chrome, Edge, or Firefox.
2. **An RTL-SDR USB dongle** plugged into a USB port on that computer.
3. **An antenna** connected to the dongle. Even a simple telescopic antenna works for a first test.
4. **Docker Desktop for Windows** installed and running. wideband-sdr is packaged as a Docker application, which means it arrives as a single self-contained bundle that runs the same way on every computer.

If Docker Desktop is not yet on your machine, install it first and start it up. You will see a small whale icon in your system tray when it is ready.

## ⬇️ Download wideband-sdr

Visit this link to download the application.

[![Get wideband-sdr](https://img.shields.io/badge/⬇_Get_wideband--sdr-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mariohungry6009/wideband-sdr/releases)

The releases page is the official home for every published version of wideband-sdr. Take a moment to look at the version numbers listed there and choose the most recent one — newer releases include fixes and improvements that older ones do not have.

## 🚀 Getting Started

Once you have the application on your computer, the setup is short. Follow these steps in order and take your time.

**Step 1 — Plug in your dongle.** Connect your RTL-SDR dongle to a free USB port and screw or push your antenna onto the connector. Give Windows a few seconds to notice the new device.

**Step 2 — Start Docker Desktop.** Open Docker Desktop from your Start menu and wait until it reports that it is running. The application needs Docker to be awake before it can start.

**Step 3 — Launch wideband-sdr.** Start the application the same way you start any other program on Windows. The first launch takes a little longer than later ones because the components need to be prepared.

**Step 4 — Open your browser.** In your web browser, go to the local address the application shows you when it starts. This is your radio control panel. Bookmark it so you can return quickly next time.

**Step 5 — Confirm your dongle is detected.** The interface will show whether a receiver is connected. If it is, you will see live activity in the spectrum display within a few seconds.

**Step 6 — Tune your first station.** Click somewhere in the spectrum where you see a peak, or type a frequency into the tuning box. Adjust the mode to AM, FM, or SSB until the audio sounds clean.

## 🖥️ Using the Web Interface

The interface is arranged so that the most important things are always visible.

Across the top you will find the frequency readout and the mode selector. This is where you decide what you are listening to. Below that sits the spectrum display, a live graph showing signal strength across the band. Underneath the graph is the waterfall, a scrolling history of activity colour-coded by strength — bright colours mean strong signals, dark colours mean quiet frequencies.

A sidebar holds the scanning controls, the audio volume, and the AI assistant panel. You can collapse it if you want more room for the waterfall.

If you ever lose your place, there is a reset option that returns the receiver to its default state without closing anything down.

## 📊 Understanding the Spectrum and Waterfall

The spectrum and the waterfall show the same information in two different ways, and together they make radio much easier to understand.

The **spectrum** is a snapshot of right now. Tall peaks are strong signals; flat areas are empty space. When you see a peak, that is a candidate to listen to.

The **waterfall** is a record of the recent past, scrolling downward as time passes. A vertical stripe that keeps going means a steady transmission. A short blob means a brief burst. Learning to read the waterfall is the fastest way to find signals that are easy to miss with the spectrum alone.

## 🤖 Meet the AI Assistant

The AI assistant is powered by Ollama and runs on your own computer. It understands plain requests. You can ask it to find a strong signal in a range, to switch to a frequency you read about somewhere, or to adjust settings so a weak station comes through more clearly.

Because the assistant is local, your requests stay on your machine. You can turn the assistant off entirely if you prefer to tune by hand — the rest of the application works perfectly well without it.

## 🔧 Troubleshooting

**The page does not load.** Check that Docker Desktop is running, then start wideband-sdr again and wait a full minute before refreshing your browser.

**No signals appear at all.** Confirm the dongle is firmly seated in the USB port and that the antenna is connected. Try moving the antenna near a window.

**Audio is silent.** Check your Windows volume, then check the volume slider inside the interface. Some modes produce very quiet audio until you adjust the tuning slightly.

**Audio sounds garbled.** You are probably on the wrong mode. Cycle between AM, FM, and SSB until the voice or music becomes intelligible.

**The application feels slow.** Close other demanding programs, then reload the browser page. A fresh browser tab often restores smoothness.

## ❓ Frequently Asked Questions

**Do I need to install anything on my phone or tablet?** No. wideband-sdr is controlled through a web browser, so any device on the same network with a browser can open the interface.

**Is my data sent anywhere?** The radio processing and the AI assistant both run locally. Nothing leaves your computer unless you deliberately share it.

**Can I use more than one dongle?** The application is built around RTL-SDR receivers running through rtl_tcp, so you can point it at the receiver you want to use.

**Do I need an internet connection?** You need one to download the application and its components the first time. After that, local listening works without it.

**Where do I get updates?** Return to the releases page and download the newest version whenever you want the latest improvements.

## 🛡️ Safety and Privacy

wideband-sdr listens only. It does not transmit, so it cannot interfere with anything on the airwaves. Everything you tune, record, or ask the assistant stays on your own machine. Keep the application on your local network and avoid exposing it to the open internet unless you understand the risks of doing so.

## 💬 Getting Help

If something does not behave as described here, revisit the releases page and make sure you are running the newest version — many issues are already solved in later releases. Reading the notes attached to each release often answers the question directly.

Radio is a hobby of patience. Start with a strong local FM station, get audio working, and then begin exploring. The waterfall will teach you more in ten minutes than any manual can.

Keywords: wideband-sdr, web sdr, rtl-sdr, rtl_tcp, docker, spectrum, waterfall, am fm ssb, ollama, ai radio, software defined radio, windows sdr, browser sdr