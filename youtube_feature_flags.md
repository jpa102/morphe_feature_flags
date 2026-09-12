> [!NOTE]
>
> some flags can also show up on the suggested versions of youtube
> 
> these may be only available for a certain amount of time
>
> **legend**: flags marked with `$` are inactive flags,  `゜` has a different behavior *(buggy a/b testing flag? a "dependency" of a flag? short-lived a/b testing flag? buggy when blocked? only god knows this)*
>
> it's advised that you do not use settings like spoof app version or disable layout updates as some flags are bound to the app version the server responds

# from 21.14.484

* 45383916 - new swipeable cast device dialog popup (blocking this will fall back to the centered popup version) ゜
* 45400535 - shows a weird opaque space at the top of the video player in watch page (probably to make it 4:3 aspect ratio? somehow connected to the ambient mode flag?) `゜`

# from 21.19.280 beta

* 45376186 - ambient mode for video player (flag only appears when you visit the watch page)
* 45714755 - makes use of some gray colored icons in some places (block the flag)
* 45680009 - new right and left page navigation transitions `゜`
* 45701806 - a continuation of right and left page navigation transitions (a bit "choppy" when this is blocked, like a dependency?) `゜`

# from 21.23.481 beta

* 45748489 - smaller compact flyout menu (seen in home feed via 3-dots menu button)
* 45753913 - a sorta dependency of 45748489, except this breaks it and makes the flyout's background transparent `゜`

# from 21.36.45-SECONDARY

* 45621960 - increased top and bottom padding of bottom navigation bar `$`
* 45624413 - long press a bottom navigation button to quickly navigate to that page `$`
* 45625289 - THIS WILL CRASH THE APP WHEN SWITCHING TO TABS LIKE SEARCH, SUBSCRIPTIONS, NOTIFICATIONS, LIBRARY, AND OTHERS `$`
* 45642407 - some color-coded debug popup about "flash call time" `$`
* 45630927, 45631257, 45647369 - translucent blur effect at the bottom navigation bar, originally enabled for capable devices `$` `゜`
* 45685200 - cat icons everywhere `$`
* 45708621 - THIS WILL CRASH THE APP IMMEDIATELY `$`
