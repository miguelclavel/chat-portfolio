# Build log: from idea to live, and the loop after

How [chat.miguelclavel.com](https://chat.miguelclavel.com/?utm_source=github&utm_medium=chat-portfolio) went from an idea to a live site, and how it keeps getting better. Dates are 2026.

## The brief I gave myself

**Problem.** Recruiters skim portfolios in seconds, and most portfolios make them dig. I design conversational and AI products, so my portfolio could show that skill instead of describing it.

**Goal.** A portfolio that answers the questions recruiters and hiring managers actually ask, stays honest about what was and wasn't measured, and gets people to the work fast.

**The rule that shaped everything.** Written answers first. A portfolio should not guess about a person, so every answer comes from my resume and case studies, in my words.

## Timeline

| When | What happened |
| --- | --- |
| **Before Sep 28** | Designed and iterated the whole experience in Claude Design: the chat, Quick and Detailed answers, job post matching, the Memoji avatar. Started from the questions people ask, then wrote the answers. |
| **Sep 28** | Moved the export into a real project. Added a build step, crawlable page metadata, and tests, then ran a first audit: a safer setup for the optional AI endpoint, working lazy images, lighter pages, accessibility fixes, and tests on every change. |
| **Sep 29** | Finished the audit (contrast, reflow down to a 320 pixel screen, a runtime error, a clean console). Attached the chat.miguelclavel.com address and **went live**. The same day: a small log of visitor questions, so unanswered ones could be reviewed every week. |
| **Sep 30** | One public contact address everywhere: hello@miguelclavel.com. |
| **Oct 7** | A full walkthrough as a visitor, then fixes: a calmer start screen, one microphone instead of two, keyboard navigable menus, clearer tracking names, wrapping suggestions on phones. Wrote a launch checklist for security, search, accessibility, UX and speed, and checked the site against all of it. |
| **Oct 8** | Shared it on LinkedIn. The first real feedback arrived within hours and was fixed the same day (below). |
| **Every Monday since** | The weekly loop: read the questions the chat couldn't answer, write the answers, add each question to the test bank. |

## Key decisions

1. **Written answers first.** A chat that improvises about a real person is a liability. Mine answers from what I wrote, and says so under every answer.
2. **Honest confirmations.** The contact form says your email app should open, not "Sent", because a mail link can't know if anything was sent.
3. **A calmer home screen.** Early versions had more on the first screen. Testing felt busy, so it went down to a greeting, the box, a few questions to try, and four case studies.
4. **Pose selection over fake animation.** The Memoji follows your cursor by picking real recorded head poses from one video, never by inventing ones I didn't record.
5. **Test it like a product.** It started with 520 questions from 12 kinds of visitors. Every real question since has joined them, and the bank is now over 2,000.

## The first real feedback, fixed the same day

Someone tried it on launch day and sent two notes:

- **"I would train your AI to know your name. The first thing I wrote was 'Tell me about Miguel's work' and it couldn't give me an answer."** The chat was written in the first person, so it understood "your work" but not "Miguel's work". Now questions about me in the third person, typos, text speak and a few common questions in Spanish all reach the right answer, and each one is a test.
- **"I didn't clock [the suggestions] because they weren't phrased as questions. I thought they were jump links or tags."** The suggestions said "Experience" and "Contact". Now they say "What's your experience?" and "How can I reach you?", under a small "Try asking" label.

Two notes, two fixes, both live before the end of the day. That's the whole point of building it this way.

## What I'd tell someone building one

1. **People ask the same thing a hundred ways.** A big question set finds gaps you'd never guess.
2. **Honesty is a design material.** Saying where answers come from builds more trust than hiding the seams.
3. **The work after launch is the product.** The weekly loop matters more than the launch.

---

[Back to the chat portfolio](README.md) · By [Miguel Clavel](https://github.com/miguelclavel)
