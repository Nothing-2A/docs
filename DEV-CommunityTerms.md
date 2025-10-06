# Terms of Conduct for Developers (1.1)
### Nothing Phone (2a) & (2a) Plus

------

#### Lead Developers:
The following people regularly work on [The Nothing Phone (2A) & (2A) Plus Organization](https://github.com/Nothing-2A), and will be referred to as "Lead Developers" from here on for brevity.

@FanDeMaraiste92 \
@witchersredirect \
@arteryring1 \
@itsHanibee \
@R0rt1z2

> All usernames match those on Telegram as of 06/10/25.

------

### [1] — Exclusions

You can build any ROM or port any OEM ROM excluding the ROMs that the lead developer team is maintaining. \
As of writing, we maintain "Lineage OS" & "YAAP". This is only to ensure reliable quality between builds as we use them as the standard for the quality of the community common trees.

------

### [2] — Maintenance

If you are building ROMs for the public, you are expected to maintain them. You must own the device you are developing for. Blind maintenance, or unverified testing without physical access to the device are not acceptable. This is general practice between all aftermarket communities for good reasons.

- We won't force you to release builds at strict, defined intervals, but be sure to update whatever it is that you maintain regularly whenever you can do so.
- If you think you might skip a point release for your ROM for any reason, please notify your users ahead of time so they are informed. 
- You are free to detach yourself from maintaining a ROM if someone else starts maintaining it at an "official" capacity.
- You are free to abandon a ROM when the developers for it break device-specific functionality.

> These are just examples to preface that you can't just switch between ROMs just because you feel like it. Competence and consistency are paramount over everything else. If you don't have the discipline for it, just don't ask us to advertise your work to the wider community.

------

### [3] — Limitations & Quality
You can request to post your source-built ROMs to the public at any time, but remember that the quota is 2 different ROMs per person. This is so you, as a maintainer, keep up quality with whatever it is you maintain. 

- You should not ship any pre-rooted builds.
- All release builds must be configured as `user` or `userdebug`, SELinux Enforcing. (Signing them with privately generated release-keys is recommended but not enforced).
- All release builds must have all the basics working. Unless your build is marked as experimental/beta/pre-release/testing, you must work to keep any sort of bugs to a minimum.
> All known unfixed bugs are documented and tracked @ [2A Issue Tracker](https://github.com/Nothing-2A/releases/issues)

- The use of AI-generated code in device trees is strictly prohibited, especially in any part of the kernel that impacts system stability or security. We understand if you're eager to do something cool but lack the skills to do so, but we cannot trust generated code following the recent malicious releases of kernels with AI-generated code ruining devices in the Redmi Note 10 Pro community.

------

### [4] — Divergence 

You should generally refrain from making any changes in the device trees apart from adaptations to whatever ROM you are building for. There's really barely any original "improvements" you can make on the publicly available trees. An exception can be made if something is absolutely essential or you feel like an addition would be in the best interest of your users' usecases. If you have any suggestions for improvements, discuss them with the lead developers and make a pull request to the device trees.

------

### [5] — Transparency
You are not allowed to have your forks of the community trees or your custom self-brought up trees private as long as you want to release builds publicly through official channels. Your trees, however minor the changes may be, need to be available publicly for the community to look at, use, and audit. We cannot make exceptions for this. If you feel like having your trees hidden, you're more than welcome to do so. Just don't ask for your builds or projects to be shared through the official 2A channel. 

------

### [6] — Monetization

We support developers who wish to receive recognition or compensation for their time and effort, as long as it’s done in good faith and without compromising on ethics. \
We stand behind fair compensation, but this ecosystem exists to share work freely. Not to commercialize it.

You are encouraged to accept donations through transparent and legitimate platforms (PayPal, Patreon, Ko-fi, UPI etc.). We understand that monetary support can help offset costs for build servers or personal time spent on maintenance. However, it must remain **voluntary** and **non-restrictive** in nature.

 **What’s Allowed**
- Publicly sharing donation links in your release posts or profiles.  
- Offering optional perks that do not impact access — such as early testing builds, shout-outs, or supporter roles, as long as stable releases remain free for everyone.  
- Crowdfunding for device purchases, infrastructure, or hosting costs, provided it’s done transparently.

**What’s Not Allowed**
- Paywalling or restricting ROMs, updates, or features in any capacity.  
- Offering “early access” or “exclusive” builds that never reach the public.  
- Accepting money in exchange for removing already public features, or prioritizing changes for your donors.  
- Using community resources (trees, infra etc.) to promote personal profit ventures.

### [7] — Lenience & Liability
If your reputation as a maintainer is unanimously golden both among the public and the developer circle, you are allowed lenience with patches to your fork of the trees as long as the changes you make are sensible and add value to your user base. 

You are never allowed to force feature-sets into your builds that break regulatory, legal compliance in certain parts of the world or put the user in danger. \
Examples of such include Call Recorders, enabling radio bands that are not permitted in certain regions, modifying thermals or boost values.

You may always offer the choice to your users if that's really what they want, but never ever force a risky option as default.

When in doubt, ask the lead developer team, and we may provide some guidance on the matter.

------

### [8] — Credit & Gratitude
You are to credit the people who have helped you or provided the resources you have used to do your work. This applies to both your group and on the main channel. The credits must include the lead developers if you are using any work that's made or worked on by them.

------

### [9] — Enforcement & Consequences

Compliance with these terms is mandatory. The Nothing Phone (2a)/(2a+) developer community operates on trust, mutual respect, and shared standards. \
Egregious or repeated violations of any section of this document, including but not limited to misconduct, poor maintenance practices, paywalled content, or malicious intent will result in immediate removal from all associated community channels and related groups.  

Depending on the severity of the situation, actions may include:
- Revocation of maintainer status or repository access.
- Removal of builds from official listings or announcements.
- Temporary or permanent bans from developer spaces and affiliated chats.  

While we aim to handle most disputes with clarity and conversation, **willful disregard of these terms or abuse of community trust will not be tolerated.**  
Repeated offenders will not be given second chances.

