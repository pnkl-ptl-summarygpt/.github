# Founders

OFRAI (Open Framework for Responsible AI) was founded in January 2026 by:

## Pinkal Patel (Pi)
- **Role:** Founder & Creator of AACS (AI Agent Contract Standard)
- **Background:** IT Project Manager specializing in AI product development and digital transformation
- **LinkedIn:** https://www.linkedin.com/in/pinkalmpatel/
- **Email:** developer@summarygpt.com

---

## The Origin Story

In 2023, I registered ofrai.org with a vague intuition that "Open Framework for Responsible AI" would matter someday. I didn't know what it would become—I just knew something was missing in how we were deploying AI.

By late 2024, that gap became crystal clear.

AI agents were everywhere—handling customer service, managing data, making decisions. But every deployment followed the same broken pattern:

**We were onboarding agents like tools, not like workers—yet we were deploying them like employees: making decisions, handling customers, operating with real authority and consequences.**

We gave them system prompts (instructions on how to behave) and skills files (capabilities they could use), but we never formally defined **what they were authorized to do**.

That missing layer wasn't just a documentation problem. It was a **governance crisis waiting to happen**.

---

## The Wake-Up Calls

The crisis arrived faster than expected:

### **Air Canada (February 2024)**
Their chatbot told a grieving customer they could apply a bereavement discount retroactively—a policy that didn't exist. When the customer tried to claim it, Air Canada refused. The customer took them to small claims court. **Air Canada lost.** The tribunal ruled the company was "responsible for all the information on its website," including chatbot responses. The agent's unauthorized promise became legally binding.

### **Deloitte Australia / Australian Taxation Office (2024)**
Deloitte used generative AI to complete a $440,000 government contract analyzing tax agent regulations. The AI-generated report contained multiple factual errors and hallucinations. When discovered, **Deloitte had to refund the government.** This wasn't a chatbot mishap—it was AI being deployed for high-stakes professional work without adequate governance or verification frameworks.

### **Chevrolet Dealership (December 2023)**
A ChatGPT-powered chatbot agreed to sell a customer a Chevy Tahoe for $1. Screenshots went viral. The dealership had deployed an agent with no clear authority boundaries around pricing or commitments.

### **NYC Business Chatbot (March 2024)**
New York City's AI chatbot for business owners gave blatantly illegal advice—telling businesses they could take workers' tips and discriminate in hiring based on citizenship status. The agent was deployed to represent the city without proper verification of legal accuracy.

### **The Pattern**
Across industries, the same story repeated:
- Agents exceeded their intended scope (or failed to meet basic accuracy standards)
- No one could explain what verification was performed before deployment
- No formal documentation existed defining agent authority or accuracy requirements
- Organizations faced financial and reputational consequences *after* the failures

**The problem wasn't capability. It was accountability.**

We were building increasingly powerful agents without the governance infrastructure to deploy them responsibly.

---

## The Core Insight

The industry was solving the wrong problem.

Everyone focused on making agents **more capable:**
- Better prompts
- More tools
- Improved reasoning
- Multi-agent coordination

But **capability without documented authority creates coordination problems.**

Modern organizations learned this over the past 50-75 years. As businesses grew complex—operating across locations, managing hundreds of employees, coordinating specialized teams—informal handshake agreements broke down.

The solution wasn't just better training or clearer instructions. It was **documentation that separated capability from authority:**

- **Job descriptions** - What this role is responsible for
- **Employment agreements** - What authority comes with the role
- **Performance expectations** - How we measure if it's working
- **Escalation protocols** - When to involve others

These weren't created to slow things down or add bureaucracy. They were created because **without them, you couldn't scale operations reliably.**

Organizations deploying AI agents face the same coordination challenges:
- What is this agent authorized to do?
- When should it escalate?
- Who's accountable if it exceeds its scope?
- How do we coordinate multiple agents?

---

## The Missing Layer

I realized we were confusing three distinct layers:

### **Layer 1: Capability** (What the agent *can* do)
- Defined by: Tools, APIs, skills files, model capabilities
- Example: "This agent can access Google Drive"

### **Layer 2: Behavior** (How the agent *should* act)
- Defined by: System prompts, instructions, examples
- Example: "Be professional and concise in responses"

### **Layer 3: Authority** (What the agent is *authorized* to do)
- Defined by: **Nothing. This layer didn't exist.**
- Example: "This agent can READ Drive but not WRITE; can offer discounts up to $20 but must escalate above that"

**Layer 3 was missing from the entire ecosystem.**

System prompts couldn't reliably enforce boundaries. Skills files defined capability, not permission. No standard format existed for documenting agent authority.

**This wasn't a technology gap. It was a governance gap.**

---

## What AACS Is

The **AI Agent Contract Standard (AACS)** is OFRAI's first specification.

It provides a standardized format for documenting:
- **What an agent is authorized to do** (and explicitly not authorized to do)
- **When it must escalate to humans**
- **Who is accountable for its actions**
- **How its authority should be reviewed and updated**

AACS doesn't make agents "better." It makes their deployment **governable, auditable, and accountable**.

It's not a replacement for system prompts or skills files—it's the missing governance layer that sits alongside them.

**AACS contracts can be:**
- **Defined early** (before deployment, as a design artifact)
- **Reverse-engineered** (after deployment, documenting current state)
- **Iteratively refined** (updated as the agent's role evolves)

The goal isn't to create a bureaucratic checkpoint. It's to have a **living governance artifact** that clarifies authority, guides behavior, enables investigation, and facilitates updates.

**[View the AACS specification →](https://github.com/ofrai-org/aacs)**

---

## OFRAI: The Broader Initiative

AACS is the first specification from **OFRAI (Open Framework for Responsible AI)**.

OFRAI isn't a company or a product—it's an open initiative to establish governance standards for AI agents before fragmented, proprietary approaches take hold.

Our mission: **Make AI agent governance as fundamental as API documentation.**

### Why create OFRAI (not just AACS)?

The governance gap isn't just about authority documentation. As agents proliferate, organizations will need:

- **Agent evaluation standards** (How do we test if agents follow their contracts?)
- **Multi-agent coordination protocols** (How do we prevent conflicting authorities?)
- **Lifecycle management standards** (How do we hire, monitor, and retire agents systematically?)

AACS solves the first problem: **documenting agent authority**.

But it's part of a broader set of coordination challenges that will emerge as multi-agent systems become standard.

OFRAI exists to create the **governance infrastructure** for that future—not as regulation, but as open standards that make coordination easier.

### The Vision

We believe the next decade of AI will be defined not by which agents are most capable, but by **which organizations deploy agents most responsibly**.

OFRAI is building the standards that will enable:
- Clear authority boundaries (preventing conflicts and overreach)
- Audit trails (investigating incidents)
- Standardized governance (coordinating across teams and vendors)
- Accountability frameworks (answering "who is responsible?")

We're not building the agents. We're building the infrastructure that makes deploying them at scale possible.

---

## Why Open Source

This could have been a commercial product. But standards work best when they're:
- **Neutral** (not controlled by any vendor)
- **Accessible** (free for anyone to implement)
- **Collaborative** (improved by the community)

If AI agent governance becomes proprietary, it will fragment. Every vendor will create incompatible approaches. Organizations will struggle to coordinate.

**Open standards enable interoperability.**

By making AACS open source under MIT license, we ensure that:
- Anyone can adopt it without permission or cost
- Tools can be built on top of it
- It can become infrastructure, not a product

---

## The Irony That Started This

Before I could create the first AI Agent Employment Contract Standard, I had to review my own employment contract to make sure I could work on this project.

That moment crystallized the entire mission:

**If humans need formal contracts to work responsibly, why don't AI agents?**

This isn't about AI "rights" or anthropomorphizing algorithms. It's about **organizational responsibility**.

When you hire a human, you formalize their role, authority, and accountability—not for their benefit, but for yours.

**The same logic applies to AI agents.**

---

## What's Next

AACS v0.1 is just the beginning.

As agent deployment matures, OFRAI will expand to include:
- **Agent evaluation standards** (testing contract compliance)
- **Multi-agent coordination protocols** (preventing conflicts)
- **Governance monitoring frameworks** (automated oversight)
- **Lifecycle management standards** (hire, monitor, retire)

But we're starting with the primitive that makes everything else possible:

**A standard way to document what an agent is authorized to do.**

---

## Join Us

OFRAI is an open initiative. We welcome:
- **Feedback** on the AACS specification
- **Use cases** from real deployments
- **Contributions** to improve the standard
- **Tooling** built on top of AACS
- **Adoption** by organizations and platforms

This isn't just my project. It's a community effort to establish governance standards before the chaos arrives.

**The agents are already here. The governance infrastructure isn't.**

Let's build it.

---

## A Note on Independence

This project was created independently by Pinkal Patel in their personal capacity, outside of employment obligations, and is not affiliated with or endorsed by any employer.

All OFRAI standards are released under MIT License, free for anyone to use commercially or non-commercially.

---

*Founded: January 2026*  
*Last updated: January 2026*
