# Facebook Auto Poster v2.3 — User Tutorial

A step-by-step guide to installing, configuring, and using the Facebook Auto Poster (FAP) Chrome extension.

🌐 **Official page:** [tools.tigerzplace.com/facebook-auto-poster](https://tools.tigerzplace.com/facebook-auto-poster/) · 📚 **Docs:** [tools.tigerzplace.com/docs](https://tools.tigerzplace.com/docs/) · 💳 **Plans:** [tools.tigerzplace.com/pricing](https://tools.tigerzplace.com/pricing/)

> 📺 **Prefer to watch?** The video tutorial covers the core workflow of FAP (recorded on v2.0, before the v2.3 redesign). The steps are the same, but buttons now live in the places described below:  
> 👉 [Watch on YouTube — FAP Full Tutorial](https://www.youtube.com/watch?v=hlqqBId04GI)

---

## Table of Contents

1. [Installation](#1-installation)
2. [First Launch and Finding Your Way Around](#2-first-launch-and-finding-your-way-around)
3. [Loading Your Groups](#3-loading-your-groups)
4. [Choosing Groups for a Campaign](#4-choosing-groups-for-a-campaign)
5. [Writing Your Post](#5-writing-your-post)
6. [Adding Photos](#6-adding-photos)
7. [Link Previews](#7-link-previews)
8. [Delay Between Posts](#8-delay-between-posts)
9. [Starting a Campaign](#9-starting-a-campaign)
10. [Pause, Resume and Stop](#10-pause-resume-and-stop)
11. [When a Run Finishes](#11-when-a-run-finishes)
12. [Saving and Opening Campaigns](#12-saving-and-opening-campaigns)
13. [Scheduling Posts](#13-scheduling-posts)
14. [Post Variations](#14-post-variations)
15. [Dashboard and Activity](#15-dashboard-and-activity)
16. [Saved Group Lists](#16-saved-group-lists)
17. [Posting as a Page](#17-posting-as-a-page)
18. [Safety Break](#18-safety-break)
19. [Smart Failure Handling](#19-smart-failure-handling)
20. [Plans and Locked Features](#20-plans-and-locked-features)
21. [Backup and Transfer](#21-backup-and-transfer)
22. [Updating FAP](#22-updating-fap)
23. [Safety Tips and Best Practices](#23-safety-tips-and-best-practices)
24. [Troubleshooting](#24-troubleshooting)

---

## 1. Installation

### Step 1: Download the Extension

Download the latest version from the official page — [tools.tigerzplace.com/facebook-auto-poster](https://tools.tigerzplace.com/facebook-auto-poster/) (or from this repository's Releases) — and extract it to a folder you will keep (don't delete or move it later; Chrome loads the extension from that folder).

> 📺 **Video:** Prefer to follow along visually? The [tutorial on YouTube](https://www.youtube.com/watch?v=hlqqBId04GI) walks through installation from scratch at the start of the video.

### Step 2: Open Chrome Extensions Page

Navigate to `chrome://extensions` in your Chrome browser.

```
📸 Screenshot: Chrome address bar showing chrome://extensions
```

### Step 3: Enable Developer Mode

Toggle the **Developer mode** switch in the top-right corner of the extensions page.

```
📸 Screenshot: Developer mode toggle in ON position
```

### Step 4: Load the Extension

Click **"Load unpacked"** and select the FAP extension folder (the one containing `manifest.json`).

```
📸 Screenshot: Load unpacked button highlighted, folder selection dialog
```

### Step 5: Verify Installation

You should see "Facebook Auto Poster" appear in your extensions list with the FAP icon. Pin it to your toolbar for easy access.

```
📸 Screenshot: FAP extension card in chrome://extensions showing version 2.3.0
📸 Screenshot: FAP icon pinned in Chrome toolbar
```

---

## 2. First Launch and Finding Your Way Around

### Step 1: Log into Facebook

Make sure you're logged into your Facebook account in the same Chrome profile where FAP is installed.

### Step 2: Click the FAP Icon

Click the FAP icon in your Chrome toolbar. The extension will:
1. Close the popup
2. Replace your current tab with FAP

```
📸 Screenshot: FAP icon in toolbar
📸 Screenshot: FAP Dashboard after loading
```

### Step 3: License Activation

FAP opens on the free plan with core features unlocked. To unlock more groups, photo posts and other plan features, pick a plan on the [pricing page](https://tools.tigerzplace.com/pricing/), then follow the steps to [activate your license](https://tools.tigerzplace.com/activate/?tool=fap&tier=pro). See [Plans and Locked Features](#20-plans-and-locked-features) for what each plan includes.

If your license has not been activated on this computer yet, FAP shows a full-page **Activate FAP** screen with three choices: start free, enter a key you already have, or buy a plan. After you activate, press **I've activated, check again**.

> Need a walkthrough of buying and activating? See the [licensing guide](https://tigerzplace.com/how-to-buy-tool-license/) on the blog.

### Step 4: Learn the Layout

FAP has six pages in the dark sidebar on the left:

| Page | What it is for |
|---|---|
| **Dashboard** | Your numbers for today, the live run monitor, the live log and a short Get started list |
| **Campaigns** | Your saved campaigns. Create, open, duplicate, import and export them here |
| **Groups** | Every group you have joined, your saved group lists, and details for one group at a time |
| **Activity** | The posting log with filters and CSV export |
| **Insights** | Reserved for a later release |
| **Settings** | License and plan, Backup and transfer, Preferences, Notifications, Updates and help |

At the bottom of the sidebar the **plan card** shows your plan, whether it is active, when it renews, and two meters: groups in the current campaign and post variations. Use **Manage plan** or **Upgrade** there to change plans.

The **top bar** is on every page. It holds the **run capsule** (the run's status and its Start posting, Pause and Stop buttons), the **License** button, the bell for notifications and a chip that shows which Facebook account FAP is posting as.

Banners appear under the top bar when something needs attention, for example a license that is about to end, an expired license or a new version. Only the most important one shows at a time.

You can switch between a light and a dark theme in **Settings → Preferences**. **System** follows your computer.

```
📸 Screenshot: Sidebar with the six pages and the plan card; top bar with the run capsule
```

---

## 3. Loading Your Groups

### Step 1: Open Groups and Press "Reload from Facebook"

Open the **Groups** page and press **Reload from Facebook**. FAP fetches all Facebook groups you have joined. Groups are saved in this browser, separately for each Facebook account, so next time they are already there.

```
📸 Screenshot: Groups page with the Reload from Facebook button
```

### Step 2: Wait for Groups to Load

This may take a few seconds depending on how many groups you are in. The Groups table shows "Loading your groups…" until the list arrives.

### Step 3: Browse Your Groups

The **All groups** tab is a searchable table. Each row shows:
- The group's **profile picture** and **name**, with its privacy (Public or Private)
- **Members**
- **Last visited** (for example *Today*, *1w ago*, *2mo ago*). Click the header to sort groups by most recently visited
- **Status**, which tells you if you have had a post waiting for approval in that group

Use the filter chips above the table (for example **Visited this week**) and the search box to narrow the list.

### Step 4: See Details for One Group

Click a row and the **Group details** panel on the right shows the picture, a link that opens the group on Facebook, members, privacy, last visited and how many posts you have made there today. **Refresh** reads that one group again from Facebook. **Add to list** puts the group in a saved list.

```
📸 Screenshot: Groups table with filter chips and the Group details panel
```

---

## 4. Choosing Groups for a Campaign

You choose groups inside a campaign, in the **Audience** step (step 2 of the campaign editor). Groups load **unselected**: you decide where to post.

1. Open **Campaigns → New campaign** (or open a saved campaign) and go to **Audience**.
2. Pick a source: **All joined groups** or one of your saved lists.
3. Tick the groups you want. Use **Select shown** to tick everything that matches your search or filter, and **Clear** to untick all.
4. Watch the meter, for example *12 of 500 groups selected*. It turns red if you pick more than your plan allows.
5. Press **Save as list** to keep this selection for later.

The **Reload** button next to the source refreshes groups from Facebook. Under the table, **Show more** loads the next batch of rows.

At the bottom of the step, the switch **Skip a group for the rest of the run when a post goes to pending** is on by default. It saves posts for groups that need admin approval.

```
📸 Screenshot: Audience step with the selection meter, filter chips and the group table
```

---

## 5. Writing Your Post

Open **Campaigns → New campaign**. A campaign has four steps, shown at the top: **Write**, **Audience**, **Timing and safety** and **Review and launch**. Each step shows a short summary under its name, and the **Back** and **Next** buttons at the bottom move between steps. You can click any step name to jump to it.

### Write Your Message

In **Write**, click a variation card, then type your post in the text box. You can include regular text, emojis, links and hashtags. The counter under the box shows characters and hashtags.

### Name Your Campaign

Type a name at the top of the page, next to the **Draft** label. A name is needed to save the campaign.

### Preview

The **Preview** panel on the right shows how the post will look in a group, including the photo or link preview. The **This run** panel under it summarises groups, variations, delay, safety breaks, total time and the time the run finishes.

### Character Support

FAP supports full Unicode — emojis, special characters, and non-English text all work correctly.

```
📸 Screenshot: Write step with the variation cards, the text box and the Preview panel
```

---

## 6. Adding Photos

> **Plan note:** Photo posts are available on the **Basic** plan and above. On the free plan the Photos card shows which plan unlocks it — see [Plans and Locked Features](#20-plans-and-locked-features).

### Step 1: Choose "Photos"

In the **Photos** card of the Write step, switch from **Text only** to **Photos**.

### Step 2: Pick a Photo

Click the drop zone to browse, or drag a photo onto it. JPG, PNG, GIF and WEBP work, up to 10 MB. One photo per campaign for now; every variation shares it.

```
📸 Screenshot: Photos card with the drop zone
```

### Step 3: Preview or Remove

The photo appears in the media tray and in the Preview panel. Use the remove button on the photo, or switch back to **Text only**, to post without it.

> **Note:** A photo replaces the link preview for every variation in the run.

---

## 7. Link Previews

When your post contains a URL, FAP shows a **link row** under the text box.

### Step 1: Write a Post with a URL

Include a link in your post text. The link row appears.

### Step 2: Select Which Link to Preview

If the post has several URLs, choose one from the list in the row.

### Step 3: Turn On the Preview and Fetch It

Switch on **Show link preview**, then press **Get Preview**. FAP loads the title, description and picture from Facebook, and the Preview panel shows the card.

### Step 4: Clear (Optional)

Press **Clear** to post without a preview.

> **Note:** Link previews are saved with the campaign. Opening the campaign later restores the preview without fetching it again.

```
📸 Screenshot: Link row with the switch, the Get Preview button and the preview card
```

---

## 8. Delay Between Posts

The delay is the wait between one group post and the next. It is the most important safety setting. Set it in **Timing and safety** (step 3).

### Random Range or Fixed

At the top of the **Delay between posts** card choose **Random range** (FAP waits a random time inside a range before each post) or **Fixed** (always the same wait). A random range looks more natural to Facebook.

### Range Slider and Presets

Drag the two handles, or use the quick buttons: 1–20 s, 20–60 s, 1–3 min, 3–20 min, 20–30 min and 30–60 min. Choose **Custom** to type exact minutes (from 1 to 180, with at most 120 minutes between the two numbers).

```
📸 Screenshot: Delay card with the range slider and preset buttons
```

### Suggested Delay

When you have groups selected, FAP suggests a delay for your group count. The suggestion appears in a note under the slider with a **Use** button when your range is shorter than half of the suggestion.

### Delay Warning

If you press Start with a delay that is too short for your group count, a warning window shows your delay next to the recommended one, with **Apply Safe Delay** and **Post Anyway**.

### Recommended Delay Tiers

| Groups Count | Recommended Delay |
|---|---|
| Under 20 | 20–60 Seconds |
| 20–50 | 1–3 Minutes |
| 50–300 | 3–20 Minutes |
| 300–500 | 20–30 Minutes |
| 500–1,000 | 30–60 Minutes |
| 1,000+ | Custom 45–60 Minutes |

Treat the table as a safe starting point; longer is always safer.

---

## 9. Starting a Campaign

### Step 1: Open "Review and launch"

The last step lists what is ready (post text, groups, delay, safety break, photos, license) and what needs attention. Each line that needs attention has a button that takes you to the right step. The top of the card shows **Ready** or **Needs attention**.

The **Plan check** card shows whether your plan allows this run, the same answer you get when you press Start.

The **Posting timeline** shows when each post will go out; safety breaks are the hatched sections.

### Step 2: Send a Test Post (Optional)

Pick one group and press **Send test post**. FAP posts variation 1 to that group so you can check the text, photo and link preview. It is a normal post.

### Step 3: Press "Start posting"

Press **Start posting** in the Review card, or in the top bar. The first post goes out immediately; delays only apply between posts.

```
📸 Screenshot: Review and launch with the readiness list, plan check and timeline
```

### Step 4: Watch the Run

While posting, the **run capsule** in the top bar shows *Posting*, how many groups are done and the time until the next post. The **Dashboard** shows the same run in more detail: a coloured progress bar, counters for Posted, Pending, Failed and Skipped, the group and variation going out next, and a live log of the last few events.

```
📸 Screenshot: Run capsule in the top bar and the run monitor on the Dashboard
```

---

## 10. Pause, Resume and Stop

### Pause

During a run press **Pause** in the top bar. The post in progress finishes, then the run holds.

### Resume

Press **Resume** (the same button) to continue from where you stopped.

### Stop

Press **Stop**. FAP asks you to confirm and tells you how many groups have not been posted to yet. Choose **Keep posting** or **Stop run**. After a stop the capsule shows *Stopped* with what was posted.

> **Tip:** Pausing is useful if you want to wait for better engagement hours or need to step away temporarily.

---

## 11. When a Run Finishes

When a run ends, the capsule shows *Finished* with the posted, pending and failed counts, and the Dashboard's run monitor changes to **Run finished**. It shows when the run started, how long it took, and the totals:

- **Posted**
- **Pending approval** (the group's admins need to approve your post)
- **Failed**
- **Skipped**

Pending posts are counted as pending, not as failed: the post is not lost. Open **Activity** to see every group with a **View post** link.

```
📸 Screenshot: Run finished state on the Dashboard
```

---

## 12. Saving and Opening Campaigns

Campaigns save your complete setup so you can reuse it later. They are stored in this browser, separately for each Facebook account.

### Save a Campaign

1. Set up the campaign: name, variations, groups, timing and safety
2. Press **Save** at the top of the editor. The status next to the name changes from **Draft** to **Saved**

### The Campaigns Library

The **Campaigns** page lists your saved campaigns with their variations, media, groups, last update and the actions **Run**, **Open**, **Export**, **Duplicate** and **Delete**. Deleting asks you to confirm first.

- **New campaign** starts a blank one
- **Import** opens a backup file (see [Backup and Transfer](#21-backup-and-transfer))
- If you leave the editor with unsaved work, an **Open in the editor** card on the Campaigns page takes you back so nothing is lost

### Open a Campaign

Press **Open** on a row. FAP restores the name, the variations, the groups, the link previews and every timing and safety setting. Go to **Review and launch** and press **Start posting**.

If a campaign was saved on a bigger plan than you have now, it still opens, but the extra variations and groups are not used, and a notice tells you.

### Duplicate

**Duplicate** makes a copy that you can change without touching the original.

### Without Saving

On the free plan saving is locked. You can still create a campaign and run it; it stays until you close FAP.

```
📸 Screenshot: Campaigns library with the row actions
```

---

## 13. Scheduling Posts

Schedule posts to be published at a specific future date and time. Scheduling is in **Timing and safety**, in the **When posts appear** card.

### Step 1: Choose "Schedule"

Switch from **Right away** to **Schedule**.

### Step 2: Set the Date and Time

Pick a date and a time. FAP uses your computer's time zone. The time must be at least 35 minutes from now.

### Step 3: Start the Campaign

FAP sends the posts to Facebook now, and Facebook publishes each of them at the time you picked.

> **Note:** Scheduling is not available when you post as a Page.

Switch back to **Right away** to post immediately again.

---

## 14. Post Variations

A campaign can hold several different posts. FAP gives each group one variation, picked at random. Different wording lowers the chance of spam flags.

### How It Works

1. In **Write**, press **Add variation** (V2, V3 …)
2. Write each one. Click a card to edit it; **Remove** deletes the one you are editing
3. A meter shows how many your plan allows, for example *3 of 10 variations used*

```
📸 Screenshot: Variation cards V1 to V3 with the meter
```

### Why Use This

- Avoids posting identical content to every group (reduces spam detection risk)
- Lets you tailor messages for different audiences
- Each variation can have its own link preview

---

## 15. Dashboard and Activity

### Dashboard

The Dashboard shows:
- **Posted today**, **Pending approval**, the **Success rate** for the last 7 days and your lifetime posts
- The **run monitor** for the current or last run
- The **live log** with the last events
- A **Get started** list that ticks itself as you load groups, save a campaign, send a test post and export a backup. It disappears when it is done

### Activity

**Activity → Log** lists every group posted to in this session. Use the chips (**All**, **Posted**, **Pending**, **Failed**, **Skipped**, **Breaks**) to filter. Each row has the time, the status, the group, the variation, a short detail and a **View post** link. **Export CSV** saves the log as a file; **Clear** empties it.

```
📸 Screenshot: Activity log with the status chips
```

---

## 16. Saved Group Lists

Save frequently-used group selections for quick access.

### Save a Group List

1. In a campaign's **Audience** step, select your groups
2. Press **Save as list** and give it a name (for example "Marketing Groups" or "Local Buy/Sell")

You can also save a list from the **Groups** page, using **Add to list** in the group details.

### Use a Group List

Open **Groups → Saved lists**. Each list shows its name, how many groups it has and when it was updated. **Use in campaign** opens a campaign with that list ready in the Audience step.

### Rename, Export or Delete

Each list has **Rename**, **Export** and **Delete**. Import a list from a file with **Import list**.

```
📸 Screenshot: Saved lists tab
```

---

## 17. Posting as a Page

FAP automatically detects whether you're logged in as a personal profile or a Facebook Page.

### How It Works

1. Log into Facebook as your Page (switch to Page mode in Facebook)
2. Launch FAP
3. FAP detects your Page identity and posts on behalf of the Page

```
📸 Screenshot: Top bar chip showing the Page name and avatar
```

### User vs Page Indicators

The top bar shows the name and picture of the account FAP is posting as, so you always know which one is posting.

---

## 18. Safety Break

A Safety Break automatically pauses your campaign after a set number of posts, then resumes by itself — like taking a breather during a long run.

### Turn It On

In **Timing and safety**, open the **Safety break** card and switch it on. Choose:

| Setting | Presets | Default |
|---|---|---|
| Take a break after every… | 10 / 15 / 25 / 40 posts, or a custom number | 25 posts |
| Each break lasts | 2 / 5 / 10 / 15 minutes, or custom minutes | 5 minutes |

A line and a strip under the settings show how many breaks the run will have and where they fall (one mark per post).

### While a Break Runs

- The run capsule shows the safety break and when it resumes
- The break **replaces** the normal wait before the next post (you don't wait twice)
- The log notes when the break starts and when it ends
- When the break finishes, posting resumes automatically from the next group

> **Tip:** For campaigns of 100+ groups, a Safety Break (for example every 25 posts for 5 minutes) is an easy way to make the run look more natural.

---

## 19. Smart Failure Handling

FAP reads the reason behind each failed post and responds accordingly instead of failing blindly:

| What happened | What FAP does |
|---|---|
| Temporary hiccup or empty reply | Waits a few seconds and retries once |
| Your Facebook session needs refreshing | Refreshes automatically and retries |
| Group no longer accessible, or you can't post there | Skips it for the rest of the run |
| Post is waiting for admin approval | Counts it as **pending** and skips that group for the rest of the run |
| Facebook is rate-limiting you | Shows a warning and carries on — consider longer delays |
| Facebook blocks the account or asks for verification | Stops the campaign and tells you why |

### Auto-Pause After Repeated Failures

If **5 posts fail in a row**, FAP pauses the campaign automatically so you can check what's wrong (your login, your delay, the content) before continuing. The **Automatic protection** card in Timing and safety shows this is always on. Press **Resume** when you're ready.

---

## 20. Plans and Locked Features

FAP comes in four plans: **Freemium, Basic, Pro and Advance**. Core posting and the group list features (profile pictures, Last visited and sorting) are available on every plan. Some capabilities — such as the number of groups per campaign, photo posts, and scheduling — depend on your plan.

- When a feature is locked, its card tells you **which plan unlocks it** and has a **See plans** button
- **Settings → License and plan** lists everything your plan includes, your license ID and the dates, and has a **Check license** button that reads your license fresh from the server (you can use it once every 30 seconds)
- If your license has ended, FAP switches to **read-only**: you can look at your campaigns, groups and settings, and export a backup, but you cannot start or save
- See what each plan includes on the [pricing page](https://tools.tigerzplace.com/pricing/)
- Already purchased? [Activate your license](https://tools.tigerzplace.com/activate/?tool=fap&tier=pro) and press **Check license** — your plan updates automatically
- Questions about billing? See the [refund policy](https://tools.tigerzplace.com/refund/) or [contact us](https://tools.tigerzplace.com/contact/)

---

## 21. Backup and Transfer

Your campaigns, group lists and preferences live in this browser. A backup file lets you keep a copy, or move them to another computer or browser. Backup and transfer is free on every plan.

### Export

1. Open **Settings → Backup and transfer** and press **Export a backup**
2. Tick what you want: campaigns, group lists, preferences
3. Save the file. It is named like `fap-backup-2026-11-01.fap.json`

To export just one item, use **Export** on a campaign row (or in the editor), or on a saved list in **Groups → Saved lists**.

A backup file never contains your Facebook login, your license or any password. Photos are saved as file names only, unless you tick **Include photos** and the original files are still on this computer.

### Import

1. On the other computer or browser, install FAP and open **Settings → Backup and transfer**
2. Press **Import**, then choose the file or drop it on the box
3. FAP shows a preview of every item and what will happen to it:

| Label | Meaning |
|---|---|
| **New** | Nothing like it here yet; it will be added |
| **Already exists** | You have one with the same name. Choose **Keep both** (the new one is called "name (imported)"), **Replace mine** or **Skip** |
| **Over your plan** | It has more variations than your plan allows. It is imported in full and opens with the extra ones switched off, with a notice |
| **Check groups** | Some groups in a list are not in your current joined groups. They are kept and marked |

When you choose **Replace mine**, FAP first keeps a copy of what you had, so nothing is lost by accident.

Campaigns need a plan that includes saving campaigns. Group lists and preferences can be imported on every plan.

> **Tip:** Export a backup now and then, and before you reinstall Chrome or change computers. The Dashboard's **Get started** list reminds you.

```
📸 Screenshot: Settings → Backup and transfer, and the import preview
```

---

## 22. Updating FAP

1. Download the latest version from [tools.tigerzplace.com/facebook-auto-poster](https://tools.tigerzplace.com/facebook-auto-poster/)
2. **Replace all files** in your existing FAP folder with the new ones — don't mix old and new files
3. Go to `chrome://extensions` and click **Reload** on FAP

Keep using the **same folder** — your license stays linked to it. Your campaigns, group lists and settings are kept. **Settings → Updates and help** shows your version and the latest one.

---

## 23. Safety Tips and Best Practices

### Do's ✅

- **Trust the suggested delay** — it is calculated from your group count against a tiered risk curve
- **Use range delays** over fixed delays for more natural timing
- **Start small** — send a test post, then run 5–10 groups before scaling up
- **Watch the run capsule and the live log** — consecutive failures are an early warning sign (FAP auto-pauses after 5 in a row)
- **Use a Safety Break** on long runs — see [Safety Break](#18-safety-break)
- **Use variations** to rotate content and reduce detection risk
- **Save campaigns and export a backup** — reuse proven setups instead of rebuilding each time

### Don'ts ❌

- **Don't ignore the delay warning** — click "Apply Safe Delay" unless you have a specific reason
- **Don't post identical content** to hundreds of groups back to back
- **Don't run FAP 24/7** — take breaks between campaigns
- **Don't share your license** — it's tied to your FAP installation

### If You Get Restricted

1. Stop posting immediately
2. Wait 24–48 hours before trying again
3. When you resume, use longer delays and fewer groups
4. Rotate your post content more aggressively

---

## 24. Troubleshooting

### FAP won't load / shows blank page

- Make sure you're logged into Facebook in the same browser profile
- Try refreshing the page or relaunching FAP
- Check `chrome://extensions` for any error messages on the FAP card

### "Login check failed" error

- Your Facebook session may have expired
- Go to facebook.com, confirm you're logged in
- Relaunch FAP

### Groups not loading

- Facebook may have updated their page structure — check if you can access `facebook.com/groups` normally
- Try logging out and back into Facebook
- Press **Reload from Facebook** on the Groups page, or reload the extension from `chrome://extensions`

### Posts failing

- Check **Activity → Log** for specific error messages
- Your `session` token may have expired — relaunch FAP to refresh tokens
- Facebook may be rate-limiting you — increase the delay
- Some groups may have posting restrictions or require admin approval — those show up as **pending** or are skipped automatically
- If 5 posts fail in a row FAP pauses on its own — check the log, fix the cause, then Resume

### The delay warning keeps appearing

- This means your selected delay is too short for your group count
- Click **"Apply Safe Delay"** to let FAP set the recommended tier automatically

### Run finished with 0 posted

- Check **Activity → Log** for errors — `session` expiry and rate-limiting are the most common causes
- Relaunch FAP and try with a smaller group selection first

### Extension shows wrong version

- Go to `chrome://extensions` and click the refresh icon on FAP
- If you updated by copying files, make sure you replaced **all** files in the same folder (see [Updating FAP](#22-updating-fap))

### A feature shows as locked

- The card tells you which plan unlocks it — see [Plans and Locked Features](#20-plans-and-locked-features)
- Just bought or upgraded? [Activate your license](https://tools.tigerzplace.com/activate/?tool=fap&tier=pro), press **Check license** in Settings, then reload FAP if needed

### "Start posting" is greyed out

- A red banner under the top bar says why: license ended, or an update is required
- Fix that (renew, or download the update) and press **Check license**

### My campaigns are not where I expect

- Campaigns and group lists are saved separately for each Facebook account in this browser. Make sure you are logged in as the same account
- To move them to another computer, use [Backup and Transfer](#21-backup-and-transfer)

### "Check your connection" card instead of the Dashboard

- FAP couldn't reach the license service — check your internet connection (and any VPN/firewall) and reload FAP; your plan isn't affected

### FAP closes on launch or says the installation is corrupted

- The FAP files may be incomplete or a mix of two versions
- Download a fresh copy from [tools.tigerzplace.com/facebook-auto-poster](https://tools.tigerzplace.com/facebook-auto-poster/), replace **all** files in your FAP folder (don't edit any file), then click **Reload** on `chrome://extensions`

### Need more help?

- Browse the [FAP documentation](https://tools.tigerzplace.com/docs/) and the [tool page](https://tools.tigerzplace.com/facebook-auto-poster/)
- Read the full step-by-step guide on the blog: [How to post in multiple Facebook groups](https://tigerzplace.com/how-to-post-in-multiple-facebook-groups/)
- Reach support via the [contact page](https://tools.tigerzplace.com/contact/) or the [Tigerzplace Facebook page](https://www.facebook.com/tigerzplace)
- Policies: [Refund](https://tools.tigerzplace.com/refund/) · [Terms](https://tools.tigerzplace.com/terms/) · [Privacy](https://tools.tigerzplace.com/privacy/)
