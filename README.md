<h1 align="center">Auto Vibes</h1>

<p align="center"><b>A Chrome extension that turns Vibes AI (vibes.ai) into a batch image and video studio - paste prompts, press Start, and every result is saved to your computer.</b></p>

<p align="center">
  <b>English</b> ·
  <a href="README_vi.md">Tiếng Việt</a>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/auto-meta-automation-for/bchhcfjoloinebjpbfklckgohpjehdmf"><img alt="Get it on the Chrome Web Store" src="https://img.shields.io/badge/Chrome%20Web%20Store-Add%20to%20Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
</p>

> **Formerly "Auto Meta - Automation for Meta AI".** Auto Vibes is the new name and version of the same extension, under the same Chrome Web Store listing. It now works on **vibes.ai** (no longer on meta.ai/media).

---

## Install

### Step 1 - Add it from the Chrome Web Store

Open the **[Chrome Web Store page](https://chromewebstore.google.com/detail/auto-meta-automation-for/bchhcfjoloinebjpbfklckgohpjehdmf)** in Google Chrome and click **Add to Chrome**. Chrome keeps it up to date automatically. The full name shown in the store and on `chrome://extensions` is **Auto Vibes x G-Labs Automation**.

### Step 2 - Sign in &amp; pick a plan

You need two accounts:

- **A Vibes AI account** (Facebook / Instagram) signed in on **vibes.ai** in the same browser - images and videos are made by *your own* Vibes account, within its limits.
- **A Google account** - click **Sign in with Google** in the control panel so the extension can load your licence plan. Nothing can start until you are signed in.

The free **Basic** plan **cannot run generation** on Vibes AI - you need **Lite** or higher. Plans pay for the automation tool only; they do **not** mean unlimited generation. Plans never auto-renew.

| Plan | 1 month | 6 months | 1 year | What you get |
|---|---|---|---|---|
| **Lite** | $3 | $15 | $30 | Image &amp; video generation on Vibes AI · 10 threads · unlimited prompts · 10 tasks in the queue · 4 images / 4 videos per prompt · every reference mode · auto retry · extension only |
| **Plus** | $5 | $25 | $50 | Everything in Lite + the G-Labs Studio desktop app (Plus) |
| **Max** | $10 | $50 | $100 | Everything in Plus · unlimited queue, up to 1000 threads · G-Labs Studio Max incl. the Webhook API server |

6 months cost the same as 5, a year the same as 10. Buy inside the extension: click the **plan badge** in the top bar → **Upgrade**, then pay by **PayPal**, **USDT / Binance**, or **VietQR** bank transfer (Vietnamese banks only). After paying, wait 1-3 minutes and click **Refresh status**. Upgrading Plus → Max mid-term only charges the difference for the days left.

Already on **G-Labs Studio Plus / Max**? Sign in with the same Google account - those plans cover both the desktop app and this extension. A licence runs on one device at a time: signing in elsewhere signs this session out.

---

## First run

1. **Open [vibes.ai](https://vibes.ai)** in Chrome and sign in to your Vibes AI account.
2. **Open the control panel** - click the **Auto Vibes** icon on the toolbar, or the glowing floating button at the bottom-right of the vibes.ai page (you can drag it anywhere). The panel opens in its own window.
3. **Sign in with Google** in the top bar. The **Vibes account** box should read *Signed in*; if it doesn't, click it to open or re-check the vibes.ai tab.
4. **Pick a page** - **Vibes Image** or **Vibes Video**.
5. **Paste prompts** (or **Import TXT**), choosing **1 line / prompt** or **Split on blank line** for multi-line prompts. Set the model, aspect ratio, count, resolution (video), threads and delay.
6. Press **START**. Each prompt becomes a row in the table, and the results are saved to your Downloads folder as they finish.

---

## Features

- **Two generators, one queue** - Vibes Image (text → image, image → image) and Vibes Video (text → video, image → video), up to 4 results per prompt.
- **References by role** - images get **Character / Scene / Style** slots; videos use **Start / End frames** or **3 component images**.
- **Automatic distribution** - load many images and spread them across rows: *Start only*, *1 Start - N End*, *N Start - 1 End*, *Chain (1:2→2:3)*, *Pairs (1:2→3:4)*.
- **Reference library that matches prompts** - a shared library assigns images to rows **by keyword** or **exact** name; names like `anna_char`, `beach_scene`, `shot1_start` go straight into the right slot.
- **Multi-task queue** - name tasks, give each its own settings, then pause, resume, reset or skip a whole task from the **Queue manager**.
- **Every prompt is a row** - edit, reorder, rerun or delete rows; **Retry failed** or **Run selected**; filter by status. From Lite up, temporary errors are retried automatically.
- **Never lose your work** - the engine runs inside the vibes.ai tab, so a batch keeps going when you close the control panel; prompts, queue and results are restored when you reopen it.
- **Auto-save per task** - save directly or one subfolder per task, with file-name presets; click a result to open the file.
- **11 interface languages**, including English and Vietnamese.

---

## Pages

### 🖼 Vibes Image

Batch text → image and image → image. Choose the model, aspect ratio, images per prompt (1-4), threads and the delay between threads. Each row can carry **Character / Scene / Style** reference images - add them per row, from the library, or with **Load &amp; distribute**. Reference images over 3.8 MB are shrunk automatically before upload.

### 🎬 Vibes Video

Batch text → video and image → video at **480p or 720p**, up to 4 videos per prompt. Pick the reference mode: **Start / End frame** (with the distribution modes above) or **3 component images**. A `_480p` / `_720p` suffix is always added to the file name.

### 📋 Queue manager

Click **Add to queue** to save the current prompts + settings as a named task. The Queue manager lists each task's name, config, prompt count, save path and status, and lets you edit, reset (clears that task's results and reruns it), skip or delete tasks. Lite and Plus hold up to 10 tasks; Max is unlimited.

### 🗂 Reference images

A library of reference images shared by both pages. Add images, check whether their names are good for matching, then either **Add to selected rows** or turn on **Auto-assign images to rows from the prompt** (by keyword: the first 3+ letters of a word match; exact: the full name must appear in the prompt).

### ⚙ Settings

**File Naming** presets - *Default* `{row}_{prompt}_{slot}`, *Timestamped*, *Numbered Only*, *Prefix + Counter*, *Date + Prompt* or *Custom* - with prefix, row padding, separator, max prompt length and a live preview. The interface language is picked from the top bar.

---

## Permissions &amp; privacy

| Permission | Why |
|---|---|
| `storage`, `unlimitedStorage` | Keep your prompts, queue, reference library (stored as images), settings and session in the browser; the extra quota stops the library from being silently lost. |
| `alarms` | A light timer that keeps the batch engine running while the panel is in the background. |
| `downloads`, `downloads.open` | Save results to your Downloads folder and open them from the results table. |
| `identity`, `identity.email` | Google sign-in and reading your account email to identify your licence plan. |
| `https://vibes.ai/*` | Runs the generation on your own vibes.ai session. |
| `https://glab.duckmartians.info/*` | The licence server - only checks your plan and its limits. |
| `https://www.googleapis.com/*` | Reads your Google account email once after sign-in. |

Prompts, images, videos, queue, library and settings **stay in your browser**; generation goes straight from your own vibes.ai session. The licence server only receives your Google email, a sign-in token (used transiently) and a random install ID. No remote code is loaded.

---

## Where your data lives

| What | Where |
|---|---|
| Generated images | `Downloads/AutoVibes/Image` by default (directly, or one subfolder per task) |
| Generated videos | `Downloads/AutoVibes/Video` by default (directly, or one subfolder per task) |
| Prompts, queue, library, settings, session | The extension's local storage in Chrome (`chrome.storage.local`) |

When a plan ends, the extension returns to Basic; your data in the browser stays as it is.

---

## Troubleshooting

**"Not signed in on the vibes.ai tab"** - sign in to Vibes AI on the vibes.ai tab; the extension picks it up automatically. Click the **Vibes account** box to re-check.

**"Could not reach the vibes.ai tab"** - reload (F5) the vibes.ai tab and press Start again. Don't close the vibes.ai tab while a batch is running.

**Start does nothing / "upgrade" prompt** - the Basic plan can't generate on Vibes AI. Check the plan badge in the top bar; after paying, click **Refresh status**.

**Signed out with "CONFLICT DETECTED"** - your licence was signed in on another device. Sign in again to continue here.

**Chrome asks where to save every file** - go to `chrome://settings/downloads` and turn off **Ask where to save each file before downloading**.

**A row fails with a policy error** - Vibes AI blocked the content (often a celebrity, violence, minors or sexual content in the prompt or reference image). Edit it and rerun the row.

---

<sub>Auto Vibes is an independent tool, not affiliated with, sponsored or endorsed by Meta or Vibes AI. Meta, Vibes, Facebook and Instagram are trademarks of Meta Platforms, Inc.</sub>
