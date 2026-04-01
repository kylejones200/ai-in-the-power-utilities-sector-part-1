# AI in the Power & Utilities Sector (part 1) Artificial intelligence has arrived in the physical world. It has moved
beyond consumer apps and academic research. It is entering our...

### AI in the Power & Utilities Sector (part 1)
Artificial intelligence has arrived in the physical world. It has moved
beyond consumer apps and academic research. It is entering our systems,
our workflows, and our infrastructure. In the power and utilities
sector, the implications are immediate and serious. AI will not simply
support the business. It will change how the business functions.


<figcaption>Photo by <a
href="https://unsplash.com/@calanthe?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com/@calanthe?utm_source=medium&amp;utm_medium=referral"
rel="photo-creator noopener" target="_blank">Zosia Szopka</a> on <a
href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
rel="photo-source noopener" target="_blank">Unsplash</a></figcaption>


IOU are embedding AI in outage prediction models. They are using it to
interpret imagery from line inspections. They are applying it to call
center transcripts and grid event logs. In each of these cases, AI is
not replacing humans. It is reshaping how decisions get made, how
patterns are identified, and how actions are prioritized.

This shift brings pressure to an already fragile system. AI consumes
power. It draws on real infrastructure. As model complexity grows, so
does energy demand. That energy must be forecasted, delivered, and
priced. The organizations that operate grids will feel this first.
Utilities already carry the responsibility of load balancing and demand
forecasting. AI adds a new dimension to that task. It introduces loads
that are unpredictable, non-linear, and sensitive to trends in other
industries.

At the same time, AI introduces new requirements for data readiness.
Models work best when the data is structured, consistent, and grounded
in context. In an industry known for conservatism and regulation, AI
introduces tension. It rewards speed, iteration, and experimentation.
Yet infrastructure demands reliability, safety, and verification. These
two mindsets must find a way to coexist.

This series begins with that challenge. AI is not a separate project. It
is a force already reshaping the edge of our infrastructure. Whether you
are an executive, a systems engineer, or a regulator, your work will
soon involve AI systems --- if it does not already. Understanding how
those systems behave, what they consume, and what they require is
essential.

The key to this transition is *context*. Data without context leads to
misleading answers. Compute without structure leads to wasted power. AI
without discipline leads to fragile systems. The organizations that
benefit from AI will be the ones that treat their infrastructure as a
living system. Those organizations will not just run models. They will
frame questions well, manage data carefully, and align tools with tasks.
That is the work ahead.

This series tells the story of that work. It begins by looking
backward --- at the last time we made a similar mistake. It follows the
curve of compute growth and data scarcity. It explores the rise of
multimodal models and the myth of the general-purpose solution. It shows
where AI falls short and what governance must do to keep systems safe.
Most of all, it argues for a grounded approach. One that treats AI not
as a black box or a shortcut, but as a system that must be integrated
into the fabric of utility operations.

Each part draws from real trends, public data, and lived experience. The
examples are drawn from the industry itself, not from speculative
futures. What you will find here is not hype. It is a set of
reflections, hard questions, and emerging principles for how to build
wisely with AI in the power and utility sector.

### **A Repeating Pattern**
The rise of artificial intelligence has triggered a familiar response in
large organizations. The response is not measured. It is enthusiastic,
widespread, and largely improvised. People want to be early. They want
to experiment. They want to prove they are forward-looking. In this
process, many return to a behavior that already failed us once.

When data lakes gained popularity a decade ago, the promise was clear.
Data had become fragmented. It was locked in systems that could not
speak to one another. Moving it to a single, scalable location would
solve that problem. Data lakes were supposed to create access, unify
analytics, and reduce duplication. Companies moved fast to adopt the
model.

The result was a decade of ungoverned data accumulation. Organizations
poured everything they had into the lake --- files, tables, logs,
models --- often without cataloging, labeling, or tracing the source.
The idea of centralized access was realized. The idea of centralized
understanding was not. Analysts could query anything, but they rarely
knew what they were looking at. What system produced it? What filters
had been applied? What timestamp was valid? These answers were not
always available. And when they were not, trust disappeared.

Executives learned a lesson. Access alone does not produce insight.
Quantity alone does not produce clarity. Data without lineage becomes a
liability. Data without standards becomes misleading. The lake did not
fail because the idea was wrong. It failed because execution skipped the
essentials. It skipped governance.

Now we face the same conditions again. Generative AI is today's lake. It
promises speed, reach, and impact. It invites users to ask anything and
receive answers in natural language. The interfaces are sleek. The
marketing is confident. Teams are encouraged to plug models into
chatbots, pipelines, and customer-facing portals. The tools are easier
than ever to deploy. What they produce is harder than ever to verify.

The same problem has returned. It is the problem of context. Models
respond with confidence even when the data is wrong. They summarize logs
without checking their integrity. They hallucinate metrics that were
never recorded. This is not a software issue. It is a structure issue.
When the model has no access to lineage, no schema to enforce rules, no
framework to distinguish a draft from a final value, it cannot be
expected to return reliable results. It will respond. It will complete
the task. It will not tell you that the task should not have been
completed.

This is the danger of working outside structure. The model will say yes
to a question that should never have been asked. And when that answer is
wrong, the mistake will carry the full authority of automation. That is
the kind of mistake we must prevent. We prevent it not by shrinking the
model. We prevent it by structuring the input.

Here we must recognize a core principle. Good AI depends on good data.
Good data depends on governance. Governance depends on clarity of
purpose. Without purpose, data becomes noise. And without purpose,
models become guesswork.

Many companies now find themselves deploying advanced tools to answer
basic questions. I have seen teams use large language models to write
SQL that simply selects every row in a table. I have seen models used to
summarize data that no one has checked for duplication. I have seen
infrastructure designed to support AI workloads that still cannot
produce a consistent definition of "customer" across systems. These are
not technology failures. They are judgment failures.

This is not a call to stop building. It is a call to remember what we
already know. Structured data outperforms unstructured data. Documented
systems outperform opaque systems. Clarity outperforms novelty.

The principles of good data management are not outdated. They are more
important now than ever. In fact, they are the only way AI can work at
scale in regulated, mission-critical environments. Without version
control, you cannot trust the model. Without data contracts, you cannot
scale the output. Without access rules, you cannot ensure compliance.
These are not academic constraints. They are the scaffolding of
operational intelligence.

Power and utility companies know this better than most. These are
industries that already depend on traceability. Every outage must be
explained. Every dispatch must be logged. Every system must be
auditable. AI cannot enter that world as a casual observer. It must meet
those same requirements. And the only way it will meet them is if we
stop treating AI as a shortcut and start treating it as a component of
the system.

That requires a shift in how we adopt. Not faster. Not flashier. More
disciplined. More deliberate. We must pair the model with the structure
it needs. That means governed data. That means metadata that travels
with the payload. That means systems that enforce what used to be manual
habits. The good news is that the tools now exist to do that well.

We can build pipelines that capture lineage automatically. We can track
access. We can enforce constraints. We can annotate columns and fields
with definitions that live through time. These are not blockers. These
are enablers. They allow AI to do what it does best --- identify
patterns, simulate decisions, and scale knowledge --- without turning
fragile inputs into fragile results.

The first wave of AI deployment will reward speed. The next wave will
reward trust. That trust comes from clarity. And clarity comes from
applying the lessons we already learned.

We do not need to *reinvent* governance. We need to remember why it
mattered.
::::::::By [Kyle Jones](https://medium.com/@kyle-t-jones) on
[July 14, 2025](https://medium.com/p/6b0491419861).

[Canonical
link](https://medium.com/@kyle-t-jones/ai-in-the-power-utilities-sector-part-1-6b0491419861)

Exported from [Medium](https://medium.com) on November 10, 2025.
