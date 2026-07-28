# HCOS™ Release Process

All HCOS standards, prompts, instruments, examples, and supporting documents follow the same lifecycle:

> **Develop → Review → Commit → CHANGELOG → Git Tag → Release**

## 1. Develop
- Create or revise the document in the correct folder.
- Confirm purpose and audience.
- Follow HCOS naming conventions.
- Mark unfinished work as **Draft**.
- Update the version only when ready for release.

Example:

```markdown
**Status:** Draft
**Version:** 1.1.0
**Last Updated:** July 2026
```

## 2. Review
Review for:
- Human dignity
- Accuracy
- Systems awareness
- Preservation of agency
- Safety
- Readability
- Consistency with related HCOS documents

Record review status in the document.

## 3. Commit
Use descriptive commit messages.

Examples:

```text
feat: add HCOS 302 compassionate response examples
docs: clarify HCOS 302 safety guidance
fix: correct terminology
refactor: reorganize document structure
```

## 4. CHANGELOG
Update the standard's `CHANGELOG.md`.

Summarize meaningful additions, improvements, fixes, and removals.

## 5. Git Tag
Use semantic versioning:

- MAJOR.MINOR.PATCH

Examples:

```text
hcos-302-v1.1.0
v2.0.0
```

## 6. GitHub Release
Create a release from the tag including:
- Summary
- Additions
- Improvements
- Known limitations
- Review status

---

## Release Checklist

- [ ] Development complete
- [ ] Review complete
- [ ] Version updated
- [ ] Commit completed
- [ ] CHANGELOG updated
- [ ] Git tag created
- [ ] GitHub Release published

---

## Versioning Principle

Keep filenames stable.

Track versions using:
- Document header
- Git history
- CHANGELOG
- Git tags
- GitHub Releases

---

## HCOS Principle

A release identifies a reviewed, referenceable point in the evolution of the HCOS framework. Future improvements should build upon—not erase—that history.

