# Kaya improvement log

Use this log for de-identified operational learning under SKILL.md section 16. Keep candidate information and transcripts out of this file. Log one concise review per meaningful touchpoint, including "no rule change" when appropriate. Consolidate repeated lessons without losing the evidence needed to assess or undo a rule.

## Review format

- Date and source: owner instruction, tool observation or authorised relationship-record reference; never fabricate a reference.
- Objective and success evidence:
- Observed result: achieved / partial / pending / blocked / not achieved; limitations and next action.
- Lesson: evidence-backed finding or explicitly labelled hypothesis; scope.
- Decision: no rule change / proposed / applied; old and new behaviour if changed.
- Version, validation and regression check:
- Expected benefit and follow-up evidence: unvalidated / supported / revised / rolled back.
- Rollback: prior behaviour or exact change to reverse, when applicable.

## 2026-11-04 — Review-loop setup

- Source: Leon's explicit instruction in the Kaya chat to review every touchpoint and carry supported learning into the skill.
- Objective: establish a durable review and improvement practice.
- Result: achieved for configuration. Added section 16's bounded review cycle and this linked log; no background worker or automatic event integration is installed.
- Decision: applied in v1.5. Previously the skill captured corrections but did not require an objective/outcome review after every touchpoint. It now requires review, evidence-scoped updates and later evaluation.
- Validation: inspected the rule and linked file. Intended case: a verified send failure produces a scoped correction and next-use check. Counterexample: an unanswered message stays pending and does not trigger extra outreach or a global personality rule. The Python skill validator was unavailable earlier in this session; no automated validation is claimed.
- Expected benefit: fewer repeated operational mistakes and clearer outcome reporting. Follow-up status: unvalidated until exercised on subsequent touchpoints.
- Rollback: remove the continuous-touchpoint-review subsection and its log link, restore the earlier permanent-change wording, and revert the metadata version to v1.4 if this workflow is withdrawn.

## 2026-11-05 — Recruitment longlist verification

- Source: authorised sourcing task and observed LinkedIn Recruiter controls, search cards and opened profile Experience sections in the Kaya chat. No candidate details are retained in this learning entry.
- Objective: produce a technology recruitment leadership longlist with a ten-mile location constraint and at least eighteen months in the current role.
- Result: achieved as a sourced longlist with explicit limitations: 23 stronger matches and 6 broader/clarification entries. Reviewed 129 visible cards and opened 32 profiles; exact addresses and employer-side verification were unavailable. The requested report is stored separately in the owner's Kaya folder.
- Lesson: a promotion can reset current-role tenure despite long company service; overlapping Present positions and headline discrepancies need explicit flags. Typed numeric filter text did not initially update the active slider range; committing a control change and checking the final chip resolved this.
- Decision: applied a scoped sourcing-verification paragraph in SKILL.md section 8, v1.6. Preserve the existing evidence-first workflow and make role-tenure and radius checks explicit.
- Validation: intended case excludes a recent promotion whose prior title had sufficient tenure. Counterexample preserves a long-standing current role when an unrelated concurrent membership exists. Confirmed the radius chip and active tenure range and used role start dates for the deliverable. No automated validator run is claimed.
- Expected benefit: fewer false-positive sourcing matches. Status: supported for this task; evaluate again on the next comparable search. This does not establish a causal improvement across future searches.
- Rollback: remove the sourcing-verification paragraph and restore version 1.5 if withdrawn; candidate report remains an independently sourced deliverable.

## 2026-11-05 — Name corrections

- Source: Leon’s explicit company and persona spelling corrections.
- Objective and result: applied Chameleon Recruiting and Kaya DeMarco throughout the skill, version 1.7.
- Decision: preserve the Senior Consultant title and friendly tone; retain truthful answers to direct identity questions. Concealment and false-denial examples were not adopted.
- Validation: checked old spellings and reviewed the identity section. No runtime behaviour changed.
- Rollback: restore the prior spellings and version only if the owner corrects them again.

## 2026-11-05 — Owner-message style review

- Source: Leon explicitly requested a full review of three selected LinkedIn conversations to learn his tone, natural language and follow-up timing. Read both sides of each complete available thread and checked the earliest history boundary; available ranges were 5–19 October and two threads spanning 7 October–5 November 2026.
- Objective and result: achieved for the available LinkedIn text. Added the linked de-identified message-style reference and incremented SKILL.md to v1.8. No outreach or scheduling was performed. No raw transcripts, phone numbers or candidate personal circumstances were copied into the skill.
- Lesson: short paragraphs, familiar greetings, direct scheduling questions, occasional light humour, low-pressure call framing and warm acknowledgements recur. Unanswered-message follow-ups ranged from roughly 38 to 59 hours, with one later nudge about a week later. A promised later contact was honoured after the agreed break; this is not a universal recurring cadence. Active-response speed varied from minutes to about a day.
- Decision: applied a contextual voice and timing guide, preserving factuality, opt-outs and sending authority. Do not infer changed intent solely from an open-to-work badge or invent historical market/placement/busyness claims.
- Validation: checked the linked reference, frontmatter and scope. Intended case: an authorised nudge after an unanswered scheduling proposal is short and uses real availability. Counterexamples: a requested later date prevents an earlier nudge; a clear decline receives a respectful close; an unverified profile signal is a question, not an assertion. The Python validator remains unavailable on this machine; no automated validator pass is claimed.
- Outcome limits: an agreed call time, a permitted reconnection and a declined call are different outcomes. No causal conversion benefit is established by this sample; assess future owner-reviewed drafts.
- Rollback: remove the section 9 reference paragraph and the message-style reference, and restore metadata version 1.7 if the owner withdraws this guide.

## 2026-11-05 — Contrasting long and short paths to call agreement

- Source: owner explicitly requested two additional LinkedIn chain reviews and an extension to the message-style skill. Both complete available chains were read and their earliest history boundaries checked.
- Objective and result: achieved for available text. Updated the existing style reference, its evidence base from three to five chains, and SKILL.md to v1.9. No messages sent.
- Lesson: one chain spanned nearly a year but included an eleven-month quiet gap, followed by eight days of renewed engagement and adaptation to clarified requirements. The other reached initial call agreement within six calendar days; later exchanges were rescheduling. Distinguish renewed relevance and practical scheduling from continuous chasing or further persuasion.
- Decision: added evidence-scoped timing comparisons, fact-based re-engagement, responsiveness to stated requirements, and prompt scheduling once interest is expressed. Preserved opt-outs and existing sending scope. No candidate phone numbers, private reasons or raw transcripts retained in the skill.
- Validation: reviewed timestamp arithmetic and year boundaries, link existence, instruction consistency and five-thread evidence description. Intended case: clarified location changes the verified proposition. Counterexamples: requested rescheduling does not restart the pitch; an old compensation figure cannot become a current offer; a long quiet gap is not a recurring follow-up cadence. Python skill validator remains unavailable; no automated validator pass claimed.
- Outcome limits: call times were agreed, with no evidence here of completed calls or placements. Causal benefit of persistence is unproven from these two examples.
- Rollback: remove the additional comparison section, restore the prior three-thread wording and outcome paragraph, and restore version 1.8 if withdrawn.

## 2026-11-05 — Austin agency recruiter sourcing

- Source: authorised LinkedIn Recruiter sourcing and project-save task; observed search cards, opened profiles, save-state changes and project navigation.
- Objective and result: saved 18 verified technology agency recruiter profiles to the existing project. Screened 95 distinct cards. Verified current-role start months, external/client recruitment remit and LinkedIn radius membership. All selected start months were October 2025 or earlier. Exact residential distances were not verified. The sourced list is kept separately in the owner's Kaya folder; no candidate details are retained here.
- Lessons: Staffing and Recruiting industry membership can persist for people now recruiting in-house. A technical agency name does not establish that a person's desk covers IT/software. Current roles must be checked individually. Previously archived candidates were left untouched.
- Verification limit: each save produced project membership or a recorded add event, and the project navigation showed 18 uncontacted candidates. The results count/list remained inconsistent across refreshes (12–15) despite the 18 counter; no duplicate saves or archive changes were used to force reconciliation. Reported this UI limitation rather than claiming a fully reconciled list view.
- Decision: no new global rule; existing evidence-first sourcing rules cover this. No messages or background monitoring initiated.
- Follow-up: assess search/list freshness in a future authorised session if needed; no assumption that a fixed wait resolves indexing. Skill version remains 1.9.

## 2026-11-06 — Recruitment approaches directed at Kaya

- Source: explicit owner instruction to decline external recruitment approaches to Kaya and privately notify Leon.
- Objective and result: added a scoped section 9 playbook, version 2.1, covering warm declines, approved Chameleon flexibility/owner-led business/trust wording, and one-channel notifications to the owner-provided WhatsApp or email destination.
- Decision: treat the example as hypothetical, not an inbound message. No notification or decline sent during this update. Preserve truthful identity, factual sender context, destination verification and existing human takeover rules.
- Validation: reviewed intended case (clear approach produces a polite decline and a faithful internal quote) and counterexamples (client vacancy is not mistaken for a personal approach; unavailable audio is handed over rather than fabricated; failed notification remains pending; uncertain sends are not duplicated). Contact values match the owner's instruction. Python validator remains unavailable; no automated validator pass claimed.
- Rollback: remove the recruitment-approach subsection and restore version 2.0 if withdrawn.

## 2026-11-06 — Agency-based sourcing expansion

- Source: owner instruction to expand each verified recruiter's current and former agency employers into further sourcing searches and persist that workflow in the skill.
- Objective and result: added the section 8 agency-expansion workflow in v2.0, retained in v2.1. Ran two agency Boolean searches using 41 agency names/aliases, screened 88 distinct cards and verified 12 new project saves. The project later showed 29 active candidates and one earlier saved profile archived; archive choices were not reversed. A separate report in the owner's Kaya folder records names, dates, discovery trails and remaining scope.
- Lesson: former employers produce useful new agency leads, but alumni may now recruit in-house; agencies also have internal TA and non-technology desks. Match every new candidate to the original constraints. Promptly search newly discovered agencies without turning the workflow into an endless unattended loop.
- Decision: applied deduplicated agency queue, candidate/project deduplication, current-role verification and explicit coverage reporting. No sending authority expanded. Remaining result pages and a final newly discovered agency remain recorded for future authorised work; no exhaustive-market claim made.
- Validation: source-to-agency-to-new-recruiter trails produced additional verified matches. Counterexamples excluded non-IT desks, recent title changes and ambiguous location evidence. Individual membership receipts verified saves; the results-list count remained inconsistent with navigation totals. Python validator unavailable, so no automated validator pass is claimed.
- Rollback: remove the agency-expansion subsection if withdrawn, preserving the later recruitment-approach playbook.

## 2026-11-06 — London open-to-work sourcing

- Objective and result: created technology and life sciences projects with five verified uncontacted profiles each. This is an initial shortlist; not every broad result was reviewed. Detailed evidence and scope are in the owner's Kaya folder.
- Lesson: current-position tenure must use the promoted title's start, not company tenure. A sector keyword may match an old desk or unrelated experience. Current-or-past employer expansion can return alumni who now work in-house or outside recruitment.
- Decision: manually checked month-level role starts and recruitment history; preserved archive choices and excluded stated current delivery/180 roles. Platform radius is location evidence, not independent distance verification; ambiguous headline locations are flagged in the report.
- Validation: individual membership receipts plus both pipeline totals of five; no outreach. No new global rule or sending authority added; existing sourcing guidance covers this outcome. Skill version remains 2.1.

## 2026-11-06 — Search lists must maximise qualifying coverage

- Source: Leon explicitly corrected stopping at five per project and instructed that every requested search list should shortlist as many recruiters as possible who meet the criteria.
- Before/after: an initial small shortlist was treated as a finished task despite unreviewed results. Version 2.2 now prohibits arbitrary caps and requires continued relevant result-page, search-variation and agency-expansion review, without relaxing criteria or adding duplicates.
- Scope and rationale: all owner-requested recruiter search lists, unless he sets a specific count or limit. Expected benefit is greater qualifying coverage and accurate completion reporting. Does not authorise outreach or unattended work.
- Validation: reviewed intended case (five valid profiles plus unreviewed relevant results means continue) and counterexamples (an explicit five-person request stays bounded; weak matches remain excluded; a concrete platform limit is reported with remaining scope). Behavioural benefit awaits the next sourcing run. Python validator unavailable as a working runtime in this environment; no automated validation pass claimed.
- Rollback: remove the Search-list breadth and completion subsection and restore version 2.1 if withdrawn. Existing verification, archive and agency-expansion rules remain intact.

## 2026-11-06 - Expanded both London searches

- Result: continued beyond the initial five. Verified 39 active technology and nine active life sciences candidates, all uncontacted; preserved five technology profiles observed in the archive. Save receipts verified current-project membership and pipeline totals reconciled active versus archived saves.
- Coverage: navigated all 23 original technology pages and nine restored life sciences agency-industry pages, plus specialist variants and current/past agency expansion. Result counts are not unique full-profile review counts; no exhaustive-market claim.
- Lesson: removing an industry restriction recovered valid agency recruiters classified under pharma/medical equipment. Verify current sector rather than old experience or agency boilerplate. Distinguish active pipelines from archived saves.
- Decision: existing v2.2 rules applied; no new global rule or outreach authority. Evidence and location caveats recorded in the Kaya folder.

## 2026-11-06 - Founder and executive prospect exclusions

- Source: Leon explicitly prohibited messaging founders, co-founders, owners, non-executive directors and any C-suite position. Prior message also requested removing founders and talent acquisition profiles from both London projects.
- Change: v2.2 to v2.3 adds a cross-channel prospect exclusion, checks all current positions before shortlisting and outreach, and scopes the additional talent acquisition/talent partner exclusion to these London searches. Preserves ordinary employed directors, agency managers and management handovers.
- Validation: checked intended cases (co-founder also titled recruiter, concurrent NED role, owner stated in description, C-suite leader) and counterexamples (ordinary employed director, consultant with a former in-house TA role, internal handover to Leon). No sending authority expanded. Python resolves only to the WindowsApps alias; automated validator was not run.
- Outcome: both active pipelines cleaned and visibly verified at 16 technology and six life sciences candidates, all uncontacted. Exclusions archived reversibly. Existing and concurrently observed archives preserved. Updated screenshots and action ledger stored in Kaya folder.
- Rollback: restore v2.2 and remove the prospect exclusion subsection if Leon withdraws this rule; do not automatically restore archived candidates.

## 2026-11-12 - Mandatory searches of previous recruitment employers

- Source: explicit owner instruction that every suitable recruiter found while creating LinkedIn projects must lead to searches of their previous recruitment companies for other recruiters meeting Leon's criteria.
- Change: v2.3 to v2.4 strengthens the existing agency-expansion rule with a trigger for every verified match, current-staff searches at every previous recruitment employer, recursive expansion from new matches, and reuse of recorded coverage to avoid duplicate work. Preserves project criteria, candidate verification, archive handling and outreach boundaries.
- Validation: reviewed a qualifying recruiter with two former agencies (both enter the queue), a repeat agency (reuse completed coverage), a colleague outside the requested market or below the tenure cutoff (exclude), and a promotion within the current employer (apply company or role tenure as requested). This update establishes the instruction; live sourcing coverage has not been validated by this edit.
- Rollback: restore the previous agency-expansion paragraph and metadata version 2.3 if the instruction is withdrawn.

## 2026-11-12 - Current recruitment employers require systematic review

- Source: explicit owner correction that suitable colleagues at a recruiter's existing employer were missed in Belgium and current employers must always be scanned.
- Change: v2.4 to v2.5 makes searches of current and previous recruitment employers equally mandatory for every verified match. Adds company identity and brand checks, an active current-employer filter check, relevant result-page and search-variation coverage, and recorded remaining scope.
- Validation: manually reviewed the intended case (a suitable recruiter triggers searches for current colleagues and former agency staff) and counterexamples (one visible colleague does not exhaust the company, a past-employer match is not treated as current staff, and colleagues below the tenure cutoff remain excluded). Live coverage awaits the next sourcing run. Automated validation was not run because Python is unavailable in this environment.
- Rollback: restore the v2.4 agency-expansion paragraph and metadata version if withdrawn. Preserve candidate verification and project archives.

## 2026-11-07 - Sydney technology agency sourcing

- Objective and result: added and verified 91 active uncontacted recruiters in the existing Sydney technology project; preserved 11 existing archives. No outreach. Candidate evidence is stored separately in the owner''s Kaya folder.
- Coverage: seven focused pages, 18 agency-expansion pages and three final newly discovered agency pages. Page/result totals overlap and are not full-profile review counts. No exhaustive-market claim.
- Lesson: apply the tenure unit the owner requested. This search specified current-company tenure, so continuous service across promotions qualifies even when the latest title started recently. This differs from the prior London current-role requirement. Use actual date fields and the review-date cutoff, not rounded duration badges.
- Verification: pipeline total matched the 91-save ledger; reconciled 90 names from list views and one via direct current-project membership. Active candidates in another project could be copied without changing an archive elsewhere; archived-only prospects remained untouched.
- Supported outcome: wider agency searches without a staffing-industry restriction recovered additional qualified specialists. Current technical remit, title, location and employer still needed individual checks. Contradictory locations, recent company moves and ambiguous cutoff dates stayed unsaved.
- Decision: existing v2.3 rules applied; no new global rule or sending authority. Completed one touchpoint review; no background loop or automated validator claimed.
