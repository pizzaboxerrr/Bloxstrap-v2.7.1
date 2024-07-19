Hello! Sorry about the dumpster fire that was v2.6, I had to rush the release of that on short notice, with no time for testing. It was a rough couple of weeks but things have cleared up now.

Additions
Localization has been fully implemented, finally! By default it follows your system language, but you can manually choose one in the Bloxstrap Menu's appearance tab too. Massive thank you to all the translators who contributed!
In the flag editor, the JSON import utility now allows you to easily import from a file
Added the ability to easily disable the configuration of any Fast Flags (intended for troubleshooting purposes)
Added the ability to use unsupported Roblox app languages
Added the ability to easily open Roblox's current log file, through the activity tracker menu
Also added a update file which brings back textures and gives you access to use fastflags that don't work yay!!!
Existing changes
On version upgrade, the new release notes now open in a webpage instead of just a notification popping up.
The prompt to confirm second instance launching is now optional, being disabled by default
Bootstrapper styles have now been given more sensible names
The presets section of the Fast Flags tab has been given a complete refresh, with loads more options, and fixes for problematic presets.
A proper error message is now shown for downloads that failed verification (yknow this)
Functionality for custom integrations has been vastly improved, with the added ability to specify files instead of only executables, applications now launching with the same working folder as the executable's location, and a file picker dialog.
Exception dialog message now makes reference to the Wiki, telling you to read it first before opening an issue.
Improved readability of menu alert bar (#2219)
Scroll bars in the Bloxstrap Menu are now always shown
Bug fixes
Fixed inconsistent handling of desktop app closing for "Don't exit to desktop app" integration
Fixed performance bug with the activity tracker (which was also contributing to the above issue)
Fixed bug with installation erroring if the given path had a lowercase drive letter (thank you @cryolithic!)
Fixed BloxstrapRPC not working under certain foreign system locales
Fixed bug with JSON exporter in the flag editor erroring when copying to the clipboard
Fully implemented flag editor validation, as I didn't do it properly last time, now validating flag types and values too.
Added handler for if a log file cannot be written (#2135)

