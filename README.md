# GhostVoice — Real-Time AI Voice Changer for Windows

GhostVoice changes your voice live in Discord and in-game voice chat. Its AI voices run in real time on an ordinary CPU, so you don't need a dedicated graphics card.

**[Website](https://ghostvoice.pages.dev/)** · **[Download](https://ghostvoice.pages.dev/download)** · **[Discord community](https://discord.gg/h89bAcdGR)**

This repository hosts the Windows installer and the release notes. The latest `GhostVoice-Setup.exe` is on the [releases page](https://github.com/alialsartawi7-sketch/ghostvoice-app/releases/latest) and on the website.

## Features

- **AI voices that run on your CPU.** Four built-in AI voices (Leen, Salma, Reem and Noor) with pitch control, in real time, no GPU needed. If the PC is overloaded the AI voice backs off on its own, and Low-end PC mode lowers CPU use further.
- **31 classic voices** in five groups:
  - female and male, 4 each, at different pitches;
  - characters: giant, ghoul, zombie, ghost, android, villain, stadium announcer, robot, demon and alien;
  - places: cave, cathedral, stadium, bathroom, behind a wall and underwater;
  - devices: phone call, radio, walkie-talkie, megaphone, broken speaker, old TV and 8-bit.

  They are very light on the CPU and run on any PC.
- **Works in Discord and games.** Setup adds a microphone named **GhostVoice**; pick it as your input device.
- **Soundboard** and global hotkeys.
- **A clean mic:** noise removal, a noise gate, auto level, and mic boost up to 400%.
- **Effects:** reverb and broken speaker.
- **Record:** recordings include the game or Discord sound, *Instant replay* saves the last 30 seconds of video and audio, and *Say it again* plays the last 3–15 seconds you heard back into the call.
- **Train your own voice** (beta, for subscribers): add at least 10 minutes of recordings of one person, and the voice trains for free on your own Kaggle account. The recordings stay in your account; GhostVoice never receives them.
- **Arabic and English.** Full right-to-left Arabic interface, with English in Settings. The AI voices were trained on Arabic speakers, so letters like خ ق ع غ ح come out clear.
- **Runs on your PC.** After the first activation it works offline. Updates install from inside the app, and each one is checked against its fingerprint and signature before it runs.

## Install

1. Download `GhostVoice-Setup.exe` from the [website](https://ghostvoice.pages.dev/download) or the [latest release](https://github.com/alialsartawi7-sketch/ghostvoice-app/releases/latest).
2. Optional: compare the file's SHA-256 with the one in the release notes:

       certutil -hashfile GhostVoice-Setup.exe SHA256

3. Run the installer. GhostVoice is not code-signed yet, so Windows may warn about an unknown publisher the first time. [Step-by-step help](https://ghostvoice.pages.dev/download#windows-warning).
4. In Discord, open **User Settings → Voice & Video** and set **Input Device** to **GhostVoice**. In a game, pick **GhostVoice** as the microphone in its voice chat settings.

Your saved voice, settings, sounds, hotkeys and trained voices carry over between updates.

## Plans

Start with a free trial, then choose a monthly or yearly plan. Details are on the [website](https://ghostvoice.pages.dev/).

## Credits

The AI voice uses [Project Beatrice](https://prj-beatrice.com/). Voice training data comes from Mozilla Common Voice (CC0).

<div dir="rtl">

## بالعربية

GhostVoice برنامج لتغيير الصوت بالذكاء الاصطناعي في الوقت الفعلي على Windows، يعمل في ديسكورد وفي محادثات الألعاب الصوتية. تعمل أصوات الذكاء الاصطناعي على معالج الحاسوب العادي، فلا تحتاج إلى كرت شاشة منفصل.

- أربعة أصوات ذكاء اصطناعي (لين، سلمى، ريم، نور) دُرّبت على متحدثين بالعربية، فتخرج حروف مثل خ ق ع غ ح بوضوح، مع التحكم بطبقة الصوت.
- 31 صوتاً كلاسيكياً في خمس فئات: نسائية، ورجالية، وشخصيات، وأماكن، وأجهزة.
- لوحة أصوات (Soundboard)، وإزالة الضجيج، وتوحيد مستوى الصوت تلقائياً، وتكبير الميكروفون حتى 400%.
- التسجيل، والإعادة الفورية لآخر 30 ثانية بالصوت والصورة، وإعادة آخر ثوانٍ سمعتها في المكالمة ليسمعها الجميع.
- درّب صوتك الخاص (تجريبي، للمشتركين) مجاناً على حسابك في Kaggle، وتبقى التسجيلات في حسابك ولا تصل إلى GhostVoice.
- واجهة عربية كاملة من اليمين إلى اليسار، والإنجليزية متاحة من الإعدادات.

**[التحميل](https://ghostvoice.pages.dev/download)** · **[سيرفر ديسكورد](https://discord.gg/h89bAcdGR)**

</div>
