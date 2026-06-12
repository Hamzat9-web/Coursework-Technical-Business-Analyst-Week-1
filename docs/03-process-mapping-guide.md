# Process Mapping Guide

Use this guide when you build the As-Is process map.

## Minimum actors and systems to include

- customer
- collections agent
- team leader or manager
- spreadsheet tracker
- email or manual communication channel
- legacy collections database

## Suggested As-Is flow

1. Account enters delinquency queue
2. Agent creates or receives worklist
3. Agent checks legacy account status
4. Agent cross-checks spreadsheet or email history
5. Agent contacts customer
6. Outcome is captured manually
7. Promise or next action is tracked manually
8. Follow-up is scheduled manually
9. Exceptions are escalated
10. Managers reconcile status for reporting

## Pain points to mark on the flow

Mark at least five directly on the map:
- duplicate status checks
- spreadsheet version or ownership conflict
- missed next action due to manual tracking
- repeated customer contact attempts
- poor visibility of promise-to-pay fulfilment
- manager reporting based on reconciliation rather than live status

## Self-service suitability test

A step is a better Phase 1 candidate if it is:
- high-volume
- repeatable
- rules-driven
- low to medium risk
- understandable for customers

1. A self serve or payment plan selection for customers
2. Duplicate contact prevention check
3. A unified activity log
4. An Automated flag for follow up when promise to pay overdue
5. Automatic delinquent account updates, for any activity that is done on the account

## Keep agent-led if the step is:
- high-risk
- specialist-controlled
- judgment-heavy
- dependent on negotiation or exception handling

1. Payment dispute resolution must stay client lead 
2. Assessment of hardship claims and plan negotiations
3. Legal escalations


## Deliverables to produce from the map

- As-Is process map
- pain-point overlay
- short current-state summary
- first-pass automation candidate list


### How the Current Process Feels
For the customer, the experience is repetitive. They have no visibility into what's happening with their account between contacts, so when someone does reach out it can feel random or even duplicated — two agents calling within days of each other about the same debt. There's no way to check their balance, see what was agreed last time, or resolve anything without going through a phone call. For the subset who would willingly pay if given a clear path, the current process actively gets in their way.

For the agent, almost every working day begins with an information-gathering exercise that shouldn't be necessary. Before making a single contact, they're cross-referencing the legacy DB against spreadsheets, checking whether a colleague already called this person, and trying to piece together what was promised in a previous conversation from a manual note that may or may not exist. That's time and cognitive load spent on context reconstruction rather than recovery. When they do make contact and log a promise to pay, there's no system to validate or store it.

For Gareth as team leader, the process is one he can see breaking but can't easily fix. His visibility into what's actually happening across 50+ agents relies on the same fragmented spreadsheets his agents are working in. He can't tell at a glance which accounts are stalled, which promises have lapsed, or which agents are overloaded — he has to chase that information manually. A significant part of his day is consumed by end-of-day reconciliation to catch the discrepancies that would otherwise create downstream problems, this reduces his time which means less capacity for the coaching, escalation review, and capacity planning that only he can do.