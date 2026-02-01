---
title: "Keyboard Maestro via AppAdict"
author: Cruz Mendoza
lang: en
date: 2026-01-31 23:10:14 +01:00
tags:
  - productividad
  - frikismos
  - software
---

[Keyboard Maestro, The App That Makes Everything Better - Tips for the Automation Curious - AppAddict](https://appaddict.app/post/keyboard-maestro-the-app-that-makes-everything-better-tips-for-the-for-the-automation-curious)

> Macros
> 
> Keeping apps alive -- Runs every 10 minutes with a trigger of "If Raycast is not running" and an action of "Start Raycast."
> 
> Log out cleanly -- One action quits all apps, the next pauses, then Keyboard Maestro ejects all disks and issues the logout command. This is how macOS is supposed to do it, but if you have apps that hang up your logouts or external drives that don't eject cleanly, you can insert a solution into this macro.
> 
> Mark all mail as read -- Uses menu bar commands and simulated mouse clicks.
> 
> Mount and unmount attached backup drives -- Keyboard Maestro runs a simple script to mount and unmount USB drives that stay physically connected but don't need to be available all the time. You can do the same with network shares. For example, when a backup or syncing app launches, the mounting script runs; when the app quits, the drive is unmounted.
> 
> If Bloom opens, close QSpace and If Rectangle Pro launches, quit SnapsOfApps.
> 
> Display a list of running Dock and menu bar apps and restart (not quit) the one you click -- I like to test software and keep up with new features by running multiple apps in the same category. This keeps my MacBook from getting bogged down.
> 
> Automatically connect via screen sharing to other Macs and Linux boxes -- Apple's built-in VNC client supports internal URLs, which Keyboard Maestro can open directly.
> 
> Batch open URLs in a specific browser -- I use this with Firefox. The macro closes the current window and opens a new one containing only the URLs I specify.
> 
> If Updatest opens, also open Nektony -- When testing apps, I often need them side by side. A macro is the easiest way to make that happen.
> 
> Batch quit jobs for groups of apps -- Just as you can open a group of apps with one command, you can close them when you're done.
> 
> Backup Homebrew -- This macro backs up my entire Homebrew configuration via a script, then copies the resulting file to a specific folder on my backup drive.
> 
> Restart Finder -- If Finder starts misbehaving, issuing killall Finder via a hotkey is far more pleasant than hunting through Activity Monitor.

I'm  a lady nerd, a nerd nonetheless. I love [Keyboard Maestro](https://www.keyboardmaestro.com/). I checked an I have 695 macros. I probably use half of them on a regular basis. I use it for everything, and I still find new ways to use it in this article.
