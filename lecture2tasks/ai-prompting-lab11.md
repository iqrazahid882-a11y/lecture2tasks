# AI Prompting Lab: All 13 Concepts

Practice every concept, by doing. Thirteen hands-on exercises, one per concept. You type the prompts, read the answers, and write what you noticed.

- **Time:** ~2 hours (split it across sessions)
- **Exercises:** 13
- **Tools:** ChatGPT, Claude, or Gemini (all free tiers work)
- **Level:** Beginner friendly

Most exercises give you two examples: a **Daily** (everyday) version and a **Work** (simple-professional) version. Run at least one; try both if you have time. Copy any prompt directly.

Some exercises need a little setup (a file to upload, a second tool, or a specific feature). Those are marked with **Needs**. If you can't do one today, read it and move on.

> **The one rule behind all 13:** Get the right context in, keep the wrong context out.

---

## Jump to an Exercise

| # | Exercise | Part |
|---|----------|------|
| 1 | [Novice vs Power User](#1-novice-vs-power-user) | Part 1: How AI knows things |
| 2 | [Knows vs Guesses](#2-knows-vs-guesses) | Part 1 |
| 3 | [The 3 Retrieval Modes](#3-the-3-retrieval-modes) | Part 1 |
| 4 | [Context Is Everything](#4-context-is-everything) | Part 2: Talking to AI well |
| 5 | [Think Hard](#5-think-hard) | Part 2 |
| 6 | [Stop the Flattery](#6-stop-the-flattery) | Part 2 |
| 7 | [Brainstorm-Iterate Loop](#7-the-brainstorm-iterate-loop) | Part 2 |
| 8 | [Multimodal (Image/Audio)](#8-multimodal--image--audio) | Part 3: Beyond text |
| 9 | [Build a Small App](#9-build-a-small-app) | Part 3 |
| 10 | [Data Analysis](#10-data-analysis) | Part 3 |
| 11 | [Desktop Apps & Permissions](#11-desktop-apps--permissions) | Part 4: Working safely & choosing tools |
| 12 | [Which Model When](#12-which-model-when) | Part 4 |
| 13 | [Models Checking Models](#13-models-checking-models) | Part 4 |

---

## Part 1: How AI Knows Things

### 1. Novice vs. Power User

**6 min -- feel what context does**

**Goal:** Same question, two ways. The briefing changes everything.

#### Step A: The novice prompt (try one)

Type a bare, no-context question:

**Daily:**

```
Which phone should I buy?
```To recommend the right phone, I need a bit more information:

What's your budget? (e.g., $200, $500, $1000, or in PKR)
Android or iPhone?
What matters most to you?
Camera
Gaming
Battery life
Performance/speed
Video recording (for singing covers and social media)
Overall balance

If I had to recommend phones without knowing your budget:

Best budget phone: Samsung Galaxy A16 5G
Best mid-range phone: Samsung Galaxy A56
Best value flagship: Samsung Galaxy S24 FE
Best Android flagship: Samsung Galaxy S25 Ultra
Best iPhone value: iPhone 15
Best iPhone overall: iPhone 16 Pro

Tell me your budget and priorities, and I'll narrow it down to the best option for you

**Work:**

```
How do I write a good email?
```A good email is usually clear, concise, and polite. A simple structure works for most situations:

Subject line – Briefly state the purpose.
Example: Meeting Request for Next Week
Greeting
Formal: Dear Mr. Smith, or Hello Ms. Johnson,
Less formal: Hi Sarah,
Opening
State why you're writing.
Example: I'm writing to ask about the status of my application.
Main message
Keep it organized and focused.
Use short paragraphs.
Include any necessary details.
Closing
State any action needed or thank the recipient.
Example: Thank you for your time. I look forward to hearing from you.
Sign-off
Formal: Kind regards, Best regards, Sincerely,
Followed by your name.

Example:

Subject: Project Update

Dear Mr. Smith,

I hope you are doing well. I am writing to provide an update on the project. The first phase has been completed, and we are currently testing the new features.

Please let me know if you would like a detailed progress report.

Thank you for your time.

Best regards,
John Doe

Tips:

Keep it brief.
Check spelling and grammar.
Be polite and professional.
Make sure the purpose of the email is clear in the first few sentences.

If you tell me the specific type of email you need (job application, complaint, request, professor, client, etc.), I can show you a more tailored example.

Read it -- generic. True for anyone, useful to no one.

#### Step B: The power-user prompt (same topic + context)

**Daily:**

```
Help me choose a phone. Context: my budget is about $300, I
mostly take photos of my kids and use WhatsApp, my current
phone's battery dies by 3pm, and I find big phones hard to
hold. Give me 3 options with a one-line reason for each, then
tell me which you'd pick and why.
``` Based on your priorities:

Budget: about $300
Main use: photos of your kids, WhatsApp
Pain point: battery dies by 3pm
Preference: easier-to-hold phone (not huge)
1. Samsung Galaxy A25 5G

Why: Good camera with optical stabilization, solid battery life, and a relatively manageable 6.5-inch size for everyday use.

2. Google Pixel 7a (new on sale or refurbished)

Why: Best photo quality in this price range, especially for capturing kids and moving subjects.

3. Xiaomi 12 Lite

Why: Lighter and slimmer than most budget phones, making it more comfortable to hold while still offering a decent camera.

Which one I'd pick

Google Pixel 7a.

For your specific situation, the camera matters more than raw performance. Kids rarely stay still, and Pixels consistently produce excellent photos with minimal effort. The phone is also noticeably more compact than many budget Android phones, which addresses your concern about large devices. As long as you can find it within budget (often refurbished or discounted), it gives you the best overall experience for family photos and everyday messaging.

If battery life is your #1 concern, then I'd switch my recommendation to the Samsung Galaxy A25 5G, which generally offers stronger endurance while still taking good photos.

**Work:**

```
Help me write an email. Context: I need to ask my manager
to move our Friday team meeting to Monday because I have a
doctor's appointment. We have a friendly working relationship.
Keep it short and polite. Give me the email, ready to send.
```
Hi,

I have a doctor's appointment scheduled for Friday and was wondering if it would be possible to move our team meeting to Monday instead.

If Monday doesn't work, I'm happy to find another time that suits everyone.

Thanks for considering it!

Best,
[Your Name]

**Write it down:** What was DIFFERENT about the second answer? (2 sentences)
In the first prompts, the user provided only a basic request, so the LLM could generate only a general response and often needed additional information to give a more accurate answer. In the second prompts, the user supplied detailed context, constraints, and preferences, which enabled the LLM to produce a more personalized, precise, and immediately usable output tailored to the user's specific needs.
> **Takeaway:** AI is like a smart new coworker. It only knows what you tell it.

---

### 2. Knows vs. Guesses

**5 min -- confident does not equal correct**

**Goal:** A confident tone is not the same as a correct answer.

#### Step A: Something AI knows well

**Daily:**

```
Why do onions make you cry when you cut them? Answer in 2 short
paragraphs.
```
When you cut an onion, you break its cells and release compounds that react to form a gas called syn-propanethial-S-oxide. This gas rises from the onion and reaches your eyes.

Your eyes react to the gas as an irritant and produce tears to wash it away. The extra tears help protect your eyes, which is why cutting onions often makes you cry.
**Work:**

```
What is the difference between a CV and a cover letter? Keep it short.
```
A CV (Curriculum Vitae) is a document that lists your education, work experience, skills, and qualifications. It provides a factual summary of your background.

A cover letter is a short letter sent with your CV that explains why you are applying for a specific job and why you are a good fit for that role.
Common topics -- the answers should feel solid.

#### Step B: Something AI may NOT know

**Daily:**

```
What were the main news headlines in my city today? If you cannot
be sure, say so clearly instead of guessing.
```I can't be certain of the main headlines in your city today. Based on your apparent location near Narowal, Punjab, I found some recent local and regional news, but I could not verify a complete "today's headlines" list from reliable local news sources.

Some recent items relevant to Narowal and the surrounding area include:

Severe weather and thunderstorms recently affected Narowal district, with reports of deaths and injuries caused by lightning strikes, strong winds, and collapsing structures.
Punjab authorities have continued issuing weather-related advisories following recent storms and heavy rainfall in parts of the province.

Because I cannot reliably verify the full set of today's local headlines for your exact city, I don't want to guess. If you tell me the city name (for example, Narowal, Shakargarh, Zafarwal, or another city), I can do a more targeted search and provide a more accurate summary.

**Work:**

```
What is the current minimum notice period an employer must give
before changing an employee's contract in my country? Be specific.
If you are not sure this is current, say so instead of guessing.
```
If you mean Pakistan, I am not sure there is a single current legal minimum notice period that employers must give before changing an employee's contract. The required notice often depends on the employment contract, the type of change, and the applicable provincial labour laws.

I can verify the specific rule if you tell me your province and employment type.
A legal/HR fact that changes over time and varies by country -- watch whether the AI gives a confident number anyway.

**Write it down:*Did the AI admit when it wasn't sure, or sound confident anyway?
AI admitted when it wasn't sure.
> **Takeaway:** Always ask "How would the AI even know this?" For recent, local, or private facts, make it search or admit uncertainty.

---

### 3. The 3 Retrieval Modes

**8 min -- steer pretrained / search / research**

**Goal:** See how your wording makes the AI answer from memory, search the web, or run deep research.

**Needs:** a tool with web search on (most have it by default)

#### Mode 1: Pretrained (from memory)

**Daily:**

```
Romeo and Juliet, from two feuding families in Verona, fall in love and secretly marry. After Romeo kills Juliet’s cousin Tybalt in a fight, he is banished from the city. To avoid an arranged marriage, Juliet takes a potion that makes her appear dead. Romeo believes she has truly died, takes his own life, and when Juliet awakens and finds him dead, she kills herself, leading their families to reconcile.```

No search needed -- this doesn't change week to week. Should be instant.

#### Mode 2: Web search (fresh info)

**Daily:**

```
What's the weather forecast for my city this weekend? Use a
current source and cite it.
```
For Narowal this weekend, expect very hot and mostly dry weather. Temperatures are forecast to reach about 40°C on Saturday and 39°C on Sunday, with plenty of sunshine and little chance of rain.
**Work:**

```
What are the latest developments this month in [your field]?
Cite each claim, and mark anything you can't support as 'unverified'.
```
Here are some notable digital marketing developments this month (June 2026):

Google Ads expanded AI-driven bidding tools. Google announced wider availability of Smart Bidding Exploration and additional bidding/budgeting updates designed to help advertisers find new conversion opportunities.
Google's data and measurement ecosystem continues to change. A 37-month limit on granular Google Ads reporting data is now in effect, affecting long-term campaign analysis and reporting workflows.
Meta is increasing automation in advertising. Recent updates to Meta's Advantage+ campaigns strengthen AI-driven budget allocation, creative optimization, and integration with conversion tracking systems.
Search visibility and AI-generated search results remain a major focus. The UK's Competition and Markets Authority introduced new requirements aimed at making Google's search rankings, including AI-generated results, more transparent and fair for businesses.
AI-generated advertising is moving into mainstream media. Disney announced a beta AI-powered ad creation system that can generate video ads for advertisers using existing creative assets.
Industry discussion is increasingly centered on AI-first marketing. Marketing leaders are emphasizing that as AI makes content creation easier, differentiation will depend more on creativity, brand strategy, and customer insight.

Unverified: Claims that Meta will soon run "nearly 100% AI-powered advertising" or that specific platform performance declines are industry-wide trends are discussed in community forums, but I could not verify them from authoritative primary sources this month.
Notice if it shows it searched. "Today / this week / latest / my city" are the trigger words.

#### Mode 3: Deep research (a structured report)

**Work:**

```
Research [a topic you care about] thoroughly. Use reputable
sources only (government sites, peer-reviewed studies, official
reports -- not forums). Produce a structured report with:
(1) the 3 most important points, (2) a comparison table,
(3) 3 open questions. Cite sources.
``` Structured Report: Artificial Intelligence (AI) in Healthcare
1. Three Most Important Points
1. AI is improving diagnosis and clinical decision-making

AI systems are increasingly used in medical imaging, disease prediction, treatment planning, and patient monitoring. Research shows that diagnostic imaging remains the most common healthcare AI application, while newer uses include wearable-device data and predictive analytics.

2. Governance, safety, and bias remain major challenges

Many studies highlight concerns about algorithmic bias, lack of transparency, privacy risks, and unequal performance across patient groups. Researchers and health systems emphasize the need for ongoing monitoring and ethical oversight before large-scale deployment.

3. Adoption is accelerating, but real-world evidence is still limited

Although AI promises cost savings and workflow improvements, many economic evaluations rely on theoretical models rather than long-term clinical evidence. Governments and organizations such as the OECD are developing frameworks to scale AI responsibly.

2. Comparison Table
Aspect	Benefits of AI in Healthcare	Current Limitations
Diagnosis	Faster image analysis and disease detection; can approach expert-level performance in some tasks.	Performance may vary across populations and settings.
Efficiency	Can automate routine tasks and support clinical workflows.	Integration into existing systems can be costly and complex.
Access to Care	May expand services in underserved or remote regions through telemedicine and mobile diagnostics.	Requires digital infrastructure and workforce training.
Regulation	Growing number of authorized AI medical devices and emerging policy frameworks.	Regulatory approaches remain fragmented across jurisdictions.
Ethics	Potential to support more personalized care.	Privacy, explainability, accountability, and bias remain unresolved issues.
3. Three Open Questions
How can healthcare organizations continuously monitor AI systems after deployment to ensure safety and fairness over time?
What regulatory framework can balance rapid innovation with patient protection across different countries?
Will long-term real-world studies confirm the projected cost savings and clinical benefits reported in current models?
Sources
OECD, Scaling Artificial Intelligence in Health (2026).
npj Digital Medicine, How AI is used in FDA-authorized medical devices (2025).
Frontiers in Public Health, Economic, Ethical, and Regulatory Dimensions of AI in Healthcare (2025).
European Journal of Medical Research, Artificial Intelligence in Healthcare and Medicine (2025).
BMC Primary Care, AI Implementation in Primary Health Care (2025).
npj Digital Medicine, FAIR-AI Framework (2025).

Words like "research thoroughly," "report," "cite sources," "use these source types" steer toward the deepest mode.

**Write it down:** The prompts from my previous questions that would require AI to perform a web search are:

“What’s the weather forecast for my city this weekend? Use a current source and cite it.”
→ This requires real-time, location-specific weather data.
“What are the latest developments this month in digital marketing? Cite each claim…”
→ This requires up-to-date industry news and recent changes.
“What is the current minimum notice period an employer must give before changing an employee’s contract in my country?”
→ This requires country-specific, current legal information.
“Research any active topic thoroughly. Use reputable sources only…”
→ This requires external sources and verification of current information.

These prompts involve time-sensitive, location-specific, or research-based information, so web search would be necessary to provide accurate and reliable answers.
> **Takeaway:** You don't click a mode -- your wording picks it. Name your sources and ask for citations to keep web answers honest.

---

## Part 2: Talking to AI Well

### 4. Context Is Everything

**6 min -- brief it like a colleague**

**Goal:** Load context up front instead of making the AI guess.

#### Use this shape for both

**Daily:**

```
I need help planning dinner for tonight.
Here is what you need to know:
- I have chicken, rice, onions, and yogurt in the kitchen
- I have only 30 minutes
- One person at the table doesn't eat spicy food
What I want back: 3 simple meal options, no commentary.
```
Yogurt Chicken Rice Bowl
Cook chicken with onions, season lightly with salt and pepper. Serve over boiled rice with a side of plain yogurt.
Mild Chicken & Onion Stir Rice
Sauté onions, add diced chicken, cook until tender, mix with cooked rice. Serve with yogurt on the side for cooling.
Creamy Yogurt Chicken Rice
Cook chicken with onions until soft, turn off heat, mix in yogurt to create a mild creamy sauce, serve over rice.
**Work:**

```
I need help writing a short update for my team.
Here is what you need to know:
- We finished the customer survey this week
- 2 tasks are still pending (the report and the slides)
- The reader is my team, who like quick bullet points
What I want back: a 4-line status update, friendly tone.
```

**The template (copy and fill in):**

```Hi team 👋

* We’ve successfully completed the customer survey this week
* The report and slides are still in progress
* We’re working on wrapping both up next
  Thanks everyone for the great effort so far!

I need help with [your task].
Here is what you need to know:
- [fact 1 -- a constraint, like time or budget]
- [fact 2 -- who it's for]
- [fact 3 -- anything the AI couldn't guess]
What I want back: [a list / an email / 3 options / a plan].
```
Here’s a simple Meta Ads plan based on your details:

Option 1: Single Conversion Campaign (Best for Sales)
Objective: Sales / Conversions
Budget: $150 total (3 days ≈ $50/day)
Targeting: Women in Pakistan, age 18–40
Interests: Beauty, skincare, makeup, cosmetics, salons, online shopping
Placement: Automatic placements (focus on Instagram + Facebook feeds/Reels)
Creative: 1–2 short videos showing product before/after or usage
CTA: “Shop Now” / “Order Today”
Option 2: Engagement + Retargeting Strategy (Safer start)

Phase 1 (Day 1–2): Awareness

Objective: Engagement / Video views
Target: Women in Pakistan
Content: Short beauty demo video
Goal: Build warm audience

Phase 2 (Day 3): Sales

Objective: Conversions
Target: People who engaged in last 2 days
CTA: Strong offer + urgency
Option 3: Simple Boosted Post Strategy (Beginner-friendly)
Post: One strong beauty product video/image
Boost for 3 days
Audience: Women in Pakistan (broad + beauty interest)
Budget: $150 total
Goal: Reach + basic sales traffic
CTA: “Send Message” or “Shop Now”
**Write it down:** Which single piece of context changed the answer the most?

“3 days under 150 dollar”

Why it changed the answer the most:

This constraint directly shaped the entire ad strategy structure.

Because of it, AI had to:

Prioritize short-term performance strategies (no long testing phases)
Avoid complex long funnels (like week-long optimization or scaling plans)
Focus on quick conversion setups and simple campaign structures
Limit recommendations to low-budget, high-impact targeting
Secondary important factors (less impact than budget + duration):
“women beauty” → determined audience + interests + creative style
“run in Pakistan” → defined geographic targeting and platform assumptions

But the budget + time limit combination (3 days / $150) was the key constraint that forced the response into a fast, simplified performance plan instead of a full marketing strategy.
> **Takeaway:** Five lines of good context beats five paragraphs of clever wording. When the topic changes, start a new chat.

---

### 5. Think Hard

**6 min -- hand it a real, hard decision**

**Goal:** Invoke reasoning mode and ask for structured output, not a wall of prose.

#### A quick contrast

Ask a tricky question normally, then ask again with "think hard." Compare.

**Daily:**

```
I have $200 to improve my home office and I work from home full
time. Think hard before answering. Then give me:
1) the 3 upgrades with the biggest impact on comfort and focus,
2) which one you'd do first and why,
3) one thing I should NOT waste money on.
```
1) Top 3 upgrades (highest impact for comfort + focus)
1. Ergonomic chair (highest impact)

A proper chair with lumbar support changes everything:

Reduces back/neck pain
Improves posture for long work sessions
Directly increases focus because discomfort disappears
2. External monitor (or larger screen setup)
Reduces eye strain and mental fatigue
Makes multitasking much easier (tabs, documents, meetings)
Feels like an “instant productivity boost”
3. Lighting upgrade (desk lamp or soft white lighting)
Improves alertness and reduces fatigue
Helps during late-night work sessions
Makes your workspace feel more professional and less tiring
2) What I would do first (and why)

Start with the ergonomic chair.

Because:

You physically sit in it all day
Poor seating causes constant low-level discomfort you may not even notice until it’s fixed
It has the biggest long-term effect on health, focus, and stamina compared to everything else

If your body is uncomfortable, even a great monitor or lighting won’t fully help.

3) What NOT to waste money on

Avoid expensive “aesthetic-only” desk accessories first (like RGB decor, fancy organizers, or minimal gadgets that don’t improve function).

Why:

They don’t improve comfort or productivity
They often distract from real upgrades
You get better value from ergonomic + workflow tools
**Work:**

```
I'm choosing between two job offers. Offer A: higher pay, longer
commute, less interesting work. Offer B: lower pay, remote,
steeper learning curve. I value learning and time with family.
Think hard. Then tell me:
1) the 3 trade-offs that actually matter for me,
2) which you'd pick and why,
3) under what conditions your answer flips.
```
Based on your values of learning and family time, here is the direct breakdown of your choices.1) The 3 Trade-Offs That Actually Matter for YouCommute Time vs. Family Presence: Offer A steals physical time via a long commute. Offer B eliminates transit, giving you immediate daily access to family.Stagnant Income vs. Skill Growth: Offer A pays more now but offers less interesting work. Offer B pays less but builds a steeper learning curve, which increases your long-term market value.Mental Energy vs. Exhaustion: Offer A drains your energy through boredom and traffic. Offer B challenges your mind, leaving you more fulfilled when you step away from your desk to see family.2) Which I'd Pick and WhyI would pick Offer B.You explicitly state that you value learning and family. Offer B directly aligns with both core values by eliminating the commute entirely and forcing you onto a steep learning curve. Offer A actively works against your values by wasting your time in transit and offering unstimulating work, making the higher salary a short-term trap.3) Under What Conditions the Answer FlipsThe decision flips back to Offer A only under these specific conditions:Financial Distress: The pay cut for Offer B endangers your family's ability to cover basic needs like housing, food, or healthcare.Isolation Stress: You find that fully remote work hurts your mental health, making you irritable or disconnected from your family.No Mentorship: Offer B’s "steep learning curve" turns out to be a chaotic environment with zero guidance, causing severe burnout.If you would like to test the numbers, let me know the exact salary difference between the two offers and your expected daily commute hours so we can calculate the true hourly rate of each job.
**Write it down:** Did "think hard" produce a deeper answer? What changed?
The "think hard" prompt shifted the response from a generic feature comparison to a targeted evaluation based strictly on your personal values. In the first turn, the analysis focused on immediate utility by simply identifying the primary keyboard shortcuts for your technical query. In the second turn, the deeper prompt forced a structural change that looked past surface-level factors like salary and commute. Instead of listing basic pros and cons, it reframed the decision around your core anchors of family time and skill acquisition. This approach exposed how a higher salary could become a psychological trap if it costs you personal freedom and mental growth. Ultimately, it transformed standard career advice into a personalized strategic roadmap with clear conditional flipping points.
> **Takeaway:** Save thinking mode for multi-trade-off questions you'd want a human to take their time on -- not quick lookups.

---

### 6. Stop the Flattery

**6 min -- sycophancy**

**Goal:** See how the way you ask pushes AI to just agree with you.

#### Step A: The "bait" prompt (AI tends to agree)

**Daily:**

```
Don't you think mornings are obviously the best time to exercise?
```
AI didn't agree with my prompt.Infact it gave me the reasons why mornings are not the best time to exercise.
**Work:**

```
Don't you agree that working from home is clearly better than the
office?
```AI didn't agree with my prompt saying, working from home is not universally better than the office, as the ideal environment depends entirely on an individual's role, personality, and personal values.


Notice: it probably agrees and lists reasons that match what you implied.

#### Step B: The neutral prompt (AI actually thinks)

**Daily:**

```
Compare exercising in the morning versus the evening. List the
strongest case for each, and what kind of person each option
suits best. Don't tell me which to pick.
``` The comparison between morning and evening exercise reveals distinct biological and behavioral advantages for each timeframe.The Case for Morning WorkoutsThe Strongest ArgumentMorning workouts ensure unmatched consistency and optimal metabolic priming. Exercising first thing in the morning eliminates the risk of daily distractions, late work meetings, or evening fatigue hijacking your fitness routine. Furthermore, clinical studies indicate that consistent morning exercise enhances morning biological signals, which can improve glucose tolerance, accelerate fat oxidation, and lower blood pressure over time.
Who It Suits BestThe Busy Professional: Individuals with unpredictable evening schedules or heavy family commitments after work.The Routine-Driven Individual: People who rely on strict habits, structure, and an immediate dopamine boost to set a productive tone for the rest of the day.The Weight-Loss Seeker: Anyone whose primary focus is metabolic conditioning and optimizing fasted or early-day fat burning.The Case for Evening Workouts. 
The Strongest Argument
Evening workouts capitalize on peak physical performance and serve as a powerful psychological decompressor. Biologically, human core body temperature peaks between 2:00 PM and 6:00 PM, meaning muscles are warmer, joints are more flexible, and anaerobic power (strength and speed) is naturally at its highest. This significantly reduces injury risk and allows for higher intensity training, while simultaneously acting as a healthy boundary to sweat away the mental stress accumulated during the workday.Who It Suits BestThe Strength Athlete: Powerlifters, bodybuilders, or sprinters looking to maximize muscle hypertrophy, lift heavier weights, and utilize peak physical reaction times.The Night Owl: Individuals whose circadian rhythms make waking up early highly disruptive to their sleep quality and morning alertness.The Stressed Worker: People who need a physical outlet to transition mentally from high-pressure work brain to relaxed home brain.

**Work:**

```
Compare working from home versus working in the office. List the
strongest arguments for each. Don't tell me which is better.
```Working from Home (WFH) — strongest arguments
Flexibility and time control: No commuting means more usable personal time and easier scheduling around deep work, errands, or family needs.
Higher focus for many tasks: Fewer office interruptions, meetings-by-accident, and casual distractions can improve concentration for independent work.
Cost savings: Reduced transport costs, meals, coffee spending, and sometimes housing flexibility.
Comfort and personalization: You can control environment (noise, lighting, temperature, seating setup).
Wider talent access (for employers, indirect benefit for workers): Remote systems often allow more role flexibility and global opportunities.
Working in the Office — strongest arguments
Stronger collaboration and communication: Faster feedback loops, spontaneous discussions, and easier teamwork on complex problems.
Clear separation of work and home life: Physical boundary helps many people “switch off” after work and avoid burnout overlap.
Access to resources and structure: Better equipment, stable internet, meeting rooms, and a structured routine.
Visibility and career signaling: Being present can increase informal recognition, mentorship opportunities, and relationship-building.
Fewer home distractions: Some people find home environments less disciplined due to family, chores, or comfort distractions.

**Write it down:** Did Step B give you a reason you hadn't thought of? Write one.
No, it wasn't like that.
> **Takeaway:** Verbs like find, prove, defend, confirm hand the AI your answer. Use compare, evaluate, list both sides instead.

*Note: newer models resist obvious flattery, so the bait may make the AI hedge rather than fully agree. The lesson still holds -- notice how much more balanced Step B is.*

---

### 7. The Brainstorm-Iterate Loop

**8 min -- the highest-leverage habit**

**Goal:** Never accept the first answer. The value is in the back-and-forth.

#### Round 1: Ask for OPTIONS, not one answer

**Daily:**

```
I want a small hobby that costs almost no money and that I can do
for 15 minutes at home. Give me 5 different ideas, one line each.
Don't explain any of them yet.
```Freewriting in a notebook or notes app for 15 minutes
Bodyweight stretching or light yoga routine
Learning simple drawing or doodling shapes and objects
Solving logic puzzles or Sudoku
Practicing basic meditation or breathing exercises

**Work:**

```
I need to write a short message asking a coworker to send me a
file they keep forgetting to send. I want to sound friendly, not
annoyed. Give me 5 different versions, one or two lines each.
Don't explain any of them yet.
```1. Hey! Just a quick reminder—could you please send me the file when you get a chance? Thanks 🙂

2. Hi, hope you’re doing well! When you have a moment, can you share that file with me?

3. Hey, just checking in on the file—whenever you’re free, please send it over. Appreciate it!

4. Hi! Whenever you get a chance, could you forward me that file? Thank you!

5. Hey, just looping back on the file—no rush, but please send it when possible 🙂


#### Round 2: Give feedback, ask again

Read the 5. Then type (fill the blanks):

```
I don't like option ___ because ___________.
I like option ___ but I want it to be more __________.
Give me 5 NEW ideas based on this feedback.
```
15-minute guided breathing exercise with calming music or nature sounds
Short body scan meditation (focusing on each part of your body step by step)
Light shadowboxing or slow movement flow routine in your room
Simple origami folding using scrap paper or old notes
Memory game practice (try recalling lists, numbers, or objects after a short focus session)
#### Round 3: Expand the winner

**Daily:**

```Great choice—guided breathing is one of the easiest habits to start.

15-minute guided breathing plan (this week)
Step 1: Set your time (Day 1–7)
Pick one fixed time daily (e.g., morning after waking OR before sleep)
Keep it the same every day so it becomes automatic
Step 2: Prepare your space (1 minute)
Sit on a chair or bed with your back straight
Put your phone on “Do Not Disturb”
Use headphones if possible (optional but helpful)
Step 3: Start breathing session (10–12 minutes)

Choose ONE simple pattern:

Box breathing:
Inhale 4 sec → Hold 4 sec → Exhale 4 sec → Hold 4 sec (repeat)

OR

4-7-8 breathing:
Inhale 4 sec → Hold 7 sec → Exhale 8 sec (repeat slowly)

Keep eyes closed and focus only on breath.

Step 4: Finish calmly (2–3 minutes)
Sit quietly without trying to do anything
Let your breathing return to normal
Notice how your body feels
Step 5: Simple tracking (optional)
Just mark ✔ on a note each day you do it
Don’t overthink missed days—just continue next day
I'll go with [your favorite hobby]. Give me a simple step-by-step
plan to start it this week.
```

**Work:**

```
I'll go with version [number]. Now make it slightly warmer and
add a friendly closing line, but keep it under 3 sentences.
```
Hey! Just a quick reminder—could you please send me the file when you get a chance? Thanks so much 🙂
No rush at all, I really appreciate it!
**Write it down:** Was the idea you ended with better than anything in Round 1? Why?

> **Takeaway:** Load context, ask for options, give feedback, repeat, expand. The value isn't the first answer; it's the loop.

---

## Part 3: Beyond Text

### 8. Multimodal -- Image & Audio

**7 min -- give the AI a photo to read**

**Goal:** Practice handing AI something that isn't text.

**Needs:** a photo on your device (a receipt, handwritten note, or whiteboard)

#### Image input: transcribe & summarize

Upload any photo of text, then paste this:

**Daily:**

```
Here's a photo of a handwritten note (or receipt). Transcribe
what it says. Keep the original wording. If a word is unclear,
mark it [unclear] and give your two best guesses.
```
Transcription:

Dear Nan,
You make the best
toast and butter

Love Oscar
**Work:**

```
Here's a photo of a whiteboard from a meeting. List the main
points as bullets, then list any action items you can spot.
Flag anything you couldn't read with confidence.
```
Main points (from the whiteboard)
There are no secrets to success
Success is the result of preparation
Success also comes from hard work and learning from failure
Action items
None explicitly stated
Text on whiteboard (for clarity)
“There are no secrets to success, it is the result of preparation, hard work and learning from failure.”
Confidence / unclear parts
“preparation” — slightly faint but readable
The rest of the text is clear and confidently readable
AI is great at the gist, weak on tiny detail -- always check totals and the bits it flagged.

#### Bonus: let the AI write an image prompt

```
Write me a detailed image-generation prompt for a cozy,
watercolor-style illustration of a cat reading a book by a
window, suitable for a greeting card. Then I'll paste it into
an image tool.
```
A cozy, warm watercolor-style illustration of a cute cat reading a book by a window on a peaceful afternoon. The cat is softly fluffy, sitting comfortably on a cushioned windowsill with a small blanket draped beside it. Outside the window, there is a gentle, dreamy view of falling golden leaves or light rain, depending on mood, creating a calm atmosphere. Soft natural light filters through the window, casting warm highlights and subtle shadows inside the room.

The interior is cozy and inviting: a few stacked books, a small cup of tea or coffee on the side, and subtle homey details like a knitted pillow, a plant in a ceramic pot, and wooden textures. The cat looks deeply focused and peaceful, holding or resting against an open book.

Art style: traditional watercolor painting with soft edges, gentle brush strokes, pastel tones, and a storybook illustration feel. Emphasize warmth, comfort, and emotional coziness.

Lighting: soft golden-hour lighting, warm and diffused.

Mood: relaxing, nostalgic, peaceful, wholesome.

Composition: centered or slightly off-center cat as the focal point, with the window framing the background naturally.

High detail, greeting card quality, visually soothing, no text, no watermark.
**Write it down:** What did the AI read correctly? What did it get wrong or flag?
) Handwritten note image
✅ What AI read correctly:
“Dear Nan,” → correct
“You make the best toast and butter” → correct meaning and wording
“Love Oscar” → correct
⚠️ What AI flagged / could be tricky:
AI did not flag any word as unclear in this one because everything was readable
However, very slight uncertainty always exists with handwriting, but nothing significant here
2) Whiteboard image
✅ What AI read correctly:
“There are no secrets to success”
“it is the result of preparation, hard work and learning from failure”
⚠️ What AI flagged / uncertainty:
“preparation” → noted as slightly faint but still readable (no real doubt, just lower contrast)
AI did not detect any missing words or errors in meaning
Punctuation (like the comma after “success”) was inferred from standard formatting, not clearly emphasized in writing
Overall summary
Both images were read with high confidence
No major words were misread or marked as unclear
Only minor note: faint handwriting on “preparation,” but still confidently interpreted
> **Takeaway:** AI does the boring 90% (typing it out) so you focus on the careful 10% (checking what it flagged).

---

### 9. Build a Small App

**8 min -- one prompt, a working tool**

**Goal:** Use the Goal / Input / Output shape to build a real working artifact.

**Needs:** a tool with Artifacts (Claude) or Canvas (ChatGPT / Gemini)

#### The three-slot recipe

**Daily:**

```
Build me a tip calculator.
Goal: split a bill and add a tip.
Input: I type the total, the tip %, and the number of people.
Output: show the tip amount, the grand total, and each person's
share. Make it clean and easy to use. Show me the working version.
```

**Work:**
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tip Calculator</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      width: 320px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }

    h2 {
      text-align: center;
      margin-bottom: 15px;
    }

    input {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 14px;
    }

    button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      background: #2d89ef;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 15px;
    }

    button:hover {
      background: #1b6fd1;
    }

    .result {
      margin-top: 15px;
      padding: 10px;
      background: #f1f1f1;
      border-radius: 8px;
      font-size: 14px;
      line-height: 1.6;
    }
  </style>
</head>

<body>

  <div class="card">
    <h2>Tip Calculator</h2>

    <input type="number" id="bill" placeholder="Total Bill Amount" />
    <input type="number" id="tip" placeholder="Tip % (e.g. 10)" />
    <input type="number" id="people" placeholder="Number of People" />

    <button onclick="calculateTip()">Calculate</button>

    <div class="result" id="result"></div>
  </div>

  <script>
    function calculateTip() {
      let bill = parseFloat(document.getElementById("bill").value);
      let tipPercent = parseFloat(document.getElementById("tip").value);
      let people = parseInt(document.getElementById("people").value);

      if (!bill || !tipPercent || !people) {
        document.getElementById("result").innerHTML = "Please fill all fields correctly.";
        return;
      }

      let tipAmount = (bill * tipPercent) / 100;
      let total = bill + tipAmount;
      let perPerson = total / people;

      document.getElementById("result").innerHTML = `
        💰 Tip: $${tipAmount.toFixed(2)} <br>
        🧾 Total: $${total.toFixed(2)} <br>
        👥 Per Person: $${perPerson.toFixed(2)}
      `;
    }
  </script>

</body>
</html>
```
Build me a simple countdown timer for focused work.
Goal: 25-minute work sessions with 5-minute breaks.
Input: I press start.
Output: a large timer counting down, a clear sound when each
session ends, and a clean layout. Show me the working version.
``` <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Focus Timer</title>

<style>
    body {
        margin: 0;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background: #0f172a;
        color: #fff;
        font-family: Arial, sans-serif;
    }

    h1 {
        margin-bottom: 20px;
        font-size: 28px;
    }

    #timer {
        font-size: 80px;
        font-weight: bold;
        margin: 20px 0;
        letter-spacing: 2px;
    }

    .status {
        font-size: 20px;
        margin-bottom: 20px;
        color: #38bdf8;
    }

    button {
        padding: 12px 25px;
        font-size: 18px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        background: #22c55e;
        color: white;
        transition: 0.3s;
    }

    button:hover {
        background: #16a34a;
    }
</style>
</head>

<body>

<h1>Focus Timer</h1>
<div class="status" id="status">Ready</div>
<div id="timer">25:00</div>
<button onclick="startTimer()">Start</button>

<script>
let workTime = 25 * 60;
let breakTime = 5 * 60;
let isWork = true;
let timeLeft = workTime;
let interval = null;

function formatTime(seconds) {
    let min = Math.floor(seconds / 60);
    let sec = seconds % 60;
    return `${String(min).padStart(2,'0')}:${String(sec).padStart(2,'0')}`;
}

function playBeep() {
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    const oscillator = ctx.createOscillator();
    oscillator.type = "sine";
    oscillator.frequency.setValueAtTime(800, ctx.currentTime);
    oscillator.connect(ctx.destination);
    oscillator.start();
    oscillator.stop(ctx.currentTime + 0.5);
}

function updateDisplay() {
    document.getElementById("timer").innerText = formatTime(timeLeft);
    document.getElementById("status").innerText = isWork ? "Work Session" : "Break Time";
}

function tick() {
    timeLeft--;

    if (timeLeft < 0) {
        playBeep();

        isWork = !isWork;
        timeLeft = isWork ? workTime : breakTime;
    }

    updateDisplay();
}

function startTimer() {
    if (interval) return; // prevent multiple starts

    updateDisplay();
    interval = setInterval(tick, 1000);
}
</script>

</body>
</html>

#### Then iterate on it (it edits the existing app in place):

```
Make the buttons bigger and change the color theme to calm blue.
Add a reset button.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Focus Timer</title>

<style>
    body {
        margin: 0;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background: linear-gradient(135deg, #0ea5e9, #1e3a8a);
        color: #fff;
        font-family: Arial, sans-serif;
    }

    h1 {
        margin-bottom: 20px;
        font-size: 32px;
    }

    #timer {
        font-size: 90px;
        font-weight: bold;
        margin: 20px 0;
        letter-spacing: 2px;
    }

    .status {
        font-size: 22px;
        margin-bottom: 20px;
        color: #dbeafe;
    }

    .buttons {
        display: flex;
        gap: 15px;
    }

    button {
        padding: 18px 35px;
        font-size: 20px;
        border: none;
        border-radius: 12px;
        cursor: pointer;
        color: white;
        transition: 0.3s;
        min-width: 140px;
    }

    .start {
        background: #22c55e;
    }

    .start:hover {
        background: #16a34a;
    }

    .reset {
        background: #ef4444;
    }

    .reset:hover {
        background: #dc2626;
    }
</style>
</head>

<body>

<h1>Focus Timer</h1>

<div class="status" id="status">Ready</div>
<div id="timer">25:00</div>

<div class="buttons">
    <button class="start" onclick="startTimer()">Start</button>
    <button class="reset" onclick="resetTimer()">Reset</button>
</div>

<script>
let workTime = 25 * 60;
let breakTime = 5 * 60;
let isWork = true;
let timeLeft = workTime;
let interval = null;

function formatTime(seconds) {
    let min = Math.floor(seconds / 60);
    let sec = seconds % 60;
    return `${String(min).padStart(2,'0')}:${String(sec).padStart(2,'0')}`;
}

function playBeep() {
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    const oscillator = ctx.createOscillator();
    oscillator.type = "sine";
    oscillator.frequency.setValueAtTime(800, ctx.currentTime);
    oscillator.connect(ctx.destination);
    oscillator.start();
    oscillator.stop(ctx.currentTime + 0.5);
}

function updateDisplay() {
    document.getElementById("timer").innerText = formatTime(timeLeft);
    document.getElementById("status").innerText =
        isWork ? "Work Session" : "Break Time";
}

function tick() {
    timeLeft--;

    if (timeLeft < 0) {
        playBeep();
        isWork = !isWork;
        timeLeft = isWork ? workTime : breakTime;
    }

    updateDisplay();
}

function startTimer() {
    if (interval) return;

    updateDisplay();
    interval = setInterval(tick, 1000);
}

function resetTimer() {
    clearInterval(interval);
    interval = null;

    isWork = true;
    timeLeft = workTime;

    updateDisplay();
}
</script>

</body>
</html>
**Write it down:** Did it work first try? What did you change in the iterate step?
yes it worked and in this iteration, I changed the UI to a calm blue gradient theme to make it more relaxing for focus work, made the buttons bigger and easier to click with clearer colors for Start and Reset, and added a Reset function so I can stop the timer and return it back to the original 25-minute work session anytime.
> **Takeaway:** The skill isn't coding -- it's writing a clear brief (Goal / Input / Output) and iterating. Small one-screen tools work great.

---

### 10. Data Analysis

**10 min -- expose the silent failure mode**

**Goal:** Learn to make the AI actually run code -- and verify that it did.

#### Round 1: The trap (don't mention code)

In a fresh chat, paste this exactly:

```
Here are 18 numbers: 47, 52, 89, 91, 23, 67, 78, 12, 95, 44,
88, 71, 33, 56, 99, 18, 64, 82. What is the median, the average,
and which numbers are outliers? Be specific.
```

Did it show a code block that ran? Or just a paragraph with numbers? Note your answer.
just a paragraph with numbers
#### Round 2: The fix (force the code)

```
Now run that calculation again -- but this time write and run
code to do it, and show me the code you ran.
```
import statistics

# The dataset
data = [47, 52, 89, 91, 23, 67, 78, 12, 95, 44, 88, 71, 33, 56, 99, 18, 64, 82]

# 1. Sort the data
sorted_data = sorted(data)

# 2. Calculate Average (Mean)
average = sum(sorted_data) / len(sorted_data)

# 3. Calculate Median
median = statistics.median(sorted_data)

# 4. Calculate Outliers using IQR Rule
# Split the data into lower and upper halves to find Q1 and Q3
n = len(sorted_data)
lower_half = sorted_data[:n//2]
upper_half = sorted_data[n//2:]

q1 = statistics.median(lower_half)
q3 = statistics.median(upper_half)
iqr = q3 - q1

lower_bound = q1 - (1.5 * iqr)
upper_bound = q3 + (1.5 * iqr)

outliers = [x for x in sorted_data if x < lower_bound or x > upper_bound]

# Output results
print(f"Sorted Data: {sorted_data}")
print(f"Average: {average:.2f}")
print(f"Median: {median}")
print(f"Q1: {q1}, Q3: {q3}, IQR: {iqr}")
print(f"Lower Bound: {lower_bound}, Upper Bound: {upper_bound}")
print(f"Outliers: {outliers if outliers else 'None'}")
Correct answers: median 65.5, average ~61.6, no clear outliers (roughly even spread). If Round 1 was off, you just saw the silent failure mode.

#### Bonus (Work): if you have a spreadsheet

**Needs:** any CSV (a budget, grades, a tracker export)

```
Here's a CSV. Before analyzing anything, tell me the exact row
count, the column names, and the date range. Then write and run
code to show me the 3 most interesting patterns, with a chart.
Show me the code you ran.
```

**Write it down:** Did Round 1 run code or guess? How could you tell the difference?
In Round 1, AI did not run code. AI performed the calculations using internal reasoning (essentially "mental math" for an AI).
Here is how you can tell the difference and why it matters:
1. How to tell the difference
The "Show Code" Toggle: In most AI interfaces, if the AI runs actual code, you will see a distinct block or a button that says "Finished working" or "View Analysis." If you don't see a way to expand a code block to see Python logic, the AI just "wrote" the answer like a human would.
Step-by-Step Arithmetic: In Round 1, AI showed the addition string (12 + 18 + 23...). This is a sign of "text-based reasoning." When AI runs code, AI usually just presents the final result and the code block itself.
The "Hallucination" Risk: If AI had 100 numbers instead of 18, AI's "mental math" in Round 1 would almost certainly have made a mistake (like skipping a number or miscalculating the sum). Code, however, is deterministic—if the logic is right, the math is perfect every time.
2. Was Round 1 a "Guess"?
It wasn't a random guess, but it was probabilistic.
How AI did Round 1: AI looked at the numbers, sorted them in "working memory," and performed the addition. Because AI is a language model, AI is predicting the most likely next number in a sequence. For small sets of numbers, AI is very good at this.
How AI did Round 2: AI wrote a Python script and (internally or via a tool) executed it. The result came from a CPU performing literal binary math, which is 100% reliable.
3. Why you should prefer code for math
If you ask an AI to do math, you can spot "text-based" (non-code) errors by looking for these red flags:
Counting Errors: Asking "How many numbers are in this list?" and the AI says 17 when there are 18.
Sorting Errors: Missing a number when rearranging them from smallest to largest.
Summation Errors: Being off by a few digits on a long string of addition.
The Verdict: If the task involves more than 10 numbers or complex formulas (like IQR or Standard Deviation), always ask the AI to "write and run code" to ensure you aren't getting a "hallucinated" calculation.
> **Takeaway:** Always say "write and run code, show me the code." No code block = it probably guessed.

---

## Part 4: Working Safely & Choosing Tools

### 11. Desktop Apps & Permissions

**5 min -- mostly a read + plan exercise**

**Goal:** Understand the safe workflow before you ever let an app touch real files.

**Needs:** nothing to install -- this one is about judgment. (Optional: a desktop app like Cowork.)

#### Practice the "plan, don't act" habit in chat

You can rehearse the mindset in any chat tool. Paste this:

```
Imagine you are an AI assistant with permission to reorganize a
messy folder of 50 personal files (photos, PDFs, receipts).
Before doing anything, write me a step-by-step SAFE workflow you
would follow so that nothing is lost or wrongly renamed. Then
list 3 things I should NEVER let you do.
```

**The rule to memorize:** The safe order is always: 1) tell the task, 2) ask for a plan, 3) review & edit, 4) only then approve.

**Write it down:** What's one thing you'd NEVER grant an AI app on day one?
access to all my files or data.
> **Takeaway:** Deleted files often skip the recycle bin; edits overwrite. Scope permissions tight; grow them with track record, not trust in the brand.

---

### 12. Which Model When

**8 min -- same prompt, two tools**

**Goal:** Feel how different models answer the same prompt differently.

**Needs:** two AI tools open (any two of ChatGPT / Claude / Gemini)

#### Run the SAME prompt in both

Pick one prompt. Paste it into Tool A, then Tool B. Read both answers.

**Daily:**

```
Plan a relaxing Saturday for someone who works hard all week and
lives in a city. Give me a simple hour-by-hour plan from 9am to
9pm, with cheap or free activities.
```

**Write it down:** Which tool did better on THIS task -- and what was different?
ChatGPT’s answer is better because it is simpler and easier to follow, while Gemini includes too much extra detail that feels cluttered. It also gives a more relaxed flow of the day, focuses more on the mood and experience instead of descriptions of places, and uses a more direct, user-friendly tone. Overall, it feels more practical and less like a travel guide.

> **Takeaway:** There's no single best AI -- it's "jagged." Keep two tabs open so you always have a tiebreaker. Re-test monthly; leaders rotate.

---

### 13. Models Checking Models

**10 min -- an objective quality signal**

**Goal:** Get honest feedback by making two different models grade the same draft.

**Needs:** two tools from different families (e.g. Claude + ChatGPT, not two of the same)

#### Step 1: Grade it in Tool A

Take any 150-250 word thing you wrote (an email, a paragraph from Exercise 7). Paste it, then:
 Dear Sir,

I hope you are doing well. I am writing to request a leave of absence from work for two days, from June 25 to June 26, due to a family commitment that requires my presence. This matter is important and cannot be postponed, so I would be grateful if you could approve my request.

I understand the importance of my responsibilities at work and have already completed the urgent tasks assigned to me. I will also ensure that any pending work is properly handed over to a colleague before my leave begins. If needed, I will remain available by email for any important updates or questions during this period.

I value my role in the team and appreciate your understanding regarding this request. Thank you for considering my application. I would be grateful for your approval and support.

Please let me know if you require any additional information.

Kind regards,

Sarah Ahmed

```
Score this draft 1-10 on clarity, structure, evidence, and
what's missing -- one sentence of reasoning per score. Then tell
me the single change that would raise the lowest score the most.
```Clarity: 9/10
The purpose of the email (requesting two days of leave) is stated clearly in the first paragraph and remains easy to understand throughout.

Structure: 9/10
The email follows a logical flow: request, explanation, work arrangements, appreciation, and closing.

Evidence: 5/10
The email mentions a family commitment but provides no specific details or supporting information that would help justify the request.

What's Missing: 6/10
It lacks a brief explanation of the family commitment and does not mention whether supporting documentation can be provided if required.

Single change that would raise the lowest score the most:
Add one specific sentence explaining the reason for the family commitment (for example, attending a close family member's medical appointment or important family event), which would significantly strengthen the evidence for the leave request while keeping the email professional.

#### Step 2: Same draft, same question, Tool B

Open a different-family tool. Paste the same draft and the same prompt.
Clarity: 9/10
The request is direct, polite, and clearly states the exact dates needed, leaving no ambiguity about the timeframe.

Structure: 9/10
The flow is logical and professional, moving smoothly from the initial request to workload management, and finally to contact availability.

Evidence: 4/10
While it mentions a "family commitment," it lacks any specific context or detail to justify why the matter is important enough to warrant missing work.

What's Missing & The Single Impactful Change
The letter is missing a specific named point of contact for coverage while Sarah is away.

The Single Change: Replace the vague phrase "properly handed over to a colleague" with the specific name of the coworker who has agreed to cover her duties (e.g., "handed over to John Doe").

Making this change eliminates ambiguity for the manager and instantly raises the Evidence score by proving a concrete backup plan is already in place.
#### Step 3: Compare

Put the two critiques side by side. Find any point only one of them caught -- that's the value of cross-checking.

**Write it down:** What did Tool B catch that Tool A missed (or vice versa)?
Only Critique #1 caught:(searched through gemini)

The backup plan is vague because no specific coworker is named.
Naming a colleague increases confidence that work coverage has been arranged.

Only Critique #2 caught:(searched through chatgpt)

The leave request itself is weakly justified because the family commitment is not explained.
Mentioning documentation or a brief reason would strengthen credibility.
Which suggestion is stronger?

If the goal is to get the leave approved, Critique #2's suggestion is likely more impactful because managers usually first want to know why the leave is needed. A specific reason directly addresses the weakest part of the email.

If the goal is to show professionalism and preparedness, Critique #1's suggestion is stronger because it demonstrates a concrete continuity plan.

Combined best revision: Add a brief reason for the family commitment and name the colleague covering your duties. Together, those two changes would likely raise the email from good to excellent.
> **Takeaway:** Different families have different blind spots. A point one misses, the other often catches. Save this for work where being wrong is expensive.

---

> **If you remember one thing from all 13:** Get the right context in, keep the wrong context out.

*A 13-exercise companion to "AI Prompting in 2026." Split it across sessions -- Part 1 & 2 first, Part 3 & 4 later. Exercises marked Needs require a little setup. No setup? Read it and come back when you can.*
