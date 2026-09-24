# LockDock

A small Android app that keeps your private photos behind a password or your fingerprint.

## Why this repo has no code

This repo only holds the app file. The source code is private, and I'd rather say that plainly than have you find out. I get that a privacy app you can't inspect is a fair thing to be skeptical about. So here is exactly what it does, and what it doesn't.

## What it does

- Encrypts each photo with a key held in your phone's secure hardware (Android Keystore) before storing it
- Unlocks with your password, or your fingerprint if you turn that on
- Keeps everything on your phone

## What it doesn't do

- No account, no sign-up
- No cloud backup, no uploads
- No password reset: forget it and the only way back in is clearing the app's data, which erases your photos

## If you'd rather not trust it

That's a reasonable call. Try it with a few photos you don't mind losing before you put anything private in it. It's a solo project, and I'm not going to pretend it's been through a professional security audit.

## Download

Android 11 or newer

Site: https://getlockdock.vercel.app/
