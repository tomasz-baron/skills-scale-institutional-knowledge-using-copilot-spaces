# OctoAcme Role Interaction Matrix

This document helps clarify how key personas/roles should interact throughout the project lifecycle, supporting onboarding, responsibilities, and seamless handoffs.

| Role                | PM                | PdM               | Developer         | QA             | Designer        | DevOps        | Tech Writer    | Scrum Master         |
|---------------------|-------------------|-------------------|-------------------|----------------|-----------------|---------------|----------------|----------------------|
| PM                  | -                 | Weekly planning   | Sprint planning   | Risk/QA sync   | Design review   | Release prep  | Doc readiness  | Retro facilitation   |
| PdM                 | Weekly planning   | -                 | Backlog & specs   | Feature review | Design shaping  | Release notes | User guides    | Vision alignment     |
| Developer           | Sprint planning   | Backlog grooming  | -                 | QA handoff     | Design handoff  | CI/CD review  | API doc input  | Standup/feedback     |
| QA                  | Risk/QA sync      | Feature review    | QA handoff        | -              | UX validation   | Test automation| Doc support    | Test review          |
| Designer            | Design review     | Design shaping    | Design handoff    | UX validation  | -               | Design for ops| Screenshots    | Usability retro      |
| DevOps              | Release prep      | Release notes     | CI/CD review      | Test automation| Design for ops  | -             | Infra docs     | Postmortem retro     |
| Tech Writer         | Doc readiness     | User guides       | API doc input     | Doc support    | Screenshots     | Infra docs    | -              | Retro documentation  |
| Scrum Master        | Retro facilitation| Vision alignment  | Standup/feedback  | Test review    | Usability retro | Postmortem retro | Retro documentation| -                  |

_Note: This matrix can be expanded by teams to include specific touchpoints and escalation paths as needed._
