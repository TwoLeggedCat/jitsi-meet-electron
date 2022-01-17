Fork of the Jitsi meet electron client to re-enable remote control.

# **DO NOT USE THIS UNLESS YOU UNDERSTAND THE RISK BEHIND IT AND THE [REASONS IT WAS DISABLED](https://github.com/jitsi/jitsi-meet-electron/security/advisories/GHSA-x4h8-fhrp-pm3p)**.

This fork will be updated periodically from upstream. It will not always be based off of a commit that was released, mind you, so the latest release *here* might not be the same as the latest release *there*, even aside from the direct modifications of this fork.

These binaries have not been tested on Windows and Linux, as I only use them on macOS, but I see no reason they would have problems as the only important change was one line of code (which is the same change for all platforms).

Please do not pester the Jitsi team if you have problems related to this fork that don't occur on their client.

Note that I know nothing about the remote control system in Jitsi, and can probably not fix any bugs in it. Whether or not they plan on continuing to do so while it's disabled, I do not know, and you'd have to ask them.

## Links
The following releases were based off of upstream releases:

[rc-2.8.6](https://github.com/TwoLeggedCat/jitsi-meet-electron/releases/tag/rc-2.8.6) (actually I borked this one; there's one extra commit in here but it was just a temporary downgrade of electron-builder so shouldn't be a problem.)

[2.8.7](https://github.com/TwoLeggedCat/jitsi-meet-electron/releases/tag/rc-2.8.7)

[2.8.8](https://github.com/TwoLeggedCat/jitsi-meet-electron/releases/tag/v2.8.8)

[2.9.1](https://github.com/TwoLeggedCat/jitsi-meet-electron/releases/tag/v2.9.1)

If you have a GitHub account, you may also download from the worflows section to get builds directly from the actions, giving me no oppurtunity to tamper with them (even though they're the same files I upload as releases). Requiring an account for this is GitHub's decision, not mine.

