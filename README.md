# Robotics Data Buyers

Find potential customers for agricultural video datasets using an AI assistant and [Treg](https://treg.to/).

The skill researches robotics companies, compares their training needs with your footage, finds current contacts, and produces a spreadsheet with sources and email verification status. It distinguishes documented data purchases from plausible interest.

## Install

Use an assistant that supports Agent Skills, such as Claude Code or Codex.

```bash
npx skills add ethanagarwal3/robotics-data-buyers --skill robotics-data-buyers
```

The skills installer requires Node.js 22.20 or later. You can ask your coding assistant to handle installation.

For ChatGPT, import the `skills/robotics-data-buyers` folder as a skill if your account supports imports. Availability and import steps depend on the product.

## Connect Treg

Use your own Treg account. Ask your coding assistant:

> Set up Treg using https://treg.to/llms.txt. Then check that company research, people search, and work-email tools are available.

For assistants with custom MCP connectors, Treg's connection URL is `https://treg.to/mcp/`. Complete its normal sign-in flow in your assistant. Do not put account tokens in this project.

Installing the skill does not include Treg credit. Treg data calls and AI assistant usage may cost money. Each run uses the spending limit you specify.

## Use it

> Use Robotics Data Buyers to research five potential customers for first-person video of agricultural workers harvesting and sorting produce. We can collect to order with smartphones. Camera placement, labels and volume are still undecided. Maximum Treg spend: $3. Return a sourced spreadsheet and suggested outreach angles. Do not contact anyone.

The assistant asks for essential missing information or marks unknowns in an exploratory shortlist. Explain whether you have existing footage, can collect to a customer's specification, or both.

## What you receive

- Ranked prospects with fit, purchasing evidence, contacts and work emails.
- Source links and a distinction between facts and inferences.
- Recording requirements and commercial questions to confirm.
- Suggested outreach angles and actual Treg charges.

The preferred output is an Excel workbook with Prospects, Evidence, Dataset brief and Run receipt sheets. If Excel creation is unavailable, the assistant can provide equivalent CSV files.

Deliverable email status reports what the verification provider found. It does not establish person ownership, purchasing authority or interest. Using human video does not by itself establish that a company buys outside datasets.

## How it works

1. Establish your dataset offering and budget.
2. Find companies and read original sources.
3. Assess purchasing evidence and technical fit.
4. Identify relevant current contacts.
5. Find and verify work emails for qualified companies.
6. Return the spreadsheet and spending receipt.

The skill runs in your assistant using Treg's catalog discovery tools. It does not schedule itself or send outreach.

See [the skill](skills/robotics-data-buyers/SKILL.md) and [output schema](skills/robotics-data-buyers/references/output-schema.md).

## License

Created by Ethan Agarwal. Released under the [MIT License](LICENSE).
