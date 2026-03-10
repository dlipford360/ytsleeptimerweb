# YT SleepTimerWeb

A web frontend that plays YouTube from a URL, with a built-in sleep timer and screen dimming.

**Try it:** [https://ytsleeptimer.com/](https://ytsleeptimer.com/)

## Why This Exists

YouTube's own sleep timer is not always available. For example:

- **Web on mobile** — The sleep timer may be missing or unreliable when using YouTube in a mobile browser
- **Brave on mobile** — Brave browser on mobile often lacks access to YouTube's native sleep timer
- **Other browsers & platforms** — Various combinations of browser, device, and YouTube interface can omit or restrict the sleep timer feature

This webapp fills that gap by providing a consistent sleep timer experience across devices and browsers.

## Features

- Play YouTube from a URL or video ID
- Sleep timer with preset buttons (10, 30, 60 minutes) or custom duration
- Screen dims when the timer ends; tap or move the mouse to undim
- URL-based video selection: add `?v=VIDEO_ID` or `/watch?v=VIDEO_ID` to load a video directly

## How to Run

1. **Install dependencies** (optional — uses `npx`):

   ```bash
   npm install
   ```

2. **Start the server**:

   ```bash
   npm start
   ```

   Or with npx directly:

   ```bash
   npx serve . -l 3000 -s
   ```

3. **Open in your browser**:

   ```
   http://localhost:3000
   ```

4. **Optional — load a video via URL**:

   ```
   http://localhost:3000/?v=VIDEO_ID
   http://localhost:3000/watch?v=VIDEO_ID
   ```

## Usage

1. Paste a YouTube URL (or video ID) into the input and click **Play**
2. Set a sleep timer using the preset buttons or a custom duration
3. When the timer ends, playback stops and the screen dims
4. Click or move the mouse to restore the screen

---

Yes, this was vibecoded.
