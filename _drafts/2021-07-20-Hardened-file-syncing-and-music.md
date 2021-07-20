---
layout: post
title: "Infrastructure hardening: File syncing and music"
comments: true
---

The first thing you're probably going to want is a way to auto-synchronize files between computers; once you have that, we can build a few things on top of it.

Lots of my friends use Dropbox, Google Drive, or Onedrive to sync files between their computers. This has a few advantages, but the big downside is that the amount of "cloud storage" you get is limited. Let's set up something that will sync as much data as we want between any computers we want, including phones.

Visit the [Syncthing download page](https://syncthing.net/downloads/). Click "SyncTrayzor" if you're on a Windows PC, "syncthing-macos" if you're on a Mac, or "Google Play" if you're on Android. If you're on iOS, you'll instead need a third-party program called [Möbius Sync](https://apps.apple.com/us/app/mobiussync/id1539203216?ign-itsct=apps_box&ign-itscg=30200). Go ahead and install Syncthing on two of the computers you want to share files between.

On Mac or PC, once the program is set up, it will open a tab in your browser with the Syncthing interface. Here's what mine looks like.

<img class="meme" src="{{'/assets/2021-07-20/Syncthing-interface.png' | absolute_url }}" alt='Screenshot of Syncthing' />

Now you need to connect your different devices together. See under "This Device" where it says "Identification", with a series of letters next to it? Click the letters to see how this computer will identify itself to others. It will show you a QR code with a long string of letters above it; that's the "Device ID".

Open Syncthing on your second computer and click "Add Remote Device" (near the lower-right corner). Type in the Device ID the first computer is showing. Then go down to "Device Name" and give it a name that makes sense, like "Bob's laptop". Click "Save". Shortly, your first computer should notice that the second one is trying to connect and ask whether that should be allowed; click the green "Add Device" button to confirm. 

Now you need to do the same thing, going the other direction.
// Run this on Holly's laptop
