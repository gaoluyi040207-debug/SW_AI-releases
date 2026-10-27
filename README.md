# SW_AI

A menu-bar Mac app that shows the real chatgpt.com in its own window, under your own ChatGPT login, and adds a **Quick Window**: a small, always-on-top ChatGPT you can call up over any app with **Option+Space**.

SW_AI is an independent app. It is not made by or affiliated with OpenAI. Everything inside its windows (history, the model picker, attachments, voice mode, custom instructions) is chatgpt.com itself.

This repository only hosts downloads. The source code is not public.

## Download

Get the latest `SW_AI-x.y.dmg` from [Releases](../../releases/latest).

Requires macOS 14 or later, on Apple Silicon or Intel.

## Install

1. Open the `.dmg` and drag **SW_AI** into **Applications**.
2. Open SW_AI from Applications. macOS will say it can't verify the app, because SW_AI isn't notarized by Apple. Click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to the SW_AI message. Confirm with your password.

You only need to do this once per version.

## Using it

- **First launch:** the main window opens on chatgpt.com. Sign in the way you normally do (email, Google, Apple or Microsoft). You stay signed in across relaunches; SW_AI never stores your password.
- **Later launches:** if you're signed in, SW_AI starts quietly in the menu bar.
- **Quick Window:** press **Option+Space** anywhere, including over full-screen apps. Press it again or **Esc** to hide it. Within 15 minutes it continues the same conversation; after that it starts a fresh chat. Drag it by any empty spot in its top strip.
- **Menu-bar icon:** Show Main Window, Quick Window, Open Quick Chat in Main Window, Change Shortcut…, Open at Login, Quit.

## Permissions

SW_AI needs **no** Accessibility or Input Monitoring permission: the shortcut is a standard system hotkey.

macOS asks for the **microphone** the first time you use ChatGPT's voice mode, and for the **camera** the first time you take a photo for ChatGPT. Only chatgpt.com and openai.com pages can use either. After installing a new version, macOS may ask again.

## Things to know

- **Terms of service.** SW_AI shows chatgpt.com in an embedded web view rather than a browser, and slightly changes the page (it hides "download the app" prompts and the sidebar in the Quick Window). Check that this is acceptable under OpenAI's terms for your use.
- **Site changes.** chatgpt.com changes often. If it stops accepting sign-in from embedded web views, signing in may fail. If its page layout changes, SW_AI's small page tweaks stop applying and the page simply shows unchanged.

## License

Copyright © 2026 Luyi Gao. All rights reserved.

You may download and use SW_AI for personal use. You may not copy, modify, redistribute, sell, decompile or reverse-engineer it.
