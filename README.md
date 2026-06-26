# Xiaohongshu Franchise Growth Skill Template

一个面向小红书招商引流、教育/本地服务/品牌加盟内容运营的 Codex Skill 模板。

This repository contains a public-safe Codex skill template for Xiaohongshu content generation, benchmark research, account review, and conversion-safe copywriting.

## Why This Exists

很多招商引流内容的问题不是“不会写”，而是生成前缺少三件事：

- 账号当前状态判断
- 同领域近期内容观察
- 品牌事实和风险边界

这个 skill 把这些步骤固化成一个可复用工作流，让 Codex 在生成小红书内容前先做诊断、研究和风险检查。

## What Is Included

- `skill/xhs-franchise-growth-template/SKILL.md`
- `references/core-knowledge.md`
- `references/account-grounding.md`
- `references/benchmark-research.md`
- `references/source-map-template.md`
- `references/output-template.md`
- `references/review-loop.md`
- `agents/openai.yaml`

## Install

Copy the skill folder into your Codex skills directory:

```bash
cp -R skill/xhs-franchise-growth-template ~/.codex/skills/
```

Then use it in Codex:

```text
$xhs-franchise-growth-template
```

## Customize Before Use

Edit these files first:

- `references/core-knowledge.md`: account positioning, target audience, offer, voice, and risk boundaries.
- `references/source-map-template.md`: public or private source materials the agent may use.
- `references/account-grounding.md`: where account performance data should come from.

Do not commit private customer data, contracts, internal financials, unpublished strategy notes, personal contact information, cookies, tokens, or login data.

## Open Source Safety

This template intentionally avoids:

- real account names
- real brand names
- local desktop paths
- private source-material references
- customer or deal records
- platform credentials

If you fork this repository for your own business, keep your filled-in version private unless you have reviewed every reference file for sensitive information.

## License

Choose a license before publishing as a public GitHub repository.

Suggested options:

- MIT: simple and permissive.
- Apache-2.0: permissive, with explicit patent language.
- No public license: visible source, but not truly open source for reuse.
