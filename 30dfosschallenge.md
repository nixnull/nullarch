# What is this?

The **30 Day FOSS Challenge** asks people to spend 30 days reducing their reliance on proprietary and nonfree software. This can be done through a pure "vegan" approach of entirely eliminating proprietary software for 30 days, or a more pragmatic approach of replacing one or two apps.

I will be doing my own challenge in April, and if you're schedule allows I encourage you to join me. If not, feel free to do it any time of year!

# "Proprietary"? "FOSS"? "Whirligig"?

**Proprietary** software is software where exactly how it works and how it's made is a secret. Usually, proprietary software is made by a company. Examples include iOS, Windows, Facebook, TikTok, etc.

**FOSS** stands for **free open-source software**. In this case, **free** means both free to obtain and free to use without restriction. **Open-Source** means that how it works is open for all to see. FOSS software is made by motivated individuals, nonprofits, and communities.

# Is this quick and painless? Or excruciatingly painful?

No to both, or a little of yes to both. We have an unfortunate cycle of FOSS advocates over-promising and assuring people that everything will be perfect and fine, and then new people running into issues and getting discouraged and giving up. I want to give you an accurate understanding.

First, keep in mind that this is a **30 day challenge**. Go in expecting to have problems. Some of those problems will be solvable, and you'll learn something in the process. Some of them will not be, but you'll be able to say you tried. In either case, if you talk about your experience you don't only help other people find new software to use, but you help the creators of FOSS software see where they can improve your experience in the future.

There are a small handful of cases where it really is painless. Firefox is FOSS, and it's just as good as Chrome in every way. The interface isn't even that different.

Most of the time you will encounter some inconvenience. Most FOSS software is less polished and slick than its proprietary counterparts. Sometimes, some cutting edge features are missing. Often, the interface will be significantly different, and it'll take a while to learn the new workflow.

And then there are unfortunate gaps. Cloud features of proprietary software are usually either missing from FOSS or require you to do it yourself with significant expertise. Tweaking and fixing issues on some software will require technical skills you may lack - some people see this as a feature, as it gives users (with the appropriate knowledge) more control.

# Give me some quick, simple, and doable changes.

You got it. Here's some of the best known, most immediate changes you could make. You may know some of these and not have known they were FOSS.

* Replace **Google Chrome** with **Firefox**
* Replace **Microsoft Outlook** with **Thunderbird**
* Replace **Microsoft Office**/**Google Drive** with **LibreOffice**

# What about X? What can I replace it with?

I cannot give exhaustive advice here. Instead, check out [alternativeto.net](https://alternativeto.net/). Remember to sort by Open Source. Ironically they are not themselves FOSS, and run ads. However, I think their crowd-sourced rankings and comments give more realistic expectations than some FOSS advocate websites which may recommend solutions that are not practical for all users.

# I want to go "FOSS vegan", what are the big changes?

Currently, without significant technical knowledge (or perseverance to gain those skills), going truly "vegan" is not practical. Thus, I will provide both "vegan" recommendations and the closest you can get with a 'reasonable' amount of effort.

## Desktop/Laptop Operating Systems

Your Operating System (OS) right now is probably Windows, Mac OS, or ChromeOS. All of those are proprietary. The best known alternative is Linux, sometimes also known as GNU/Linux. *Keep in mind that changing OSes means you will lose access to some software, as not all software supports all OSes. Additionally, the interface, where things are stored, and even the way you install software will be different. This is why this is considered a major change.*

Before you jump straight to replacing your OS with Linux (and deleting *everything on your computer*), consider some ways to "trial" Linux:

* Install it on an old/unused device
* Run it off a USB drive to try it out
* Run it in a Virtual Machine (like an emulator, for OSes)
* [More technical:] Dual-Boot/Boot Camp, allowing you to keep both your current OS and Linux and switch between them

All versions of Linux are *mostly* FOSS, but most versions are not 100% FOSS. Unfortunately, I cannot recommend a 100% FOSS version to any non-technical user currently. If you're a non-technical user interested in trying Linux, try [Linux Mint](https://linuxmint.com/).

Technical users have more options. The most common FOSS option is [Debian](https://www.debian.org/). Most of the time, Debian will work out of the box with little issue. However, due to being FOSS, some hardware will not work properly (unless you manually install the proprietary drivers). It is this reason I cannot recommend it for non-technical users.

## Phone Operating Systems

Most phones run Android or iOS. Android is mostly FOSS, but some of it is proprietary Google code. This is why an Android phone requires google apps to be installed, a google account to use the store, and gives special privilege to look at your data to google apps.

iPhones are so locked down that there are no good options to replace iOS currently, without some significant tinkering.

Androids, however, vary from company to company. There are several alternatives to Google Android, including AOSP (Android minus google) variants and mobile versions of Linux. Which ones are available to you will depend on your phone. You will need to do some research yourself, by searching for "[model] aosp" or "[model] linux". If available to you, DivestOS and GrapehenOS (the one I use) are both highly recommended.

If you have the money and resources, and need a new phone, there are also some FOSS phones available for sale, such as the Pine Phone.

# I want support/someone to talk to/to complain about how hard it all is

Please do all of the above! If you're on Mastodon (or stuck on one of the corporate social medias) I recommend the hashtag #30DayFOSSChallenge.

If you're having trouble or have questions, I will personally answer you on mastodon: [@nix@social.stlouist.com](https://social.stlouist.com/@nix).

# I'm skeptical. Convince me.

## Why do I care how it works?

Because it's made by a for-profit company, proprietary technology is usually monetized. There's three main ways to do this:

* sell the software,
* put ads in the software,
* sell your user's data.

Most companies double or triple dip, implementing more than one of these. Sometimes newer platforms and software are proprietary but entirely free, surviving off investments. This is a temporary state, building a dedicated userbase to later monetize and pay back the investors.

Selling software may seem honest and inoffensive. Unfortunately, many companies are moving to a model called **Software as a Service** where they charge a subscription, which they claim helps them to continue to support/update it. Not paying the monthly/yearly subscription means you will lose access to the software you're heavily invested in using. This is basically a ransom.

Selling user's data is already controversial. Companies are secretive about how much data they actually collect, and who they sell it to. And while governments are (slowly) trying to limit data harvesting, they are mostly doing so through regulatory fines. For a corporation, if the punishment is purely financial, then it's simply a business expense.

## How does FOSS software stay around without funding?

This is a common anxiety of FOSS software. If there's no profit motive, why doesn't it get abandoned or die?

The biggest FOSS projects do have funding. Some implement paid support tiers, where you can call the maintainers for help. Many receive donations from individuals, companies, and governments who rely on this software.

Smaller projects are more vulnerable to this issue, but even if a maintainer no longer has the ability to work on a project, the open nature of it means another person can pick it up. For proprietary software the opposite is true: a defunct company often means a dead product.

## I can't because I need...

### ...proprietary software, for work!

Indeed you may. Your job may mandate certain software and there's nothing you can do about that. I'm in the same spot myself.

However, the goal here is to do what we can, not worry about what we cannot do. Knowing which things are non-negotiable simply lets us focus on everything we *could* change.

### ...social media for [my business, keeping up on activism].

Social media has become the primary way to keep up with people and organizations. You likely communicate with friends daily through social media. If you run a business, you probably rely on it as a way to freely advertise. And when it comes to activism and social movements, social media is usually the best way to get up-to-date info. Simply leaving can feel isolating.

While leaving entirely might not be feasible, you may be able to reduce usage through the following methods:

* Evaluate which social media are most important, and reduce to just those. Which ones are you getting healthy and important info from? Which ones are just annoying you or making you go "heh" every few posts?
* If you communicate through something like **facebook messenger**, try replacing it with **[Signal](https://signal.org/)**.
* Make a **Mastodon** account for your personal and business usage. Mastodon is a FOSS social network with some similarity to Twitter (tho it's not an exact match).
* Encourage everyone around you to make the same changes.

### ...videogames to stay sane.

Understandable. If you're like me and your primary form of entertainment is videogames, it'd be glib to tell you to simply drop them. I want you to stay sane and happy.

Keep in mind tho, that this is a 30 day challenge. There are some things you could do in this time. The number one thing you could do is **try some FOSS games**. I personally recommend **OpenTTD** or **Battle for Wesnoth**. Alternatively, you could consider catching up on any books, movies, boardgames, or hikes that you've been putting off.





