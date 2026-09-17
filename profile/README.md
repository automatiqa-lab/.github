# Automatiqa Lab

Open-source experiments where operations meet the algorithm.

This is where I build and publish small, sharp tools for the parts of supply chain and operations that software still walks past - the physical work, the tribal knowledge, the decisions nobody ever wrote down. Each project is open source, built in public, and small enough to read in one sitting.

The lab, with every project and its status, lives at **[automatiqa.io](https://www.automatiqa.io)**.

## Projects

| Project | What it does | Status |
|---------|--------------|--------|
| [oodaa](https://github.com/automatiqa-lab/oodaa) | A small, readable self-improving agent loop - Observe, Orient, Decide, Act, and the second A, Adjust | live |
| [risk-monitor](https://github.com/automatiqa-lab/risk-monitor) | Multi-agent operational risk monitoring across freight, fuel, labour, weather, and geopolitics, turned into briefings and a live dashboard | live |
| [procezio](https://github.com/automatiqa-lab/procezio) | A guided canvas that helps you spot automation opportunities in your own processes, with an agent working the board alongside you | live |
| [ppwr-screener](https://github.com/automatiqa-lab/ppwr-screener) | PPWR Compliance Screener - screens supplier packaging declarations for EU packaging conformity - twelve n8n workflows, judgement in a deterministic rule engine | live |
| [ship-doc](https://github.com/automatiqa-lab/ship-doc) | Shipment document control - checks the document pack against the shipping instruction on OneDrive and SharePoint, a named person approves, Outlook chases the originals | live |
| [flowtwin](https://github.com/automatiqa-lab/flowtwin) | Watch an operational process once, get editable process maps and runbooks back | work in progress |
| [orchestriq](https://github.com/automatiqa-lab/orchestriq) | The kernel for agents that run real operations - evals, approvals, earned autonomy and Article 50 transparency in the runtime | work in progress |
| [auspex](https://github.com/automatiqa-lab/auspex) | A prediction and forecasting harness for supply chain operations - connect a table, pick a model, read the signs | work in progress |
| [sample-trail](https://github.com/automatiqa-lab/sample-trail) | Sample approval for agri-food and soft commodities - pre-shipment and arrival samples, QR intake, voice cupping notes, deterministic spec check | live |

## Heuristics

Alongside the tools there is a writing series: **[heuristics](https://github.com/automatiqa-lab/heuristics)** - rules of thumb for supply chain and operations, one rule per page.

Most operational advice is either a war story you can't reuse or a framework with no edges. A heuristic sits between the two: the problem named without euphemism, who has been absorbing the cost, one imperative rule, a test you can run on Monday, a case where it actually cost or saved something, and the ways it gets misapplied by people who half-remember it.

Read them at [automatiqa.io/heuristics](https://www.automatiqa.io/heuristics/), or fork the markdown from the [repo](https://github.com/automatiqa-lab/heuristics). CC BY 4.0, because prose is not code.

## The idea behind the lab

Most agentic AI assumes a level of digital maturity that real operations do not have. The process lives in someone's head, the exception gets handled by instinct, and nothing downstream can be automated because nothing upstream is described. The lab works the other side of that gap: capture what actually happens, make it legible, and only then let an algorithm act on it.

Everything here is open. Fork it, break it, send it back better.

## Transparency

The tools here draft with language models, so their output carries EU AI Act Article 50 marking:
a line you can read, and metadata a machine can detect. Marking is conditional - content a model
wrote is marked, content a person wrote is not, because labelling everything would misstate
provenance and train readers to ignore the label. The model itself is never named in visible
output; Article 50 asks you to disclose that content is AI-generated, not which system produced it.

Per-project classification and reasoning: [procezio](https://github.com/automatiqa-lab/procezio/blob/main/COMPLIANCE.md),
[risk-monitor](https://github.com/automatiqa-lab/risk-monitor/blob/main/COMPLIANCE.md)
[ppwr-screener](https://github.com/automatiqa-lab/ppwr-screener/blob/main/COMPLIANCE.md)
and [ship-doc](https://github.com/automatiqa-lab/ship-doc/blob/main/COMPLIANCE.md).

- Lab: [automatiqa.io](https://www.automatiqa.io)
- Manifesto: [The Intelligent Orchestration Manifesto](https://www.automatiqa.io/manifesto/)
- LinkedIn: [Aleks Sidorecs](https://www.linkedin.com/in/alxsidr/)
