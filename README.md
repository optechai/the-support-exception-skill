# The Support Exception by Lorikeet: Claude Skill

Ask Claude why AI support is winning while AI anxiety rises, instead of reading the report.

This skill gives Claude the full [The Support Exception](https://www.lorikeetcx.ai/content/the-support-exception?utm_source=github&utm_medium=referral&utm_campaign=support-exception-report-aug-2026&utm_content=skill-readme) report by [Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=support-exception-report-aug-2026&utm_content=skill-readme): a survey of 2,015 people who recently used AI customer support across the US, UK and Canada, fielded July 2026.

## What you can ask

- **Get the numbers.** "Do people still want a human if the AI fixes their problem?"
- **Size it for your business.** "Our AI handles 50,000 chats a month and fails first time on 12%. How many of those people would give it another go?"
- **Score your setup.** Describe your AI support setup and ask "Is our AI support building or hurting our brand?" Claude scores it against the report's findings (resolution, recovery, hand-off, industry, measurement, brand) and ranks your next 3 steps.
- **Decide what to do.** "Should we let customers retry the bot before escalating?"

Claude answers with the report's figures and its caveats: mention counts vs percentages, Amazon's lead as ubiquity rather than a quality verdict, and why the Pew comparison is context, not a like-for-like measure.

Once installed, call it directly with `/the-support-exception-report`, for example: `/the-support-exception-report Is our AI support building or hurting our brand?`

## What's inside

- All five findings: the support exception, Amazon and industry quality, the conditional human preference, brand memorability, and the second chance
- Chart data: sentiment change vs Pew, brand and industry mention counts, would you still want a human, memorability, retry vs ask for a human
- Methodology, the founder's note, the Flex and Eucalyptus customer stories, and the five key implications

## Install

### Claude.ai (web, desktop)

1. Download [`the-support-exception-report.zip`](https://github.com/optechai/the-support-exception-skill/raw/main/the-support-exception-report.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/optechai/the-support-exception-skill.git /tmp/the-support-exception-skill \
  && cp -r /tmp/the-support-exception-skill/the-support-exception-report ~/.claude/skills/
```

## Methodology

2,015 respondents from Prolific with respondent verification, across the US, UK and Canada, fielded July 2026. Roughly 95% had used an AI support agent in the last three months. No per-country or demographic breakdowns. Full methodology is in the [report](https://www.lorikeetcx.ai/content/the-support-exception?utm_source=github&utm_medium=referral&utm_campaign=support-exception-report-aug-2026&utm_content=skill-readme-methodology).

## About Lorikeet

[Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=support-exception-report-aug-2026&utm_content=skill-readme-about) is an AI customer support platform for complex and regulated businesses, with AI agents that work across voice, chat and email.
