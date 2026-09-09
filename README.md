# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Trojan Kane Perseus V. Castro
- Section: TN32
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Explain in 2-3 sentences why selecting the correct DevNet resource matters before beginning a network-automation task.

Selecting the apropriate DevNet resource is important because each one has a unique service and effect that it provides to the user. Selecting a weak matched resourcce can derail the task and cost the team or user to spend more of their resources in order to get back on track or catch-up on lost time and work.

## Validated Resource Decisions

Summarize your four selections from `student_plan.json`. For each use case, state the selected resource, the most important requirement, and the official Cisco evidence used.

Use Case 1:
Selected Resource: always-on-sandbox
Most Important Requirement: API-testing, instant access, shared environment, read-only
Official Cisco Evidence Used: https://developer.cisco.com/docs/sandbox/getting-started/#reservation-sandboxes

Use Case 2:
Selected Resource: reservation-sandbox
Most Important Requirement: private environment, deep access, scheduled access, VPN connection, setu-time toleration
Official Cisco Evidence Used: https://developer.cisco.com/docs/sandbox/getting-started/#reservation-sandboxes

Use Case 3:
Selected Resource: learning-lab
Most Important Requirement: step-by-step instruction, guided practice, independent study, immediate access
Official Cisco Evidence Used: https://developer.cisco.com/learning/

Use Case 4:
Selected Resource: code-exchange
Most Important Requirement: access to exsiting code with exclusion of guided training and live testing environment
Official Cisco Evidence Used: https://developer.cisco.com/site/codeexchange-about-page/

## AI Evaluation

Identify at least one AI recommendation that you accepted, rejected, or modified. Explain the evidence behind your decision.

AI recommendation:
Use Case 1: always-on-sandbox
Decisive requirement: The team needs immediate access and cannot wait for provisioning. Because the students only need safe, read-only API practice and do not require administrative privileges, a shared environment is appropriate.

Evidence taken from DevNet website:
Always-On Sandboxes
Always-On (AO) sandboxes are always ready to go when you are! AO sandboxes don't require a reservation. These environments are shared among all users so administrative access is restricted. This provides access to "kick the tires" with non-admin APIs on the fly.

Pros
Instant access - no setup time
Always available
No reservations required
Powerful access to APIs

Cons
No admin access
Shared environment

Conclusion: Based on the information gathered from the DevNet website, the requirements stated by AI matches the features listed down for Always-on Sandboxes in its pros and cons section. The following requirements where verified: immediate access, no waiting time for provisioning, read-only API, lack of need for administrative priviledges and a shared environment.

## Validation Evidence

- Validator result:
PASS: JSON file loaded
PASS: student and AI disclosure completed
PASS: all four scenario IDs present
PASS: resource classifications match scenario requirements
PASS: official Cisco evidence URLs supplied
PASS: AI verification statuses are valid
PASS: rationales are sufficiently detailed
PASS: AI recommendations are summarized in the student's own words
PASS: no credential-like fields detected

VALIDATION COMPLETE: 9/9 checks passed.

- Command used: python validate_plan.py
- Official Cisco pages reviewed: 3

## Git Evidence

- Initial commit message: Initialize DevNet resource planning project
- Validation commit message: Complete and validated DevNet resource plan
- Output of `git log --oneline`:

bfd6a02 (HEAD -> master) Complete and validated DevNet resource plan
bb8ed56 Initialize DevNet resource planning project

## AI-Use Disclosure

State the AI tool used, the type of assistance received, what was independently checked, and what you revised.

I used an AI assistant (ChatGPT) to recommend and explain possible Cisco DevNet resources. I independently checked its claims against official Cisco documentation found in their website and retained responsibility for the final classifications.