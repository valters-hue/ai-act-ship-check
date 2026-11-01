# AI Act Ship Check: help

AI Act Ship Check tells your team, inside Jira, whether a change to an AI system triggers EU AI Act duties: which duties, from when, and what evidence is still missing.

## Get started in two minutes

1. Install the app and open **Apps → AI Act Ship Check**.
2. Go to **Settings → Demo data**, pick a test project and select **Load demo data**. This adds three AI systems of a fictional HR-tech company, a compliance plan and four work items.
3. Open the work item "Add emotion analysis to video interviews". Open the **AI Act** panel (the app icon below the work item title): it says **Do not ship yet**, because emotion recognition at work is banned under Art. 5(1)(f). Change watch has also commented on the work item.

## Features

- **AI system register.** Register each AI system you build or use and your role (provider, deployer, importer, distributor). The risk check shows the result live, with the article behind each finding.
- **Compliance plan in Jira.** One click creates a work item per duty, each with the article, the evidence needed and a due date based on when the rule applies.
- **Change watch.** New and edited work items are screened for EU AI Act signals (for example emotion recognition, CV screening, credit scoring, chatbots, synthetic media). The app comments and adds the label `ai-act-review`.
- **Ship gate.** An optional workflow rule that blocks a transition (for example to Done) when a work item contains a banned practice, or when an AI-related change touches a system whose duties already in force are still open. Work with no AI signals only gets a warning. To add it, edit your workflow, add a rule to the transition and choose **AI Act ship gate**. It works in company-managed and team-managed projects.
- **AI Act Advisor (Rovo agent).** In Rovo chat, choose **AI Act Advisor** and ask, for example, "Can we ship PROJ-42?" or "What is due before December 2027?".
- **MCP tools.** Coding agents such as Claude Code can use the same checks. A site admin enables them under **Atlassian Administration → Apps → Sites → your site → Connected apps → AI Act Ship Check → Tools**. Then connect your MCP client to `https://mcp.atlassian.com/forge/<app id>` and sign in.

## Permissions

- People see only work items that Jira lets them see.
- Creating a compliance plan or demo data needs permission to create work items in that project.
- Changing the app settings and deleting AI systems need a Jira admin.

## Legal basis

Regulation (EU) 2024/1689 (AI Act), as amended by Regulation (EU) 2026/1744 (in force 27 July 2026). Key dates: prohibitions and AI literacy from 2 February 2025; transparency duties from 2 August 2026; new bans on non-consensual intimate imagery and CSAM generators from 2 December 2026; Annex III high-risk duties from 2 December 2027; Annex I high-risk duties from 2 August 2028.

The app gives decision support, not legal advice.

## Support

Questions, bugs or ideas: [Support](https://github.com/valters-hue/ai-act-ship-check/issues). See also the [privacy policy](privacy.md) and the [terms of use](terms.md).
