# pill-for-the-hacked
A comprehensive checklist to follow when you get your accounts compromised (maybe be falling victim to a cookie stealer)


First off. Do not pay. You’re not going to get accounts back and they’ll just keep asking for more money.

> Disconnect the affected computer from the internet right away. Unplug the Ethernet cable and turn off WiFi.
> Stop using that computer for anything involving logins. Don’t sign into email, banking, social media, or anything else.

> While still on the infected computer:
	- Back up only personal data like documents, photos, and videos. Do not backup executable files like .exe, .scr, .bat, .msi, or unknown .zip files, and do not back up browser profiles or AppData folders.


We need to now start using a known clean computer. On that clean system, do the following:
1- Using a password manager, change your passwords in this order

1.1- Primary email
1.2- Any backup or recovery emails
1.3- Banking, financial, PayPal, Venmo, Crypto accounts
1.4- All social media (Facebook, Instagram, Reddit, Discord, etc.)
1.5- Gaming platforms
1.6- Anything else that had user credentials stored in your browser
1.7- The passwords should all be unique, alphanumeric, at least one special character (where available), and at least 10 characters
2- While in each account,
2.1- turn on two factor authentication everywhere you can. Ideally, you'd use a hardware token--like a Yubikey. Next would be an authenticator app--like Google Authenticator.
2.2- Only use SMS if there's no other option
2.3- Make sure to copy your recovery key or one-time use codes. Print these out. Do NOT just save them on a file on your computer
2.4- If you’ve previously had 2FA enabled, disable it and then re-enable it. This will generally cause any previous one-time use codes or recovery keys to become void
Confirm ALL your recovery methods are correct (a lot of info stealers will change the recovery methods).
2.5- If you don’t have recovery methods set, do it NOW
2.6- Sign out of all active sessions
2.7- Remove devices you don’t recognize.
2.8- Remove any linked apps or integrations you didn’t add or no longer need.

3- In your email account settings
3.1- check for forwarding rules, auto‑reply rules, recovery email, recovery phone number, and anything else that could redirect or recover your account.
3.2- Delete anything you didn’t set up.
3.3- Assume anything you've saved/stored in your browser has been compromised
3.4- Go to your OS manufacturer's website and download your OS. ONLY GET THIS FROM THE OFFICIAL SOURCE.
3.5- Create a bootable USB installer for your OS
3.6- No. A reset and restore from cloud backup is not sufficient. You need to use the USB installer route.

4- Back to working with the infected machine.
4.1- Boot the infected computer from the USB.
4.2- During setup, delete every existing partition on the drive.
4.3- Install the OS fresh on the unallocated space.
4.4- Run your update tools until nothing is left
4.5- Install drivers and software, making sure to ONLY use OFFICIAL sources
4.6- Install your browser (if needed)
4.7- Install your browser extensions
4.8- DO NOT import any old data, profiles or save passwords
4.9- If any financial accounts were access from the previously infected machine
4.10- Watch accounts closely
4.11- Turn on any transaction alerts the accounts allow
4.12- Consider placing credit freezes for each of the "Big 4" credit bureaus (Equifax, Transunion, Experian, and Innovis)

> The above assumes you have a PC running Windows or Linux. If you have a Mac, you’ll need to substitute downloading and creating an bootable USB OS installer with:

5- Boot into recovery mode
5.1- Use Disk Utility to erase your macOS Data Volume
5.2- Exit out of Disk Utility
5.3- Run the “Install macOS <name>”
5.4- Follow the instructions to install
5.5- Do NOT restore from a Time Machine backup unless you can confirm it’s clean—the Time Machine disk wasn’t attached at the time you got the malware

> Be prepared to lose access to some of your accounts. Only those services can help you regain access. Those that can’t/won’t help just means those accounts have been lost. No one else can help, and anyone claiming otherwise is just trying to scam you.
