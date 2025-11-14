# Guide 00 — Playground Build (Everyone Starts Here)

> **Who this is for**  
> Everyone using this playbook, whether you arrive with a dream idea or zero ideas.
>
> The goal of this guide is simple: in a short session, use AI to design, build, and **deploy something small and genuinely useful that you can share**, while learning how the tools think.

---

## How this guide works (in 10 seconds)

- Use a light coaching prompt to pick a tiny, real problem from your life.  
- Turn that into a short MVP brief.  
- Build and **deploy** a small app from that brief in an AI playground (we suggest **Google AI Studio**).  
- Share it (a live link if possible, or at least a screenshot/clip).

After this, you’ll move on to the next guide to decide what you really want to build next.

---

## Step 0 — Light Idea Coach (ChatGPT, ~10 minutes)

Do this first, even if you already have a dream idea in mind. We’re starting fresh, with a small, real problem from your life.

1. Open ChatGPT (or a similar chat model) in a new tab. Create a **new chat** and name it something like `AI Product Playbook – Playground` so all conversations about this project stay together.
2. Paste the prompt below and follow the questions.

```markdown
You are my "Light Idea Coach" for an AI-powered mini app.

Your job is to help me pick ONE tiny but real problem in my own life that a simple AI-powered app could help with, and then turn that into a short MVP brief I can paste into an AI playground like Google AI Studio.

Ask me questions one at a time in this order:

1. Roles & context
   - What roles do I play in my life right now? (e.g. parent, partner, employee, runner, student, etc.)
   - Which role do I most want a tiny helper for this month?

2. Friction & struggles (for that role)
   - In that role, what are 3–5 recurring tasks that are annoying, boring, or easy to procrastinate on?
   - Which one would make the biggest difference if it were easier?

3. Job-to-be-done & outcome
   - For that problem, what job is this app doing for me?
   - What does "success" look like in one or two sentences?

4. Constraints & flavour
   - How much time per day/week would I realistically give this app?
   - What devices do I expect to use? (phone, laptop)
   - Any constraints like diet, budget, kids' ages, mileage targets, etc.

Then propose 3 concrete mini-app ideas for me, phrased like:
- [Name] – [who it's for, the core job, and the desired outcome]

Help me pick ONE that feels both fun and genuinely useful.

Finally, produce a short MVP brief with these headings:

- Persona
- Problem & context
- Job to be done
- Desired outcome (1–2 sentences)
- Vision statement ("A simple app that…")
- Value proposition (why this matters vs doing nothing / my current workaround)
- Core features (MVP) – 2–4 bullets
- Nice-to-have later – 2–3 bullets

Keep the brief under 300 words and use simple language.
```

When you have your brief, you’re ready to actually build.

---

## Step 1 — Choose a tiny, real problem

If you already have a small, real problem you care about, you can start here. Otherwise, use the MVP brief from **Step 0** and pick the idea that feels most fun *and* genuinely useful to you this week.

1. **Weekly recipe planner**  
   Plan simple meals for the week based on your constraints (time, diet, budget).

2. **Mood‑based film night picker**  
   A helper that asks how you’re feeling and suggests 2–3 films for the evening.

3. **Weekend micro‑adventure suggester**  
   Given your city, budget, and time window, propose 3 simple outings.

4. **Inbox reply helper for one type of email**  
   Draft polite, on‑point replies for e.g. meeting requests or “can you send me details?” emails.

5. **Tiny focus planner**  
   Ask 3 questions about your day and return a one‑page “today plan” with 3 priorities and 2 breaks.

6. **Learning snack designer**  
   Take a topic (e.g. “basic SQL”) and turn it into a 5‑day micro‑learning plan with 10‑minute tasks.

Don’t overthink your choice. The goal is not “my big idea”. The goal is: *get something working quickly that you’d genuinely use once or twice*.

---

## Step 2 — Open an AI playground (we suggest Google AI Studio)

Use any playground you like. The examples below assume **Google AI Studio** because:

- it runs in the browser  
- you can create agents/apps without wiring APIs  
- it’s fast to experiment, slow to get stuck

If you already love Replit, v0, Lovable or something similar, feel free to use that instead.

---

## Step 3 — Describe what you want to build

In the prompt/description box, write something like:

> "I want to build a very simple [idea] helper. It should:
>
> - ask me [2–4 key questions]
> - then return [a short, concrete output]
> - keep the interface simple enough that a beginner can use it.
>
> Please propose a first version and tell me what it can and cannot do."

Adapt the bracketed parts for the idea you chose.

Let the tool generate an initial version. Don’t worry if it’s imperfect; that’s the point.

---

## Optional — Peek under the hood (no editing)

If you’re using Google AI Studio (or a similar tool with **Preview/Code** tabs):

- Switch from **Preview** to **Code**.  
- Look at the **file list** on the left – notice that your app is made up of multiple files (components, services, config, etc.).  
- Open the main file for your app (often a component) and just scan for:
  - where the **UI text** lives  
  - where any **lists** (meals, films, tasks, etc.) are defined  
  - where click/submit handlers live (things like `onClick`, `onSubmit`).

You don’t need to change anything. This is just about building a feel for how a real app is structured behind the scenes.

---

## Step 4 — Play, poke, and purposely break it

Spend 10–20 minutes doing this:

- Try obviously “normal” inputs (your real answers).  
- Try weird or edge‑case inputs and see what happens.  
- Ask the tool how it could be improved for a real user (you).  
- Ask it what assumptions it’s making about you or your context.
- If you feel comfortable, ask it to add **one small improvement at a time** – for example: make each recipe card clickable to show details, add an "export to PDF" button, or let you change the number of people.

If you’re using Google AI Studio, you may see **feature suggestion chips** (for example, “Add ‘Favourite’ button”). These are great training wheels: click one, read how it describes the change (“In the [Component]…, add a button that…”), and then try writing your own requests in the same style for features you care about.

After each change, test it in **Preview**. Notice what worked, what broke, and what surprised you.

Your goal for this guide is to **deploy** a small app you can share. If your playground offers a Deploy button, use it to get a live URL. If it also offers **Save to GitHub**, treat that as optional bonus – nice to have, but not required.

You’re not debugging; you’re learning how the AI behaves, how to ask for changes, and what it takes to get from “idea” to “live link I can send to someone”.

If you want to share, capture a quick screenshot or short clip and post it with a note like:

> "Built a tiny [idea] helper in under 30 mins using the AI Product Playbook playground guide. Not perfect, but wild how fast you can get to something usable."

(Link back to the repo if you like.)

---

## Step 5 — Reflect for 3 minutes

Before you move on, ask yourself:

- What felt easy?  
- What surprised me?  
- What clearly broke or felt wrong?  
- What would make this actually worth keeping for me?

Write a few bullets in your own notes. This is the bridge into the more deliberate work.

---

## Your next move: START-HERE

You’ve now:

- seen what’s possible in a low‑stakes playground  
- watched an AI‑powered tool come to life  
- noticed at least one weakness or limitation

Next, go to:

- `start-here/START-HERE.md`

This is where you:

- pick (or refine) an idea that is actually worth your time  
- run the 30‑Minute Product Thinking Interview  
- leave with a clear product brief that future experiments and builds will plug into

From there, you’ll move on to **Guide 01 – Product Thinking** to turn that brief into something an AI (or an agency, or a future team‑mate) can help you build without creating a mess.
