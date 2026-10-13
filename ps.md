# AdamX Trial Task: Signal-to-Outreach Agent

## About AdamX

AdamX runs AI agents that do go-to-market (GTM) work for B2B companies. GTM work is everything a company does to find and win customers: prospecting, outreach, content, social, SEO, ads and the website. A customer uses an AdamX agent to get this work done, with or without new hires. We build the agents, run them for the customer and make sure they deliver.

Our agents are: Website, SEO & AEO, Social, Outbound Prospecting, Inbound Prospecting, Content, Ads and Expand (upsell and cross-sell to existing customers).

Our engineers own their work end to end. In this task you build a small product with real moving parts.

## Why a GTM hire is a buying signal

When a company posts a job for a GTM role, three things are true:

- It has GTM work that must get done, for example more pipeline or more content.
- It has set aside budget for that work.
- A senior person is thinking about the problem right now.

That is the best moment for AdamX to reach out. An AdamX agent can take on much of that work, with or without the new hire. For example, a company that hires two SDRs needs more outbound pipeline. Our Outbound Prospecting agent does that work.

These roles count as a signal: SDR/BDR, demand generation, marketing operations, RevOps, content marketing, GTM engineer and sales leadership.

We want an agent that finds these companies and writes to the right person at each one. A person approves every email before it goes out.

## What to build

Build a live system that runs every day without anyone starting it by hand:

1. **Find signals.** Find companies that match our ICP (below) and that posted a GTM role in the last 7 days.
2. **Find the right person.** Choose the best person to contact at each company. Get their name, title and email.
3. **Draft the email.** Write a short, personal email. It must refer to the role the company is hiring for and link it to the AdamX agent that fits. It must not read like a template.
4. **Approve.** A non-technical approver must be able to review each draft from their phone in under a minute. The approver can approve the draft, edit it, reject it or mark the company "do not contact". A company marked "do not contact" must never get another draft.
5. **Send.** Send each approved email to the test inbox (see Rules).
6. **Handle replies.** Read each reply, understand it and take the correct next step. If a reply needs an answer, draft one. That answer goes through the same approval as any other email.
7. **Show status.** Give us a simple view of every company and person and where each one is in the process.

## Who we sell to

- B2B software companies with 200 to 2,000 employees, at Series B to D.
- Based in the US.

## Rules

- **Do not send email to real people.** Create a test inbox and send every email there. Make the test recipient a setting, so that we can change it to our own inbox during the review. At the top of each email, write who the email was meant for. You can use real company and job data.
- **Send no more than 5 emails per day.**
- **Choose your own tools.** We do not name any services, on purpose. Choosing them is part of the task. Set up all accounts and API keys yourself.
- **Budget: $100.** Keep your receipts. We will pay you back.
- **Use AI agents** as much as you want. We expect you to.
- **Time: 3 calendar days.**
- If something is not clear, make a sensible decision and write it down in your README.

## What to send us

- At the end of day 1: a two-line status. Tell us what works and what blocks you.
- At the end of the task:
  - The live URL, with approver access for abhishek@adamx.ai and chetan@adamx.ai.
  - A private repo, with invites to the GitHub users gutgutia and chetan-adamx.
  - A README of no more than 2 pages. Cover these points:
    - the architecture
    - how one prospect moves through the system
    - which tools you chose, and why
    - what you cut
    - what breaks at 50 companies a day
    - what you would build next
  - Your agent session logs, or a short note on how you used agents.

## After you submit

We will meet again to discuss your work.

## What we look at

- Does it work end to end, live, without you touching it?
- Does it behave correctly in real conditions, not only on the happy path?
- How good are your decisions, and how well do you explain them?
- How much did you get done in 3 days?