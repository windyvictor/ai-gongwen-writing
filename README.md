# ai-gongwen-writing

English | [中文](README.cn.md) · [Research Skillbox](https://github.com/windyvictor/research-skillbox)

A Chinese official-document and workplace-writing skill covering notices, bulletins, meeting minutes, plans, reports, speeches, applications, retrospectives, weekly reports, and other common genres.

## Why this skill

Official writing fails early when the wrong genre is chosen or when proposals, facts, decisions, and action items are mixed together. This skill selects the document type before drafting, extracts usable facts from the supplied material, and writes toward a real reader and action.

### What you get

- A genre decision when the user is unsure whether to write a notice, request, report, bulletin, or minutes
- A complete draft built from the user's actual facts
- Visible placeholders for missing names, dates, policy references, or data
- A final check of structure, tone, action ownership, deadlines, and factual consistency

**Workflow:** identify the action and reader → choose the genre → extract facts and missing fields → draft by function → verify the final document.

## Use it for

- Choosing the correct document type
- Drafting a complete official or workplace document
- Turning meeting records into accurate minutes
- Revising, shortening, expanding, or restructuring an existing draft
- Checking document structure, tone, facts, and placeholders

## Design

The skill combines genre-specific structures with three practical principles: action orientation, audience awareness, and safe public readability. Templates guide the draft but do not override the user's facts, current policy, or internal office rules.

## Contents

- `SKILL.md`: task routing and delivery rules
- `references/00-*.md` to `references/25-*.md`: genre guides and prompt patterns
- `references/15-输入素材模板.md`: input fields
- `references/16-公文格式规范.md`: formatting reference
- `references/17-易混文种辨析.md`: genre decision tree
- `references/18-成稿自检清单.md`: final-draft checks
- `evals/`: behavioral boundary cases

## Core rule

Never invent policy titles, document numbers, dates, people, units, or performance data. Mark missing fields with `××`. In meeting minutes, keep proposals, disagreements, and decisions distinct.

## Install

```bash
git clone https://github.com/windyvictor/ai-gongwen-writing.git
ln -s "$PWD/ai-gongwen-writing" ~/.agents/skills/ai-gongwen-writing
```

## License

MIT. Referenced books, courses, standards, and quotations retain their original rights.

