# Personal Data Removal Playbook

Prepared for Ramu Reddy — July 2026

---

## Read this first

**You cannot remove all of it.** Three categories are permanently out of reach:

- **Public records** — property deeds, voter registration (in most states), court filings, marriage/divorce records, business registrations, professional licenses. These are public by law. Brokers that *republish* them can be forced to stop; the underlying record cannot.
- **Data already sold** — anything a broker sold before you opted out is now in someone else's database. Deletion is forward-looking.
- **Archived and cached copies** — Internet Archive, screenshots, scrapes, and leaked datasets circulating in criminal markets.

**What you *can* do** is make yourself expensive to look up. Most casual searches — a nosy coworker, a scam caller, a stalker without money — stop at the free tier of people-search sites. Clearing those, plus the aggregators feeding them, removes the majority of practical exposure.

**This decays.** Brokers re-scrape from the same public sources. Expect data to reappear in 3–12 months. Anything you do here needs a repeat cycle, which is the strongest argument for a paid service.

---

## Do these five things this week

Ranked by exposure reduced per minute spent.

| # | Action | Time | Why it's first |
|---|---|---|---|
| 1 | Freeze credit at all 6 bureaus | 60 min | Highest-consequence protection. Free, permanent, blocks account fraud outright. |
| 2 | Google "Results about you" | 15 min | Removes the search path most people actually use to find your address. |
| 3 | Turn off LinkedIn public profile indexing | 2 min | Single toggle. Your LinkedIn is likely the top result for your name. |
| 4 | Opt out of the top 12 people-search sites | 3 hrs | Where address, phone, relatives, and age are exposed for free. |
| 5 | Suppress at the 4 upstream aggregators | 45 min | LexisNexis, Acxiom, Epsilon, Oracle feed the smaller sites. Cuts off resupply. |

Everything after this is cleanup and maintenance.

---

## Step 1 — Freeze your credit (60 min, free, do it today)

A freeze is the single most valuable item on this list. It doesn't remove data, but it neutralizes the main harm that exposed data enables. Free and legally mandated under the Economic Growth, Regulatory Relief, and Consumer Protection Act of 2018.

**The big three** — freeze each separately; one does not cover the others:

- Equifax — https://www.equifax.com/personal/credit-report-services/credit-freeze/
- Experian — https://www.experian.com/freeze/center.html
- TransUnion — https://www.transunion.com/credit-freeze

**The three most people miss:**

- **Innovis** (fourth bureau, used by some lenders) — https://www.innovis.com/personal/securityFreeze
- **NCTUE** (telecom + utility accounts — how phones get opened in your name) — https://www.nctue.com/consumers
- **ChexSystems** (used by ~80% of banks to screen new checking accounts) — https://www.chexsystems.com/security-freeze/place-freeze

Store each PIN/confirmation in your password manager. You'll need them to thaw temporarily when applying for credit — which is easy and takes minutes.

Also worth freezing if you're thorough: LexisNexis and CoreLogic (see Step 5 — their opt-out and freeze are separate processes).

---

## Step 2 — Google and search engines (30 min)

### Results about you

Go to **https://myactivity.google.com/results-about-you**

Enter the name variants, addresses (current and prior), phone numbers, and email addresses you want monitored. Google scans its index and flags matches. Enable email or app notifications so new hits reach you automatically.

Google upgraded this in February 2026: it now also finds and processes removal requests for **government-issued ID numbers** — passport, driver's license, SSN — and streamlined removal of non-consensual explicit imagery.

You can also request removal inline from a search result: click the **three dots** next to any result and use the removal option in that menu.

### Direct removal request form

For anything the tool misses: **https://support.google.com/websearch/troubleshooter/9685456**

Grounds that Google accepts include your address/phone/email appearing with explicit or implicit intent to harm, ID and financial account numbers, medical records, images of handwritten signatures, and non-consensual imagery. Doxxing content is removable — say so explicitly if it applies.

### Critical limitation

Removal from Google **delists the result** — it does not delete the page. Anyone visiting the source site directly still sees it. Always pair a Google removal with an opt-out at the source. Do the source first where you can; otherwise Google re-indexes it.

### Other engines

- Bing — https://www.bing.com/webmasters/tools/contentremoval
- DuckDuckGo, Ecosia, Startpage: these syndicate Bing/Google results, so the above generally propagates.

---

## Step 3 — LinkedIn and social media (45 min)

### LinkedIn — the highest-value single toggle

**Settings & Privacy → Visibility → Edit your public profile → "Your profile's public visibility" → Off**

This removes your profile from Google, Bing, and every scraper that reads them. Logged-in LinkedIn members can still see you per your other settings, so this costs you nothing professionally unless you rely on cold inbound.

While you're in Visibility, also review:

- **Profile viewing options** → set to Private mode or semi-private
- **Who can see your connections** → Only you
- **Who can see your email address** → Only me (or 1st-degree)
- **Representing your organization** → off
- **Profile discovery using email address / phone number** → Nobody
- **Data privacy → Salary data, Social/advertising data, Data research** → opt out of all

Note: search engines take days to weeks to drop the cached copy. If it lingers past two weeks, submit the URL to Google's removal tool as outdated content.

### Other platforms

Set profiles to private, then audit what's exposed even when private (usually: profile photo, display name, bio, follower list). Delete rather than privatize accounts you don't use.

- **Facebook** — Settings → Privacy → "Do you want search engines outside Facebook to link to your profile?" → No. Also run **Privacy Checkup** and use "Limit Past Posts."
- **X/Twitter** — Settings → Privacy → Discoverability: disable email and phone lookup. Consider protecting posts.
- **Instagram** — private account; Settings → "Similar account suggestions" off.
- **Venmo** — this is a common overlooked leak. Set past and future transactions to Private, and hide your friends list.
- **Strava / fitness apps** — set privacy zones around home and work, or disable public activity entirely. Reverse-engineering a home address from run routes is trivial.
- **Spotify / Goodreads / Letterboxd** — public by default, tied to real names surprisingly often.

### Old and dormant accounts

Each dormant account is a breach waiting to expose you. To find them:

1. Search your Gmail for: `"welcome to"`, `"verify your email"`, `"confirm your account"`, `"your new account"`, `"free trial"`
2. Check saved passwords in your password manager and browser
3. Review **https://myaccount.google.com/permissions** — every third-party app with Google sign-in
4. Run your usernames through **https://whatsmyname.app**
5. Check **https://haveibeenpwned.com** — breach listings reveal services you forgot existed

Delete via each service's account settings. **https://justdelete.me** catalogs the deletion URL and difficulty for hundreds of services.

---

## Step 4 — People-search sites (the main event)

These are the sites that expose your home address, phone, age, relatives, and prior addresses to anyone who types your name. Highest priority by far.

**Before you start:**

- Create a **dedicated throwaway email** for opt-outs (e.g. `optout.rr.2026@gmail.com`). Many brokers add your opt-out email to their marketing lists. Never use your primary.
- Consider a **VoIP number** (Google Voice) for phone verification for the same reason.
- **Search yourself first** on each site and save the exact profile URL. Most opt-outs require it.
- Watch for **duplicate profiles** — old addresses and name variants often generate two or three listings per site. Removing one leaves the others live.
- Never pay a people-search site to remove you, and never accept a "premium removal" upsell. Free opt-out is legally required.

### Tier 1 — do these first

| Site | Opt-out URL | Method | Typical time |
|---|---|---|---|
| Whitepages | https://www.whitepages.com/suppression_requests | Profile URL + phone verification (automated call, 4-digit code) | 1–2 days |
| Spokeo | https://www.spokeo.com/optout | Profile URL + email confirmation | 24–72 hrs |
| BeenVerified | https://www.beenverified.com/app/optout/search | Search, select record, email confirm | 24 hrs–7 days |
| Radaris | https://radaris.com/control/privacy | Claim profile, then remove | 1–3 days |
| Intelius | https://www.intelius.com/opt-out/ | Email + confirmation link | 3–7 days |
| TruePeopleSearch | https://www.truepeoplesearch.com/removal | Profile URL + email | Minutes–24 hrs |
| FastPeopleSearch | https://www.fastpeoplesearch.com/removal | Profile URL + email | Minutes–24 hrs |
| PeopleFinders | https://www.peoplefinders.com/opt-out | Name + state → select → email | 2–3 days |
| TruthFinder | https://www.truthfinder.com/opt-out/ | Search + email confirm | 2–7 days |
| Nuwber | https://nuwber.com/removal/link | Profile URL + email | 1–3 days |
| USPhoneBook | https://www.usphonebook.com/opt-out | Profile URL + phone | 1–2 days |
| PeopleLooker | https://www.peoplelooker.com/f/optout/search | Search + email | 1–7 days |

### Tier 2 — next pass

Instant Checkmate, Been Verified's sister sites, SmartBackgroundChecks, Advanced Background Checks, CheckPeople, ClustrMaps, PublicRecordsNow, USSearch, ZabaSearch, AnyWho, 411.com, Addresses.com, NeighborWho, Ownerly, PeopleSmart, SearchPeopleFree, ThatsThem, Cyber Background Checks, Verecor, Yellowbook, Pipl.

For current opt-out links on these and roughly 100 more, use one of these maintained lists rather than a static table that will rot:

- **https://privacyinsightsolutions.com/data-broker-opt-out-list** — 104 sites with direct opt-out links
- **https://www.securityhero.io/how-to-opt-out-of-data-brokers/** — step-by-step per broker
- **https://www.cagoldberglaw.com/resources/data-website-opt-outs/** — maintained by a victims'-rights law firm; good for the harassment case
- **https://easyoptouts.com/sites** — 200+ site index

### Realistic expectation

Manual opt-out across 100+ brokers runs roughly **40 hours**, and a meaningful share of it reappears within months. Budget Tier 1 manually (about 3 hours, covers most real-world exposure) and consider paying for the long tail. See Step 7.

---

## Step 5 — Upstream aggregators (45 min, high leverage)

These are the wholesalers. The people-search sites in Step 4 are largely retail outlets for their data. Suppressing here slows the rate at which your removed listings come back.

- **LexisNexis** — https://optout.lexisnexis.com/ — the most important one. Also request a **security freeze** on your LexisNexis consumer report separately at https://consumer.risk.lexisnexis.com/freeze
- **Acxiom** — https://isapps.acxiom.com/optout/optout.aspx (also https://aboutthedata.com)
- **Epsilon** — https://legal.epsilon.com/dsr/ or email optout@epsilon.com
- **Oracle Data Cloud** — https://www.oracle.com/legal/privacy/marketing-cloud-data-cloud-privacy-policy.html
- **CoreLogic** — email privacy@corelogic.com; opt-out form download on their privacy page
- **Thomson Reuters CLEAR** — https://www.thomsonreuters.com/en/privacy-statement.html (suppression request form)

Expect these to be slower and more bureaucratic than the retail sites — some require a mailed form with ID. Worth the friction.

---

## Step 6 — Use your legal rights

You have statutory rights that most people never invoke. They convert a polite request into a legal obligation with a deadline.

### If you live in California — do this first, it's the biggest lever available

**DROP (Delete Request and Opt-out Platform)** — https://privacy.ca.gov/drop

Run by the California Privacy Protection Agency (now operating as **CalPrivacy**); the agency site is https://www.cppa.ca.gov if that link moves.

Live since **January 1, 2026** under the Delete Act (SB 362). Create one profile, verify California residency, submit **one** deletion request — and it reaches **all 575+ data brokers registered in California**. There is nothing else like it in the country.

Timing: brokers must begin honoring DROP requests from **August 1, 2026**, checking the platform at least every 45 days. So submitting now means removal starts within weeks. Do this before spending money on a paid service — it may cover most of what you'd pay for.

### If you live elsewhere

Roughly 20 states now have comprehensive privacy laws granting a **right to delete**. As of January 1, 2026, **12 states** legally require businesses to honor **Global Privacy Control** signals: California, Colorado, Connecticut, Delaware, Maryland, Minnesota, Montana, Nebraska, New Hampshire, New Jersey, Oregon, and Texas.

**Install Global Privacy Control** — https://globalprivacycontrol.org — built into Brave, DuckDuckGo browser, and Firefox (Settings → Privacy → "Tell websites not to sell or share my data"). In those 12 states this is a legally binding opt-out signal on every site you visit, automatically.

**Standard response window: 45 days**, extendable once by another 45. If a broker blows the deadline, that's an enforceable violation — complain to your state AG.

### Template — right-to-delete request

Use this when a broker has no self-service form. Send from your throwaway email.

> **Subject: Consumer Request to Delete and Opt Out of Sale — [Your Full Name]**
>
> To Whom It May Concern:
>
> I am a resident of [STATE]. Pursuant to [CCPA/CPRA — or your state's statute], I am exercising my rights to:
>
> 1. **Delete** all personal information you have collected about me;
> 2. **Opt out** of the sale and sharing of my personal information;
> 3. **Limit** the use and disclosure of my sensitive personal information;
> 4. Direct all **service providers and third parties** to whom you have sold or disclosed my information to do the same.
>
> Identifying information: [Full name, any prior/variant names, current address, prior addresses, DOB, phone, email]
>
> Please confirm completion in writing and identify all categories of third parties to whom my information was sold or disclosed in the preceding 12 months.
>
> I expect a response within 45 days as required by law.
>
> [Name]

### Other free registries worth 15 minutes

- **National Do Not Call Registry** — https://www.donotcall.gov
- **DMAchoice** (direct mail, $6 for 10 years) — https://www.dmachoice.org
- **OptOutPrescreen** (credit card and insurance prescreened offers — permanent opt-out) — https://www.optoutprescreen.com
- **Yellow Pages opt-out** — https://www.yellowpagesoptout.com

---

## Step 7 — Should you pay someone?

Given you want all four categories covered and a recurring problem, a service is probably worth it. **Except if you're in California** — submit through DROP first, wait for the August 2026 processing cycle, then re-audit and see what's left. You may not need to pay at all.

| Service | Price | Brokers covered | Best for |
|---|---|---|---|
| **Optery** | Free tier available; paid from ~$39 | ~390 default, 640+ with Expanded Reach | Best evidence of results. Free tier scans and shows you exactly where you appear with before/after screenshots — useful even if you never pay. US only. |
| **Incogni** | ~$7.99/mo (~$7.19/mo annual) | 420+ | Cheapest, and the only one with real international coverage under GDPR. Single plan covers multiple regions. |
| **DeleteMe** | ~$10.75/mo | ~85–100 automated on the Standard plan; up to 850 via custom requests | Longest-established. Note the entry tier automates far fewer than the headline number suggests. Separate subscription per country. |
| **EasyOptOuts** | ~$20/yr | 200+ | Cheapest option that exists. No dashboard, no polish, but it works. |

**Suggested approach:** start with **Optery's free tier** this week purely as a diagnostic — it will show you exactly which sites list you, which is worth having regardless of what you do next. Then either work that list manually or upgrade.

A caveat on all of them: independent reviews are heavily affected by affiliate commissions. Treat "expert winner" rankings skeptically — including the ones cited here. The free-tier scan is the honest test.

---

## Step 8 — Stop the resupply

Removal without this is a treadmill. These practices matter more over time than any single opt-out.

**Email compartmentalization.** Your primary Gmail is now a permanent identifier tied to breaches. Going forward:

- Use **email aliases** for new signups — Gmail's `+tag` trick is trivially stripped by brokers; use a real aliasing service (SimpleLogin, Fastmail masked email, Apple Hide My Email, DuckDuckGo Email Protection). Each service gets a unique address you can burn.
- Keep three tiers: **financial/government** (never given out), **real people** (primary), **everything else** (aliases).

**Phone.** Give a **Google Voice or MySudo number** for retail, loyalty programs, appointments, and delivery. Your real mobile goes to banks, doctors, and people who know you. This is the single biggest reducer of spam calls, because brokers correlate on phone number more than any other field.

**Address.** Use a **PO Box, UPS Store box, or virtual mailbox** for anything requiring a mailing address that isn't legally required to be your residence. Property records will still show your home; everything downstream doesn't have to.

**Register-to-vote leak.** Voter files are public in most states and are a major broker input. A handful of states offer confidentiality for cause — see the safety note below.

**Browser.** Brave or Firefox with GPC enabled, uBlock Origin. This stops new collection rather than removing old data, which over a year matters more.

---

## Safety note

You indicated harassment/safety as one of your motivations. Two things worth knowing:

**Address Confidentiality Programs.** Roughly 40 states run an ACP for survivors of domestic violence, stalking, sexual assault, or trafficking. Enrollment gives you a legal substitute address usable on voter registration, driver's license, school forms, and court filings — and it **seals the underlying public record**, which is otherwise the one thing you cannot remove. It's administered through your Secretary of State or AG's office. If you qualify, this is more powerful than everything else in this document combined.

**Priority shift.** If someone specific is looking for you, sequence differs: address suppression and the ACP come before anything cosmetic, and you should not wait on the 45-day statutory windows. C.A. Goldberg's opt-out resource (linked in Step 4) is maintained specifically for this situation. The Safety Net project at the National Network to End Domestic Violence (https://www.techsafety.org) has guidance written for exactly this threat model.

---

## Maintenance schedule

| Cadence | Task |
|---|---|
| **Weekly, first month** | Check throwaway email for confirmation links — most opt-outs die because a verification email went unclicked |
| **Monthly** | Google your name, name + city, name + employer, phone number, email address. Log new hits. |
| **Quarterly** | Re-run Tier 1 opt-outs. Re-check Optery/Incogni dashboard. Check HIBP. |
| **Annually** | Full sweep: re-audit aggregators, confirm credit freezes still active, review social settings after platform policy changes |
| **After any move** | Everything resets — new address enters public records and propagates within weeks. Re-run the whole list. |

Set a recurring calendar reminder now. The single most common failure mode is doing this once, thoroughly, and never again.

---

## Sources

- [How to Opt Out of Data Brokers: The Complete Manual Guide (2026) — Security Hero](https://www.securityhero.io/how-to-opt-out-of-data-brokers/)
- [List of 104 US Data Brokers & People-Search Sites — Opt-Out Links (2026)](https://privacyinsightsolutions.com/data-broker-opt-out-list)
- [Data Broker Opt-Out Guide 2026 — State of Surveillance](https://stateofsurveillance.org/guides/basic/data-broker-opt-out/)
- [Data Website Opt-Outs — C.A. Goldberg Law](https://www.cagoldberglaw.com/resources/data-website-opt-outs/)
- [Find and remove personal info in Google Search results — Google Search Help](https://support.google.com/websearch/answer/12719076?hl=en)
- [Results about you — Google](https://myactivity.google.com/results-about-you)
- [Remove personal information and outdated content from Search results — Google Blog](https://blog.google/feed/results-about-you-new-design/)
- [California's Deletion Request and Opt-Out Platform (DROP) is Live — Byte Back](https://www.bytebacklaw.com/2026/02/californias-deletion-request-and-opt-out-platform-drop-is-live/)
- [How Californians can use a new state website to block hundreds of data brokers — CalMatters](https://calmatters.org/economy/technology/2026/01/californians-block-personal-data/)
- [January 2026: DROP Is Coming — California Privacy Protection Agency](https://privacy.ca.gov/2025/12/january-2026-drop-is-coming/)
- [The State Privacy Patchwork in 2026: Opt-Out Rights, Global Privacy Control — LawsuitGuard](https://lawsuitguard.com/insights/state-privacy-gpc-and-opt-out-signals)
- [How to Freeze the Secondary Credit Bureaus in 2026 — Crowned Credit](https://getcrownedcredit.com/blog/freeze-secondary-credit-bureaus-2026)
- [How to Freeze Your Credit at All 3 Credit Bureaus — Experian](https://www.experian.com/blogs/ask-experian/credit-education/preventing-fraud/security-freeze/)
- [Individual Requests for Information Suppression — LexisNexis](https://www.lexisnexis.com/en-us/privacy/for-consumers/opt-out-of-lexisnexis.page)
- [How to make LinkedIn private: a comprehensive guide (2026) — Incogni](https://blog.incogni.com/how-to-make-linkedin-private/)
- [Privacy Fix: How to Find Old Online Accounts — Consumer Reports](https://www.consumerreports.org/electronics/digital-security/how-to-find-old-online-accounts-a1266305698/)
- [Optery vs DeleteMe vs Incogni: Which Is Best in 2026? — Cybernews](https://cybernews.com/privacy-tools/optery-vs-deleteme-vs-incogni/)
- [Data Removal Services July 2026 — State of Surveillance](https://stateofsurveillance.org/guides/basic/data-removal-services-comparison/)
- [We Cover 200+ Data Brokers + People Search Sites — EasyOptOuts](https://easyoptouts.com/sites)
