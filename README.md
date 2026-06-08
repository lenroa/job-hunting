# Job hunting

Job hunting is a Codex skill for building a reusable job-search material library, matching target JDs, drafting recruiter outreach, suggesting resume edits, analyzing application feedback, and maintaining an application tracker.

It is designed for product manager and adjacent job-search workflows, but the evidence-first matching method can be adapted to other roles.

The public version of this skill intentionally ships with blank templates. Keep private user facts in `references/user-profile.md` and `references/job-application-tracker.md` only in your local copy.

## Install In Codex

Ask Codex to install the skill with the built-in skill installer:

```text
Use $skill-installer to install https://github.com/lenroa/job-hunting/tree/main
```

After installation, restart Codex so the new skill is discovered.

You can then invoke it with:

```text
Use $job-hunting to build my job-search material library, match this JD, and draft recruiter outreach.
```

## Manual Install

Copy this repository folder into your personal Codex skills directory:

```text
~/.codex/skills/job-hunting/
```

The folder should contain `SKILL.md` at its root. Restart Codex after copying.

## Files

- `SKILL.md`: main workflow and rules.
- `agents/openai.yaml`: display metadata and default prompt.
- `references/user-profile.md`: private material-library template.
- `references/job-application-tracker.md`: private application-tracker template.
- `references/message-patterns.md`: outreach patterns.
- `references/resume-learning-guidance.md`: resume and learning-gap guidance.
- `references/application-feedback-analysis.md`: application feedback analysis patterns.
- `references/resume-reference-materials.md`: resume rewriting patterns.

## Privacy

Do not commit real resumes, application records, recruiter messages, salary details, contact details, or interview feedback to a public repository.

If you fork this repo for your own job search, keep your filled-in `user-profile.md` and `job-application-tracker.md` private.
