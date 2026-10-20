# Gimbalabs Live Research and Ecosystem Testing Program

**Status:** Draft  
**Funding requested:** 12,000 ADA  
**Duration:** 12 weeks  
**Tracks:** Layer 2 and specialized infrastructure; DeFi and liquidity

## Gimbalabs Primary Driver

To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems.

Gimbalabs funds experiments, not just activities. This program must leave evidence, reusable notes and code, and a clear record of what is worth building next.

## Proposal Driver

### Current Situation

Cardano builders often discuss Layer 2 designs, bridges, oracles, and DeFi tools before those tools are tested for cost, speed, trust, and failure. Project Catalyst’s recent themes — stablecoins, programmable tokens, oracles, and verifiable identity — are useful starting points, not a build list.

### Effects

Without tests, time and funds can go to tools that already exist, or a real gap can be missed. Recordings alone do not show what to build or what to leave alone.

### Need

Run a 6-week public experiment: test what exists, publish the results, and build only where a gap is real. The ask is **12,000 ADA**. A smaller option is **9,000 ADA**.

## Proposal

### 1. Title or Brief Description

**Gimbalabs Live Research and Ecosystem Testing Program: Cardano Layer 2 and DeFi**

Twelve public sessions. Six on Layer 2 and specialized infrastructure. Six on DeFi and liquidity. The output is repeatable tests, ecosystem maps, and small prototypes — not twelve recordings.

### 2. Background or Rationale

**Track A — Layer 2.** Test existing execution setups, payment channels, oracle networks, Plutus zero-knowledge proofs, and cross-chain checks or bridges. A general-purpose Layer 2 may not be the result.

The open question: if a general-purpose Layer 2 is not feasible, can a Hydra fork serve a special-purpose Layer 2? By session 6, deliver one prototype that works with Cardano L1, or a written reason not to build one.

**Track B — DeFi.** Test how Cardano apps can improve liquidity access, routing, capital use, stablecoin use, and app-to-app connections with tools that already exist. Liquidity fragmentation — assets split across pools and apps — is the problem. Programmable tokens, identity, oracles, and stablecoins are inputs to that problem, not separate products.

Rules:

1. Pick one Layer 2 prototype after the early tests. Do not build Hydra, oracles, zero-knowledge checks, and bridges as four projects.
2. If a current tool already solves the problem, document that and do not build a copy.
3. Publish notes, code, setup steps, and recordings.

### 3. Intended Outcome

After 12 weeks:

- Twelve recorded sessions, with slides and links to the tools tested.
- One Layer 2 prototype that works with Cardano L1, or a public reason not to build it.
- Three Cardano app case studies on liquidity.
- At least two DeFi prototypes, or implementation plans, aimed at liquidity fragmentation.
- Tests, benchmarks, diagrams, and a final report.
- A public reason for each idea that was built, narrowed, or dropped.

If two DeFi prototypes cannot be built well in the time and budget left, narrow the build. Do not add weak software to hit a count.

### 4. Details of the Proposal

Each session: name one Cardano problem, find existing tools, test them, record speed, cost, setup, trust, and limits, then publish whether a prototype is justified. Tools are chosen in the first two sessions. The list below is the plan, not a claim that every feature exists.

The livestream is the public part. Research, brainstorming, coding, testing, and writing happen between sessions. The budget pays for that work.

#### Track A — Sessions 1 to 6

| Session | Question | Output |
| --- | --- | --- |
| 1. Hydra and other payment channels | How do flow, settlement, throughput, user experience, and operating assumptions compare with designs such as Lightning? | Execution and settlement comparison. |
| 2. Specialized execution | Can a single-purpose environment beat a general-purpose Layer 2 on setup, interoperability, and trust? | Feasibility matrix and shortlist. |
| 3. Oracles | How do Cardano price feeds compare on update rate, delay, failure, cost, and use in Plutus validators? | One integration test and a reference design. |
| 4. Zero-knowledge and cross-chain checks | Can an existing proof or bridge let Cardano verify an outside event, and at what cost and trust? | A small proof of concept, if feasible. |
| 5. Messaging | How can an outside event trigger a Cardano action, and what trust does that require? | Threat model and one interoperability test. |
| 6. Prototype | Which single problem is worth a Hydra fork or other special-purpose Layer 2 that works with Cardano L1? | One working prototype, or a decision not to build. |

#### Track B — Sessions 7 to 12

| Session | Question | Output |
| --- | --- | --- |
| 7. DEX execution | How do selected exchanges, and aggregators where they exist, compare on pools, slippage, fees, depth, and swap construction? | DEX comparison and execution benchmark. |
| 8. Fragmentation and routing | Where does liquidity sit, and can current routing find a better trade? | Fragmentation map and routing spec. |
| 9. Stablecoins and lending | What blocks collateral, borrowing, and stablecoin use across apps? | Case study and integration note. |
| 10. Programmable tokens | How do CIP-0113 tokens work with wallets, SDKs, and apps, including transfer limits? | Integration test and compatibility gaps. |
| 11. Identity and oracles | Do identity tools and oracle feeds meet one concrete DeFi workflow? | Integration matrix and one tested workflow. |
| 12. Final demos | Which three apps, and which liquidity gaps, are worth a prototype? | Three case studies, two prototypes, and the final report. |

**A prototype must include** a named problem, a comparison with at least two existing approaches, a test someone else can run, a threat model and known limits, measurements where they apply, an open repository with setup steps, and a short roadmap.

DeFi candidates, not a promise to build all three: routing or discovery across liquidity sources; one link across exchange, lending, or stablecoin apps; or analytics of depth, execution, and fragmentation. If an aggregator already routes well enough, write that down.

**Out of scope:** a full security audit, a production bridge, liquidity provision, token rewards, large infrastructure buys, and a production general-purpose Layer 2.

**Treasury return.** Every Gimbalabs-funded project returns **10%** of the amount it receives to the Gimbalabs treasury. Of 12,000 ADA, **1,200 ADA** goes back and **10,800 ADA** pays for the work.

### 5. Impact and Benefits

Developers get a public record of how the selected tools behave and where they fail. Gimbalabs gets a reason to fund a next step or to stop.

This phase does not promise income. A prototype that holds up can support a later grant, build, or paid tool. Ownership and any revenue share for that later phase are set before more funds are used.

### 6. Evaluation Criteria

Views are recorded. They are not the success test. The program succeeds if:

- All twelve sessions and their materials are public.
- Repositories include setup steps, tests, and open issues.
- The Layer 2 prototype meets section 4, or the report explains why it was not built.
- Three app case studies are published, and at least two DeFi prototypes meet section 4 — or a written scope cut replaces a dropped prototype.
- At least three cross-ecosystem comparisons are published, each with a reason to build or not build.
- 10% of each release is returned to the treasury and recorded.

A documented “do not build” result passes the milestone.

### 7. Timeline

One session per week. Work continues between sessions.

| Weeks | Work |
| --- | --- |
| 1–2 | Choose tools, set criteria, prepare test environments, publish the plan. |
| 3–6 | Run Layer 2 tests. Publish notes. Choose the single L1-compatible prototype. |
| 7–8 | Finish the Layer 2 prototype. Start liquidity baselines. |
| 9–11 | Run DeFi tests, write three case studies, build the selected prototypes. |
| 12 | Demo, publish code and the final report, and recommend whether a next phase is justified. |

### 8. Resources Required

One technical lead runs most tests and prototype code, with a small number of contributors. These are planning figures, not quotes.

| | ADA |
| --- | ---: |
| Requested | 12,000 |
| Returned to treasury (10%) | 1,200 |
| Spent on the program | 10,800 |

Lean option: **9,000 ADA** requested, **900 ADA** returned, **8,100 ADA** for a smaller prototype scope.

| Item | ADA | Pays for |
| --- | ---: | --- |
| Research and technical leadership | 3,600 | Tool selection, experiments, architecture, analysis, writing |
| Prototype development | 2,700 | Layer 2 proof of concept and DeFi prototypes |
| Sessions | 1,080 | Demos, slides, streaming, recording, editing |
| Testing | 720 | Environments, node or API access, testnet, limited mainnet tests |
| Documentation | 720 | Repositories, setup steps, diagrams, final report |
| Expert review | 900 | Guests, technical feedback, developer review |
| Contingency | 1,080 | Unexpected integration work and tool costs |
| **Program spend** | **10,800** | |
| **Returned to treasury** | **1,200** | |
| **Total** | **12,000** | |

Do not raise this request above 12,000 ADA before the tests show what deserves more money.

Funds move only when the output is accepted. Ten percent of each release returns at payout. A “do not build” finding can satisfy a milestone. A second phase is a separate proposal.

| Milestone | Released | Returned | Kept | Accepted when |
| --- | ---: | ---: | ---: | --- |
| 1. Framework (25%) | 3,000 | 300 | 2,700 | Schedule, candidate projects, method, repositories, and baseline notes are public. |
| 2. Experiments (35%) | 4,200 | 420 | 3,780 | Layer 2 comparisons, early experiments, and first liquidity benchmarks are public. |
| 3. Prototypes (30%) | 3,600 | 360 | 3,240 | The L1-compatible prototype, two DeFi prototypes, and three case studies are demonstrated. A written scope cut can replace a dropped prototype. |
| 4. Publication (10%) | 1,200 | 120 | 1,080 | Recordings, code, setup steps, the final report, and a short retrospective are public. |
| **Total** | **12,000** | **1,200** | **10,800** | |

### 9. Responsibilities

The **program lead** selects tools, runs the experiments, writes or directs the code, and presents the sessions. **Contributors** help with tests, reviews, and documentation from the budget above. **Guest reviewers** are invited, not assumed. **Gimbalabs** accepts or returns each milestone with specific gaps, releases funds, and records the 10% return. Attendance is not acceptance.

### 10. Potential Risks and Mitigation Strategies

| Risk | Mitigation |
| --- | --- |
| Sessions produce talks, not tests. | The next milestone requires published experiments, code, or a report. |
| The budget is split across too many builds. | One Layer 2 prototype. DeFi stays on liquidity fragmentation. Narrow scope in writing if needed. |
| The build copies an existing tool. | Test current tools first. “Do not build” satisfies the milestone. |
| Tests create security or cost risk. | Keep tests small. No production bridge, liquidity provision, or full audit in this budget. |

### 11. Review and Adaptation Plan

Review at each milestone, and in Open Spaces while the program runs. If a prototype is unnecessary or unsafe, publish that and narrow the output before more build funds are released. If a budget line is exceeded, use contingency and record it; anything beyond that needs a new proposal. The week-12 report states what was learned, built, not built, returned to the treasury, and whether a second phase should be proposed.

### 12. Licensing and Intellectual Property

Notes, recordings, diagrams, benchmarks, and new code from this funding are public. New code uses an open-source license agreed with Gimbalabs before the repository is created. Dependency licenses and the licenses of projects under test still apply.

The 10% treasury return is a funding term, not an ownership claim. If a later phase turns a prototype into a product or a paid service, ownership and any revenue share are written down before that phase is funded.

---

## Consent Process

### Objections Raised

_Record any objections raised during the consent period, along with how they were addressed._

### Resolution Notes

_Document how the proposal was modified to address objections, or why objections were considered invalid._

### Final Decision

_Record the final outcome: Approved, Withdrawn, or Rejected. Include the date and brief reasoning._

---

## Discussion Notes

_Optional: Capture key points from discussions during Open Spaces or Discord._
