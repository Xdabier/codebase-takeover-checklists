# The first 14 days of a codebase takeover

What to do in the first two weeks after you take over a software project that another developer or agency built. The first five days are an audit. The rest is the fixes that fit.

The full guide, with sources: **[badii.studio/project-takeover](https://badii.studio/project-takeover)**

## Days 1 to 5: the audit

- [ ] **List every account and who owns it.** Repo, hosting, domain, database, payments. Flag any in the old developer's name.
- [ ] **Check the backups.** Confirm they exist, what they cover and when one was last restored.
- [ ] **Run it from a clean checkout.** Build the app from scratch and write down the setup steps.
- [ ] **Read how it deploys.** Who can release, how, and how to roll back.
- [ ] **Trace the flows that make money.** Sign-up, payment and the core action, used the way a customer would.
- [ ] **Check versions and secrets.** Which frameworks still get security fixes, and whether keys sit in the code.
- [ ] **Findings by business day 5.** Ranked by risk: where it is, what to change and a rough effort.

## Days 6 to 14: the fixes

- [ ] **Fix the top risks that fit.** Security holes, broken deploys and missing backups come first.
- [ ] **Test before touching a money flow.** Record what it does today, then change it.
- [ ] **Ship one small change.** Through the real release path, so the deploy is proven by someone new.
- [ ] **Written plan and a call on day 14.** What to keep, what to fix next, and what to rebuild in parts, if anything.

This is how the 14-day Trial on badii.studio runs. The full guide explains each step and when a rebuild is the right call.

[![The first 14 days of a codebase takeover, as one printable image](https://badii.studio/images/first-14-days-of-a-takeover.png)](https://badii.studio/project-takeover#first-14-days-of-a-takeover)

---

By [Badii Boutar](https://badii.studio), a senior full-stack developer who takes over live products. Free to share and adapt with credit and a link back, under [CC BY 4.0](LICENSE).
