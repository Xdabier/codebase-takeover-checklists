# Your developer left: the first 48 hours

What a founder should do when the only developer quits or goes silent. The one rule: get ownership before you remove anyone. On most services only the current owner can hand an account over.

The full guide, with sources: **[badii.studio/developer-left](https://badii.studio/developer-left)**

## First: see what you have

- [ ] **List every account and its owner.** Code, domain, hosting, database, payments, app stores. Change nothing yet.
- [ ] **Take a full copy of the code.** Mirror the repository into one you own, today.
- [ ] **Find who holds the domain.** Ask the registrar who the registrant of record is.
- [ ] **Control the owner mailboxes.** Password resets go to the owner email. Make sure it is yours.

## Then: take ownership

- [ ] **Move the code to your organization.** The current owner transfers it. Keep two owners.
- [ ] **Take over hosting and the database.** The owner transfers each project to a team you own.
- [ ] **Take over payments and app stores.** Stripe, Apple and Google Play each have an owner change.

## Last: close the doors

- [ ] **Remove the developer's access.** Only now. Removing the one owner first makes recovery slower.
- [ ] **Replace every key they could see.** Deploy keys and tokens can keep working after a person is removed.
- [ ] **Search the code for secrets.** If you find one, replace it first and clean the history second.
- [ ] **Read the contract.** Find the sentence that says who owns the code.
- [ ] **Ask for a handover.** A recorded walkthrough, while the developer still answers.

Start these within 48 hours. Transfers that need the old owner or a support team take longer. In a hostile exit, cut access first on the services where you are already the owner. The full guide covers GitHub, AWS, Google Cloud, Vercel, Heroku, Supabase, Netlify, Firebase, Stripe, Apple and Google Play, with a link to each vendor's own documentation.

[![Your developer left: the first 48 hours, as one printable image](https://badii.studio/images/developer-left-first-48-hours.png)](https://badii.studio/developer-left#developer-left-first-48-hours)

---

By [Badii Boutar](https://badii.studio), a senior full-stack developer who takes over live products. Free to share and adapt with credit and a link back, under [CC BY 4.0](LICENSE).
