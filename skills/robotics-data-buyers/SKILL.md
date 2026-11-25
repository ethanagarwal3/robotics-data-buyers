---
name: robotics-data-buyers
description: Find and qualify buyers or commissioners of agricultural video datasets for robotics. Use when matching footage to robot training needs, researching dataset customers, identifying data decision makers, finding work emails, or preparing a sourced prospect spreadsheet using Treg.
---

# Robotics Data Buyers

Find commercially credible prospects and explain findings in plain English. Use the current user's offering, Treg connection and budget. Read [the output schema](references/output-schema.md) when assembling the spreadsheet.

## Establish authorization and inputs

- Start research only when requested. Creating or installing the skill does not authorize paid calls, outreach or recurring tasks.
- Read the conversation and dataset description before asking questions. Separate confirmed facts, assumptions, unknowns, existing inventory and collection that could be commissioned.
- Establish the requested number of prospects and maximum Treg spend. Honor authorization and limits already given. Do not ask again without a material change.
- Bundle essential missing questions into at most three: (1) activities, crops, environments and existing versus commissioned footage; (2) camera perspective, volume, recording specifications, annotations and sensor data; (3) commercial training rights and geography or company exclusions.
- Explain technical terms with examples. If specifications are undecided, offer an exploratory shortlist and mark fit as conditional. Do not invent quantities, prices, camera specifications, permissions or rights.
- Do not upload private footage or unpublished business files to providers without specific authorization. Search with the minimum descriptive information needed.
- Provide unsent outreach suggestions. Contact people, submit forms or schedule recurring work only on a separate explicit instruction identifying the recipients or scope.

## Discover and qualify companies

Search agricultural robotics developers, general-purpose robot model developers, and commercial teams learning from human task video. Keep resellers, data brokers and academic groups separately labeled.

Read original sources: company technical posts, research papers, dataset documentation, procurement requests, careers pages and statements by responsible employees. Use snippets only for discovery. Attribute supplier announcements and seek buyer confirmation.

Look for relevant human demonstrations, agricultural tasks, external acquisition, supplier partnerships, procurement responsibilities and recording requirements. Funding, hiring or the word robotics alone does not establish purchasing intent.

Record source URLs, publishers, publication dates when available, access dates and the claims supported. Distinguish facts from inference and announcement dates from event dates. Mark inaccessible or unverified claims. Respect quotation limits.

Assign one purchasing evidence category:

| Category | Required support |
| --- | --- |
| Documented external data purchaser | Explicit purchase, paid licensing or paid commissioning. Record data type and date; do not assume demand continues. |
| Documented external data acquisition; payment unconfirmed | External acquisition, contribution or partnership is documented, but payment is unconfirmed. |
| Relevant data need documented | Compatible data use or need is documented; outside acquisition is unconfirmed. |
| Plausible prospect only | A reasoned hypothesis based on relevant work, with specific need and purchasing unconfirmed. |

Do not treat a procurement job posting alone as a completed purchase. Note a documented supplier procurement function separately when no transaction is confirmed. Open datasets, grants and research collaborations do not establish paid buying.

## Assess footage fit

Compare the offering with each company's actual tasks and training approach. Distinguish video used for perception or representation learning from robot demonstrations paired with actions and state.

Check relevant constraints: perspective, visible hands/tools, crops and environments, task coverage, continuity, image quality, annotations, timestamps, calibration, depth/stereo, hand motion, robot actions/state and licensing. Do not assume every buyer needs every field.

Classify fit as Compatible, Conditional, Poor or Unknown. Cite published requirements and label unpublished ones as questions. Identify gaps collection to order could address. Do not claim smartphone footage contains depth, calibrated hand poses or robot action labels.

Rank compatible and realistically addressable conditional prospects first, then weigh purchasing evidence, contact relevance and dated demand signals. Keep uncertainties visible. Exclude poor matches from the main shortlist with reasons. Return fewer prospects if evidence does not support the requested count.

## Find current contacts and work emails

Qualify companies before paying for contact enrichment. Find a primary contact and an alternate when useful, responsible for robotics learning, training data, acquisition or relevant research. Verify current employer and role with a recent reliable source. Resolve same-name ambiguity and stale records.

Distinguish technical sponsor, data operations contact and budget owner. Mark purchasing authority as inferred unless documented. Say when an executive is only a routing contact.

Include professional profile links and work emails when available. Do not invent email patterns. Check domains against current employers. Exclude personal emails and phone numbers by default.

Preserve the provider's result:
- Verified deliverable: a provider explicitly checked deliverability. Record provider and date. This does not independently confirm person ownership.
- Publicly published, unverified: company or person published it, but deliverability was not tested.
- Found, unverified: enrichment returned it without a successful verification.
- Catch-all, Unknown, Invalid or Not found: preserve the actual status. Never present catch-all or unknown as verified.

Leave missing fields blank with a clear status. If verification fails or cannot fit the budget, report the gap rather than imply success.

## Use Treg within budget

Use connected Treg MCP tools or its installed CLI. Follow Treg's available operating instructions. If disconnected, direct the user to https://treg.to/llms.txt for setup appropriate to their assistant. Never request tokens in chat or store credentials in the skill.

1. Search the catalog by the job in plain words: web search, page reading, company search, people at a company, work email or email verification.
2. Read current parameters, prices, pricing units and reliability. Prefer an appropriate routed endpoint when available. Do not assume remembered endpoint IDs remain valid.
3. If paid research lacks authorization, use free research where possible and ask before paid calls. Before a batch, state its expected cost or ceiling. State the price before an individual call costing over $0.01.
4. Check balance before many calls. Plan within available funds and the authorized cap. Do not top up or subscribe automatically.
5. Keep a ledger of actual charges and holds. Before each call, ensure its upper-bound cost fits the remaining budget. Establish that bound when unclear. Apply supported per-call caps and the total run limit. Stop before exceeding either and return partial results if necessary.
6. Run a small call before scaling. Qualify using public research before paying for contact details. Confirm returned identities, employers and domains match.
7. After a timeout or lost response, retrieve the stored result or retry with the same idempotency key. Use a new key for genuinely new work. Diagnose provider errors before retrying.
8. Explain authentication, funds and capability gaps. Do not send business information to tool-request or feedback channels without authorization.

Report actual Treg spend separately from assistant usage. Do not treat illustrative prices or a prior pilot's bill as a guarantee.

## Deliver and verify

Create an Excel workbook with the assistant's available tools. If unavailable, provide equivalent clearly named CSV files and disclose the limitation. Use a supported persistent saving workflow and return working links. Otherwise use a relative output directory such as `outputs/robotics-data-buyers/`.

Include Prospects, Evidence, Dataset brief and Run receipt using the linked schema. Use one row per company, readable widths, wrapped descriptions, frozen headers, filters and clickable sources. Preserve numeric amounts and dates as typed values where supported. Store source-derived strings as text rather than executable formulas.

Deduplicate by domain. Exclude prior prospects only when their list is accessible in the current context; request the prior spreadsheet if needed. Do not claim access to unseen past results.

Reopen the output and check source support, evidence categories, fit reasoning, current contact identities, email statuses, duplicates and reconciled costs. Never present illustrative or fabricated rows as live research.

Finish with the strongest prospects, important uncertainties, coverage, actual Treg spend and spreadsheet links. Keep outreach unsent. Do not promise a sale.
