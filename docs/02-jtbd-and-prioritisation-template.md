# JTBD and Prioritisation Template

Use this template after reviewing the stakeholder notes.

## Step 1: Group the evidence

Suggested theme labels:
- duplicate work
- missed follow-up
- poor visibility
- customer friction
- financial credibility
- change resistance

## Step 2: Build an evidence table

- In excel file 

## Step 3: Write JTBD statements

### Customer:
Stakeholder group(s): Customer
Job: Resolve simple debt cases quickly with minimal effort
Desired Outcome Statement:
When I have a straightforward repayment matter to settle,
I want to execute the transaction immediately through a convenient channel,
so that I can resolve my account status quickly without undergoing unnecessary phone queues or conversations.
Supporting evidence:
"Some customers will do anything if given the chance to manage this themselves."
— Tracy Field, Systems Administrator (Note ID: SN-005) 
"Most customers do not even know they can pay online; they think they have to call."
— Eleanor Clark, Service Design Lead (Note ID: SN-017) 
Explanation: Customers currently spend days stuck in manual queues or phone loops for simple cases. The true underlying job for a subset of these customers is self-direction—they want a frictionless, low-effort path to clear their obligations immediately without being forced into human-led operational workflows.

Frequency of evidence - Medium
Business impact - High
Relevance to the portal - High



### Agent:
Stakeholder group(s): Agent
Job: Route and prioritize accounts based on case complexity
Desired Outcome Statement:
When a new or progressing recovery case enters the operational queue,
I need the system to automatically distinguish and prioritize straightforward accounts versus complex, specialist-led ones,
so that simple cases are resolved swiftly and complex cases receive immediate specialist attention without artificial delays.
Supporting evidence:
"Simple cases that could be resolved in minutes take days because they get stuck in the wrong queue."
— Priya Nair, Operations Manager (Note ID: SN-003) 
"Straightforward cases get delayed because they are queued behind complex ones with no priority logic."
— Barry Skinner, Operations Analyst (Note ID: SN-029) 
Explanation: The current "one-size-fits-all" queuing structure creates massive logjams for agents. The agent's underlying job is to work from an intelligently sorted workload where tasks match their skill level and urgency, eliminating the time wasted hunting through irrelevant or misallocated files.

Frequency of evidence - High
Business impact - High
Relevance to the portal- High

Why this job matters now
- Simple and complex cases sit in the same queue creating artificial urgency and not allowing high value accounts to receive the right attention, with the 12month ROI window fixing this issue could provide a quick when to help payback. 

Which evidence supports it


How it could influence Phase 1 scope
- This is a core aspect of the portal propisition, simple cases can be quickly resolved with self service allowing agents to quickly work through cases that require human judgement. This would greatly improve workflow productivity.

### Operations manager:
Stakeholder group(s): Operations Manager, Compliance Links
Job: Standardize workflow definitions and status rules across the floor
Desired Outcome Statement:
When I manage account distributions across the collections team,
I need to establish a universally enforced set of status definitions and case transition rules,
so that reporting metrics are meaningful, data quality is reliable, and agents handle accounts with consistent criteria.
Supporting evidence:
"There is no standard definition of what each status actually means across the team."
— Jacqueline Norris, Operations Analyst (Note ID: SN-085) 
"Different agents use different status codes, which makes reporting meaningless."
— Dr Louis Sinclair, Service Design Lead (Note ID: SN-122) 
Explanation: The frustration with broken reports and conflicting data stems from a deeper process problem: a lack of operational alignment. The manager's core job is to build a foundation of standardized, systemic rules so that operational behavior is uniform and performance data can be trusted.

Frequency of evidence - High
Business impact - High
Relevance to the portal - High

Why this job matters now
- This status inconcistency directly causes the issue of duplicate cases and late follow ups, as their is no shared systematic standard for reporting cases. It would be imperative to create this before building automation over the current system.
How it could influence Phase 1 scope
- The portal needs to read and display account status to customers and write status updates back to the system. This requires a defined, agreed status taxonomy before any UI is built. Phase 1 scope should include a status definition workshop with Amina and Gareth, a mapping of current codes to the new taxonomy, and a validation rule set to prevent non-standard entries at the point of agent input.
 
### Finance partner
Stakeholder group(s): Finance Business Partner, Compliance Lead
Job: Verify operational efficiency gains and financial ROI
Desired Outcome Statement:
When I review resource allocation and business cases for process adjustments,
I need to explicitly measure the net financial impact and cost-to-serve reductions of changing workflows,
so that I can prove realized headcount savings or collections optimization without shifting costs onto other operational areas.
Supporting evidence:
"If self-service reduces agent workload, that headcount saving needs to be real, not theoretical."
— Andrea Hunt, Finance Analyst (Note ID: SN-031)
"The finance team will ask for proof that this is not just shifting cost from operations to lost recovery."
— Tracy Field (Note ID: SN-071)
Explanation: Finance partners look past the high-level vision to assess the hard numbers. They need concrete financial feedback loops to validate that operational alterations actually drive true savings and structural efficiency, rather than merely masking expenses or creating downstream losses.

Frequency of evidence - Medium
Business impact - High
Relevance to the portal - Medium

### Change Friction:
Stakeholder group(s): Operations Manager, Process Improvement Lead
Job: Address root-cause operational inefficiencies during system re-designs
Desired Outcome Statement:
When a legacy system is being updated or replaced,
I need to re-engineer and fix the underlying broken processes instead of just applying a new technology layer over them,
so that the new operation achieves maximum performance and avoids automating existing inefficiencies.
Supporting evidence:
"We need to fix the fundamentals before we can build anything new on top."
— Jacqueline Norris, Operations Analyst (Note ID: SN-030) 
"This will work only if we address the underlying broken process, not just add a layer on top."
— Mr Martyn Akhtar, Operations Analyst (Note ID: SN-058) 
Explanation: Stakeholders recognize that technology alone cannot fix bad habits or broken mechanics. Their fundamental job during a transition is to use the change window to overhaul baseline operational logic, ensuring the new solution sits on a stable, logical foundation.

Frequency of evidence - Medium
Business impact - Medium
Relevance to the portal - Medium

### Agents & System:
Stakeholder group(s): Systems Administrator, Compliance Lead
Job: Consolidate duplicate customer profiles at data entry points
Desired Outcome Statement:
When a customer interacts with the bank through multiple intake channels,
I need the data architecture to identifies where duplication is causing the most pain points,
so that we eliminate data fragmentation, avoid contradictory account actions, and secure a perfect compliance trail.
Supporting evidence:
"A single customer can have five separate records in the system from different entry points."
— Mr Philip Stone, Service Design Lead (Note ID: SN-100) 
"Every new tool we add makes the job harder because it adds another place where data can get out of sync."
— Simon Burns, Compliance Liaison (Note ID: SN-062) 
Explanation: Systemic capacity is artificially choked and fractured because the current infrastructure generates duplicate entries across different systems. The architectural job here is data unification—ensuring that irrespective of the entry vector, the bank maintains an accurate, single identity for every customer to eliminate processing friction.

Frequency of evidence - High
Business impact - High
Relevance to the portal - High

Why this job matters now
- The portal will read and write customer records from day one. If duplicate profiles exist at launch, the portal will surface conflicting balances to real customers leading to disputes, complaints, and immediate loss of trust. This cannot be fixed retrospectively once the portal is live. It is something that should be fixed before the portal is launched.

How it could influence Phase 1 scope
- A data deduplication and master record exercise must be scoped first before portal build begins. The Phase 1 backlog should include a defined data standard for customer identity, an audit of current entry points generating duplicates, and a merge or suppression rule set. Without this, portal UAT will be unreliable.

## JTBD table

| JTBD ID | Actor | Statement | Evidence link | Portal relevance | Priority |
|---|---|---|---|---|---|
| JTBD-01 | TODO | TODO | TODO | TODO | TODO |

## Step 4: Top 3 justification

For each of your top 3 JTBDs, write:
- why it matters now
- which evidence supports it
- how it should influence Phase 1

## Quality check

Ask yourself:
- Does this describe a need instead of a feature?
- Would the job still exist if the screen or tool changed?
- Can I point to real evidence behind the priority?
