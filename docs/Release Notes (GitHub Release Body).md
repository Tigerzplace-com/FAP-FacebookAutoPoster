## Facebook Auto Poster v2.2

**Group Intelligence & Table Improvements**

---

### What's New

**Group profile pictures** — Groups now load with their avatars displayed in the table.
Recognise groups at a glance without opening each one.

**Last visited timestamps** — Each group row shows how recently you visited — Today,
1w ago, 2mo ago. Quickly identify your active groups versus cold ones. Visited times are
also saved with your saved group lists.

**Sort by recently visited** — Click the Visited column header to bring your most
active groups to the top.

**Skip pending-approval groups** — If a group already has a post from you waiting for
admin approval, FAP detects this and skips it for the rest of the session. No duplicate
submissions in the same approval queue.

**Pending counter** — Posts waiting for approval now have their own count in the
post-run summary and the live counter strip.

### What's Fixed

**Facebook link previews** — Pasting a Facebook post or share link now shows a proper
preview card with the author, post text and photo. Previously these links showed a blank
card with the raw URL as the title. External links were already working and are unchanged.

**Safety Break countdown** — The break and the normal post delay no longer run at the
same time. When a break triggers, only the break countdown is shown, and the next post
goes out as soon as it ends.

**Safety Break uses your settings** — The break now follows the values you selected
(for example 10 posts / 2 minutes) instead of falling back to the defaults.

**Pause during a break** — Pausing and resuming while a break is running now works
correctly and no longer leaves the campaign stuck.

**Live counter label** — "Posted in" now shows the group you just posted to, not the
next one.

### What's Improved

**Group table rebuilt** — Consistent fixed-width columns for number, checkbox, picture,
and visited. Group name takes all remaining space, left-aligned. Custom styled checkboxes
throughout.

**Feature lock UI corrected** — Locked feature cards now show the correct plan that
unlocks them. Image Upload correctly shows Basic (was showing Pro).

**Group info available on all plans** — Group pictures and visited timestamps are
free for all users including Freemium.

---

### Upgrade Notes

No migration needed. Replace all files in your existing FAP folder with the new version
(don't mix old and new files), then click Reload on `chrome://extensions`. All saved
campaigns, group lists, and settings are fully preserved.