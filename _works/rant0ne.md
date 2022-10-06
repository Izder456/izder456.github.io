---
title: "Rant ep. 1"
subtitle: "gentoo devs: whyY"
thumbnail: "/images/linux.png"
---

# Lets talk Gentoo:


Gentoo is a beautifully designed diy-type linux distribution that I've come to lie as of late. I like the adherence to sane defaults when needed and let the user choose otherwise as need be.


Theres a package deprecation notice for a common package that I just don't jive with


---

### Okay, netmeister2000-neckbeard, what idiocy will you spew today?



Gentoo has a package that I used to initialise my system, namely: x11-base/xorg-x11.


This is a meta-package, which means that its sole purpose is to pull in other packages, and thats it. 


This metapackage has some (old-ish, yet still used), Xorg tools like xrandr, xset, xinput, xkill etc, that are commonly used for X11 scripting for ricers like myself


Well, this package is planned to be removed from the Gentoo base-repo, next month.


The standpoint I've seen in favor of this change has some merit, but for the end user it could potentiall be extremely annoying to fix


Paraphrased:
>Gentoo thrives on customisability, and having a meta-package like x11-base/xorg-x11 contradicts that concept, since it includes things users may not want on their system.


So what? The existence of the meta-package existing in the repos, doesn't stop users from installing Xorg components as they wish. Just acknowlege in the handbook that x11-base/xorg-x11 isn't 
the *only* patch, and maybe write an article about the implications of using it or not.

Problem: solved

It just comes of as a pseudo-modernist obsession of "it's just a bit too easy". This is gentoo, nothing is easy. Breakage *will* occur. This breakage is entirely unavoidable, however. Odds are, 
this change will just force ordinary users who 
dont want to or need to troubleshoot, "fix" their previosly working system, just cos some idiot upstream decided against a common user configuration.

---

## Closing Notes

but, why?

-iz
