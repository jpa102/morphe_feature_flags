# you want it? you find it!

this is `more_feature_flags`, a repository filled with collection of feature flags for apps patched with [Morphe](https://github.com/MorpheApp/morphe-patches) and [Reseam](https://git.reseam.app/reseam/patches) *(applicable if it has a **Feature Flags Manager** in settings → Miscellaneous, in the patched application or similar)*. it's also compatible with reseam at least to my limited testing

it's called "more" because **Mo**rphe + **Re**seam = **MoRe**, you get me?

and because the name "**MoRe**" implies there are **more** feature flags that are yet to be uncovered

***

if you found a bug and identified a feature flag that somehow solves it, you can provide the flag to them and they could implement a solution for it. users can also test it out

if you found feature flag(s) that look interesting, pretty sure the morphe and reseam contributors would also take interest into it and possibly develop a patch

# getting started (morphe)

go to Debugging inside Miscellaneous at Morphe settings *(example: youtube → settings → morphe → miscellaneous)*, then enable **Debug logging** and restart the app *(like **end** the app from your recents, okay?)*

on your restart, you will see the feature flags in **numerical order**. they are **unreadable** for sure but once you identify what it does based on **blocking** and **unblocking** them, you can start labeling them with a **clear description** and their behavior when blocked or unblocked / forced *(use a note app for example, on pc with [scrcpy](https://github.com/Genymobile/scrcpy) it's more convenient, or whatever suits you best)*

# note

sometimes, flags are only **specific** to an app version, therefore you need to document their limitations and what version(s) they only appear. hell, they may even **disappear** in later app versions at **any given time**

you can either create your **own** repository for flags, or freely share them **here** so they're in one place

with that said, are you up for the challenge finding and documenting feature flags in apps?

***

<sup>[notably featured in Jman-Github's Awesome Android Patching repository, listed as a project](https://github.com/Jman-Github/Awesome-Android-Patching)</sup>
