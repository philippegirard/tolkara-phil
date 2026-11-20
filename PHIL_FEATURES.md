# phil features

What this fork (`philippegirard/tolkara-phil`) adds to Tolkara on `phil`, one
line per feature, newest last, with its pull request (or its commit, for a
feature merged before pull requests were used). Every feature pull request
adds or updates its line here.

- **Paste button on the on-screen keyboard.** iOS's paste control in the row above the keyboard types the clipboard (for a long password), never Return or Tab. Commit [4fdd58e](https://github.com/philippegirard/tolkara-phil/commit/4fdd58ee4091878cb1dc7c86a95a992209be9345).
- **Update button for WoW Forever.** The library shows "Update available" when Blizzard has a newer build, and updates the client in place; the game then fetches its new data. Also: device builds from any committed branch. [PR #1](https://github.com/philippegirard/tolkara-phil/pull/1).
- **Installed WoW build on the library row.** The WoW Forever row always shows the installed build (from the device's `.build.info`), with "Update available" beside it when a newer one is out. [PR #2](https://github.com/philippegirard/tolkara-phil/pull/2).
