# message-writer: a Claude.ai skill for better writing

## The problem

Claude is a strong writer, but the output depends heavily on context: who the audience is, what the goal is, the tone, and the relationship.

When prompting, it takes time to figure out what context to include and how to phrase it. We often forget to include important details or skip them because it’s **easier not to think through everything upfront**.

As a result, **we either over-explain or provide too little**. The output ends up generic or slightly off, leading to unnecessary back-and-forth to fix it.

This skill fixes that by giving Claude a framework to identify what it needs and ask only about that before writing.

## What it does

When you ask Claude to write or rewrite something meant for another person, this skill has it read what you've given, figure out what's genuinely missing, and ask about only that in plain language. Then it writes.

**Covers:** messages, emails, texts, LinkedIn posts and DMs, Slack messages, outreach, follow-ups, requests, feedback, apologies, announcements, bios, speeches, proposals

**Does not cover:** cover letters, creative or fiction writing, technical documentation, essays, code

## How to install

**Option 1 (easy):** Download the `.skill` file from the Releases section of this repo and drag it into the Skills section of your Claude.ai settings.

**Option 2 (manual):** Copy the contents of `SKILL.md` and paste it into a new skill in Claude.ai settings.

## Example

> **You:** I need to message my landlord. I've asked twice about a broken heater and he keeps saying he'll handle it. It's been three weeks.
>
> **Claude:** Good sense of the situation. Two quick things — what's your goal with this message, and how do you usually communicate with him?
>
> **You:** *(selected: Stay cordial but make clear it's urgent · Email)*
>
> **Claude:** Here's a draft that stays friendly but makes clear this can't keep slipping:
>
> ---
>
> **Subject: Heater Follow-Up**
>
> Hi [Name],
>
> I wanted to follow up again on the heater issue I reported three weeks ago. I know things get busy, but with the weather as it is, not having heat has become a real problem for me day-to-day.
>
> I'd really appreciate a concrete update — even just a date when someone can come take a look. Is there a timeline you can share?
>
> Thanks for your help with this.
>
> [Your name]
>
> ---
>
> Kept it warm but made the ask specific — a date, not just a vague "please fix it" — which is harder to brush off with another non-answer.
>
> One thing worth knowing: in California, landlords are legally required to provide heat, and three weeks without a repair could give you grounds to escalate. Want a version that hints at that, in case this one doesn't get a response?

---

It just makes sure Claude understands your situation before it starts, so you spend less time correcting and more time sending.
