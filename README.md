# Style guide

Generated from the Microsoft Writing Style Guide. Everything here is yours to edit—this is a starting point, not a contract. Hints marked "Needs your input" are the parts you must customize for your company and product. Everything else is pre-filled from Microsoft's guide and ready to use as-is.

**How the AI uses this page:** GitBook's AI editor and agent read this page—and only this page—when writing, editing, and reviewing your documentation. Pages elsewhere in this space are for people; the AI never reads them, so every rule you want enforced must appear here. Your edits always win: change a rule here and the AI follows your version; delete a rule and the AI stops enforcing it.

**About the rule IDs:** Numbered rules (like MS-9) are the enforceable tier: the AI flags violations of them directly and cites the ID, so you can trace any flag back to the exact rule that produced it. Unnumbered guidance—like the voice description—is judgment territory: the AI applies it when writing and offers it as suggestions for human review, but never flags it as a violation. **A rule without a number is a rule the AI won't flag.** To add an enforceable rule, give it the next number after the current highest, wherever on the page the rule lives. Never renumber or reuse an ID, because past flags and your decision log refer to them. Over time, numbers won't match page order—that's normal; an ID's only job is to stay stable.

_This page reflects the Microsoft Writing Style Guide (learn.microsoft.com/style-guide). GitBook reviews and updates base templates when the source guides change._

{% hint style="info" %}
Needs your input: Add the snapshot date for the Microsoft guide version this template reflects. Replace `[snapshot date]`.
{% endhint %}

## Introduction

{% hint style="info" %}
Needs your input:

* Replace `[Product name]` in the page title.
* Add your documentation mission.
{% endhint %}

This style guide defines the writing standards for your documentation. It uses the Microsoft Writing Style Guide as its base. Its goal is to keep our documentation simple, human, and consistent, no matter who writes it—humans or AI.

Our documentation exists to support the mission you define for your documentation team.

## Audience and scope

{% hint style="info" %}
Needs your input:

* Confirm that the default reader description matches your readers.
* Add who writes your documentation.
* Add what this guide covers.
{% endhint %}

**Who reads our documentation:** A broad audience—developers, IT professionals, and business users, including readers who aren't technology experts. We don't assume expertise, and we never make anyone feel less capable for needing the explanation.

Readers scan before they read. We write for scanning first: the most important thing comes first, in the heading, in the paragraph, and in the sentence.

**Who writes our documentation**

**What this guide covers**

## About our Microsoft base

Writers can consult the [Microsoft Writing Style Guide](https://learn.microsoft.com/style-guide) for questions this page doesn't answer. **The AI enforces only what's written on this page**—it doesn't consult Microsoft's guide or apply rules from it that aren't recorded here. If a Microsoft rule matters to us, it lives on this page. When we decide to differ from Microsoft style, we change the rule here and record why in the decision log.

## Voice and tone

Above all, simple and human. Our voice is warm and relaxed, crisp and clear, and ready to lend a hand. We write like we're talking to a smart friend—not lecturing a student, not pitching a customer. The traits below are guidance, not flags: the AI writes and edits with them, and raises them only as suggestions for a human to weigh.

| Trait                  | Do                                                                                        | Don't                                                                                                           |
| ---------------------- | ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Warm and relaxed       | ✅ "You're all set. Your site is live."                                                    | ❌ "Configuration is complete. The site has been deployed."                                                      |
| Crisp and clear        | ✅ "Store files online and share them with your team."                                     | ❌ "You can access file storage capabilities across your devices, and you also get sharing functionality."       |
| Ready to lend a hand   | ✅ "Something went wrong. Try importing the file again—and if it still fails, contact us." | ❌ "Import failed. Invalid input."                                                                               |
| Lead with what matters | ✅ "Save time by creating a template with the styles you use most."                        | ❌ "Templates provide a starting point. A template can include styles. Consider one if you often reuse layouts." |

**Contractions are required, not optional** _(MS-1)_. Avoiding them makes writing stiff—and stiffness is a style violation here, not caution. ✅ "You're ready to publish." ❌ "You are ready to publish." _Exception: quoted material and legal text keep their original wording._

**No exclamation points** _(MS-2)_, except at most one in a genuinely celebratory moment—setup complete, first success—and never in routine prose.

**Use "please" only when the reader is inconvenienced** _(MS-3)_. ✅ "Please wait while we restore your files." ❌ "Please select **Save**." ✅ "Select **Save**."

**Tone by context:**

| Context                   | Adjustment                                                                                                            |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| Errors and failure states | Most empathy, least personality. Explain what happened, what happens next, and how to fix it. Never blame the reader. |
| Procedures                | Brisk. Warmth here means brevity.                                                                                     |
| Success states            | Light is fine—warm, not giddy.                                                                                        |

## Word list

Terms inherited from the Microsoft guide _(MS-4)_. Delete any row you disagree with—and log the change in the decision log so it sticks.

| Term                        | Use                                             | Don't use                                            | Notes                                                                              |
| --------------------------- | ----------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------------------------------------- |
| sign in (verb)              | sign in                                         | log in, login, log on                                | "Sign in to your account."                                                         |
| email                       | email                                           | e-mail                                               |                                                                                    |
| set up (verb), setup (noun) | "Set up your account." / "Finish setup."        | "Setup your account."                                |                                                                                    |
| app                         | app                                             | application                                          | Unless the formal or API context needs it                                          |
| select                      | select                                          | click on                                             | "Select" is the default for UI; "click" only for explicitly mouse-specific content |
| website                     | website                                         | web site                                             |                                                                                    |
| address, fix, stop          | address the issue, fix errors, stop the process | combat the issue, eliminate errors, kill the process | Avoid militaristic language; the literal `kill` command keeps its name             |

**Banned filler** _(MS-5)_: "simply," "easily," "just" (as a minimizer), "obviously," "quick and easy." _Exception: "just" meaning "only" or "recently" is fine._

**Plain words win** _(MS-6)_: "use," not "utilize" or "leverage"; "through" or "by using," not "via."

{% hint style="info" %}
Needs your input: Add rows for your product names, feature names, and any terms your team debates.
{% endhint %}

| Term | Use | Don't use | Notes |
| ---- | --- | --------- | ----- |

## Grammar and mechanics

| ID    | Rule                                                   | Do                                                    | Don't                                                     | Exception                                                                               |
| ----- | ------------------------------------------------------ | ----------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| MS-7  | Address the reader as "you"                            | ✅ "You can share the file with your team."            | ❌ "Users can share files with their teams."               |                                                                                         |
| MS-8  | Use present tense                                      | ✅ "The report shows last month's data."               | ❌ "The report will show last month's data."               | Future tense for genuinely future events ("Support for v2 ends in March")               |
| MS-9  | Use active voice                                       | ✅ "The app saves your changes automatically."         | ❌ "Changes are saved automatically by the app."           | Passive is fine when the actor is unknown or irrelevant, or to avoid blaming the reader |
| MS-10 | Use the serial comma                                   | ✅ "docs, wikis, and knowledge bases"                  | ❌ "docs, wikis and knowledge bases"                       |                                                                                         |
| MS-11 | One space after a period                               | ✅                                                     | ❌ two spaces                                              |                                                                                         |
| MS-12 | Spell out zero through nine; numerals for 10 and above | ✅ "five workspaces," "24 integrations"                | ❌ "5 workspaces"                                          | Numerals always for versions, measurements, and technical values                        |
| MS-13 | Em dashes take no surrounding spaces                   | ✅ "Pipelines—groups of activities—consolidate tasks." | ❌ "Pipelines — groups of activities — consolidate tasks." |                                                                                         |

**Brevity rules:**

| ID    | Rule                                   | Do                                           | Don't                                               | Exception                                                                                                                                                                                |
| ----- | -------------------------------------- | -------------------------------------------- | --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MS-14 | In instructions, cut "you can"         | ✅ "To change the theme, select **Options**." | ❌ "You can select **Options** to change the theme." | Never flag "you can" that describes what's possible rather than instructs ("You can export up to 100 rows"). Test: if "it's possible to" substitutes cleanly, it's descriptive—leave it. |
| MS-15 | Cut "there is" and "there are" openers | ✅ "Share files from any device."             | ❌ "There are apps for every device."                |                                                                                                                                                                                          |
| MS-16 | "To," not "in order to"                | ✅ "To sync..."                               | ❌ "In order to sync..."                             |                                                                                                                                                                                          |

Brevity has a floor: never cut the context a reader needs to act. Short and incomplete isn't crisp; it's confusing.

## Formatting

| ID    | Element         | Rule                                                                                 | Example                                                                                |
| ----- | --------------- | ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| MS-17 | Headings        | Sentence case, always                                                                | ✅ "Find a partner" ❌ "Find a Partner"—product names and proper nouns keep their casing |
| MS-18 | End punctuation | None on headings or on list items of three or fewer words                            | ✅ "Find a partner" ❌ "Find a partner."                                                 |
| MS-19 | UI elements     | Bold UI element names exactly as they appear on screen; "select" as the default verb | ✅ Select **Save**.                                                                     |
| MS-20 | Code            | Code font for code, commands, and file names                                         | ✅ Run `npm install`.                                                                   |
| MS-21 | Links           | Descriptive link text; never "click here"                                            | ✅ Learn how to \[set up two-factor authentication].                                    |
| MS-22 | Dates           | Month D, YYYY—never all-numeric dates                                                | ✅ July 6, 2026 ❌ 7/6/26                                                                |

## Writing procedures

* **MS-23:** Number sequential steps; one action per step. Start each step with an imperative verb: "Select," "Open," "Enter." ✅ "Select **Settings**." ❌ "The Settings page should be opened."
* **MS-24:** State the goal or location before the action. ✅ "To publish your site, select **Publish**." ✅ "On the **Settings** tab, select **Permissions**."
* **MS-25:** Tell the reader a step's result only when it isn't obvious ("The app restarts").

## Error messages and failure states

These get their own rules because errors are where readers are most stressed:

Explain what happened, what happens next, and how to fix it—in that order, in plain language. That ordering is guidance; the rules below are enforced:

* **MS-26:** Never blame the reader. Banned in error text: "invalid," "illegal," "bad," "you failed," "fatal." ✅ "That ID didn't match. IDs look like this: someone@example.com." ❌ "You entered an invalid ID."
* **MS-27:** No forced cheer or over-apology: no "Oops!", no chains of "Sorry!" Calm and useful beats cute.

## Content types and templates

{% hint style="info" %}
Needs your input: Define your content types and templates. Many teams use a framework like Diátaxis.
{% endhint %}

| Content type | Use it for | Template or example |
| ------------ | ---------- | ------------------- |

## Accessible writing

* **MS-28:** Write descriptive alt text for every meaningful image; use empty alt text for purely decorative images.
* **MS-21** applies here too: link text describes the destination and makes sense out of context.
* **MS-29:** Don't rely on color, size, or position alone to convey meaning—avoid "the red button" and "the panel on the right." Prefer "earlier" and "later" over "above" and "below."
* **MS-30:** Keep heading hierarchy intact—don't skip levels.
* **MS-31:** Put people first: "a person who uses a screen reader," not "a screen reader user"—unless the community you're describing prefers otherwise. Describe the interaction, not the limitation: "uses a screen reader," not "can't see."

## Inclusive language

* **MS-32:** Use gender-neutral language. Use singular "they" when gender is unknown or irrelevant—never "he or she."
* **MS-33:** Avoid idioms and culturally specific references that don't translate.
* **MS-34:** Replace militaristic, violent, and ableist idioms: "address the issue," not "combat the issue"; "confirmation check," not "sanity check."
* **MS-35:** Refer to people the way they refer to themselves.
* **MS-36:** Use diverse, realistic names and scenarios in examples.

## Ownership and updates

{% hint style="info" %}
Needs your input:

* Add the owner.
* Add the review cadence.
* Explain how to propose a change.
* Decide when settled decisions can be revisited.
{% endhint %}

* **Owner:**
* **Review cadence:**
* **How to propose a change:**
* **When settled decisions can be revisited:**

## Decision log

Record every deliberate departure from Microsoft style here, alongside other settled decisions, so debates don't reopen. Changing a rule above changes what the AI enforces; this log remembers why.

| Date | Decision | Differs from Microsoft? | Rationale |
| ---- | -------- | ----------------------- | --------- |

{% hint style="info" %}
Needs your input: Add the first row to the decision log. Record departures from Microsoft style and any other settled decisions you want the AI to follow.
{% endhint %}

***

_Based on the_ [_Microsoft Writing Style Guide_](https://learn.microsoft.com/style-guide)_, used under CC BY 4.0. Template structure adapted from The Good Docs Project for GitBook._
