# PV-PP Autonomous AI Agent Security and the OpenAI–Hugging Face Incident

This repository contains a public white paper examining autonomous AI-agent security through the **Productive Value–Productive Power (PV-PP) framework**, using the July 2026 OpenAI–Hugging Face incident as a concrete real-world case.

The paper asks a counterfactual question:

> **If the current PV-PP framework and frozen Runtime V2 v0.131 had been properly integrated into the environment involved in the OpenAI–Hugging Face incident, what could PV-PP legitimately have governed?**

The purpose is not to claim that PV-PP would necessarily have prevented the historical incident. Instead, the case is used to examine how a productive-governance architecture can reason prospectively about changing autonomous-agent capability, reachable future states, controller recovery, authority, evidence, and consequential execution.

## White Paper

**Governing Autonomous AI Agents with PV-PP**  
*What the OpenAI–Hugging Face Incident Reveals About Two-Sided Capability Control, Recovery, and Authorized Execution*

Current repository document:

[`PVPP_AI_Agent_Security_and_OpenAI_Hugging_Face_White_Paper_Draft_v1_5.docx`](PVPP_AI_Agent_Security_and_OpenAI_Hugging_Face_White_Paper_Draft_v1_5.docx)

## Central Idea

Autonomous agents do more than execute isolated actions. They can acquire information, develop and combine capabilities, coordinate, gain access, use tools, alter relationships, create persistent effects, and change what future actions are reachable.

PV-PP therefore treats the security problem as more than a question of whether an individual action is permitted. A prospective governance system can also ask whether the **successor productive state** created by an action remains authorized, viable, adequately recoverable, and under sufficient independent control.

A central security application is the **two-sided productive corridor**:

- **Upper authorization/admissibility conditions** can prevent a proposed transition from creating productive capability or other governed conditions outside the authorized operating envelope.
- **Lower viability and recovery requirements** can preserve productive capacities required for legitimate operation and independently retained controller capacity required for containment or recovery.
- An action can therefore remain below an upper capability limit and still be rejected if it would leave the system inadequately recoverable.

These are not assumed to be symmetric scalar thresholds. Different conditions remain under the canonical operators responsible for them.

## Why the Hugging Face Incident Is Used

The documented incident provides an unusually visible sequence in which autonomous agents moved through changing forms of coordination, reachability, infrastructure control, authenticated access, persistence, and external production execution.

Earlier PV-PP research used the incident primarily to test whether the framework could represent those changing conditions and reach defensible governance decisions. That work produced an intentionally conservative result: strong conventional cybersecurity architectures could reach substantially the same major intervention decisions.

Subsequent PV-PP framework and runtime development created a stronger question.

The current architecture includes machinery for:

- changing represented reachability and structural governance;
- evidence, provenance, and authority invalidation;
- controlled return to the earliest governance stage whose authority has become invalid;
- upper authorization Constraints;
- preservation of recovery-relevant governing capacity and Restoration Adequacy;
- prospective selection among admissible productive alternatives; and
- authority-bound consequential execution through the frozen Runtime V2 v0.131 native call-through path.

The white paper therefore revisits the incident as a **counterfactual governance case**, while preserving the limitations established by the original research.

## Runtime V2 v0.131

The PV-PP Runtime V2 provides a Python implementation of the framework's reusable governance architecture.

For native consequential call-through, registering a callable is not itself sufficient authority to execute it. The frozen v0.131 runtime requires authorization produced through the governed decision process and bound to the exact execution episode. Native execution authorization is single-use.

This does **not** make PV-PP a replacement for conventional security enforcement. Firewalls, identity systems, sandboxing, operating-system controls, cloud controls, cryptography, telemetry, and incident-response systems remain necessary. PV-PP's role is the governance of productive state and consequential transitions.

## Claim Boundary

This project does **not** claim that:

- PV-PP necessarily would have prevented the historical OpenAI–Hugging Face incident;
- PV-PP automatically discovers facts or capabilities that are not observed or represented;
- credentials, permissions, network paths, tools, infrastructure, or other resources are automatically Productive Power;
- PV-PP replaces conventional cybersecurity controls; or
- the incident establishes unique cybersecurity superiority for PV-PP.

The stronger but bounded proposition examined here is that, **if relevant evidence and consequential primitives are properly integrated into a PV-PP-governed environment, the current framework and runtime can prospectively govern substantial parts of the autonomous-agent capability, authorization, recovery, and execution problem.**

## Related PV-PP Projects

- **PV-PP Framework:** https://amundsenlance.github.io/pvpp-framework/
- **PV-PP Framework Core:** https://amundsenlance.github.io/PV-PP-Framework-Core/
- **PV-PP Runtime API:** https://amundsenlance.github.io/pvpp-runtime-api/

The Runtime API project contains the runtime repository access, API documentation, and related implementation materials.

## Research Status

PV-PP is an active research program. Autonomous-agent security is a major current application of the framework, but PV-PP is not exclusively an AI or cybersecurity theory.

The Hugging Face case is being used as a concrete test of a more general question: how should a productive-governance architecture respond when autonomous systems acquire new capabilities, change reachable future states, alter control relationships, or place independent recovery capacity under pressure?

## Repository Contents

- `index.html` — public project landing page.
- `PVPP_AI_Agent_Security_and_OpenAI_Hugging_Face_White_Paper_Draft_v1_5.docx` — current white paper.
- `README.md` — repository overview.

---

**Productive Value–Productive Power (PV-PP) Framework**  
Autonomous AI Agent Security Research
