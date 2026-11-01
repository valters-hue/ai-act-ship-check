# Privacy policy: AI Act Ship Check

Last updated: 2 November 2026

AI Act Ship Check is a Jira app made by Valters Smilgainis, an individual developer based in Latvia. Questions about this policy: see [Support](https://github.com/valters-hue/ai-act-ship-check/issues).

## In short

- The app runs entirely on Atlassian's Forge platform ("Runs on Atlassian"). It sends no data to servers outside Atlassian.
- It stores no personal data: no names, no email addresses, no Atlassian account IDs.
- Everything it stores stays in Atlassian's cloud, with your Jira site.

## What the app stores

The app keeps this in Atlassian's Forge storage for your site:

- The AI systems you register, your answers to the risk questions and the resulting classification.
- Which Jira work items are linked to which AI system.
- The keys of the compliance-plan work items the app created.
- Change-watch results for work items: the verdict, the EU AI Act signals found, and the short phrase that triggered each one (for example "emotion analysis").
- App settings (ship-check policy, watched projects, default plan project).

## What the app reads and writes in Jira

- It reads work item summaries and descriptions to screen them, plus project names and work item statuses. When a person uses the app (the app page, the work item panel, the Rovo agent or the MCP tools), it reads Jira with that person's permissions. Change watch and the ship gate read the work item they are checking.
- It writes compliance-plan work items when someone asks it to, and adds a comment and the label `ai-act-review` when change watch finds an EU AI Act signal (this can be turned off in the settings).

## AI and outside tools

- The risk checks are made by a fixed set of rules. The app does not send your data to an AI model.
- If your Jira site uses Rovo, Atlassian's Rovo can call the app's actions to answer questions. Atlassian's terms cover that processing.
- If a site admin enables the app's MCP tools, an AI tool that a person connects (for example Claude Code or Cursor) receives the answers to that person's questions, such as a work item's verdict. Those tools' own terms cover what they do with the answers.

## Logs

If your site admin allows log sharing, Atlassian gives the developer the app's logs for troubleshooting. The app logs only error messages and work item keys, never work item text.

## How long data is kept

Data stays until you delete it in the app or uninstall the app. After the app is uninstalled, Atlassian deletes its stored data under Forge's data retention rules.

## Your rights

Because the app stores no personal data, there is nothing personal to access, correct or delete. If you have a question or concern, contact us through [Support](https://github.com/valters-hue/ai-act-ship-check/issues).

## Changes

If this policy changes, the new version will be posted on this page with a new date.
