**Lead Sniper 3.11 finds every request for your services in your Facebook groups — 30 local services, from moving and cleaning to roofing, tutoring and childcare — in English and Québec French, and has a personal reply ready in one click.** With Pro, it replies for you.

### Install (2 minutes)
1. Download **lead-sniper.zip** below and double-click it. You get a folder called **lead-sniper** (the files are right inside it — there's no other folder to look for). Move it somewhere permanent, like Documents.
2. Open `brave://extensions` (or `chrome://extensions`), turn on **Developer mode**, click **Load unpacked** and pick the **lead-sniper** folder.
3. On the welcome screen, enter your business name and your group links, then scroll Facebook.

### Updating
Download the new **lead-sniper.zip**, double-click it, and copy everything inside the new **lead-sniper** folder over the files in your old one (the folder shown under *Lead Sniper → Details → Loaded from* at `brave://extensions`). Then just open the Lead Sniper dashboard: it notices the new version and updates itself — no reload button to find. (From 3.8.3 on, it also checks its folder every couple of minutes.)

### New in 3.11: a cleaner dashboard that puts the edge in front of you
- 🔥 **Today, at a glance:** the Inbox opens on how many requests are waiting, how many were posted in the last hour (the first good reply usually gets the job), how many are needed this week — and how your week compares to the last. One click replies to the newest
- 💡 **Tips from your own leads:** when your customers post most, which group brings you the most work, and what Autopilot did today — each shown only when there’s enough data for it to be true
- 🗂️ **The job on every card:** when, where, what, budget and crew right on the lead, with a green dot on anything posted in the last hour — no more reading every post to find the good ones
- 💬 **Your reply looks like the comment it becomes,** and “Won the job” gets a little celebration
- ⚙️ **Settings, simplified:** one “Which leads you see” choice (More leads · Balanced · Only the surest) replaces three score sliders; “How deep” is Quick · Normal · Deep; Autopilot’s limits show as safety badges; reply options moved to the Replies page, next to the previews. Everything you could change before still works the same way
- 🧭 The menu is grouped (Find work · Set up), Scan now and the next scan time live in the sidebar

### 3.10.2: fixes from a live test
- 🚚 “Need two movers with a truck… must be available at noon tomorrow” was scored like a mover’s ad and fell under the Autopilot minimum — it’s a customer again
- 🛏️ Giveaways like « … sans frais mais à ramasser », “available free for pickup” and “does anyone need a queen bed base?” are listings, not requests
- 🎨 “A painter to work with us” is a job posting; « faire sabler… avant de le peinturer » isn’t a painting job; « quelqu’un sait c’est qui qui se promène avec un pickup? » is asking who someone is

### 3.10.1: the safety checks really run
- 🔒 **Fix:** the Verifier’s two newest checks — proof of hiring, and “more than one word points to the job” — were dropped when a post’s analysis was saved, so inside the extension they never held anything back. They’re kept now, and Autopilot re-reads any post analysed by older rules before it comments
- 🔁 Saved posts are re-read whenever the rules change — not only when Brave starts — so an update always reaches your whole inbox

### 3.10: Autopilot only comments when someone is clearly hiring
- 🛑 **Listings aren’t requests:** “Foam mattress, good condition. Thick. Need two strong people.” is someone giving a mattress away — the strong people are for whoever takes it. Posts that describe an item (its condition, a price, “free to whoever”, « bon état », « comme neuf »…) are now read as listings, and a “need two strong people” in them doesn’t make them a lead
- ✅ **Proof of hiring before any automatic comment:** Autopilot now needs the post to ask someone to do a job — movers or a moving company, people to move, carry, load or deliver something, something of theirs to be moved, a quote for a move, or people with a route or pay. “Need two strong people for our tug of war team” is held for your look. On every labelled post we have, it would comment on none of the non-requests and still answer about 96% of real moving requests
- 🧪 Measured honestly: a fresh set of tricky listings and requests, written before the fix, was scored once — the old rules would have commented on 14 of 25 listings
- 🗣️ **One voice per comment:** a crew’s reply no longer starts with “we” and ends with “message me and I’ll…” — it’s “we… message us” throughout (« écrivez-nous »). Lines like “we do moves like this all the time” are gone
- ✍️ **Better feedback:** “Shouldn’t have commented” now asks what was wrong — giving away or selling, an ad, not a job, a different kind of job, too old, or a real request that’s not for you — with a box to type what happened. It’s saved with the post
- 🐛 « Recommandations pour déménageurs » was read as “our movers” (already booked) — fixed

### New in 3.9: the Autopilot report
- 🤖 **See what Autopilot did, every day:** a new **Autopilot** page lists each comment it posted (with exactly what it wrote) and each lead it held back for your look, with the reason. Pick today, yesterday or any of the last 7 days
- ✋ **One click when it got one wrong:** “Shouldn’t have commented” asks whether nobody was asking for help (Lead Sniper learns from it) or it was a real request that just isn’t for you (hidden, nothing learned). On a held-back lead, “Reply now” or “Should have commented”. Lead Sniper never deletes a comment on Facebook — the post is one click away if you want to
- 🔔 **End-of-day notification** when quiet hours start (or 9 PM): “3 comments posted · 1 lead held back for your look” — only on days Autopilot did something. Click it for a 10-second check. Turn it off in Settings → Automatic replies
- 🔢 The menu shows how many comments Autopilot posted since you last looked

### 3.8.5: “Not for me” and a safer Autopilot
- 🙅 **“Not for me” vs “Not a request”:** the ✕ on a lead’s banner in Facebook now asks which you mean. “Not for me” hides a real request you’re passing on (a $40 job, a service you don’t do) and teaches Lead Sniper nothing. “Not a request” is for posts where nobody is asking for help, and it teaches. The same two buttons are in the inbox
- 🧠 **Replied means real:** “Not a request” on a post you already replied to only hides it, without teaching — and earlier clicks like that are un-taught, so the second opinion stops doubting requests like them
- 🔎 **Autopilot needs more than one word:** when a single bare word is all that points to a job (“load” in a question about a beam), the post is held for your look instead of getting a comment. Every real moving request in your saved posts still passes

### 3.8.4: right comments on the right posts
- 🧱 **A “load-bearing wall” isn’t a move:** “if the wall is not load bearing… have the wall removed” was read as loading a truck, and Autopilot commented on it. Wall removals are now renovation jobs (« enlever un mur porteur » too)
- 🚚 **Plain moving requests aren’t held back:** “Need two movers for loading and unloading… drop a comment or send me a text” was held for “a human look” by the second opinion. On your real posts its doubts about plain, direct requests were wrong every time, so now it only doubts posts that also read like an ad or a job posting
- ✅ **“Update: fixed. Thank you all”** at the top of a post closes it; someone listing their experience and asking which companies are hiring is a job hunter, not a customer
- 🎯 **Other services:** “help with drywall and insulation”, a dog walker asked for along with advice, snowblower and small-engine repairs, body work (« carrosserie »), and “help with some cleaning” are now found

### 3.8.3: updates itself
- 🔄 **No more reload button:** when its folder holds a newer version, Lead Sniper updates itself — as soon as you open the dashboard, or within a couple of minutes — never in the middle of a scan, a group hunt or an automatic reply. You get a notification, and the dashboard reopens where you were

### 3.8.2: more fixes from a second full check
- ✍️ **A reply you’re writing on Facebook is never wiped:** lead banners no longer redraw while their reply panel is open (a settings change or a re-check used to clear it, and your edits)
- 💬 **Replies you type straight into Facebook count:** when your own comment shows under a lead, it’s marked replied — no more leads stuck in “To reply” because you answered without the Reply button
- 🙋 **Your own posts are never leads** (“Looking for 2 helpers Saturday” that you posted yourself), and Autopilot never comments on them
- 👤 **“Anonymous member” is many people:** replying to one anonymous post no longer blocks Autopilot from the others for a week, and “Not a lead” on one no longer hides another anonymous member’s request
- 🗓️ **Old requests aren’t new leads:** a request already older than “Skip posts older than” when a scan first reads it is kept under All, without an alert or a badge
- 📝 **Templates:** if none of your templates is for a lead’s kind of job (or its language), you get a quick reply — never another service’s template
- 📄 **CSV export:** opens with accents intact in Excel, and a post starting with “=” can’t run as a formula
- 🗺️ Changing Group Hunter’s areas re-checks what counts as “far away”; finishing setup re-checks posts read before it

### 3.8.1: reliability fixes from a full check of the app
- 🔒 **Your clicks always stick:** archiving a lead, marking it won or replying while Lead Sniper re-reads your posts (after a settings change, an update or during a scan) can no longer be undone by it
- 🤖 **Autopilot is safer:** a post can only ever be claimed once, even when two checks land at the same moment; it recognises comments from your own Facebook account (learned from your replies), so it won’t comment where you already answered by hand; and it only answers posts in groups you added — never posts Facebook’s feed shows from other groups
- 📋 **Handled leads stay put:** jobs you replied to, won or lost stay in your tabs and in Insights even if you later turn their service off
- 💾 **Restoring a backup** keeps the newer copy of each lead (a reply you sent after the backup stays sent) and no longer doubles your activity log
- 🔁 **Scans:** a progress report can no longer overwrite the move to the next group; Facebook tabs update their lead banners right after you change a setting
- 🧭 **Setup asks where you work,** for the far-away check and Group Hunter; Group Hunter’s summary talks about your services, not just moving

### New in 3.8: quick replies that sound like a person
- 💬 **Short, natural replies** replace the long “smart” ones: their first name, one plain line for the job, and how to reach you — “Hi Marie, I can take care of the cleaning. Send me a message for a quote.” Nothing from their post is repeated back, no stacked “happy to…” lines, and emoji only if you want them
- 🔀 **Never copy-pasted:** each service has a few versions in English and French, mixed so comments posted close together never match (Lead Sniper now remembers your last 50 replies)
- 🙋 One-person jobs still say “I”, crews say “we” (Settings → Replies → Speak as)

### New in 3.7: replies in your own voice, and sharper on every service
- 🙋 **“I” for jobs you do yourself:** handyman work, painting, repairs, appliances, auto, cleaning, tutoring and other one-person jobs now reply “I can take a look” / « Je peux vous aider » instead of “we”. Moving and crew jobs (renovation, roofing, trees) keep “we”. You can choose in Settings → Replies → Speak as
- 🎯 **The right service, more often** — from a hand review of 391 posts from a live test: gutters and downspouts, shingles, phone screens, TV repair, remote starters, Tempo shelters, washer hookups, septic tanks, baseboards, snow removal and more are now recognized. When a post asks for a service you offer next to one you don’t (« déneigeur… et quelqu’un pour peinturer »), yours takes it
- 🧹 **Fewer false leads:** “where can we drop off…?” questions, businesses asking for opinions, debt advice, mason jars (not masonry), contractors looking for subcontractors, “it’s fixed” updates, daycare announcements, animal-rescue appeals, photo-shoot location questions, and jobs in U.S. towns written like “Herrick IL”
- 🌐 **Posts written in both languages** get a reply in the language they open with, with the item named in that language — never « votre refrigerator »
- ✍️ **Replies that fit the job:** mounting a TV, staining a railing, getting jet skis ready for winter, hooking up a washer, moving a granite countertop
- 👋 One-word usernames (“Frogeye23”) aren’t greeted by name

### New in 3.6: get around faster
- 🔍 **Quick jump (Ctrl K, or ⌘ K on a Mac):** one box to find any lead by name or job, open any page or setting, or do things like "Scan my groups now" and "Dark mode". Also in the sidebar
- 📅 **Your leads by day:** the inbox list has Today, Yesterday, Last 7 days and Last 30 days headings
- ↕️ **"3 of 11" in every lead,** with up and down arrows to go to the next or previous lead without the list
- 👥 **A clearer Groups page:** a badge for each group, its lead rate as a small bar, and a "Top group" tag on the one bringing you the most leads
- ⏱️ **Undo messages show the time left,** and stay put while you point at them

### New in 3.5: handle more leads, faster
- ☑️ **Several leads at once:** click **Select** (or shift-click a range of leads), tick the ones you want, and mark them all Replied, Won, Lost, Archive or Not a lead in one click — with Undo
- ⏳ **No more blank screen:** the dashboard appears right away, with soft grey placeholders for the second it takes to read your leads
- 🎨 **A colour for each service in Insights:** leads per day are stacked by service, with a legend, a breakdown when you point at a day, and a table view. A service keeps the same colour in every chart, in light and dark mode, and the colours stay easy to tell apart for colour-blind eyes
- 📱 **Phone-sized windows:** the inbox's filters and tabs fit without spilling off the screen

### New in 3.4.1: design polish
- 🎨 **Easier to read:** small grey text and the orange buttons now meet the accessibility contrast standard (WCAG AA) in light and dark mode, in the dashboard, the popup and on Facebook
- 📥 **Clearer inbox:** each lead reads name → job (in orange) → post, and empty tabs (Maybe, Replied, Won) explain what will show up there

### New in 3.4: the Verifier, and tuning from a live test with 11 home services
- 🔎 **The Verifier double-checks every automatic reply.** Before Autopilot posts, it re-reads the post for context: written by a person (not a business page), no ad, promotion, job-posting or for-sale wording, hiring rather than asking about prices, reviews or hours, in your area, nothing doubtful, not a flyer. If anything fails, the lead waits in your inbox, marked "Held for your look" with the reason. On past mistakes it holds 28 of 30 false leads, while letting 99% of real customers through
- 🌐 **Your website and name only where they fit:** a site or business name made for one kind of work ("GatineauMoving.com") stays off your cleaning or plumbing replies; pick exactly which services show them, or give a service its own website (Settings → Replies)
- ✨ **Polish:** a tidier inbox (services on one scrolling row, a post count, no needless "New" tags), even Services cards, a proper Group Hunter welcome, and the Verifier's verdict on every lead
- 🤖 **Autopilot's minimum is now 75** (it was 80): most clear trade requests score 75–85, and the Verifier covers the close calls
- 🎯 **More real customers found:** landlords hiring a handyman, "LF cleaning service", typos like "lookimg", "wondering if anyone is able to…", "DM me if you can help", French posts where *tire* means pull (not tires), and price questions like "how much would it cost to mount a TV?"
- 🧹 **Fewer false alarms:** group welcome posts, page promotions full of hashtags, businesses pitching to contractors, "installer wanted" job ads, review requests about one contractor, and jobs far from your area (Halifax, Florida…), judged from your service areas and Group Hunter areas
- 🧭 **Right service, every time:** duct and furnace cleaning → Heating & AC, washer gaskets → Appliance repair, and when a moving service is off, a trade you offer takes the post
- 🤖 **Autopilot shows what it skips:** the Services page says which of your services Autopilot doesn't answer yet ("Answer all my services automatically"), and a skipped lead has a one-click fix
- ⚡ Turning several services on in a row now re-checks your posts once, not once per click; no more "maybe" for a service you turned off

### New in 3.3: polish and a sharper eye
- 🔁 **"Not a lead" now covers reposts:** a post you dismiss keeps its near copies out too — a competitor posting the same ad every week with small edits, for any service
- 🎯 **Sharper detection:** taught from a new 100-post exam across all 30 services (e.g. "Ramoneur demandé", "Taking quotes for snow plowing", "can anyone come boost me?"), and finished threads ("we booked with Pierre, all done") and opening-hours questions no longer count as leads
- ✍️ **Replies that fit the job:** a lockout gets "we can get you back in", a hot tub gets hot-tub lines, an install never hears "we'll get it running again"
- 📱 **Small screens:** the lead view fits a phone-sized window, with an "All leads" button to go back
- 💾 **Backups include what your clicks taught it**, and links to a Settings section land right on it
- 📄 **CSV export** has the service name, job, area and date as their own columns

### New in 3.2: every screen speaks all 30 services
- 📥 **Inbox:** each lead shows its service, and any job other than a move shows what's needed in the customer's own words (*"Laveuse ne vidange plus"*, *"Hot tub stopped heating"*), on Facebook and in your notifications too
- ✍️ **Replies page:** preview the smart reply for each of your services in English and French; templates are listed by service, and **New template for…** starts one in that service's own voice. New `{job}` and `{area}` fill-ins
- 🧭 **Group Hunter** searches where your services get asked for: moving groups for movers, recommendation and home-services groups for trades, parents' groups for babysitters and tutors
- 📊 **Insights:** leads and jobs won for each service
- 🧹 Replies for trades no longer borrow a mover's lines ("stairs don't scare us")

### New in 3.1
- 🧰 **10 more services (30 in all):** 🏚️ Roofing · 🔥 Chimney sweeping · 🔑 Locksmith · 🏊 Pools & hot tubs · 💻 Computer & phone repair · 🧸 Childcare · 📚 Tutoring · 💇 Hair & beauty · 📸 Photography · 🧵 Sewing & alterations
- 🎯 **Sharper on every trade:** taught from 500+ new example posts and real Québec wording (*entretien ménager*, *ramoneur*, *couvreur*, *barré dehors*, WETT inspections, winter-tire season)
- 🧹 **Fewer false alarms:** skips charity drives and contests, police news, "Need your tires changed?" ads, equipment for sale, and daycares hiring staff, while families hiring a babysitter still count
- 🔁 Your saved posts are re-read with the new rules on the first start, so leads you scanned before show up by themselves

### Everything else
- 🎯 Lead engine that reads the whole job: size, floor, route, date, items, budget
- ✍️ Smart replies written from each customer's own words, in their language
- 🧭 Group Hunter: finds and ranks local groups by requests for your services
- ⏱️ Scheduled scans and desktop notifications
- 🤖 **Pro Autopilot**: replies post themselves, with limits, quiet hours and a free Rehearsal mode

**Pro:** $20 CAD/month or $150 CAD/year, paid in Bitcoin or Monero. See [the website](https://hurbiexss.github.io/leadsniper/#pricing) or e-mail [justinhurbie@gmail.com](mailto:justinhurbie@gmail.com) with your browser code.
