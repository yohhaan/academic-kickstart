---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "You Shall Not Pass! (Password Management)"
subtitle: ""
summary: "In this post, I hope to convince you once for all to stop reusing this same exact password you use for all your accounts and start using a password manager."
authors: [admin]
tags: [security, password manager]
categories: []
date: 2020-06-12T18:17:35-04:00
lastmod: 2020-06-12T18:17:35-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

In this post, I hope to convince you once for all to stop reusing this **same exact** password you use for all your accounts and start using a password manager.

## Have I Been Pwned? 

[Have I Been Pwned?](https://haveibeenpwned.com/) is a website that allows you to search over known data breaches and check if one or several of your accounts and personal information have been compromised. If so, you will see which personal information has been leaked and obtain details about the breach. The *Notify me* service allows you to be notified if your email address appears in future breaches.

If some of your accounts have been compromised, you should change your password, as well as all the other accounts that were using the same or a similar password, so that the malicious actors will not be able to break into your other accounts.
If you were not already caught in a breach, do not think that you are safe: this is mostly a matter of time before having one of your account compromised.

## So what should I do?

First, you have to accept that at some point your passwords *will be stolen*. When this happens, the best way to protect yourself will be to have used *long*, *unpredictable*, and *unique* passwords for each of your account. 

Obviously, it is impossible for us to remember tens of different, complex, and 30-character long passwords, and that's where the password manager comes in. 

A password manager can be seen as a password safe where you safely store all your unique and complex passwords for all your accounts. And you only have to remember one unique and complex password which is used to unlock the database of passwords.

They are very simple to use, cross platforms (you can synchronize and have access to all your passwords from all your devices), they come with convenient browser extensions to log you in automatically on websites, and they will take care of  randomly generating complex passwords for you.

## Which password manager to use? 

I recommend you to use [LastPass](https://www.lastpass.com/), because it is easy to configure, synchronize, and use accross all your devices. There are other options like [1Password](https://1password.com/) and for more advanced users I would recommend to take a look at [Keepass](https://keepass.info/) or at [pass](https://www.passwordstore.org/).

You will need to create a *strong master password* which will be the one that will allow you to unlock your vault of passwords. Create a unique and complex master password (do not use one that you were previously using...), and remember it, otherwise you will loose access to all your other passwords...

Then you will have to add into your passwords vault, all your accounts and passwords. When you do so the first time, for each account:
* Log in to your account on this website with your old password
* Use your password manager to generate a long, complex, and unique password for this account
* Copy paste this password on the website in your account settings to change your old password for a random one

This might take you some time to do it for all your accounts the first time, but it's definitely worth it.

**Additional tips:**
* Consider using multifactor authentication to add a second login step before being able to unlock your passwords vault.
* Do not be always sign in by default in the browser extension of your password manager: if someone else is using your device, she might have access to your passwords...


For more advanced users, I would recommend to take a look at [Keepass](https://keepass.info/) or at [pass](https://www.passwordstore.org/).

