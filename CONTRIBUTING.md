# Contributing to Awesome Mesrai Skills

Thanks for helping curate this list. A few ground rules to keep the catalog signal-heavy.

## Adding a new skill

1. **Public source.** The skill must live in a public GitHub repository (yours or your org's) with a clear `SKILL.md` file.
2. **One PR, one skill.** Easier to review, faster to merge.
3. **Right category.** Pick the table that matches best. If your skill is India-specific (RBI, DPDP, GST, UPI, Aadhaar, SEBI), use the **India-Specific Compliance** section.
4. **Row format.** Markdown table row:
   ```
   | [skill-slug](https://github.com/your-org/repo/tree/main/path/to/SKILL.md) | Plain-English: what it does + when the agent should invoke it. One sentence. |
   ```
5. **Quality bar.** The skill should be production-grade — used by you or your team, not a draft.

## What we accept

- Reusable patterns (testing, debugging, refactoring, API design)
- Compliance + regional skills (especially India-focused — we want to be the best source for these)
- Framework-specific skills (React, Next.js, NestJS, Django, etc.)
- Tooling skills (Git workflows, CI/CD, monorepo patterns)
- Code-review and PR-process skills

## What we don't

- Marketing for closed-source products
- Skills that gate functionality behind paid signup
- Skills that duplicate something already listed (open a PR to improve the existing one instead)
- Skills with broken links, empty `SKILL.md`, or "TODO" placeholders

## Review checklist (we'll check these on every PR)

- [ ] Link works
- [ ] `SKILL.md` exists at the linked path
- [ ] Description tells the agent **when** to use it (not just "what")
- [ ] Category is correct
- [ ] No duplicate of existing entry
- [ ] Skill source is public and CC0/MIT/Apache-licensed

## Style

- Use plain language. No marketing buzzwords.
- Lowercase, kebab-case skill slugs.
- Descriptions: one sentence, no longer than ~250 characters.
- US English spelling is fine; Indian English also fine.

## License

By contributing, you agree your contribution is released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (public domain).

---

Questions? Open an issue or ping us at [contact@mesrai.com](mailto:contact@mesrai.com).
