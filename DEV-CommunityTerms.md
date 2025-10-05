# Terms of Accord for Developers (1.0)
### Nothing Phone (2a) & (2a) Plus

------

#### Lead Developers:
The following people regularly work on [The Nothing Phone (2A) & (2A) Plus Organization](https://github.com/Nothing-2A), from now on will be referred to as "Lead Developers" from here on for the sake of brevity.

@FanDeMaraiste92 \
@witchersredirect \
@arteryring1 \
@itsHanibee

> All usernames match those on Telegram as of 06/10/25.

------

### [1] - Exclusions

You can build any ROM or port any OEM ROM excluding the ROMs that the lead developer team is maintaining. \
As of writing we maintain "Lineage OS" & "YAAP", this is only to ensure reliable quality between builds as we use them as the standard for the quality for the community common trees.

------

### [2] - Maintenance

If you are building ROMs for the public, you are expected to maintain them.
- We won't force you to release builds at strict, defined intervals; but be sure to update whatever it is that you maintain regularly whenever you can do so.
- If you think you might skip a point release for your ROM for any reason, please notify your users ahead of time so they are informed. 
- You are free to detach yourself from maintaining a ROM if someone else starts maintaining it at an "official" capacity.
- You are free to abandon a ROM when the developers for it break device specific functionality.

> These are just examples to preface that you can't just switch between ROMs just because you feel like it. Competence and consistency are paramount over everything else, if you don't have the discipline for it just don't ask us to advertise your work to the wider community.

------

### [3] - Limitations & Quality
You can request to post your source-built ROMs to the public at any time but remember that the quota is 2 different ROMs per person. This is so you as a maintainer keep up quality between whatever it is you maintain. 

- You are not to ship any pre-rooted builds.
- All release builds must be configured as `user` or `userdebug`, SELinux Enforcing. (Signing them with privately generated release-keys is recommended but not enforced).
- All release builds must have all the basic working functionality, unless your build is marked as experimental/beta/pre-release/testing you must work to keep any sort of bugs to a minimum.
> All known unfixed bugs are documented and tracked @ [2A Issue Tracker](https://github.com/Nothing-2A/releases/issues)

------

### [4] - Divergence 

You should generally refrain from making any changes in the device trees apart from adaptations to whatever ROM you are building for, an exception can be made if something is absolutely essential. If you have any suggestions for improvements, discuss it with the lead developers and make a pull request to the device trees.

------

### [5] - Transparency
You are not allowed to have your forks of the community trees or your custom self-brought up trees private when you want to release builds publicly through official channels. Your trees, however minor the changes may be need to be available publicly for the community to look at, use, and audit.

------

### [6] - Lenience & Liability
If your reputation as a maintainer is unanimously golden both between the public and the developer circle, you are allowed lenience with patches to your fork of the trees as long as the changes you make are sensible and add value to your user base. 

You are never allowed to force feature-sets into your builds that break regulatory, legal compliance in certain parts of the world or put the user in danger. \
Examples for such as Call Recorders, enabling radio bands that are not permitted in certain regions, modifying thermals or boost values.

You may always offer the choice to your users if that's really what they want but never ever force a risky option as default.

When in doubt ask the lead developer team and we may provide some guidance on the matter.

------

### [7] - Credit & Gratitude
You are to credit the people who have helped you or provided the sources you have used to do your work. This applies to both your group and in the main channel. The credits must include the lead developers if you are using any work that's made or worked on by them.

Non-compliance with any of these terms will result in a swift and merciless ban from all Nothing Phone (2a)/(2a) Plus community channels and related groups.
