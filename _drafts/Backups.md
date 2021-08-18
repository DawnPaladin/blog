---
title: "Infrastructure hardening: Cheap, effortless backups"
comments: true
tags: guides hardened-infrastructure
---

The best antidote to fear is having a plan. Let's make a plan for what would happen to your files if your house burned down. We want to be as certain as anything can be in life that no matter what happens, your files cannot be lost.

I used to use a product called CrashPlan for my backups. Then one day CrashPlan decided the market for home backups wasn't profitable anymore and they were working exclusively with businesses now. I researched a bunch of alternatives, and today I will share the results with you.

As I searched for a CrashPlan replacement, I had three main requirements in mind:

1. **Effortless operation.** A backup plan that requires you to perform a chore every so often is no backup plan at all, because at some point your life will get busy, the least urgent thing (backups) will get neglected, and that will be when disaster strikes. You want something that will run 100% on automatic.
2. **Versioned backups.** Gone are the days when a virus would be content to erase your hard drive. These days we have ransomware, which encrypts your files so you can't open them, lurks insidiously until you've backed up the encrypted files, and then demands thousands of dollars in exchange for the decryption key. If you only have one backup copy, and you back up the encrypted files, then your backups are encrypted and therefore worthless. To defend against ransomware, your backup system needs to maintain several versions so you can be assured of having a good one.
3. **Low cost.** Backups aren't *that* complicated. This is an important service, and we want it done right, but whatever the monthly bill is, we're going to be spending that money every month *forever.* Let's get the bill as low as we can.

This wasn't on my original requirements list, but the solution I found had a fourth benefit: **Independence.** The most important pieces of this system will be owned by us. Someday another company will send us an email that says <span class="vader-voice">"I am altering the deal."</span> When that day comes, we will say, "Fine. See ya!", kick them to the curb, and switch to another provider in minutes. That kind of freedom is what hardened infrastructure is all about.

<style>
	.vader-voice {
		font-weight: bold;
		font-style: italic;
		font-variant: small-caps;
	}
</style>

My backup system has three components:

1. **The files.** These live on the computers in my home. We don't need writeable CDs, external hard drives, or anything like that.
2. **The backup software.** I chose a program called **[Arq Backup](https://www.arqbackup.com/)**. You purchase the program once for $50 ($80 if you need to backup multiple computers--choose the "5-computer family pack" at checkout). It monitors your hard drive and backs up files to the cloud.
3. **Cheap cloud storage.** Arq can backup files from one computer to another, but for sure protection against fire, flood, or meteor strike, nothing's as good as cloud storage. If you supply your own backup software, **[Backblaze B2](https://www.backblaze.com/)** will store your files at the rate of half a cent per gigabyte per month. My family spends about $4/month on backups. That's better than any other deal I've seen.