# Facebook Auto Poster (FAP) – Post to Multiple Facebook Groups in One Go

Facebook Auto Poster (FAP) is a Chrome extension that helps you post to **multiple Facebook groups** in a safe, controlled, and time-saving way.

Instead of copy-paste spam or risky bots, FAP keeps you in control: you choose the groups, write the post once, configure safe wait times, and let the tool handle the rest while you watch detailed logs.

👉 **Tool page & full overview:** [tools.tigerzplace.com/facebook-auto-poster/](https://tools.tigerzplace.com/facebook-auto-poster/)  
💳 **Plans & pricing:** [tools.tigerzplace.com/pricing/](https://tools.tigerzplace.com/pricing/)  
📖 **Documentation:** [tools.tigerzplace.com/docs/](https://tools.tigerzplace.com/docs/)

📺 **Prefer video?** Watch the complete v2.0 walkthrough:  
👉 [FAP v2.0 — Full Tutorial on YouTube](https://www.youtube.com/watch?v=hlqqBId04GI)

---

---

## ✨ Key Features

- **Post to Multiple Groups at Once**  
  Load your joined groups and send a single post to many groups automatically. The first post starts immediately — no pre-delay.  
  → [How to post in multiple Facebook groups at once (safely)](https://tigerzplace.com/how-to-post-in-multiple-facebook-groups-at-once-safely/)

- **Image Posting**  
  Attach a photo to any post. FAP handles the full upload pipeline automatically — drag and drop or click to browse, see a live upload progress bar and preview card, and the image is attached to every group post in the campaign. Supports JPEG, PNG, and WebP.

- **Dual-Handle Delay Slider with Presets**  
  Configure your wait time using a visual range slider. Drag the min/max handles to set a delay window, or click a preset button (1–3 min, 3–20 min, 20–30 min, etc.) to apply it instantly. Custom minute values can also be entered directly.

- **Smart Delay Recommendation & Warning**  
  FAP analyses your group count and recommends the safest delay tier. If you start with a delay that is too short for your group count, a blocking warning modal appears showing your risky setting, the recommended safe alternative, and two choices: **Apply Safe Delay** or **Post Anyway**.

- **Live Post Counter Strip**  
  A persistent strip visible on the dashboard during posting shows current post index, total groups, live success/fail counts, name of the last posted group, and a countdown timer to the next post.

- **Estimated Run Time Banner**  
  Before posting starts, a banner shows the expected total campaign duration based on your group count and delay. Includes an **ℹ️ popover** showing how much manual clicking effort FAP is saving you. A **risk pill** appears inline if your combo is flagged.

- **Post-Run Summary Modal**  
  After every campaign completes, a modal shows total posts, success count, fail count, an animated success-rate bar, and a scrollable list of up to 15 direct post links.

- **Retry on Failure**  
  If a post fails due to a transient Facebook error, FAP automatically retries once after 8 seconds before marking the group as failed. For image posts, a fresh upload is triggered before the retry.

- **Pause / Resume Campaigns**  
  Pause an active campaign at any time. The current post finishes, then the loop holds until you resume.

- **Post URL Display in Logs**  
  After each successful post, FAP shows the **direct Facebook post URL** in the event log so you can quickly open, verify, or share it.

- **Post Scheduling**  
  Schedule posts to be published at a specific future date and time. FAP submits the post to Facebook's scheduling system; Facebook publishes it at your chosen time.  
  → [How to schedule posts to Facebook groups automatically](https://tigerzplace.com/schedule-posts-to-facebook-groups/)

- **Save & Load Campaigns**  
  Save your full setup (groups, messages, link previews, delay settings) as named campaigns. Load them in one click — perfect for recurring promotions and weekly routines.

- **Manual Link Preview (Multi-Link Support)**  
  If your post contains one or more links, choose which one to use for the Facebook-style preview card. Preview data is fetched on demand, reused during posting, and saved with campaigns.

- **Multiple Posts Feature**  
  Write multiple post variations. FAP cycles through them across groups — Post 1 → Group 1, Post 2 → Group 2, etc. — reducing detection risk from identical content.

- **Saved Group Lists**  
  Save sets of groups (e.g., "Marketing Groups", "Local Buy/Sell") as named lists. Dropdowns show the group count next to each list name.

- **Single Instance Protection**  
  Prevents multiple extension windows from conflicting. If FAP is opened again, the previous instance is automatically closed.

- **Group Intelligence**  
  See each group's profile picture and last-visited time right in the table. Sort by recently visited to target your most active groups first. Groups that already have a post of yours waiting for admin approval are skipped for the rest of the session, and pending posts get their own count in the summary.

- **Safety Break**  
  Pause automatically after every N posts for a set duration (for example, every 25 posts for 5 minutes). A live countdown appears in the counter strip and posting resumes on its own.

- **Smart Failure Handling**  
  FAP reads why a post failed. Groups you can't post to are skipped for the session, five failures in a row auto-pause the campaign, and serious Facebook warning signals stop the run so you don't keep posting into a restricted state. If your Facebook session expires mid-run, FAP refreshes it and retries automatically.

---

## 🧩 How It Works (High-Level)

1. **Load Groups** — FAP reads your joined Facebook groups and displays them in a searchable table with pictures and last-visited times.
2. **Select Groups** — Choose specific groups or load a saved group list / campaign.
3. **Compose Your Post** — Write your message. Optionally attach an image or set a link preview.
4. **Configure Delay** — Use the slider or presets to set your delay range. FAP recommends the safest tier for your group count.
5. **Start Campaign** — Click **Start**. FAP posts to each group one by one. The first post begins immediately.
6. **Monitor Live** — Watch the counter strip, event log, and progress bar in real time.
7. **Review Summary** — When posting completes, a summary modal shows your results and all post links.

---

## 🚀 Quick Start

1. **Install the Extension**
   - Download the latest version from [tools.tigerzplace.com/facebook-auto-poster/](https://tools.tigerzplace.com/facebook-auto-poster/) (or clone this repository).
   - In Chrome, go to `chrome://extensions`.
   - Enable **Developer mode**.
   - Click **Load unpacked** and select the folder containing `manifest.json`.

2. **Open Facebook in Your Browser**
   - Log in to your Facebook account in the same Chrome profile.

3. **Launch FAP**
   - Click the FAP extension icon. The current tab becomes the FAP dashboard.

4. **Load Groups**
   - Click **Load Groups** to fetch all your joined groups.

5. **Set Up Your Campaign**
   - Select groups (or load a saved list / campaign).
   - Write your post. Optionally attach an image.
   - Set your delay using the slider — or accept the smart recommendation.

6. **Start Posting**
   - Press **Start**. Watch the live counter strip, event log, and progress bar.

7. **Review Results**
   - The post-run summary modal shows your success rate and all post links.

**Updating FAP:** replace all files in your FAP folder with the new version (don't mix old and new files), then click **Reload** on `chrome://extensions`. Your campaigns, group lists, and settings are preserved.

---

## 🧠 Best Practices & Safety Tips

- Use the **smart delay recommendation** — it accounts for your group count.
- **Range delays** are better than fixed — they look more natural to Facebook.
- Use the **Multiple Posts** feature to rotate content across groups.
- Watch the **live counter strip** for consecutive failures — that's an early warning of rate-limiting.
- Start small: test with 5–10 groups before scaling up.
- Enable **Safety Break** on large campaigns so FAP pauses automatically every N posts.
- Take breaks between large campaigns.

> Worried about getting restricted? Read the full safety guide:  
> → [Is Facebook auto posting safe? Avoid bans & account restrictions](https://tigerzplace.com/is-facebook-auto-posting-safe/)  
> → [Facebook posting limits 2026](https://tigerzplace.com/facebook-posting-limits-2026/)

---

## 🆕 What's New in v2.1 & v2.2

**Group Profile Pictures** — Groups load with their avatars so you can recognise them at a glance.

**Last Visited & Sorting** — Each group shows when you last visited it. Click the Visited column header to bring your most active groups to the top. Visited times are saved with your saved group lists.

**Skip Pending-Approval Groups** — Groups that already have a post of yours awaiting admin approval are skipped for the rest of the session, and pending posts are counted in the summary and live strip.

**Cleaner Group Table** — Rebuilt with consistent columns, circular avatars, and custom checkboxes.

**Safety Break** — Optional automatic pause after every N posts, with a live countdown.

**Smarter Failure Handling** — Inaccessible groups are skipped, repeated failures auto-pause the campaign, and serious Facebook signals stop the run cleanly. Expired sessions are refreshed automatically.

**Clearer Plan Labels** — Locked features show the exact plan that unlocks them. Group pictures and visited times are free on every plan.

---

## Earlier Highlights — v2.0

**Image Posting** — Attach photos to any post via drag-and-drop or file picker. Full upload pipeline with live progress, preview card, and auto-retry support.

**Dual-Handle Delay Slider** — Replaced dropdown selects with a visual range slider. Preset buttons for common tiers plus custom minute input.

**Smart Delay Recommendation & Warning Modal** — FAP recommends the safest delay tier for your group count. A blocking modal warns you before posting with a risky setting, with a one-click option to apply the safe alternative.

**Live Post Counter Strip** — Persistent real-time strip during posting showing position, success/fail counts, last group posted, and next-post countdown.

**Estimated Run Time Banner** — Pre-posting banner with estimated duration, effort-saved popover, and inline risk pill.

**Post-Run Summary Modal** — Auto-shown after campaign completion with animated success-rate bar and scrollable post link list.

**Retry on Failure** — Automatic single retry after 8 seconds on transient failures, with fresh photo upload on retry for image posts.

**Group List Count Labels** — Saved group list dropdowns now show the group count next to each list name.

**Double-Count Fix** — Fixed a bug where "All" groups + a saved list could cause duplicate posts.

**First Post Starts Immediately** — No pre-delay before the first post; wait time applies only between subsequent posts.

**Progress Bar Percentage Label** — Label tracks the bar fill at all stages and clears on reset.

See [What's New](docs/WHAT%27S_NEW.md) for the full release history.

---

## 📚 Guides & Resources

Full documentation and tutorials are published on Tigerzplace:

| Guide | Description |
|---|---|
| [▶ FAP v2.0 — Complete Video Tutorial](https://www.youtube.com/watch?v=hlqqBId04GI) | Full walkthrough of all v2.0 features — installation to posting |
| [Facebook Auto Poster — Complete 2026 Guide](https://tigerzplace.com/facebook-auto-poster/) | Pillar guide covering all features, use cases, and setup |
| [How to Post in Multiple Facebook Groups at Once](https://tigerzplace.com/how-to-post-in-multiple-facebook-groups-at-once-safely/) | Step-by-step tutorial for bulk group posting safely |
| [How to Schedule Posts to Facebook Groups](https://tigerzplace.com/schedule-posts-to-facebook-groups/) | Scheduling feature walkthrough (v1.9+) |
| [Is Facebook Auto Posting Safe?](https://tigerzplace.com/is-facebook-auto-posting-safe/) | Safety guide — avoid bans, restrictions, and rate limits |
| [Facebook Posting Limits 2026](https://tigerzplace.com/facebook-posting-limits-2026/) | Current Facebook group posting rules and limits |
| [Free Facebook Auto Poster Tools](https://tigerzplace.com/free-facebook-auto-poster/) | Overview of free options and when to upgrade |
| [FAP vs Manual Posting](https://tigerzplace.com/facebook-auto-poster-vs-manual-posting/) | Time savings, ROI, and comparison breakdown |
| [FAP Documentation](https://tools.tigerzplace.com/docs/) | Official documentation hub on the Tigerzplace tools site |
| [Plans & Pricing](https://tools.tigerzplace.com/pricing/) | Compare Freemium, Basic, Pro, and Advance |

---

## 📥 Licensing & Support

- Licenses are available at **tools.tigerzplace.com**  
  👉 **[View plans & pricing](https://tools.tigerzplace.com/pricing/)**
- After purchase, [activate your license](https://tools.tigerzplace.com/activate/?tool=fap&tier=pro) — keep your **extension ID** handy.
- Feature availability depends on your plan (Freemium, Basic, Pro, Advance — see [Plans & Pricing](https://tools.tigerzplace.com/pricing/)). Locked features show which plan unlocks them.
- For support, bug reports, or feature requests:
  - Contact via the [Tigerzplace contact page](https://tools.tigerzplace.com/contact/)
  - Comment on the relevant Tigerzplace blog post
  - Open an issue on GitHub
- Policies and information: [Documentation](https://tools.tigerzplace.com/docs/) · [About](https://tools.tigerzplace.com/about/) · [Refund Policy](https://tools.tigerzplace.com/refund/) · [Terms](https://tools.tigerzplace.com/terms/) · [Privacy](https://tools.tigerzplace.com/privacy/)

---

## ⚖️ Disclaimer

This tool is intended for **legitimate use only**:
- Respect Facebook's Terms of Service.
- Do not use FAP for spam, abuse, or any illegal/unauthorized activities.
- You are solely responsible for how you use the tool and for any consequences related to your Facebook account(s).
- Use of FAP is subject to the [Terms](https://tools.tigerzplace.com/terms/) and [Privacy Policy](https://tools.tigerzplace.com/privacy/).

---

Made with ❤️ by **Tigerzplace**